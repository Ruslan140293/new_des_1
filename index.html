<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Exchange37 — Криптообмен</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet"/>
<script src="https://unpkg.com/react@18.3.1/umd/react.development.js" integrity="sha384-hD6/rw4ppMLGNu3tX5cjIb+uRZ7UkRJ6BPkLpg4hAu/6onKUg4lLsHAs9EBPT82L" crossorigin="anonymous"></script>
<script src="https://unpkg.com/react-dom@18.3.1/umd/react-dom.development.js" integrity="sha384-u6aeetuaXnQ38mYT8rp6sbXaQe3NL9t+IBXmnYxwkUI2Hw4bsp2Wvmx4yRQF1uAm" crossorigin="anonymous"></script>
<script src="https://unpkg.com/@babel/standalone@7.29.0/babel.min.js" integrity="sha384-m08KidiNqLdpJqLq95G/LEi8Qvjl/xUYll3QILypMoQ65QorJ9Lvtp2RXYGBFj1y" crossorigin="anonymous"></script>
<style>
:root {
  --bg: #07090f;
  --bg2: #0a0d1a;
  --card: #0f1524;
  --card2: #141c30;
  --border: rgba(247,147,26,0.13);
  --border2: rgba(247,147,26,0.28);
  --accent: #F7931A;
  --accent-glow: rgba(247,147,26,0.35);
  --accent-dim: rgba(247,147,26,0.1);
  --teal: #4FC8C4;
  --text: #e2e8f0;
  --text2: #8899b4;
  --muted: #3d4f6e;
  --success: #4ade80;
  --warning: #fb923c;
  --r: 10px;
  --r2: 16px;
  --fh: 'Space Grotesk', sans-serif;
  --fb: 'Inter', sans-serif;
}
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--fb);overflow-x:hidden;-webkit-font-smoothing:antialiased}
h1,h2,h3,h4{font-family:var(--fh)}
::-webkit-scrollbar{width:5px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--border2);border-radius:3px}
input,select,button,textarea{font-family:var(--fb)}

