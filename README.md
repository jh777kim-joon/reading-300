# reading-300
book lists, need to read
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>📚 300권 독서 아카이브 — 로널드제임스리드</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@400;700&family=Noto+Sans+KR:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#0c0c0e;--bg2:#13131a;--bg3:#1a1a24;--border:#252530;--text:#e8e4dc;--text2:#9a9590;--text3:#4a4a5a;--gold:#c8a96e;--gold2:#e8c98e;--green:#4a9e6a;--red:#c85050;--blue:#5080c8;--purple:#9060c0;--amber:#d4943a}
*{box-sizing:border-box;margin:0;padding:0}
body{background:var(--bg);color:var(--text);font-family:'Noto Sans KR',sans-serif;font-size:13px;min-height:100vh}
#header{background:linear-gradient(135deg,#1a1208 0%,#0c0c0e 70%);border-bottom:1px solid #2a2010;padding:14px 20px;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:10px}
.logo{font-family:'Noto Serif KR',serif;font-size:17px;color:var(--gold)}
.logo small{display:block;font-family:'Noto Sans KR';font-size:10px;color:var(--text3);margin-top:2px}
.hstats{display:flex;gap:16px;align-items:center}
.hstat .n{font-size:18px;font-weight:700;color:var(--gold);line-height:1}
.hstat .l{font-size:9px;color:var(--text3);margin-top:2px}
.prog-wrap{width:180px}
.prog-info{display:flex;justify-content:space-between;font-size:9px;color:var(--text3);margin-bottom:4px}
.prog-bar{height:3px;background:#1e1e2a;border-radius:2px;overflow:hidden}
.prog-fill{height:100%;background:linear-gradient(90deg,var(--gold),var(--gold2));border-radius:2px;transition:width .5s}
#app{display:flex;height:calc(100vh - 58px)}
#sidebar{width:185px;flex-shrink:0;background:var(--bg2);border-right:1px solid var(--border);overflow-y:auto;padding:10px 0}
#sidebar::-webkit-scrollbar{width:4px}
#sidebar::-webkit-scrollbar-thumb{background:var(--border);border-radius:2px}
.sb-sec{font-size:9px;font-weight:700;color:var(--text3);padding:8px 14px 4px;text-transform:uppercase;letter-spacing:.1em}
.tb{display:flex;justify-content:space-between;align-items:center;width:100%;padding:6px 14px;border:none;background:transparent;cursor:pointer;font-size:11px;color:var(--text2);text-align:left;font-family:'Noto Sans KR';gap:6px;transition:background .15s}
.tb:hover{background:var(--bg3);color:var(--text)}
.tb.act{background:#2a1e0a;color:var(--gold)}
.tb .c{font-size:9px;background:var(--bg3);padding:1px 5px;border-radius:6px;color:var(--text3);flex-shrink:0}
.tb.act .c{background:#3a2a10;color:var(--gold)}
.sdiv{height:1px;background:var(--border);margin:6px 0}
#main{flex:1;display:flex;flex-direction:column;overflow:hidden}
#ctrl{padding:10px 14px;border-bottom:1px solid var(--border);background:var(--bg2);display:flex;gap:8px;align-items:center;flex-wrap:wrap}
#search{flex:1;min-width:140px;background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:6px 10px;color:var(--text);font-size:12px;font-family:'Noto Sans KR';outline:none;transition:border .2s}
#search:focus{border-color:var(--gold)}
#search::placeholder{color:var(--text3)}
.fg{display:flex;gap:3px;flex-wrap:wrap}
.fb{padding:4px 9px;font-size:11px;border-radius:6px;border:1px solid var(--border);background:transparent;cursor:pointer;color:var(--text2);font-family:'Noto Sans KR';transition:all .15s}
.fb:hover{border-color:var(--text2);color:var(--text)}
.fb.act{border:none;background:var(--gold);color:#0c0c0e;font-weight:700}
.fb.act.v{background:var(--green)}
.rc{font-size:11px;color:var(--text3);white-space:nowrap;margin-left:auto}
#gw{flex:1;overflow-y:auto;padding:12px}
#gw::-webkit-scrollbar{width:5px}
#gw::-webkit-scrollbar-thumb{background:var(--border);border-radius:3px}
#grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(190px,1fr));gap:8px}
.card{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:10px 12px;display:flex;flex-direction:column;gap:4px;transition:border-color .15s,transform .1s;cursor:default}
.card:hover{border-color:#3a3020;transform:translateY(-1px)}
.card.done{background:#0a150a;border-color:#1a3020;opacity:.87}
.ct{display:flex;justify-content:space-between;align-items:flex-start;gap:4px;margin-bottom:2px}
.th-b{font-size:9px;font-weight:500;padding:2px 5px;border-radius:5px;white-space:nowrap;max-width:60%;overflow:hidden;text-overflow:ellipsis;flex-shrink:0}
.lv-b{font-size:9px;font-weight:700;padding:2px 6px;border-radius:5px;white-space:nowrap;flex-shrink:0}
.cnum{font-size:9px;color:var(--text3)}
.ctit{font-size:12px;font-weight:500;color:var(--text);line-height:1.4}
.cauth{font-size:10px;color:var(--text3)}
.cnote{font-size:10px;color:var(--text2);line-height:1.5;border-top:1px solid var(--border);padding-top:4px;margin-top:2px}
#empty{text-align:center;color:var(--text3);padding:60px;grid-column:1/-1;font-size:14px}
@media(max-width:600px){#sidebar{display:none}#main{width:100%}}
</style>
</head>
<body>
<div id="header">
  <div><div class="logo">📚 300권 독서 아카이브<small>hahaneblog.tistory.com — 로널드제임스리드</small></div></div>
  <div class="hstats">
    <div class="hstat"><div class="n" id="hn">300</div><div class="l">전체</div></div>
    <div class="hstat"><div class="n" id="hd" style="color:var(--green)">62</div><div class="l">완료</div></div>
    <div class="hstat"><div class="n" id="hr" style="color:var(--text2)">238</div><div class="l">예정</div></div>
    <div class="prog-wrap">
      <div class="prog-info"><span>달성률</span><span id="hpct">20.7%</span></div>
      <div class="prog-bar"><div class="prog-fill" id="hpf" style="width:20.7%"></div></div>
    </div>
  </div>
</div>
<div id="app">
<div id="sidebar">
  <div class="sb-sec">테마</div>
  <div id="tlist"></div>
</div>
<div id="main">
  <div id="ctrl">
    <input type="text" id="search" placeholder="제목, 저자 검색...">
    <div class="fg" id="lvf"></div>
    <div class="fg" id="dnf"></div>
    <span class="rc" id="rc"></span>
  </div>
  <div id="gw"><div id="grid"></div></div>
</div>
</div>
<script>
const TH={
  t1:{n:'인생철학·의미',bg:'#2a1a08',c:'#d4944a'},
  t2:{n:'인생재설계·FIRE',bg:'#0a1a2a',c:'#4a94d4'},
  t3:{n:'신앙·철학',bg:'#1a0a2a',c:'#9460c4'},
  t4:{n:'동양철학',bg:'#1a1200',c:'#c4a440'},
  t5:{n:'역사·인물',bg:'#1a1a0a',c:'#b4a040'},
  t6:{n:'전략·경영',bg:'#0a1a1a',c:'#40a4b4'},
  t7:{n:'투자·재무',bg:'#1a0a0a',c:'#c45050'},
  t8:{n:'스타트업·창업',bg:'#0a1a0a',c:'#50a450'},
  t9:{n:'리더십·조직',bg:'#1a1000',c:'#c49040'},
  t10:{n:'생산성·사고',bg:'#001a10',c:'#40c490'},
  t11:{n:'심리학·행동',bg:'#1a001a',c:'#c050c0'},
  t12:{n:'가정·자녀',bg:'#001a0a',c:'#40b470'},
  t13:{n:'기술·미래',bg:'#001020',c:'#4080d0'},
  t14:{n:'경제학·거시',bg:'#100a00',c:'#d0a040'},
};
const LV={
  '필독':{bg:'#8b2020',c:'#ffd0d0'},
  '강추':{bg:'#1a5a2a',c:'#90ffa0'},
  '추천':{bg:'#2a2a50',c:'#a0a0ff'},
  '완료':{bg:'#0a3a1a',c:'#60ff90'},
};
const BOOKS=[
// ===== 인생철학·의미 t1 (25) =====
{id:1,th:'t1',t:'숨결이 공기가 될 때',a:'Paul Kalanithi',y:2016,l:'필독',n:'죽음 앞에서 보이는 진짜 삶. 36세 신경외과의의 마지막 기록.',done:true},
{id:2,th:'t1',t:'죽음의 수용소에서',a:'Viktor Frankl',y:1946,l:'필독',n:'아우슈비츠에서 발견한 의미. 태도를 선택하는 자유.',done:true},
{id:3,th:'t1',t:'좋은 인생 (The Good Life)',a:'Robert Waldinger',y:2023,l:'필독',n:'하버드 84년 추적. 행복은 관계에서 온다.',done:true},
{id:4,th:'t1',t:'명상록',a:'Marcus Aurelius',y:161,l:'필독',n:'스토아 철학의 정수. 황제의 자기 성찰 일기.',done:true},
{id:5,th:'t1',t:'4000주',a:'Oliver Burkeman',y:2021,l:'필독',n:'인생 4,000주. 한계를 받아들이는 순간 선택이 시작된다.',done:true},
{id:6,th:'t1',t:'모리와 함께한 화요일',a:'Mitch Albom',y:1997,l:'필독',n:'죽어가는 교수의 삶의 수업.',done:true},
{id:7,th:'t1',t:'마지막 강의',a:'Randy Pausch',y:2008,l:'필독',n:'시한부 선고 후 마지막 강의. 어린 시절 꿈을 이루는 법.',done:true},
{id:8,th:'t1',t:'제로에서 죽어라 (Die With Zero)',a:'Bill Perkins',y:2020,l:'필독',n:'경험을 극대화하라. FIRE의 재정의.',done:true},
{id:9,th:'t1',t:'두 번째 산',a:'David Brooks',y:2019,l:'필독',n:'성공 후의 공허함. 헌신이 자유보다 더 큰 기쁨.',done:true},
{id:10,th:'t1',t:'이키가이',a:'Francesc Miralles',y:2016,l:'강추',n:'삶의 이유. 매일 아침 눈 뜨게 만드는 것.',done:true},
{id:11,th:'t1',t:'남아있는 나날',a:'Kazuo Ishiguro',y:1989,l:'강추',n:'후회와 품위. 살지 못한 삶.'},
{id:12,th:'t1',t:'스토아 서한집',a:'Seneca',y:65,l:'강추',n:'시간·우정·죽음에 대한 스토아적 성찰.'},
{id:13,th:'t1',t:'연금술사',a:'Paulo Coelho',y:1988,l:'강추',n:'개인의 전설을 따르는 여정.'},
{id:14,th:'t1',t:'사이다르타',a:'Hermann Hesse',y:1922,l:'강추',n:'깨달음을 향한 여정.'},
{id:15,th:'t1',t:'장애물이 길이다',a:'Ryan Holiday',y:2014,l:'강추',n:'스토아 철학의 실천. 역경이 성장의 길.'},
{id:16,th:'t1',t:'에고는 적이다',a:'Ryan Holiday',y:2016,l:'강추',n:'자아가 성공을 가로막는다.'},
{id:17,th:'t1',t:'스틸니스 이즈 더 키',a:'Ryan Holiday',y:2019,l:'강추',n:'내면의 고요함이 최고의 성과를 만든다.'},
{id:18,th:'t1',t:'남은 인생을 어떻게 살 것인가',a:'Arthur Brooks',y:2023,l:'필독',n:'50대 이후 번성하는 법.'},
{id:19,th:'t1',t:'소유냐 존재냐',a:'Erich Fromm',y:1976,l:'강추',n:'소유 지향 vs 존재 지향.'},
{id:20,th:'t1',t:'사랑의 기술',a:'Erich Fromm',y:1956,l:'강추',n:'사랑은 감정이 아니라 기술이다.'},
{id:21,th:'t1',t:'이방인',a:'Albert Camus',y:1942,l:'강추',n:'부조리한 세계에서 인간의 실존.'},
{id:22,th:'t1',t:'행복의 건축',a:'알랭 드 보통',y:2006,l:'추천',n:'공간이 인간에게 미치는 영향.'},
{id:23,th:'t1',t:'채식주의자',a:'한강',y:2007,l:'강추',n:'2024 노벨문학상 작가. 폭력과 존재.'},
{id:24,th:'t1',t:'어린 왕자',a:'Saint-Exupéry',y:1943,l:'강추',n:'중요한 것은 눈에 보이지 않는다.'},
{id:25,th:'t1',t:'모모',a:'Michael Ende',y:1973,l:'강추',n:'시간 도둑들과 싸우는 소녀. 느림의 가치.'},

// ===== 인생재설계·FIRE t2 (20) =====
{id:26,th:'t2',t:'100세 인생',a:'Lynda Gratton',y:2016,l:'필독',n:'3단계 인생은 끝났다. 100세 시대 재설계.',done:true},
{id:27,th:'t2',t:'인생은 설계해 가는거야',a:'Burnett & Evans',y:2016,l:'강추',n:'스탠퍼드 디자인씽킹으로 인생 설계.',done:true},
{id:28,th:'t2',t:'배움의 발견',a:'Tara Westover',y:2018,l:'강추',n:'학교 없이 케임브리지 박사. 늦은 시작은 없다.',done:true},
{id:29,th:'t2',t:'이웃집 백만장자',a:'Stanley & Danko',y:1996,l:'필독',n:'진짜 부자는 검소하게 산다.',done:true},
{id:30,th:'t2',t:'소명 (The Call)',a:'Os Guinness',y:1998,l:'필독',n:'하나님이 우리를 부르신 이유.',done:true},
{id:31,th:'t2',t:'아웃라이브',a:'Peter Attia',y:2023,l:'필독',n:'과학적 건강관리로 100세까지 잘 사는 법.'},
{id:32,th:'t2',t:'나는 4시간만 일한다',a:'Tim Ferriss',y:2007,l:'강추',n:'라이프스타일 디자인. 경쟁 우회 전략.'},
{id:33,th:'t2',t:'부의 단순한 길',a:'JL Collins',y:2016,l:'강추',n:'인덱스 펀드 투자의 정석.'},
{id:34,th:'t2',t:'하프타임',a:'Bob Buford',y:1994,l:'필독',n:'성공에서 의미로. 인생 2막 전환점.'},
{id:35,th:'t2',t:'강점 혁명',a:'Marcus Buckingham',y:2001,l:'강추',n:'약점 보완보다 강점 강화가 효과적.'},
{id:36,th:'t2',t:'범죄로 태어나다',a:'Trevor Noah',y:2016,l:'강추',n:'아파르트헤이트 속 성장. 유머와 지혜.'},
{id:37,th:'t2',t:'나는 왜 이 일을 하는가',a:'Simon Sinek',y:2009,l:'필독',n:'WHY에서 시작하라. 골든 서클.'},
{id:38,th:'t2',t:'행복의 공식',a:'Mo Gawdat',y:2017,l:'강추',n:'구글 X 임원이 발견한 행복 방정식.'},
{id:39,th:'t2',t:'블루존',a:'Dan Buettner',y:2008,l:'강추',n:'세계 5대 장수 지역의 비밀.'},
{id:40,th:'t2',t:'두 번째 인생',a:'다양한 저자',y:2021,l:'추천',n:'한국 중년의 인생 리셋.'},
{id:41,th:'t2',t:'원씽 (The One Thing)',a:'Gary Keller',y:2013,l:'강추',n:'하나에 집중하면 모든 것이 따라온다.'},
{id:42,th:'t2',t:'나를 돌보는 시간',a:'다양한 저자',y:2022,l:'추천',n:'중년의 자기 돌봄.'},
{id:43,th:'t2',t:'에센셜리즘',a:'Greg McKeown',y:2014,l:'강추',n:'더 적게, 더 잘하라.'},
{id:44,th:'t2',t:'일이 인생의 전부가 아닌 사람에게',a:'다양한 저자',y:2023,l:'추천',n:'일과 삶의 균형.'},
{id:45,th:'t2',t:'수명 연장',a:'David Sinclair',y:2019,l:'강추',n:'노화는 치료 가능한 질병이다.'},

// ===== 신앙·철학 t3 (25) =====
{id:46,th:'t3',t:'순전한 기독교',a:'C.S. Lewis',y:1952,l:'필독',n:'기독교 변증의 고전. 이성으로 접근.',done:true},
{id:47,th:'t3',t:'하나님을 향한 이유',a:'Timothy Keller',y:2008,l:'필독',n:'21세기 C.S. Lewis. 회의주의자의 질문에 답하다.',done:true},
{id:48,th:'t3',t:'하나님을 아는 지식',a:'J.I. Packer',y:1973,l:'필독',n:'신학 지식과 신앙 관계의 차이.',done:true},
{id:49,th:'t3',t:'고백록',a:'Augustine',y:397,l:'필독',n:'인류 최초의 자서전. 당신 안에 쉬기까지.',done:true},
{id:50,th:'t3',t:'고통의 문제',a:'C.S. Lewis',y:1940,l:'강추',n:'선한 신이 왜 고통을 허용하는가.',done:true},
{id:51,th:'t3',t:'하나님을 기뻐하라',a:'John Piper',y:1986,l:'강추',n:'기쁨이 의무보다 강하다.',done:true},
{id:52,th:'t3',t:'기도',a:'Timothy Keller',y:2014,l:'강추',n:'어거스틴과 칼빈으로 배우는 기도.',done:true},
{id:53,th:'t3',t:'스크루테이프의 편지',a:'C.S. Lewis',y:1942,l:'강추',n:'악마의 시각으로 쓴 기독교 윤리.',done:true},
{id:54,th:'t3',t:'그리스도를 본받아',a:'Thomas à Kempis',y:1418,l:'필독',n:'성경 다음으로 많이 읽힌 기독교 서적.',done:true},
{id:55,th:'t3',t:'놀라운 은혜',a:'Philip Yancey',y:1997,l:'필독',n:'은혜가 무엇인지 다시 발견하다.',done:true},
{id:56,th:'t3',t:'하나님의 임재 연습',a:'Brother Lawrence',y:1692,l:'강추',n:'주방에서도 하나님과 함께.',done:true},
{id:57,th:'t3',t:'제자도의 비용',a:'Dietrich Bonhoeffer',y:1937,l:'필독',n:'값싼 은혜 vs 값비싼 은혜.'},
{id:58,th:'t3',t:'감옥에서 보낸 편지',a:'Dietrich Bonhoeffer',y:1953,l:'필독',n:'순교자의 마지막 신학적 성찰.'},
{id:59,th:'t3',t:'탕자의 하나님',a:'Timothy Keller',y:2008,l:'필독',n:'탕자 비유의 재해석. 큰아들의 실수.'},
{id:60,th:'t3',t:'놀라움으로의 여정',a:'C.S. Lewis',y:1955,l:'강추',n:'무신론자가 기독교인이 된 과정.'},
{id:61,th:'t3',t:'슬픔을 관찰하며',a:'C.S. Lewis',y:1961,l:'강추',n:'아내의 죽음 후 신앙의 위기.'},
{id:62,th:'t3',t:'하나님의 추구',a:'A.W. Tozer',y:1948,l:'필독',n:'하나님을 갈망하는 영혼.'},
{id:63,th:'t3',t:'서두름을 제거하라',a:'John Mark Comer',y:2019,l:'필독',n:'빠른 시대에 영적 삶을 사는 법.'},
{id:64,th:'t3',t:'영혼의 성',a:'Teresa of Avila',y:1577,l:'강추',n:'기도와 관상의 7단계.'},
{id:65,th:'t3',t:'사막 교부들의 금언',a:'Various',y:400,l:'강추',n:'초대 교회 수도사들의 지혜.'},
{id:66,th:'t3',t:'천로역정',a:'John Bunyan',y:1678,l:'강추',n:'기독교 순례의 알레고리.'},
{id:67,th:'t3',t:'하나님을 경험하는 삶',a:'Henry Blackaby',y:1990,l:'강추',n:'하나님이 일하시는 곳을 찾아라.'},
{id:68,th:'t3',t:'네 가지 사랑',a:'C.S. Lewis',y:1960,l:'강추',n:'애정·우정·에로스·자비.'},
{id:69,th:'t3',t:'모든 선한 일',a:'Timothy Keller',y:2012,l:'강추',n:'기독교와 직업 소명.'},
{id:70,th:'t3',t:'정원 도시',a:'John Mark Comer',y:2015,l:'강추',n:'일과 안식의 신학.'},

// ===== 동양철학 t4 (20) =====
{id:71,th:'t4',t:'논어',a:'공자',y:-479,l:'필독',n:'2,500년 동아시아 문명의 기초. 수신제가치국평천하.',done:true},
{id:72,th:'t4',t:'도덕경',a:'노자',y:-500,l:'필독',n:'5,000자로 세상을 설명한 역설의 철학.',done:true},
{id:73,th:'t4',t:'장자',a:'장자',y:-300,l:'필독',n:'나비 꿈의 철학자. 자유와 관점의 해방.',done:true},
{id:74,th:'t4',t:'맹자',a:'맹자',y:-372,l:'필독',n:'성선설. 인간 본성은 선하다.',done:true},
{id:75,th:'t4',t:'순자',a:'순자',y:-313,l:'강추',n:'성악설. 교육과 예가 인간을 만든다.',done:true},
{id:76,th:'t4',t:'손자병법',a:'손자',y:-500,l:'필독',n:'싸우지 않고 이기는 것이 최선이다.',done:true},
{id:77,th:'t4',t:'한비자',a:'한비자',y:-280,l:'강추',n:'법·술·세. 법가 사상의 완성.',done:true},
{id:78,th:'t4',t:'묵자',a:'묵자',y:-479,l:'강추',n:'겸애(兼愛). 차별 없는 사랑.',done:true},
{id:79,th:'t4',t:'역경 (易經)',a:'고대 중국',y:-1000,l:'강추',n:'변화만이 변하지 않는다. 64괘의 지혜.',done:true},
{id:80,th:'t4',t:'대학·중용',a:'유교 경전',y:-500,l:'강추',n:'유교의 핵심 두 경전. 수신의 방법.'},
{id:81,th:'t4',t:'사기 열전',a:'사마천',y:-100,l:'강추',n:'중국 역사의 아버지. 인물로 읽는 역사.'},
{id:82,th:'t4',t:'오륜서',a:'미야모토 무사시',y:1645,l:'강추',n:'일본 검도의 바이블. 전략과 정신.'},
{id:83,th:'t4',t:'채근담',a:'홍자성',y:1590,l:'강추',n:'명나라 선비의 인생 경구 모음.'},
{id:84,th:'t4',t:'명심보감',a:'추적',y:1393,l:'추천',n:'한국 전통 도덕 교과서.'},
{id:85,th:'t4',t:'불경 (핵심)',a:'釋迦牟尼',y:-500,l:'강추',n:'팔정도와 사성제. 불교의 핵심.'},
{id:86,th:'t4',t:'반야심경',a:'불교 경전',y:650,l:'추천',n:'260자로 담긴 불교의 정수.'},
{id:87,th:'t4',t:'하버드 중국사',a:'티머시 브룩',y:2010,l:'추천',n:'중국 역사의 흐름 이해.'},
{id:88,th:'t4',t:'일본은 왜 강한가',a:'다양한 저자',y:2015,l:'추천',n:'일본 문화와 사상의 원류.'},
{id:89,th:'t4',t:'한국의 사상',a:'다양한 저자',y:2018,l:'강추',n:'한국 고유의 철학적 전통.'},
{id:90,th:'t4',t:'바가바드 기타 (핵심)',a:'힌두 경전',y:-200,l:'추천',n:'의무와 행동. 인도 철학의 정수.'},

// ===== 역사·인물 t5 (40) =====
{id:91,th:'t5',t:'로마인 이야기 1권',a:'시오노 나나미',y:1992,l:'필독',n:'로마는 하루아침에 이루어지지 않았다.',done:true},
{id:92,th:'t5',t:'로마인 이야기 2권',a:'시오노 나나미',y:1993,l:'필독',n:'한니발 전쟁. 천재 vs 시스템.',done:true},
{id:93,th:'t5',t:'로마인 이야기 3권',a:'시오노 나나미',y:1993,l:'필독',n:'승자의 혼미. 내부 분열의 시작.',done:true},
{id:94,th:'t5',t:'로마인 이야기 4권',a:'시오노 나나미',y:1995,l:'필독',n:'율리우스 카이사르 (상).',done:true},
{id:95,th:'t5',t:'로마인 이야기 5권',a:'시오노 나나미',y:1995,l:'필독',n:'율리우스 카이사르 (하). 암살과 유산.',done:true},
{id:96,th:'t5',t:'로마인 이야기 6권',a:'시오노 나나미',y:1996,l:'필독',n:'팍스 로마나. 200년 평화의 설계.',done:true},
{id:97,th:'t5',t:'로마인 이야기 7권',a:'시오노 나나미',y:1997,l:'필독',n:'악명 높은 황제들.',done:true},
{id:98,th:'t5',t:'로마인 이야기 8권',a:'시오노 나나미',y:1998,l:'필독',n:'위기와 극복. 4황제의 해.',done:true},
{id:99,th:'t5',t:'로마인 이야기 9권',a:'시오노 나나미',y:1999,l:'필독',n:'현명한 군주의 시대.',done:true},
{id:100,th:'t5',t:'로마인 이야기 10권',a:'시오노 나나미',y:1999,l:'필독',n:'모든 길은 로마로 통한다.',done:true},
{id:101,th:'t5',t:'로마인 이야기 11권',a:'시오노 나나미',y:2000,l:'필독',n:'종말의 시작.',done:true},
{id:102,th:'t5',t:'로마인 이야기 12권',a:'시오노 나나미',y:2000,l:'필독',n:'미래의 지도.',done:true},
{id:103,th:'t5',t:'로마인 이야기 13권',a:'시오노 나나미',y:2001,l:'필독',n:'최후의 노력.',done:true},
{id:104,th:'t5',t:'로마인 이야기 14권',a:'시오노 나나미',y:2002,l:'필독',n:'그리스도의 승리.',done:true},
{id:105,th:'t5',t:'로마인 이야기 15권',a:'시오노 나나미',y:2002,l:'필독',n:'로마 세계의 종언.',done:true},
{id:106,th:'t5',t:'라이벌들의 팀',a:'Doris Kearns Goodwin',y:2005,l:'필독',n:'링컨이 경쟁자들로 내각을 구성한 이유.'},
{id:107,th:'t5',t:'스티브 잡스',a:'Walter Isaacson',y:2011,l:'필독',n:'창의성·집착·완벽주의의 초상.'},
{id:108,th:'t5',t:'일론 머스크',a:'Walter Isaacson',y:2023,l:'강추',n:'현 시대 가장 논쟁적인 기업가.'},
{id:109,th:'t5',t:'레오나르도 다빈치',a:'Walter Isaacson',y:2017,l:'강추',n:'천재성의 비밀. 호기심과 관찰.'},
{id:110,th:'t5',t:'스노볼',a:'Alice Schroeder',y:2008,l:'필독',n:'워런 버핏 공인 전기. 복리 인생.'},
{id:111,th:'t5',t:'사피엔스',a:'Yuval Noah Harari',y:2011,l:'필독',n:'인류 역사의 빅픽처.'},
{id:112,th:'t5',t:'호모 데우스',a:'Yuval Noah Harari',y:2015,l:'강추',n:'인류의 다음 아젠다.'},
{id:113,th:'t5',t:'넥서스',a:'Yuval Noah Harari',y:2024,l:'필독',n:'정보 네트워크로 보는 인류사.'},
{id:114,th:'t5',t:'역사의 교훈',a:'Will & Ariel Durant',y:1968,l:'필독',n:'역사의 반복 패턴을 100쪽에 압축.'},
{id:115,th:'t5',t:'왜 국가는 실패하는가',a:'Acemoglu & Robinson',y:2012,l:'필독',n:'포용적 제도 vs 착취적 제도.'},
{id:116,th:'t5',t:'총 균 쇠',a:'Jared Diamond',y:1997,l:'필독',n:'왜 어떤 문명은 다른 문명을 정복했는가.'},
{id:117,th:'t5',t:'나폴레옹',a:'Andrew Roberts',y:2014,l:'강추',n:'전략·리더십·실패의 교훈.'},
{id:118,th:'t5',t:'처칠',a:'Andrew Roberts',y:2018,l:'강추',n:'역경 속에서 위대해진 리더십.'},
{id:119,th:'t5',t:'나쁜 피 (Bad Blood)',a:'John Carreyrou',y:2018,l:'강추',n:'테라노스 사기. 거버넌스 실패.'},
{id:120,th:'t5',t:'나이키 창업기 슈독',a:'Phil Knight',y:2016,l:'필독',n:'나이키 창업기. 집착과 우연.'},
{id:121,th:'t5',t:'반도체 전쟁',a:'Chris Miller',y:2022,l:'필독',n:'반도체 패권 쟁탈전.'},
{id:122,th:'t5',t:'약속의 땅',a:'Barack Obama',y:2020,l:'강추',n:'오바마 대통령 회고록.'},
{id:123,th:'t5',t:'밤 (Night)',a:'Elie Wiesel',y:1960,l:'필독',n:'홀로코스트 생존자의 증언.'},
{id:124,th:'t5',t:'이건희 에세이',a:'이건희',y:1997,l:'강추',n:'마누라와 자식 빼고 다 바꿔라.'},
{id:125,th:'t5',t:'정주영 자서전',a:'정주영',y:1998,l:'강추',n:'이봐, 해봤어? 현대 창업자의 도전.'},
{id:126,th:'t5',t:'강대국의 흥망',a:'Paul Kennedy',y:1987,l:'강추',n:'경제력과 군사력의 관계.'},
{id:127,th:'t5',t:'세계 질서',a:'Henry Kissinger',y:2014,l:'강추',n:'21세기 지정학적 질서.'},
{id:128,th:'t5',t:'덩샤오핑 평전',a:'Ezra Vogel',y:2011,l:'강추',n:'중국 현대화의 설계자.'},
{id:129,th:'t5',t:'침묵의 봄',a:'Rachel Carson',y:1962,l:'강추',n:'환경 운동의 시작.'},
{id:130,th:'t5',t:'빌 게이츠 평전',a:'다양한 저자',y:2020,l:'강추',n:'마이크로소프트에서 자선사업까지.'},

// ===== 전략·경영 t6 (25) =====
{id:131,th:'t6',t:'좋은 전략 나쁜 전략',a:'Richard Rumelt',y:2011,l:'필독',n:'전략의 커널 구조. 진단→정책→행동.'},
{id:132,th:'t6',t:'아웃사이더스',a:'William Thorndike',y:2012,l:'필독',n:'탁월한 CEO는 자본배분을 잘한다.',done:true},
{id:133,th:'t6',t:'7 파워스',a:'Hamilton Helmer',y:2016,l:'필독',n:'사업의 해자 7가지 메커니즘.',done:true},
{id:134,th:'t6',t:'제로 투 원',a:'Peter Thiel',y:2014,l:'필독',n:'복사가 아닌 창조. 독점을 지향하라.'},
{id:135,th:'t6',t:'효과적인 경영자',a:'Peter Drucker',y:1967,l:'필독',n:'효과성이란 무엇인가.'},
{id:136,th:'t6',t:'성과 창출 경영',a:'Andy Grove',y:1983,l:'필독',n:'인텔 CEO의 경영 바이블. OKR의 원형.'},
{id:137,th:'t6',t:'혁신 기업의 딜레마',a:'Clayton Christensen',y:1997,l:'필독',n:'왜 잘나가는 기업이 망하는가.'},
{id:138,th:'t6',t:'좋은 기업을 넘어 위대한 기업으로',a:'Jim Collins',y:2001,l:'강추',n:'플라이휠과 Level 5 리더십.'},
{id:139,th:'t6',t:'블루오션 전략',a:'Kim & Mauborgne',y:2005,l:'강추',n:'경쟁 없는 시장을 만드는 법.'},
{id:140,th:'t6',t:'경쟁전략',a:'Michael Porter',y:1980,l:'필독',n:'5 Forces와 본원적 전략.'},
{id:141,th:'t6',t:'노 룰스 룰스',a:'Reed Hastings',y:2020,l:'강추',n:'넷플릭스 문화. 자유와 책임.'},
{id:142,th:'t6',t:'생각하는 시스템',a:'Donella Meadows',y:2008,l:'필독',n:'시스템 사고의 입문서.'},
{id:143,th:'t6',t:'피라미드 원칙',a:'Barbara Minto',y:1987,l:'강추',n:'맥킨지 문서 작성법의 원전.'},
{id:144,th:'t6',t:'거꾸로 일하기',a:'Colin Bryar',y:2021,l:'강추',n:'아마존의 6페이저 워킹 방식.'},
{id:145,th:'t6',t:'크리에이티비티 주식회사',a:'Ed Catmull',y:2014,l:'강추',n:'픽사의 창의적 조직 문화.'},
{id:146,th:'t6',t:'협상의 심리학',a:'Chris Voss',y:2016,l:'필독',n:'FBI 협상가가 알려주는 설득의 기술.'},
{id:147,th:'t6',t:'예스를 이끌어내는 협상법',a:'Fisher & Ury',y:1981,l:'필독',n:'원칙 협상법. 상호 이익.'},
{id:148,th:'t6',t:'비즈니스 모델의 탄생',a:'Osterwalder',y:2010,l:'강추',n:'비즈니스 모델 캔버스.'},
{id:149,th:'t6',t:'스케일링 업',a:'Verne Harnish',y:2014,l:'강추',n:'성장하는 기업의 4가지 결정.'},
{id:150,th:'t6',t:'플랫폼 레볼루션',a:'Parker & Choudary',y:2016,l:'강추',n:'플랫폼 비즈니스의 메커니즘.'},
{id:151,th:'t6',t:'ESG 경영',a:'다양한 저자',y:2021,l:'강추',n:'지속 가능한 경영의 핵심.'},
{id:152,th:'t6',t:'디지털 전환 전략',a:'다양한 저자',y:2022,l:'강추',n:'기업의 디지털 트랜스포메이션.'},
{id:153,th:'t6',t:'인수합병의 기술',a:'다양한 저자',y:2018,l:'강추',n:'M&A의 실전 가이드.'},
{id:154,th:'t6',t:'조직 문화와 리더십',a:'Edgar Schein',y:2010,l:'필독',n:'문화가 조직을 먹는다.'},
{id:155,th:'t6',t:'구독경제',a:'Tien Tzuo',y:2018,l:'강추',n:'소유에서 구독으로의 전환.'},

// ===== 투자·재무 t7 (25) =====
{id:156,th:'t7',t:'현명한 투자자',a:'Benjamin Graham',y:1949,l:'필독',n:'투자의 성경. Mr. Market과 안전마진.',done:true},
{id:157,th:'t7',t:'가난한 찰리의 연감',a:'Charlie Munger',y:2005,l:'필독',n:'멘탈 모델 격자. 심리적 오류.',done:true},
{id:158,th:'t7',t:'돈의 심리학',a:'Morgan Housel',y:2020,l:'필독',n:'부를 만드는 것은 행동이다.',done:true},
{id:159,th:'t7',t:'돈의 속성',a:'김승호',y:2020,l:'필독',n:'돈은 인격체다. 돈을 대하는 태도.',done:true},
{id:160,th:'t7',t:'투자에서 가장 중요한 것',a:'Howard Marks',y:2011,l:'필독',n:'리스크는 영구적 손실이다.'},
{id:161,th:'t7',t:'원칙 (Principles)',a:'Ray Dalio',y:2017,l:'강추',n:'극단적 투명성. 브리지워터의 원칙.'},
{id:162,th:'t7',t:'변화하는 세계 질서',a:'Ray Dalio',y:2021,l:'강추',n:'제국 흥망의 빅사이클.'},
{id:163,th:'t7',t:'보통주와 특별한 이익',a:'Philip Fisher',y:1958,l:'필독',n:'성장주 투자의 바이블.'},
{id:164,th:'t7',t:'월가에서 이기는 법',a:'Peter Lynch',y:1989,l:'강추',n:'개인 투자자가 기관을 이길 수 있다.'},
{id:165,th:'t7',t:'랜덤 워크 투자 수업',a:'Burton Malkiel',y:1973,l:'강추',n:'인덱스 펀드가 최선이다.'},
{id:166,th:'t7',t:'반취약성',a:'Nassim Taleb',y:2012,l:'필독',n:'충격에서 이익을 얻는 시스템.'},
{id:167,th:'t7',t:'블랙 스완',a:'Nassim Taleb',y:2007,l:'필독',n:'불가능한 일이 일어나는 이유.'},
{id:168,th:'t7',t:'같은 것은 영원하다',a:'Morgan Housel',y:2023,l:'강추',n:'세상을 이해하는 불변의 원칙들.'},
{id:169,th:'t7',t:'워런 버핏의 주주서한',a:'Warren Buffett',y:2015,l:'필독',n:'버핏의 투자 철학 총정리.'},
{id:170,th:'t7',t:'21세기 자본',a:'Thomas Piketty',y:2013,l:'강추',n:'r > g. 자본수익률이 성장률 초과.'},
{id:171,th:'t7',t:'빅 쇼트',a:'Michael Lewis',y:2010,l:'강추',n:'금융 위기를 예측한 사람들.'},
{id:172,th:'t7',t:'ETF 투자 교과서',a:'다양한 저자',y:2022,l:'강추',n:'ETF로 시작하는 투자.'},
{id:173,th:'t7',t:'미국 주식으로 부자되기',a:'다양한 저자',y:2021,l:'강추',n:'서학개미 투자 가이드.'},
{id:174,th:'t7',t:'부동산 투자의 핵심',a:'다양한 저자',y:2021,l:'강추',n:'한국 부동산 투자 전략.'},
{id:175,th:'t7',t:'세금의 모든 것',a:'다양한 저자',y:2022,l:'강추',n:'한국 세금 완전 정복.'},
{id:176,th:'t7',t:'숫자가 보이는 회계',a:'다양한 저자',y:2020,l:'강추',n:'재무제표 읽는 법.'},
{id:177,th:'t7',t:'인플레이션 시대 투자',a:'다양한 저자',y:2022,l:'강추',n:'고물가 시대 자산 방어.'},
{id:178,th:'t7',t:'ISA·IRP 완전 활용법',a:'다양한 저자',y:2023,l:'강추',n:'세금 혜택 투자 계좌 활용.'},
{id:179,th:'t7',t:'가치 투자',a:'Bruce Greenwald',y:2001,l:'강추',n:'그레이엄&도드의 현대적 적용.'},
{id:180,th:'t7',t:'투기의 역사',a:'Charles Kindleberger',y:1978,l:'강추',n:'거품과 패닉의 반복 패턴.'},

// ===== 스타트업·창업 t8 (15) =====
{id:181,th:'t8',t:'하드씽',a:'Ben Horowitz',y:2014,l:'필독',n:'창업의 어두운 면. CEO의 생존 가이드.'},
{id:182,th:'t8',t:'린 스타트업',a:'Eric Ries',y:2011,l:'필독',n:'Build-Measure-Learn. MVP와 피벗.'},
{id:183,th:'t8',t:'슈독',a:'Phil Knight',y:2016,l:'필독',n:'나이키 창업기. 집착과 우연.',done:true},
{id:184,th:'t8',t:'벤처 딜',a:'Brad Feld',y:2011,l:'필독',n:'VC 투자 계약서의 모든 것.'},
{id:185,th:'t8',t:'엄마 테스트',a:'Rob Fitzpatrick',y:2013,l:'필독',n:'고객 인터뷰에서 진짜 정보 얻기.'},
{id:186,th:'t8',t:'천만 달러 제안',a:'Alex Hormozi',y:2021,l:'필독',n:'저항할 수 없는 제안을 만드는 법.'},
{id:187,th:'t8',t:'훅 (Hooked)',a:'Nir Eyal',y:2014,l:'강추',n:'습관을 만드는 제품 설계.'},
{id:188,th:'t8',t:'영감 (Inspired)',a:'Marty Cagan',y:2017,l:'강추',n:'제품 관리의 바이블.'},
{id:189,th:'t8',t:'보라색 소',a:'Seth Godin',y:2003,l:'강추',n:'눈에 띄는 것만이 살아남는다.'},
{id:190,th:'t8',t:'이것이 마케팅이다',a:'Seth Godin',y:2018,l:'강추',n:'가장 작은 가능한 시장에 집중.'},
{id:191,th:'t8',t:'창업자의 딜레마',a:'Noam Wasserman',y:2012,l:'강추',n:'부자가 될 것인가 왕이 될 것인가.'},
{id:192,th:'t8',t:'EOS 트랙션',a:'Gino Wickman',y:2011,l:'강추',n:'기업가 운영 시스템.'},
{id:193,th:'t8',t:'에브리씽 스토어',a:'Brad Stone',y:2013,l:'강추',n:'아마존과 베조스.'},
{id:194,th:'t8',t:'AI 시대 창업',a:'다양한 저자',y:2023,l:'강추',n:'인공지능을 활용한 창업 기회.'},
{id:195,th:'t8',t:'크리에이터 이코노미',a:'다양한 저자',y:2022,l:'강추',n:'개인 창작자의 수익화 전략.'},

// ===== 리더십·조직 t9 (20) =====
{id:196,th:'t9',t:'근본적 솔직함',a:'Kim Scott',y:2017,l:'필독',n:'솔직하되 인간적이어야 한다.'},
{id:197,th:'t9',t:'팀 오브 팀스',a:'Stanley McChrystal',y:2015,l:'필독',n:'복잡한 환경의 조직 운영.'},
{id:198,th:'t9',t:'목표로 관리하라',a:'John Doerr',y:2018,l:'필독',n:'OKR의 교과서.'},
{id:199,th:'t9',t:'문화 코드',a:'Daniel Coyle',y:2018,l:'강추',n:'최고 팀의 3가지 조건.'},
{id:200,th:'t9',t:'드라이브',a:'Daniel Pink',y:2009,l:'강추',n:'자율성·숙달·목적. 내적 동기.'},
{id:201,th:'t9',t:'두려움 없는 조직',a:'Amy Edmondson',y:2018,l:'강추',n:'심리적 안전감의 과학.'},
{id:202,th:'t9',t:'팀의 5가지 기능 장애',a:'Patrick Lencioni',y:2002,l:'필독',n:'팀이 실패하는 5가지 이유.'},
{id:203,th:'t9',t:'리더십과 자기기만',a:'Arbinger Institute',y:2000,l:'필독',n:'상자 안에 있는 리더.'},
{id:204,th:'t9',t:'리더는 마지막에 먹는다',a:'Simon Sinek',y:2014,l:'강추',n:'섬기는 리더십.'},
{id:205,th:'t9',t:'배를 돌려라',a:'David Marquet',y:2013,l:'강추',n:'리더-리더 모델. 권한 위임.'},
{id:206,th:'t9',t:'코칭의 기술',a:'Michael Bungay Stanier',y:2016,l:'강추',n:'7가지 코칭 질문.'},
{id:207,th:'t9',t:'감성 리더십',a:'Daniel Goleman',y:2001,l:'필독',n:'EQ가 리더십 성과를 결정한다.'},
{id:208,th:'t9',t:'승가자 vs 지배자',a:'Liz Wiseman',y:2010,l:'강추',n:'멀티플라이어 리더십.'},
{id:209,th:'t9',t:'취약성의 힘',a:'Brené Brown',y:2012,l:'강추',n:'취약함이 용기의 원천이다.'},
{id:210,th:'t9',t:'도구적 리더십',a:'Stephen Bungay',y:2011,l:'강추',n:'전략 실행의 군사적 원칙.'},
{id:211,th:'t9',t:'리더십 파이프라인',a:'Charan et al.',y:2001,l:'강추',n:'조직의 리더십 개발 체계.'},
{id:212,th:'t9',t:'신뢰 기반 리더십',a:'David Horsager',y:2012,l:'강추',n:'신뢰가 경쟁 우위가 되는 이유.'},
{id:213,th:'t9',t:'일론 머스크 리더십',a:'다양한 저자',y:2022,l:'추천',n:'극단적 실행력의 리더십.'},
{id:214,th:'t9',t:'봉사적 리더십',a:'Robert Greenleaf',y:1970,l:'강추',n:'섬기는 리더십의 원전.'},
{id:215,th:'t9',t:'편집증자만이 살아남는다',a:'Andy Grove',y:1996,l:'필독',n:'전략적 변곡점 대응.'},

// ===== 생산성·사고 t10 (20) =====
{id:216,th:'t10',t:'딥 워크',a:'Cal Newport',y:2016,l:'필독',n:'집중이 희귀해진 시대. 집중이 경쟁우위.',done:true},
{id:217,th:'t10',t:'아주 작은 습관의 힘',a:'James Clear',y:2018,l:'강추',n:'1%씩 나아지면 37배가 된다.',done:true},
{id:218,th:'t10',t:'우리는 왜 잠을 자야 할까',a:'Matthew Walker',y:2017,l:'강추',n:'수면이 생산성의 가장 중요한 변수.',done:true},
{id:219,th:'t10',t:'몰입 (Flow)',a:'Mihaly Csikszentmihalyi',y:1990,l:'강추',n:'행복은 완전한 집중에서 온다.',done:true},
{id:220,th:'t10',t:'그릿',a:'Angela Duckworth',y:2016,l:'강추',n:'재능보다 열정과 끈기가 성공.',done:true},
{id:221,th:'t10',t:'슬로우 프로덕티비티',a:'Cal Newport',y:2024,l:'필독',n:'지속 가능한 생산성의 새로운 정의.'},
{id:222,th:'t10',t:'두 번째 뇌 만들기',a:'Tiago Forte',y:2022,l:'필독',n:'개인 지식 관리 시스템.'},
{id:223,th:'t10',t:'생각에 관한 생각',a:'Daniel Kahneman',y:2011,l:'필독',n:'시스템1·2 사고. 우리가 어떻게 틀리는가.'},
{id:224,th:'t10',t:'팩트풀니스',a:'Hans Rosling',y:2018,l:'필독',n:'세계는 당신이 생각보다 좋아지고 있다.'},
{id:225,th:'t10',t:'숨겨진 잠재력',a:'Adam Grant',y:2023,l:'필독',n:'시작 지점이 아닌 성장에 집중하라.'},
{id:226,th:'t10',t:'씽크 어게인',a:'Adam Grant',y:2021,l:'강추',n:'다시 생각하는 힘.'},
{id:227,th:'t10',t:'클리어 씽킹',a:'Shane Parrish',y:2023,l:'필독',n:'더 명확하게 생각하는 법.'},
{id:228,th:'t10',t:'위대한 멘탈 모델',a:'Shane Parrish',y:2019,l:'필독',n:'세상을 이해하는 핵심 프레임워크.'},
{id:229,th:'t10',t:'레인지',a:'David Epstein',y:2019,l:'강추',n:'전문화 시대에 폭넓은 경험이 강력한 이유.'},
{id:230,th:'t10',t:'결정적 선택',a:'Chip & Dan Heath',y:2013,l:'강추',n:'더 나은 의사결정을 위한 4단계.'},
{id:231,th:'t10',t:'80/20 원칙',a:'Richard Koch',y:1997,l:'강추',n:'20%의 노력으로 80%의 결과.'},
{id:232,th:'t10',t:'어텐션 스팬',a:'Gloria Mark',y:2023,l:'필독',n:'집중력 위기와 회복 방법.'},
{id:233,th:'t10',t:'노이즈',a:'Kahneman & Sunstein',y:2021,l:'강추',n:'같은 조건에서 왜 다른 판단이 나오나.',done:true},
{id:234,th:'t10',t:'시스템 사고',a:'Donella Meadows',y:2008,l:'필독',n:'복잡계를 이해하는 프레임워크.'},
{id:235,th:'t10',t:'GTD',a:'David Allen',y:2001,l:'강추',n:'스트레스 없이 일 처리하기.'},

// ===== 심리학·행동 t11 (20) =====
{id:236,th:'t11',t:'마인드셋',a:'Carol Dweck',y:2006,l:'필독',n:'성장 마인드셋 vs 고정 마인드셋.',done:true},
{id:237,th:'t11',t:'감성 지능',a:'Daniel Goleman',y:1995,l:'강추',n:'EQ가 IQ보다 중요한 이유.',done:true},
{id:238,th:'t11',t:'뇌, 욕망의 비밀',a:'Robert Sapolsky',y:2017,l:'강추',n:'인간 행동의 신경생물학.',done:true},
{id:239,th:'t11',t:'영향력',a:'Robert Cialdini',y:1984,l:'필독',n:'설득의 6가지 원칙.',done:true},
{id:240,th:'t11',t:'불안한 세대',a:'Jonathan Haidt',y:2024,l:'필독',n:'스마트폰과 소셜미디어가 10대를 망친다.'},
{id:241,th:'t11',t:'몸은 기억한다',a:'Bessel van der Kolk',y:2014,l:'필독',n:'트라우마와 신체의 관계.'},
{id:242,th:'t11',t:'정상이라는 신화',a:'Gabor Maté',y:2022,l:'필독',n:'트라우마, 질병, 사회의 관계.'},
{id:243,th:'t11',t:'콰이어트',a:'Susan Cain',y:2012,l:'강추',n:'내향인의 힘. 조용함이 강점이다.'},
{id:244,th:'t11',t:'이것을 왜 아무도 말해주지 않았을까',a:'Julie Smith',y:2022,l:'필독',n:'심리학자가 알려주는 감정 관리법.'},
{id:245,th:'t11',t:'자기 자비',a:'Kristin Neff',y:2011,l:'강추',n:'자기 자신에게 친절하라.'},
{id:246,th:'t11',t:'애착 이론',a:'Amir Levine',y:2010,l:'강추',n:'성인 애착 유형과 관계.'},
{id:247,th:'t11',t:'루시퍼 효과',a:'Philip Zimbardo',y:2007,l:'강추',n:'선한 사람이 악을 행하는 조건.'},
{id:248,th:'t11',t:'대담하게',a:'Brené Brown',y:2012,l:'강추',n:'취약성을 통한 성장.'},
{id:249,th:'t11',t:'행복의 가설',a:'Jonathan Haidt',y:2006,l:'강추',n:'고대 지혜와 현대 과학의 교차점.'},
{id:250,th:'t11',t:'의지력의 본능',a:'Kelly McGonigal',y:2011,l:'강추',n:'자기 통제의 과학.'},
{id:251,th:'t11',t:'느끼는 것을 허락하라',a:'Marc Brackett',y:2019,l:'강추',n:'감정 지능의 과학과 실천.'},
{id:252,th:'t11',t:'긍정 심리학',a:'Martin Seligman',y:2002,l:'강추',n:'행복을 과학적으로 연구하다.'},
{id:253,th:'t11',t:'감정 민첩성',a:'Susan David',y:2016,l:'강추',n:'감정에 지배받지 않는 법.'},
{id:254,th:'t11',t:'행동 경제학',a:'Dan Ariely',y:2008,l:'강추',n:'비합리적 인간의 예측 가능성.'},
{id:255,th:'t11',t:'번아웃',a:'Emily Nagoski',y:2019,l:'강추',n:'번아웃의 원인과 회복.'},

// ===== 가정·자녀 t12 (20) =====
{id:256,th:'t12',t:'온전한 뇌 육아법',a:'Daniel Siegel',y:2011,l:'필독',n:'아이 뇌 발달에 맞는 부모 대응법.'},
{id:257,th:'t12',t:'아이의 마음을 여는 대화법',a:'Faber & Mazlish',y:1980,l:'필독',n:'아이의 감정을 인정하는 대화.'},
{id:258,th:'t12',t:'사랑의 언어',a:'Gary Chapman',y:1992,l:'강추',n:'사람마다 사랑 표현법이 다르다.',done:true},
{id:259,th:'t12',t:'행복한 부부',a:'John Gottman',y:1999,l:'강추',n:'이혼 예측률 94%의 연구자의 결혼 7원칙.'},
{id:260,th:'t12',t:'자기주도 아이',a:'Stixrud & Johnson',y:2018,l:'강추',n:'통제 대신 자율성.'},
{id:261,th:'t12',t:'감성 코칭',a:'John Gottman',y:1997,l:'강추',n:'아이의 감정 다루는 법.'},
{id:262,th:'t12',t:'성공하는 아이',a:'Esther Wojcicki',y:2019,l:'강추',n:'구글·유튜브 CEO 어머니의 교육법.'},
{id:263,th:'t12',t:'드라마 없는 훈육',a:'Siegel & Bryson',y:2014,l:'강추',n:'아이의 뇌를 발달시키는 훈육.'},
{id:264,th:'t12',t:'아이는 어떻게 성공하는가',a:'Paul Tough',y:2012,l:'강추',n:'성격 강점이 성적보다 중요하다.'},
{id:265,th:'t12',t:'십대 뇌',a:'Frances Jensen',y:2015,l:'강추',n:'사춘기 자녀를 이해하는 과학.'},
{id:266,th:'t12',t:'아버지의 영향력',a:'다양한 저자',y:2022,l:'필독',n:'아버지가 자녀에게 미치는 영향.'},
{id:267,th:'t12',t:'디지털 시대 자녀 교육',a:'다양한 저자',y:2022,l:'필독',n:'스마트폰 과의존 해결책.'},
{id:268,th:'t12',t:'포용의 파트너',a:'Esther Perel',y:2006,l:'강추',n:'현대 파트너십의 재정의.'},
{id:269,th:'t12',t:'무조건적 양육',a:'Alfie Kohn',y:2005,l:'강추',n:'조건 없는 사랑이 진짜 사랑이다.'},
{id:270,th:'t12',t:'아이들을 붙잡아라',a:'Gordon Neufeld',y:2004,l:'강추',n:'부모와 자녀의 애착 관계.'},
{id:271,th:'t12',t:'경제 교육',a:'다양한 저자',y:2022,l:'강추',n:'아이에게 돈을 가르치는 법.'},
{id:272,th:'t12',t:'회복 탄력성 키우기',a:'다양한 저자',y:2022,l:'강추',n:'역경을 이기는 아이.'},
{id:273,th:'t12',t:'부모 마음 공부',a:'다양한 저자',y:2021,l:'강추',n:'부모 자신의 내면 치유.'},
{id:274,th:'t12',t:'결혼의 의미',a:'Timothy Keller',y:2011,l:'강추',n:'기독교적 결혼관의 재정의.'},
{id:275,th:'t12',t:'함께하는 식사',a:'다양한 저자',y:2020,l:'강추',n:'가족 식사가 아이에게 주는 것.'},

// ===== 기술·미래 t13 (15) =====
{id:276,th:'t13',t:'미래의 물결 (The Coming Wave)',a:'Mustafa Suleyman',y:2023,l:'필독',n:'DeepMind 공동창업자의 경고.'},
{id:277,th:'t13',t:'제2의 기계 시대',a:'Brynjolfsson & McAfee',y:2014,l:'필독',n:'AI와 자동화가 경제에 미치는 영향.'},
{id:278,th:'t13',t:'AI 슈퍼파워',a:'Kai-Fu Lee',y:2018,l:'강추',n:'미국 vs 중국 AI 패권 경쟁.'},
{id:279,th:'t13',t:'생명 3.0',a:'Max Tegmark',y:2017,l:'강추',n:'AGI 이후의 미래 시나리오.'},
{id:280,th:'t13',t:'권력과 진보',a:'Acemoglu & Johnson',y:2023,l:'강추',n:'기술 진보가 항상 인간에게 이롭지 않다.'},
{id:281,th:'t13',t:'제너레이티브 AI',a:'다양한 저자',y:2023,l:'필독',n:'생성형 AI의 현재와 미래.'},
{id:282,th:'t13',t:'챗GPT와 일의 미래',a:'다양한 저자',y:2023,l:'강추',n:'AI 시대 직장인의 대응 전략.'},
{id:283,th:'t13',t:'넥스트 인터넷',a:'다양한 저자',y:2022,l:'추천',n:'Web3와 메타버스의 가능성.'},
{id:284,th:'t13',t:'기후 변화의 과학',a:'다양한 저자',y:2022,l:'강추',n:'기후 위기의 현실과 대응.'},
{id:285,th:'t13',t:'양자 컴퓨팅',a:'다양한 저자',y:2021,l:'추천',n:'다음 기술 혁명의 이해.'},
{id:286,th:'t13',t:'바이오테크 혁명',a:'다양한 저자',y:2022,l:'강추',n:'합성 생물학과 유전자 편집.'},
{id:287,th:'t13',t:'장수 코드',a:'Andrew Steele',y:2020,l:'강추',n:'노화 역전의 과학.'},
{id:288,th:'t13',t:'스마트 팩토리',a:'다양한 저자',y:2021,l:'추천',n:'제조업의 4차 산업혁명.'},
{id:289,th:'t13',t:'우주의 시작',a:'Stephen Hawking',y:1988,l:'강추',n:'시간의 역사. 우주를 이해하다.'},
{id:290,th:'t13',t:'사피엔스와 AI',a:'다양한 저자',y:2023,l:'강추',n:'인간과 AI의 공존 방법.'},

// ===== 경제학·거시 t14 (10) =====
{id:291,th:'t14',t:'행동 경제학 (이상 행동 경제학)',a:'Richard Thaler',y:2015,l:'강추',n:'행동경제학의 아버지. 인간은 비합리적.',done:true},
{id:292,th:'t14',t:'역사의 종말',a:'Francis Fukuyama',y:1992,l:'강추',n:'자유민주주의의 최후 승리?'},
{id:293,th:'t14',t:'넛지',a:'Thaler & Sunstein',y:2008,l:'강추',n:'선택 설계로 더 나은 결정을.'},
{id:294,th:'t14',t:'문명의 충돌',a:'Samuel Huntington',y:1996,l:'강추',n:'21세기 갈등의 예측.'},
{id:295,th:'t14',t:'발전은 무엇인가',a:'Amartya Sen',y:1999,l:'강추',n:'자유로서의 발전.'},
{id:296,th:'t14',t:'동물의 본능',a:'Akerlof & Shiller',y:2009,l:'강추',n:'비이성적 경제 행동의 5가지 본능.'},
{id:297,th:'t14',t:'경제학의 배신',a:'Ha-Joon Chang',y:2010,l:'강추',n:'주류 경제학의 신화를 깨다.'},
{id:298,th:'t14',t:'한국 경제 대전환',a:'다양한 저자',y:2023,l:'강추',n:'저성장 시대 한국 경제의 방향.'},
{id:299,th:'t14',t:'글로벌 공급망 위기',a:'다양한 저자',y:2022,l:'추천',n:'탈세계화와 공급망 재편.'},
{id:300,th:'t14',t:'인구 절벽',a:'Harry Dent',y:2014,l:'강추',n:'인구 구조가 경제를 결정한다.'},
];

const THEMES=['전체',...Object.keys(TH)];
const LEVELS=['전체','필독','강추','추천'];
const DONES=['전체','완료','예정'];
let curT='전체',curL='전체',curD='전체',curS='';

function getFiltered(){
  return BOOKS.filter(b=>{
    const mt=curT==='전체'||b.th===curT;
    const ml=curL==='전체'||b.l===curL;
    const q=curS.toLowerCase();
    const ms=!q||b.t.toLowerCase().includes(q)||b.a.toLowerCase().includes(q);
    const md=curD==='전체'||(curD==='완료'?b.done:!b.done);
    return mt&&ml&&ms&&md;
  });
}

function buildSidebar(){
  const doneCount=BOOKS.filter(b=>b.done).length;
  document.getElementById('hd').textContent=doneCount;
  document.getElementById('hr').textContent=BOOKS.length-doneCount;
  const pct=((doneCount/BOOKS.length)*100).toFixed(1);
  document.getElementById('hpct').textContent=pct+'%';
  document.getElementById('hpf').style.width=pct+'%';
  const tl=document.getElementById('tlist');
  tl.innerHTML=THEMES.map(th=>{
    const cnt=th==='전체'?BOOKS.length:BOOKS.filter(b=>b.th===th).length;
    const dn=th==='전체'?doneCount:BOOKS.filter(b=>b.th===th&&b.done).length;
    const nm=th==='전체'?'📖 전체 보기':TH[th].n;
    return`<button class="tb${curT===th?' act':''}" onclick="setT('${th}')"><span style="overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${nm}</span><span class="c">${dn}/${cnt}</span></button>`;
  }).join('');
}

function buildFilters(){
  document.getElementById('lvf').innerHTML=LEVELS.map(l=>`<button class="fb${curL===l?' act':''}" onclick="setL('${l}')">${l}</button>`).join('');
  document.getElementById('dnf').innerHTML=DONES.map(d=>`<button class="fb${curD===d?d==='완료'?' act v':' act':''}" onclick="setD('${d}')">${d}</button>`).join('');
}

function render(){
  const f=getFiltered();
  document.getElementById('rc').textContent=f.length+'권';
  const grid=document.getElementById('grid');
  if(!f.length){grid.innerHTML='<div id="empty">검색 결과가 없습니다</div>';return;}
  grid.innerHTML=f.map(b=>{
    const th=TH[b.th]||{bg:'#1a1a1a',c:'#aaa'};
    const lc=b.done?LV['완료']:(LV[b.l]||{bg:'#333',c:'#aaa'});
    const yr=b.y>0?b.y:'BC '+Math.abs(b.y);
    return`<div class="card${b.done?' done':''}">
<div class="ct">
<span class="th-b" style="background:${th.bg};color:${th.c}">${th.n}</span>
<span class="lv-b" style="background:${lc.bg};color:${lc.c}">${b.done?'✅ 완료':b.l}</span>
</div>
<div class="cnum">#${b.id}</div>
<div class="ctit">${b.t}</div>
<div class="cauth">${b.a} · ${yr}</div>
<div class="cnote">${b.n}</div>
</div>`;
  }).join('');
}

function setT(t){curT=t;buildSidebar();render();}
function setL(l){curL=l;buildFilters();render();}
function setD(d){curD=d;buildFilters();render();}
document.getElementById('search').addEventListener('input',e=>{curS=e.target.value;render();});
buildSidebar();buildFilters();render();
</script>
</body>
</html>