/* ── HEADER ── */
.hdr{position:fixed;top:0;left:0;right:0;z-index:100;height:66px;padding:0 40px;display:flex;align-items:center;justify-content:space-between;background:rgba(7,9,15,0.7);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);transition:background .3s,box-shadow .3s}
.hdr.scrolled{background:rgba(7,9,15,0.97);box-shadow:0 4px 40px rgba(0,0,0,.5)}
.logo{display:flex;align-items:center;gap:10px;text-decoration:none;font-family:var(--fh);font-weight:700;font-size:21px;color:var(--text)}
.logo-icon{width:34px;height:34px;background:linear-gradient(135deg,var(--accent),var(--teal));border-radius:8px;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.logo em{color:var(--accent);font-style:normal}
.nav{display:flex;gap:28px}
.nav a{color:var(--text2);text-decoration:none;font-size:14px;font-weight:500;transition:color .2s}
.nav a:hover{color:var(--text)}
.hdr-r{display:flex;align-items:center;gap:14px}
.langs{display:flex;background:var(--card);border:1px solid var(--border);border-radius:8px;overflow:hidden}
.lang{padding:5px 9px;font-size:12px;font-weight:700;letter-spacing:.5px;color:var(--text2);background:none;border:none;cursor:pointer;transition:all .2s}
.lang.on{background:var(--accent);color:#fff}
.btn-login{padding:8px 18px;border:1px solid var(--accent);color:var(--accent);background:transparent;border-radius:8px;font-size:13px;font-weight:600;cursor:pointer;transition:all .2s}
.btn-login:hover{background:var(--accent);color:#fff;box-shadow:0 0 20px var(--accent-glow)}
.ham{display:none;flex-direction:column;gap:5px;cursor:pointer;background:none;border:none;padding:4px}
.ham span{width:22px;height:2px;background:var(--text);border-radius:2px;display:block;transition:all .3s}

/* ── HERO ── */
.hero{min-height:100vh;padding:120px 40px 80px;display:flex;flex-direction:column;align-items:center;position:relative;overflow:hidden;background:radial-gradient(ellipse 80% 50% at 50% -10%,rgba(247,147,26,.1) 0%,transparent 70%)}
.hero-canvas{position:absolute;inset:0;z-index:0;pointer-events:none}
.hero-title{font-size:clamp(32px,5vw,60px);font-weight:700;text-align:center;line-height:1.1;margin-bottom:14px;position:relative;z-index:1}
.hero-title .grad{background:linear-gradient(130deg,#fff 20%,var(--accent) 80%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
.hero-sub{color:var(--text2);text-align:center;font-size:17px;max-width:500px;margin-bottom:44px;position:relative;z-index:1;line-height:1.65;text-wrap:pretty}

/* ── EXCHANGE FORM ── */
.ex-wrap{width:100%;max-width:1060px;position:relative;z-index:1}
.ex-card{background:rgba(14,20,40,.88);backdrop-filter:blur(24px);border:1px solid var(--border2);border-radius:22px;padding:36px;box-shadow:0 24px 80px rgba(0,0,0,.55),inset 0 1px 0 rgba(255,255,255,.04)}
.ex-cols{display:grid;grid-template-columns:1fr 52px 1fr;gap:0;align-items:start}
.col-label{font-size:11px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--text2);margin-bottom:18px;display:flex;align-items:center;gap:8px}
.col-label .dot{width:8px;height:8px;border-radius:50%;background:var(--accent);box-shadow:0 0 8px var(--accent)}
.col-label .dot.t{background:var(--teal);box-shadow:0 0 8px var(--teal)}
.ex-div{display:flex;flex-direction:column;align-items:center;justify-content:center;padding-top:34px}
.swap{width:42px;height:42px;border-radius:50%;background:var(--card2);border:1px solid var(--border2);color:var(--accent);cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:18px;transition:all .3s}
.swap:hover{background:var(--accent);color:#fff;border-color:var(--accent);box-shadow:0 0 20px var(--accent-glow);transform:rotate(180deg)}
.fg{margin-bottom:13px}
.fl{display:block;font-size:11px;font-weight:500;color:var(--text2);margin-bottom:5px;letter-spacing:.2px}
.fi,.fs{width:100%;padding:10px 13px;background:var(--card2);border:1px solid var(--border);border-radius:var(--r);color:var(--text);font-size:14px;outline:none;transition:border-color .2s,box-shadow .2s;appearance:none;-webkit-appearance:none}
.fi:focus,.fs:focus{border-color:var(--accent);box-shadow:0 0 0 3px rgba(123,143,232,.14)}
.fi:disabled{opacity:.65;cursor:not-allowed}
.fi.comm{color:var(--accent);font-weight:600;background:rgba(123,143,232,.05);border-color:rgba(123,143,232,.22)}
.fi.recv{color:var(--teal);font-weight:600;background:rgba(79,200,196,.05);border-color:rgba(79,200,196,.22)}
.sw{position:relative}
.sw::after{content:'▾';position:absolute;right:11px;top:50%;transform:translateY(-50%);color:var(--text2);pointer-events:none;font-size:11px}
.curr-row{display:flex;gap:9px}
.curr-icon{width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:15px;font-weight:700;flex-shrink:0;align-self:flex-end;margin-bottom:1px}
.cbx{display:flex;align-items:flex-start;gap:9px;margin-top:11px;cursor:pointer}
.cbx input{width:15px;height:15px;flex-shrink:0;margin-top:2px;accent-color:var(--accent);cursor:pointer}
.cbx label{font-size:12px;color:var(--text2);cursor:pointer;line-height:1.5;text-wrap:pretty}
.cbx label a{color:var(--accent);text-decoration:none}

/* AML */
.aml{margin-top:26px;background:rgba(251,146,60,.05);border:1px solid rgba(251,146,60,.2);border-radius:var(--r2);padding:22px 26px}
.aml-head{display:flex;align-items:center;gap:10px;margin-bottom:10px}
.aml-badge{background:rgba(251,146,60,.15);color:var(--warning);font-size:10px;font-weight:700;padding:3px 8px;border-radius:4px;letter-spacing:1px}
.aml-title{font-size:15px;font-weight:600}
.aml-desc{font-size:13px;color:var(--text2);margin-bottom:14px;line-height:1.6;text-wrap:pretty}
.aml-acts{display:flex;flex-wrap:wrap;align-items:center;gap:16px}
.btn-bc{padding:8px 16px;background:rgba(251,146,60,.12);border:1px solid rgba(251,146,60,.28);color:var(--warning);border-radius:8px;font-size:13px;font-weight:600;cursor:pointer;text-decoration:none;display:inline-flex;align-items:center;gap:6px;transition:all .2s}
.btn-bc:hover{background:rgba(251,146,60,.2);box-shadow:0 0 14px rgba(251,146,60,.2)}
.aml-radios{display:flex;flex-wrap:wrap;gap:14px}
.radio-opt{display:flex;align-items:center;gap:7px;cursor:pointer}
.radio-opt input{accent-color:var(--accent);cursor:pointer;width:14px;height:14px}
.radio-opt span{font-size:13px;color:var(--text2)}
.ex-foot{margin-top:26px;display:flex;justify-content:center}
.btn-main{padding:14px 48px;background:linear-gradient(135deg,var(--accent) 0%,#5A6FD8 100%);color:#fff;border:none;border-radius:var(--r);font-size:16px;font-weight:700;cursor:pointer;font-family:var(--fh);transition:all .25s;box-shadow:0 6px 24px var(--accent-glow);letter-spacing:.3px}
.btn-main:hover:not(:disabled){transform:translateY(-2px);box-shadow:0 12px 36px var(--accent-glow)}
.btn-main:disabled{opacity:.42;cursor:not-allowed}

/* ── PARTNERS ── */
.partners{padding:52px 0;background:var(--bg2);border-top:1px solid var(--border);border-bottom:1px solid var(--border);overflow:hidden}
.partners-lbl{text-align:center;font-size:11px;font-weight:600;letter-spacing:2px;color:var(--muted);text-transform:uppercase;margin-bottom:24px}
.p-track{display:flex;gap:20px;animation:marquee 28s linear infinite}
.p-track:hover{animation-play-state:paused}
@keyframes marquee{from{transform:translateX(0)}to{transform:translateX(-50%)}}
.p-logo{height:42px;min-width:110px;background:var(--card);border:1px solid var(--border);border-radius:10px;display:flex;align-items:center;justify-content:center;padding:0 18px;font-family:var(--fh);font-size:14px;font-weight:600;color:var(--muted);white-space:nowrap;flex-shrink:0;transition:all .2s}
.p-logo:hover{border-color:var(--border2);color:var(--text2)}

/* ── WHY US ── */
.why{padding:96px 40px}
.feat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:18px;margin-top:44px}
.feat{background:var(--card);border:1px solid var(--border);border-radius:var(--r2);padding:26px;transition:all .3s;position:relative;overflow:hidden}
.feat::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--accent),transparent);opacity:0;transition:opacity .3s}
.feat:hover{border-color:var(--border2);transform:translateY(-3px);box-shadow:0 14px 44px rgba(0,0,0,.3)}
.feat:hover::before{opacity:1}
.feat-ic{width:46px;height:46px;border-radius:12px;background:var(--accent-dim);border:1px solid var(--border2);display:flex;align-items:center;justify-content:center;font-size:20px;margin-bottom:14px}
.feat-t{font-family:var(--fh);font-size:16px;font-weight:600;margin-bottom:7px}
.feat-d{font-size:13px;color:var(--text2);line-height:1.6;text-wrap:pretty}

/* ── ACHIEVEMENTS ── */
.ach{padding:96px 40px;background:var(--bg2);border-top:1px solid var(--border);border-bottom:1px solid var(--border)}
.stats-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:2px;margin-top:44px;background:var(--border);border:1px solid var(--border);border-radius:var(--r2);overflow:hidden}
.stat{background:var(--card);padding:38px 28px;text-align:center}
.stat-n{font-family:var(--fh);font-size:clamp(34px,4vw,52px);font-weight:700;background:linear-gradient(135deg,#fff 30%,var(--accent));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1;margin-bottom:7px}
.stat-l{font-size:13px;color:var(--text2);font-weight:500}

/* ── RESERVES ── */
.res{padding:96px 40px}
.res-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(175px,1fr));gap:16px;margin-top:44px}
.res-card{background:var(--card);border:1px solid var(--border);border-radius:var(--r2);padding:22px 18px;position:relative;overflow:hidden;transition:border-color .3s,transform .3s}
.res-card:hover{transform:translateY(-2px)}
.res-bar{position:absolute;bottom:0;left:0;right:0;height:3px;border-radius:0 0 var(--r2) var(--r2)}
.res-code{font-size:11px;color:var(--text2);font-weight:600;letter-spacing:1px;text-transform:uppercase;margin-bottom:3px}
.res-sym{font-family:var(--fh);font-size:28px;font-weight:700;line-height:1}
.res-amt{font-family:var(--fh);font-size:20px;font-weight:600;margin-top:8px}
.res-usd{font-size:12px;color:var(--text2);margin-top:3px}
.live{display:inline-flex;align-items:center;gap:5px;font-size:11px;color:var(--success);margin-top:9px;font-weight:500}
.live::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--success);animation:pulse 2s ease-in-out infinite}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.5;transform:scale(.8)}}

/* ── FOOTER ── */
footer{background:var(--bg2);border-top:1px solid var(--border);padding:56px 40px 36px}
.ft-grid{display:grid;grid-template-columns:1.5fr 1fr 1fr 1fr;gap:44px;max-width:1200px;margin:0 auto}
.ft-brand p{font-size:14px;color:var(--text2);line-height:1.65;max-width:270px;text-wrap:pretty;margin:14px 0 18px}
.ft-socials{display:flex;gap:10px}
.ft-social{font-size:12px;color:var(--text2);text-decoration:none;padding:5px 10px;border:1px solid var(--border);border-radius:6px;transition:all .2s}
.ft-social:hover{border-color:var(--accent);color:var(--accent)}
.ft-col h4{font-size:11px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:var(--text2);margin-bottom:14px}
.ft-col ul{list-style:none}
.ft-col li{margin-bottom:9px}
.ft-col a{font-size:14px;color:var(--text2);text-decoration:none;transition:color .2s}
.ft-col a:hover{color:var(--accent)}
.ft-bot{max-width:1200px;margin:36px auto 0;padding-top:22px;border-top:1px solid var(--border);display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:10px}
.ft-bot p{font-size:12px;color:var(--muted)}

/* ── SECTION SHARED ── */
.sw-inner{max-width:1180px;margin:0 auto}
.stag{display:inline-block;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--accent);background:var(--accent-dim);border:1px solid var(--border2);padding:3px 11px;border-radius:20px;margin-bottom:10px}
.stitle{font-size:clamp(26px,3.5vw,42px);font-weight:700;line-height:1.15;margin-bottom:12px}
.ssub{color:var(--text2);font-size:15px;max-width:520px;line-height:1.65;text-wrap:pretty}

/* ── FADE ANIMATIONS ── */
.fu{opacity:0;transform:translateY(28px);transition:opacity .65s ease,transform .65s ease}
.fu.vis{opacity:1;transform:translateY(0)}

/* ── MOBILE ── */
@media(max-width:860px){
  .hdr{padding:0 20px}
  .nav{display:none}
  .ham{display:flex}
  .hero{padding:100px 20px 60px}
  .ex-cols{grid-template-columns:1fr}
  .ex-div{flex-direction:row;padding:14px 0 0;justify-content:center}
  .swap{transform:rotate(90deg)}
  .why,.res,.ach{padding:60px 20px}
  footer{padding:40px 20px 28px}
  .ft-grid{grid-template-columns:1fr 1fr;gap:28px}
  .ft-bot{flex-direction:column;text-align:center}
  .aml-acts{flex-direction:column;align-items:flex-start}
  .sw-inner{padding:0 4px}
}
@media(max-width:500px){
  .ft-grid{grid-template-columns:1fr}
  .stats-grid{grid-template-columns:1fr 1fr}
  .res-grid{grid-template-columns:1fr 1fr}
  .feat-grid{grid-template-columns:1fr}
  .hdr-r .langs{display:none}
}

/* ── TWEAKS ── */
#tp{position:fixed;bottom:22px;right:22px;z-index:999;background:var(--card2);border:1px solid var(--border2);border-radius:14px;padding:18px;min-width:230px;box-shadow:0 20px 60px rgba(0,0,0,.55);display:none}
#tp.open{display:block}
#tp h3{font-family:var(--fh);font-size:13px;font-weight:600;color:var(--text);margin-bottom:14px}
.tr{margin-bottom:12px}
.tr label{font-size:11px;color:var(--text2);display:block;margin-bottom:5px}
.tr select{width:100%;background:var(--card);border:1px solid var(--border);color:var(--text);padding:6px 8px;border-radius:6px;font-size:12px;outline:none}
.tr input[type=range]{width:100%;accent-color:var(--accent)}
.tr input[type=color]{width:100%;height:30px;cursor:pointer;background:none;border:1px solid var(--border);border-radius:6px}
</style>
</head>
<body>
<div id="root"></div>
<script type="text/babel">
const { useState, useEffect, useRef } = React;

/* ── DATA ─────────────────────────────────────────────────── */
const CURRENCIES = [
  { code:'BTC', name:'Bitcoin',   sym:'₿', color:'#F7931A', bg:'rgba(247,147,26,.13)' },
  { code:'ETH', name:'Ethereum',  sym:'Ξ', color:'#627EEA', bg:'rgba(98,126,234,.13)' },
  { code:'USDT',name:'Tether',    sym:'₮', color:'#26A17B', bg:'rgba(38,161,123,.13)' },
  { code:'USD', name:'US Dollar', sym:'$', color:'#85C1E9', bg:'rgba(133,193,233,.13)' },
  { code:'EUR', name:'Euro',      sym:'€', color:'#A8D8EA', bg:'rgba(168,216,234,.13)' },
  { code:'GBP', name:'Pound',     sym:'£', color:'#C0B0E0', bg:'rgba(192,176,224,.13)' },
];
const COUNTRIES = {
  UA:{name:'Украина', cities:['Киев','Харьков','Одесса','Днепр','Запорожье','Львов','Кривой Рог']},
  PL:{name:'Польша',  cities:['Варшава','Краков','Вроцлав','Лодзь','Познань','Гданьск']},
  DE:{name:'Германия',cities:['Берлин','Мюнхен','Гамбург','Франкфурт','Кёльн','Дюссельдорф']},
  CZ:{name:'Чехия',   cities:['Прага','Брно','Острава']},
  HU:{name:'Венгрия', cities:['Будапешт','Дебрецен']},
  AT:{name:'Австрия', cities:['Вена','Грац','Зальцбург']},
  KZ:{name:'Казахстан',cities:['Алматы','Астана','Шымкент']},
};
const RATES = { BTC:66200, ETH:3180, USDT:1, USD:1, EUR:1.085, GBP:1.27 };
const PARTNERS = ['Binance','OKX','Bybit','Kraken','Visa','Mastercard','SWIFT','SEPA','Tron','Polygon','MonoBank','PrivatBank'];
const WHY = [
  {ic:'⚡',t:'Быстрый обмен',d:'Обмен выполняется за 15–30 минут. Работаем без выходных.'},
  {ic:'🛡',t:'AML-защита',d:'Проверяем чистоту средств перед каждой транзакцией.'},
  {ic:'💱',t:'Лучший курс',d:'Мониторим рынок в реальном времени. Курс обновляется каждые 5 минут.'},
  {ic:'🔒',t:'Безопасность',d:'Все транзакции защищены. Данные не передаются третьим лицам.'},
  {ic:'🌍',t:'Украина и Европа',d:'Наличный и безналичный обмен в Киеве, Варшаве, Берлине и других городах.'},
  {ic:'💬',t:'Поддержка 24/7',d:'Операторы онлайн круглосуточно. Ответим в Telegram за 5 минут.'},
];
const STATS = [
  {val:5,  suf:'+',  lbl:'Лет на рынке'},
  {val:15000, suf:'+', lbl:'Клиентов',  fmt:v=>Math.round(v).toLocaleString('ru-RU')},
  {val:50, pre:'$', suf:'M+', lbl:'Объём обменов'},
  {val:99.8,suf:'%', lbl:'Положительных отзывов', fmt:v=>v.toFixed(1)},
];
const RESERVES = [
  {code:'BTC',sym:'₿',color:'#F7931A',amt:2.4731, usd:163699},
  {code:'ETH',sym:'Ξ',color:'#627EEA',amt:48.21,  usd:153308},
  {code:'USDT',sym:'₮',color:'#26A17B',amt:248500, usd:248500},
  {code:'USD',sym:'$',color:'#85C1E9',amt:183200, usd:183200},
  {code:'EUR',sym:'€',color:'#A8D8EA',amt:94700,  usd:102749},
  {code:'GBP',sym:'£',color:'#C0B0E0',amt:41300,  usd:52451},
];

/* ── UTILS ─────────────────────────────────────────────────── */
const fmtAmt = (n, code) => n >= 1000
  ? n.toLocaleString('ru-RU', {maximumFractionDigits: code==='BTC'||code==='ETH'?6:2})
  : n.toFixed(code==='BTC'||code==='ETH' ? 6 : 2);

function calcEx(gCode, rCode, gAmt, pct) {
  if (!gAmt || isNaN(gAmt)) return {recv:'',comm:''};
  const a = parseFloat(gAmt);
  const usd = a * RATES[gCode];
  const commUSD = usd * pct / 100;
  const commGive = a * pct / 100;
  const recv = (usd - commUSD) / RATES[rCode];
  return {
    recv: fmtAmt(recv, rCode),
    comm: fmtAmt(commGive, gCode) + ' ' + gCode,
  };
}

/* ── HOOKS ─────────────────────────────────────────────────── */
function useFadeUp(ref) {
  useEffect(() => {
    const el = ref.current; if (!el) return;
    const obs = new IntersectionObserver(([e]) => {
      if (e.isIntersecting) { el.classList.add('vis'); obs.disconnect(); }
    }, {threshold:.12});
    obs.observe(el);
    return () => obs.disconnect();
  }, []);
}

function useCounter(target, active, fmt) {
  const [v, setV] = useState(0);
  useEffect(() => {
    if (!active) return;
    let s = null; const dur = 1800;
    const step = ts => {
      if (!s) s = ts;
      const p = Math.min((ts - s) / dur, 1);
      const e = 1 - Math.pow(1-p, 3);
      setV(e * target);
      if (p < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  }, [active, target]);
  return fmt ? fmt(v) : (v >= 100 ? Math.round(v) : v.toFixed(1));
}

/* ── PARTICLE CANVAS ───────────────────────────────────────── */
function ParticleCanvas() {
  const ref = useRef();
  useEffect(() => {
    const canvas = ref.current; if (!canvas) return;
    const ctx = canvas.getContext('2d');
    let W, H, pts, raf;
    const init = () => {
      W = canvas.width = canvas.offsetWidth;
      H = canvas.height = canvas.offsetHeight;
      const n = Math.floor(W * H / 11000);
      pts = Array.from({length:n}, () => ({
        x: Math.random()*W, y: Math.random()*H,
        vx: (Math.random()-.5)*.35, vy: (Math.random()-.5)*.35,
        r: Math.random()*1.8+.8, a: Math.random()*.45+.1,
      }));
    };
    const draw = () => {
      ctx.clearRect(0,0,W,H);
      pts.forEach(p => {
        p.x += p.vx; p.y += p.vy;
        if (p.x < 0) p.x = W; if (p.x > W) p.x = 0;
        if (p.y < 0) p.y = H; if (p.y > H) p.y = 0;
        ctx.beginPath(); ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
        ctx.fillStyle = `rgba(123,143,232,${p.a})`; ctx.fill();
      });
      for (let i=0;i<pts.length;i++) for (let j=i+1;j<pts.length;j++) {
        const dx=pts[i].x-pts[j].x, dy=pts[i].y-pts[j].y, d=Math.hypot(dx,dy);
        if (d<110) {
          ctx.beginPath();
          ctx.moveTo(pts[i].x,pts[i].y); ctx.lineTo(pts[j].x,pts[j].y);
          ctx.strokeStyle=`rgba(123,143,232,${.07*(1-d/110)})`; ctx.lineWidth=1; ctx.stroke();
        }
      }
      raf = requestAnimationFrame(draw);
    };
    init(); draw();
    const ro = new ResizeObserver(init);
    ro.observe(canvas);
    return () => { cancelAnimationFrame(raf); ro.disconnect(); };
  }, []);
  return <canvas ref={ref} className="hero-canvas" style={{position:'absolute',inset:0,width:'100%',height:'100%'}}/>;
}

/* ── HEADER ─────────────────────────────────────────────────── */
function Header({lang, setLang}) {
  const [scrolled, setScrolled] = useState(false);
  const [mob, setMob] = useState(false);
  useEffect(() => {
    const fn = () => setScrolled(window.scrollY > 30);
    window.addEventListener('scroll', fn);
    return () => window.removeEventListener('scroll', fn);
  }, []);
  const navLinks = [['#exchange','Обмен'],['#partners','Партнёры'],['#why-us','Почему мы'],['#reserves','Резервы'],['#footer','Контакты']];
  return (
    <header className={`hdr${scrolled?' scrolled':''}`}>
      <a href="#" className="logo">
        <div className="logo-icon">
          <svg width="18" height="18" viewBox="0 0 20 20" fill="none">
            <path d="M10 2L18 7V13L10 18L2 13V7L10 2Z" fill="white" fillOpacity=".9"/>
            <path d="M10 6L14 8.5V13.5L10 16L6 13.5V8.5L10 6Z" fill="rgba(123,143,232,.6)"/>
          </svg>
        </div>
        Exchange<em>37</em>
      </a>
      <nav className="nav">
        {navLinks.map(([h,l])=><a key={h} href={h}>{l}</a>)}
      </nav>
      <div className="hdr-r">
        <div className="langs">
          {['RU','EN','UA'].map(l=><button key={l} className={`lang${lang===l?' on':''}`} onClick={()=>setLang(l)}>{l}</button>)}
        </div>
        <button className="btn-login">Войти</button>
        <button className="ham" onClick={()=>setMob(!mob)}><span/><span/><span/></button>
      </div>
    </header>
  );
}

/* ── SELECT FIELD ───────────────────────────────────────────── */
function SF({label, value, onChange, opts, placeholder}) {
  return (
    <div className="fg">
      {label && <label className="fl">{label}</label>}
      <div className="sw">
        <select className="fs" value={value} onChange={e=>onChange(e.target.value)}>
          {placeholder && <option value="">{placeholder}</option>}
          {opts.map(o=>{
            const v=o.value||o, l=o.label||o;
            return <option key={v} value={v}>{l}</option>;
          })}
        </select>
      </div>
    </div>
  );
}

/* ── EXCHANGE FORM ──────────────────────────────────────────── */
function ExchangeForm({commPct}) {
  const [gC, setGC] = useState('BTC');
  const [rC, setRC] = useState('USD');
  const [gCountry, setGCo] = useState('UA');
  const [rCountry, setRCo] = useState('DE');
  const [gCity, setGCi] = useState('Киев');
  const [rCity, setRCi] = useState('Берлин');
  const [gAmt, setGA] = useState('1');
  const [email, setEmail] = useState('');
  const [msng, setMsng] = useState('telegram');
  const [contact, setCt] = useState('');
  const [ag1, setAg1] = useState(false);
  const [ag2, setAg2] = useState(false);
  const [aml, setAml] = useState('');
  const [done, setDone] = useState(false);

  const pct = commPct || 1.5;
  const {recv, comm} = calcEx(gC, rC, gAmt, pct);
  const gObj = CURRENCIES.find(c=>c.code===gC);
  const rObj = CURRENCIES.find(c=>c.code===rC);
  const coOpts = Object.entries(COUNTRIES).map(([k,v])=>({value:k,label:v.name}));
  const canSub = ag1 && ag2 && aml && gAmt && email && contact;

  const swap = () => {
    const [gc,rc,gco,rco,gci,rci] = [gC,rC,gCountry,rCountry,gCity,rCity];
    setGC(rc); setRC(gc); setGCo(rco); setRCo(gco); setGCi(rci); setRCi(gci);
  };

  if (done) return (
    <div className="ex-wrap">
      <div className="ex-card" style={{textAlign:'center',padding:'56px 40px'}}>
        <div style={{fontSize:52,marginBottom:14}}>✅</div>
        <h2 style={{fontFamily:'var(--fh)',fontSize:22,marginBottom:10}}>Заявка принята!</h2>
        <p style={{color:'var(--text2)',fontSize:14,marginBottom:8}}>Обмен: <strong style={{color:'var(--text)'}}>{gAmt} {gC} → {recv} {rC}</strong></p>
        <p style={{color:'var(--text2)',fontSize:14,marginBottom:24}}>Свяжемся с вами: <strong style={{color:'var(--accent)'}}>{contact}</strong> ({msng==='telegram'?'Telegram':'WhatsApp'})</p>
        <button className="btn-main" style={{padding:'12px 36px',fontSize:14}} onClick={()=>setDone(false)}>Новый обмен</button>
      </div>
    </div>
  );

  return (
    <div className="ex-wrap">
      <div className="ex-card">
        <div className="ex-cols">

          {/* LEFT */}
          <div>
            <div className="col-label"><span className="dot"/>Отдаю</div>
            <div className="fg">
              <label className="fl">Валюта</label>
              <div className="curr-row">
                <div className="sw" style={{flex:1}}>
                  <select className="fs" value={gC} onChange={e=>setGC(e.target.value)}>
                    {CURRENCIES.map(c=><option key={c.code} value={c.code}>{c.sym} {c.code} — {c.name}</option>)}
                  </select>
                </div>
                <div className="curr-icon" style={{background:gObj.bg,color:gObj.color,border:`1px solid ${gObj.color}30`}}>{gObj.sym}</div>
              </div>
            </div>
            <SF label="Страна" value={gCountry} onChange={v=>{setGCo(v);setGCi(COUNTRIES[v].cities[0])}} opts={coOpts}/>
            <SF label="Город" value={gCity} onChange={setGCi} opts={COUNTRIES[gCountry].cities}/>
            <div className="fg">
              <label className="fl">Сумма</label>
              <input className="fi" type="number" value={gAmt} onChange={e=>setGA(e.target.value)} placeholder="0.00" min="0" step="any"/>
            </div>
            <div className="fg">
              <label className="fl">Комиссия ({pct}%)</label>
              <input className="fi comm" value={comm||'—'} readOnly disabled/>
            </div>
            <div className="cbx">
              <input type="checkbox" id="a1" checked={ag1} onChange={e=>setAg1(e.target.checked)}/>
              <label htmlFor="a1">Согласен с <a href="#">политикой конфиденциальности</a></label>
            </div>
            <div className="cbx">
              <input type="checkbox" id="a2" checked={ag2} onChange={e=>setAg2(e.target.checked)}/>
              <label htmlFor="a2">Согласен с <a href="#">правилами обмена</a></label>
            </div>
          </div>

          {/* DIVIDER */}
          <div className="ex-div">
            <button className="swap" onClick={swap} title="Поменять">⇄</button>
          </div>

          {/* RIGHT */}
          <div>
            <div className="col-label"><span className="dot t"/>Получаю</div>
            <div className="fg">
              <label className="fl">Валюта</label>
              <div className="curr-row">
                <div className="sw" style={{flex:1}}>
                  <select className="fs" value={rC} onChange={e=>setRC(e.target.value)}>
                    {CURRENCIES.map(c=><option key={c.code} value={c.code}>{c.sym} {c.code} — {c.name}</option>)}
                  </select>
                </div>
                <div className="curr-icon" style={{background:rObj.bg,color:rObj.color,border:`1px solid ${rObj.color}30`}}>{rObj.sym}</div>
              </div>
            </div>
            <SF label="Страна" value={rCountry} onChange={v=>{setRCo(v);setRCi(COUNTRIES[v].cities[0])}} opts={coOpts}/>
            <SF label="Город" value={rCity} onChange={setRCi} opts={COUNTRIES[rCountry].cities}/>
            <div className="fg">
              <label className="fl">Сумма (к получению)</label>
              <input className="fi recv" value={recv||'—'} readOnly/>
            </div>
            <div className="fg">
              <label className="fl">Email</label>
              <input className="fi" type="email" value={email} onChange={e=>setEmail(e.target.value)} placeholder="your@email.com"/>
            </div>
            <div className="fg">
              <label className="fl">Канал связи</label>
              <div className="sw">
                <select className="fs" value={msng} onChange={e=>setMsng(e.target.value)}>
                  <option value="telegram">💬 Telegram</option>
                  <option value="whatsapp">📱 WhatsApp</option>
                </select>
              </div>
            </div>
            <div className="fg">
              <label className="fl">{msng==='telegram'?'Telegram @username':'Номер WhatsApp'}</label>
              <input className="fi" type="text" value={contact} onChange={e=>setCt(e.target.value)} placeholder={msng==='telegram'?'@username':'+380...'}/>
            </div>
          </div>
        </div>

        {/* AML */}
        <div className="aml">
          <div className="aml-head">
            <span className="aml-badge">AML</span>
            <span className="aml-title">Проверка происхождения средств</span>
          </div>
          <p className="aml-desc">Рекомендуем проверить чистоту криптовалюты перед обменом через независимый сервис. Это защитит вас от блокировки и возможных рисков.</p>
          <div className="aml-acts">
            <a href="https://www.bestchange.ru" target="_blank" rel="noopener" className="btn-bc">🔍 Проверить на Bestchange</a>
            <div className="aml-radios">
              <label className="radio-opt">
                <input type="radio" name="aml" value="yes" checked={aml==='yes'} onChange={()=>setAml('yes')}/>
                <span>✅ Проверил — с результатом ознакомлен</span>
              </label>
              <label className="radio-opt">
                <input type="radio" name="aml" value="no" checked={aml==='no'} onChange={()=>setAml('no')}/>
                <span>⚠️ Не проверял — принимаю риски</span>
              </label>
            </div>
          </div>
        </div>

        <div className="ex-foot">
          <button className="btn-main" disabled={!canSub} onClick={()=>canSub&&setDone(true)}
            style={{opacity:canSub?1:.4,cursor:canSub?'pointer':'not-allowed',padding:'15px 56px',fontSize:16}}>
            Обменять {gAmt&&recv?`${gAmt} ${gC} → ${recv} ${rC}`:''}
          </button>
        </div>
      </div>
    </div>
  );
}

/* ── PARTNERS ───────────────────────────────────────────────── */
function Partners() {
  const doubled = [...PARTNERS,...PARTNERS];
  return (
    <section className="partners" id="partners">
      <p className="partners-lbl">Наши партнёры и поддерживаемые сети</p>
      <div style={{overflow:'hidden',position:'relative'}}>
        <div style={{position:'absolute',left:0,top:0,bottom:0,width:80,background:'linear-gradient(90deg,var(--bg2),transparent)',zIndex:2,pointerEvents:'none'}}/>
        <div style={{position:'absolute',right:0,top:0,bottom:0,width:80,background:'linear-gradient(-90deg,var(--bg2),transparent)',zIndex:2,pointerEvents:'none'}}/>
        <div className="p-track">
          {doubled.map((p,i)=><div key={i} className="p-logo">{p}</div>)}
        </div>
      </div>
    </section>
  );
}

/* ── WHY US ─────────────────────────────────────────────────── */
function WhyUs() {
  const ref = useRef(); useFadeUp(ref);
  return (
    <section className="why" id="why-us">
      <div className="sw-inner fu" ref={ref}>
        <span className="stag">Преимущества</span>
        <h2 className="stitle">Почему Exchange37?</h2>
        <p className="ssub">Работаем с 2019 года. Тысячи клиентов из Украины, Польши, Германии и других стран Европы.</p>
        <div className="feat-grid">
          {WHY.map((f,i)=>(
            <div key={i} className="feat" style={{transitionDelay:i*.07+'s'}}>
              <div className="feat-ic">{f.ic}</div>
              <div className="feat-t">{f.t}</div>
              <div className="feat-d">{f.d}</div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

/* ── STAT CARD ──────────────────────────────────────────────── */
function StatCard({val,suf,pre,lbl,fmt}) {
  const ref = useRef();
  const [on, setOn] = useState(false);
  const display = useCounter(val, on, fmt);
  useEffect(() => {
    const obs = new IntersectionObserver(([e])=>{ if (e.isIntersecting) { setOn(true); obs.disconnect(); } },{threshold:.5});
    obs.observe(ref.current);
    return ()=>obs.disconnect();
  }, []);
  return (
    <div className="stat" ref={ref}>
      <div className="stat-n">{pre||''}{display}{suf||''}</div>
      <div className="stat-l">{lbl}</div>
    </div>
  );
}

/* ── ACHIEVEMENTS ───────────────────────────────────────────── */
function Achievements() {
  const ref = useRef(); useFadeUp(ref);
  return (
    <section className="ach" id="achievements">
      <div className="sw-inner fu" ref={ref}>
        <span className="stag">Цифры</span>
        <h2 className="stitle">Наши достижения</h2>
        <div className="stats-grid">
          {STATS.map((s,i)=><StatCard key={i} {...s}/>)}
        </div>
      </div>
    </section>
  );
}

/* ── RESERVES ───────────────────────────────────────────────── */
function Reserves() {
  const ref = useRef(); useFadeUp(ref);
  return (
    <section className="res" id="reserves">
      <div className="sw-inner fu" ref={ref}>
        <span className="stag">Резервы</span>
        <h2 className="stitle">Наши резервы</h2>
        <p className="ssub">Актуальные балансы кошельков. Обновляется каждые 15 минут.</p>
        <div className="res-grid">
          {RESERVES.map((r,i)=>(
            <div key={i} className="res-card" style={{borderColor:r.color+'25',background:`linear-gradient(145deg,var(--card),${r.color}08)`}}>
              <div className="res-bar" style={{background:r.color,opacity:.5}}/>
              <div className="res-code">{r.code}</div>
              <div className="res-sym" style={{color:r.color}}>{r.sym}</div>
              <div className="res-amt">{fmtAmt(r.amt, r.code)}</div>
              <div className="res-usd">≈ ${r.usd.toLocaleString('ru-RU')}</div>
              <div className="live">Live</div>
            </div>
          ))}
        </div>
      </div>
    </section>
  );
}

/* ── FOOTER ─────────────────────────────────────────────────── */
function Footer() {
  return (
    <footer id="footer">
      <div className="ft-grid">
        <div className="ft-brand">
          <a href="#" className="logo">
            <div className="logo-icon">
              <svg width="18" height="18" viewBox="0 0 20 20" fill="none">
                <path d="M10 2L18 7V13L10 18L2 13V7L10 2Z" fill="white" fillOpacity=".9"/>
                <path d="M10 6L14 8.5V13.5L10 16L6 13.5V8.5L10 6Z" fill="rgba(123,143,232,.6)"/>
              </svg>
            </div>
            Exchange<em>37</em>
          </a>
          <p>Надёжный криптообменник для Украины и Европы. Быстро, безопасно, прозрачно с 2019 года.</p>
          <div className="ft-socials">
            {['Telegram','WhatsApp','Instagram'].map(s=><a key={s} href="#" className="ft-social">{s}</a>)}
          </div>
        </div>
        <div className="ft-col">
          <h4>Обмен</h4>
          <ul>
            {['BTC → USD','ETH → EUR','USDT → GBP','USD → BTC','EUR → ETH','Все направления'].map(l=><li key={l}><a href="#">{l}</a></li>)}
          </ul>
        </div>
        <div className="ft-col">
          <h4>Города</h4>
          <ul>
            {['Киев','Харьков','Одесса','Варшава','Берлин','Прага'].map(l=><li key={l}><a href="#">{l}</a></li>)}
          </ul>
        </div>
        <div className="ft-col">
          <h4>Компания</h4>
          <ul>
            {['О нас','AML политика','Конфиденциальность','Правила обмена','Контакты','FAQ'].map(l=><li key={l}><a href="#">{l}</a></li>)}
          </ul>
        </div>
      </div>
      <div className="ft-bot">
        <p>© 2019–2026 Exchange37. Все права защищены.</p>
        <p>🔒 SSL · AML Compliant · Лицензированная деятельность</p>
      </div>
    </footer>
  );
}

/* ── TWEAKS ─────────────────────────────────────────────────── */
const TWEAK_DEFAULTS = /*EDITMODE-BEGIN*/{
  "accentColor": "#53ca9d",
  "commissionPct": "1.4",
  "language": "RU"
}/*EDITMODE-END*/;

function Tweaks({onCommChange}) {
  const [open, setOpen] = useState(false);
  const [vals, setVals] = useState(TWEAK_DEFAULTS);
  useEffect(() => {
    const fn = e => {
      if (e.data?.type==='__activate_edit_mode') setOpen(true);
      if (e.data?.type==='__deactivate_edit_mode') setOpen(false);
    };
    window.addEventListener('message', fn);
    window.parent.postMessage({type:'__edit_mode_available'},'*');
    return ()=>window.removeEventListener('message', fn);
  }, []);
  const set = (k,v) => {
    const n = {...vals,[k]:v}; setVals(n);
    if (k==='accentColor') document.documentElement.style.setProperty('--accent',v);
    if (k==='commissionPct') onCommChange(parseFloat(v));
    window.parent.postMessage({type:'__edit_mode_set_keys',edits:n},'*');
  };
  if (!open) return null;
  return (
    <div id="tp" className="open">
      <h3>Tweaks</h3>
      <div className="tr"><label>Акцентный цвет</label><input type="color" value={vals.accentColor} onChange={e=>set('accentColor',e.target.value)}/></div>
      <div className="tr"><label>Комиссия: {vals.commissionPct}%</label><input type="range" min=".5" max="5" step=".1" value={vals.commissionPct} onChange={e=>set('commissionPct',e.target.value)}/></div>
      <div className="tr"><label>Язык</label>
        <select value={vals.language} onChange={e=>set('language',e.target.value)}>
          {['RU','EN','UA'].map(l=><option key={l}>{l}</option>)}
        </select>
      </div>
    </div>
  );
}

/* ── APP ────────────────────────────────────────────────────── */
function App() {
  const [lang, setLang] = useState('RU');
  const [commPct, setCommPct] = useState(1.5);
  return (
    <>
      <Header lang={lang} setLang={setLang}/>
      <main>
        <section className="hero" id="exchange">
          <ParticleCanvas/>
          <h1 className="hero-title">
            <span className="grad">Быстрый и безопасный</span><br/>
            криптообмен
          </h1>
          <p className="hero-sub">Обменивайте криптовалюту и фиат в Украине и Европе. Лучший курс, AML-защита, поддержка 24/7.</p>
          <ExchangeForm commPct={commPct}/>
        </section>
        <Partners/>
        <WhyUs/>
        <Achievements/>
        <Reserves/>
      </main>
      <Footer/>
      <Tweaks onCommChange={setCommPct}/>
    </>
  );
}

ReactDOM.createRoot(document.getElementById('root')).render(<App/>);
</script>
</body>
</html>
