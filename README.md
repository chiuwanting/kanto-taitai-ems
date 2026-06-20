<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>關東太太日本代購 ── 費用試算</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700;900&family=Zen+Maru+Gothic:wght@500;700;900&display=swap');

  :root{
    --sakura:#e8889c;
    --sakura-deep:#d35d77;
    --sakura-soft:#fce4ea;
    --sakura-bg:#fff5f7;
    --ink:#3a2a2f;
    --ink-soft:#7a6469;
    --gold:#f3b54a;
    --green:#3aa888;
    --line:#f2d4dc;
    --white:#ffffff;
  }

  *{box-sizing:border-box;margin:0;padding:0;}

  body{
    font-family:'Noto Sans TC',sans-serif;
    background:
      radial-gradient(circle at 12% 8%, #ffe1ea 0%, transparent 40%),
      radial-gradient(circle at 88% 6%, #ffe1ea 0%, transparent 38%),
      var(--sakura-bg);
    color:var(--ink);
    line-height:1.6;
    min-height:100vh;
    padding:0 0 60px;
  }

  /* ---- header ---- */
  header{
    text-align:center;
    padding:38px 20px 30px;
    position:relative;
    overflow:hidden;
  }
  .flag{
    width:42px;height:42px;border-radius:50%;
    display:inline-flex;align-items:center;justify-content:center;
    background:var(--white);border:3px solid var(--sakura-soft);
    font-size:22px;margin-bottom:12px;
    box-shadow:0 4px 14px rgba(211,93,119,.18);
  }
  header h1{
    font-family:'Zen Maru Gothic',sans-serif;
    font-size:clamp(28px,7vw,46px);
    font-weight:900;letter-spacing:2px;
    line-height:1.15;
  }
  header h1 .red{color:var(--sakura-deep);}
  header .sub{
    margin-top:10px;font-size:clamp(13px,3.4vw,16px);
    color:var(--ink-soft);letter-spacing:3px;font-weight:500;
  }
  header .badge{
    display:inline-block;margin-top:16px;
    background:linear-gradient(135deg,var(--sakura-deep),var(--sakura));
    color:#fff;font-weight:700;font-size:14px;
    padding:7px 20px;border-radius:30px;
    box-shadow:0 6px 16px rgba(211,93,119,.3);
  }
  .petal{position:absolute;font-size:26px;opacity:.5;pointer-events:none;}
  .petal.p1{top:14px;left:6%;}
  .petal.p2{top:60px;right:8%;}
  .petal.p3{bottom:8px;left:14%;font-size:18px;}

  /* ---- layout ---- */
  .wrap{
    max-width:560px;margin:0 auto;padding:0 18px;
  }

  .card{
    background:var(--white);
    border-radius:22px;
    padding:24px 22px;
    box-shadow:0 10px 34px rgba(211,93,119,.12);
    border:1px solid var(--line);
    margin-bottom:20px;
  }
  .card h2{
    font-family:'Zen Maru Gothic',sans-serif;
    font-size:18px;color:var(--sakura-deep);
    display:flex;align-items:center;gap:9px;margin-bottom:18px;
  }
  .card h2 .num{
    width:26px;height:26px;border-radius:8px;
    background:var(--sakura-deep);color:#fff;
    font-size:14px;display:inline-flex;align-items:center;justify-content:center;
    flex-shrink:0;
  }

  label.fld{display:block;margin-bottom:18px;}
  label.fld:last-child{margin-bottom:0;}
  label.fld .lab{
    font-size:14px;font-weight:700;margin-bottom:7px;display:block;
  }
  label.fld .hint{font-size:12px;color:var(--ink-soft);font-weight:400;}

  .input-yen{position:relative;}
  .input-yen input{
    width:100%;font-size:24px;font-weight:700;
    padding:14px 56px 14px 16px;
    border:2px solid var(--line);border-radius:14px;
    color:var(--ink);background:var(--sakura-bg);
    font-family:'Zen Maru Gothic',sans-serif;
    -moz-appearance:textfield;
  }
  .input-yen input::-webkit-outer-spin-button,
  .input-yen input::-webkit-inner-spin-button{-webkit-appearance:none;margin:0;}
  .input-yen input:focus{outline:none;border-color:var(--sakura);background:#fff;}
  .input-yen .unit{
    position:absolute;right:16px;top:50%;transform:translateY(-50%);
    font-size:15px;color:var(--ink-soft);font-weight:700;
  }

  .weight-select{
    position:relative;
  }
  .weight-select select{
    width:100%;font-size:18px;font-weight:700;
    padding:14px 44px 14px 16px;
    border:2px solid var(--line);border-radius:14px;
    color:var(--ink);background:var(--sakura-bg);
    font-family:'Zen Maru Gothic',sans-serif;
    -webkit-appearance:none;-moz-appearance:none;appearance:none;
    cursor:pointer;
  }
  .weight-select select:focus{outline:none;border-color:var(--sakura);background:#fff;}
  .weight-select .arrow{
    position:absolute;right:18px;top:50%;transform:translateY(-50%);
    pointer-events:none;color:var(--sakura-deep);font-size:13px;
  }

  .new-toggle{
    display:flex;align-items:center;gap:12px;
    background:linear-gradient(135deg,#fff7ec,#fff0db);
    border:2px solid #f6dca6;border-radius:14px;padding:13px 16px;cursor:pointer;
    user-select:none;
  }
  .new-toggle .box{
    width:24px;height:24px;border-radius:7px;border:2px solid var(--gold);
    background:#fff;flex-shrink:0;display:flex;align-items:center;justify-content:center;
    font-size:16px;color:#fff;transition:all .15s;
  }
  .new-toggle.on .box{background:var(--gold);}
  .new-toggle .txt{font-size:14px;font-weight:700;}
  .new-toggle .txt small{display:block;font-weight:400;color:var(--ink-soft);font-size:11.5px;}

  /* ---- result ---- */
  .result{
    background:linear-gradient(150deg,#fff1f4,#ffe6ec);
    border:2px solid var(--sakura-soft);
  }
  .breakdown{
    display:flex;flex-direction:column;gap:0;
    background:#fff;border-radius:16px;overflow:hidden;
    border:1px solid var(--line);
  }
  .brow{
    display:flex;justify-content:space-between;align-items:baseline;
    padding:13px 16px;border-bottom:1px solid var(--sakura-bg);
    font-size:14px;
  }
  .brow:last-child{border-bottom:none;}
  .brow .k{color:var(--ink-soft);}
  .brow .k small{display:block;font-size:11px;opacity:.8;}
  .brow .v{font-weight:700;font-family:'Zen Maru Gothic',sans-serif;font-size:16px;}
  .brow.rate .v{color:var(--green);}

  .total{
    margin-top:18px;
    background:linear-gradient(135deg,var(--gold),#f5a623);
    border-radius:16px;padding:18px 20px;
    display:flex;justify-content:space-between;align-items:center;
    box-shadow:0 8px 22px rgba(243,166,35,.3);
  }
  .total .lab{color:#fff;font-weight:700;font-size:15px;}
  .total .lab small{display:block;font-size:11px;font-weight:400;opacity:.92;}
  .total .amt{
    color:#fff;font-family:'Zen Maru Gothic',sans-serif;font-weight:900;
    font-size:clamp(26px,8vw,38px);line-height:1;
  }
  .total .amt .cur{font-size:16px;font-weight:700;margin-right:4px;vertical-align:middle;}

  .note{
    margin-top:14px;font-size:11.5px;color:var(--ink-soft);
    line-height:1.7;text-align:center;
  }
  .note b{color:var(--sakura-deep);}

  /* ---- ref table ---- */
  details{
    background:var(--white);border-radius:18px;border:1px solid var(--line);
    padding:4px 0;overflow:hidden;
  }
  summary{
    list-style:none;cursor:pointer;padding:16px 22px;
    font-weight:700;font-size:14px;color:var(--sakura-deep);
    display:flex;justify-content:space-between;align-items:center;
  }
  summary::-webkit-details-marker{display:none;}
  summary .arr{transition:transform .2s;}
  details[open] summary .arr{transform:rotate(180deg);}
  .ref-body{padding:0 18px 18px;}
  table{width:100%;border-collapse:collapse;font-size:13px;}
  table th,table td{padding:8px 6px;text-align:center;border-bottom:1px solid var(--sakura-bg);}
  table th{color:var(--ink-soft);font-weight:700;background:var(--sakura-bg);}
  table td:first-child{text-align:left;color:var(--ink-soft);}

  footer{
    text-align:center;margin-top:26px;font-size:11.5px;color:var(--ink-soft);
    line-height:1.8;
  }
  footer .fb{
    display:inline-block;margin-top:8px;
    background:var(--sakura-deep);color:#fff;font-weight:700;
    padding:9px 24px;border-radius:30px;font-size:13px;text-decoration:none;
  }

  @media(max-width:380px){
    .weight-select select{font-size:16px;}
  }
</style>
</head>
<body>
<header>
  <span class="petal p1">🌸</span><span class="petal p2">🌸</span><span class="petal p3">🌸</span>
  <div class="flag">🇯🇵</div>
  <h1>關東太太<span class="red">日本代購</span></h1>
  <div class="sub">日本現地採購 ・ EMS 快速直送台灣</div>
  <div class="badge">💰 付款金額即時試算</div>
</header>

<div class="wrap">

  <!-- 1. 商品金額 -->
  <div class="card">
    <h2><span class="num">1</span>商品金額</h2>
    <label class="fld">
      <span class="lab">輸入商品總價 <span class="hint">（日幣 ¥）</span></span>
      <div class="input-yen">
        <input id="amount" type="number" inputmode="numeric" placeholder="例：10000" min="0">
        <span class="unit">円</span>
      </div>
    </label>
  </div>

  <!-- 2. 包裹重量 -->
  <div class="card">
    <h2><span class="num">2</span>包裹重量</h2>
    <label class="fld" style="margin-bottom:0;">
      <span class="lab">選擇預估重量 <span class="hint">（EMS 依實際重量計算・全重量區分可選）</span></span>
      <div class="weight-select">
        <select id="weightSelect"></select>
        <span class="arrow">▼</span>
      </div>
    </label>
  </div>

  <!-- 3. 新客 -->
  <div class="card">
    <h2><span class="num">3</span>優惠身分</h2>
    <div class="new-toggle" id="newToggle">
      <span class="box">✓</span>
      <span class="txt">我是新客戶（首單）
        <small>新客首單匯率最低 0.23 起</small>
      </span>
    </div>
  </div>

  <!-- result -->
  <div class="card result">
    <h2 style="color:var(--sakura-deep)">💴 付款明細</h2>
    <div class="breakdown">
      <div class="brow rate">
        <span class="k">適用匯率<small id="rateNote"></small></span>
        <span class="v" id="rateVal">—</span>
      </div>
      <div class="brow">
        <span class="k">商品費<small id="goodsFormula"></small></span>
        <span class="v" id="goodsVal">NT$ 0</span>
      </div>
      <div class="brow">
        <span class="k">EMS 國際運費<small id="emsFormula"></small></span>
        <span class="v" id="emsVal">NT$ 0</span>
      </div>
    </div>
    <div class="total">
      <span class="lab">付款總額<small>商品費 ＋ EMS 運費</small></span>
      <span class="amt"><span class="cur">NT$</span><span id="totalVal">0</span></span>
    </div>
    <div class="note">
      ※ EMS 運費一律以匯率 <b>0.25</b> 計算（日本郵局實際收費 × 0.25）<br>
      ※ 重量越重運費越高，實際金額以下單後預估為準。
    </div>
  </div>

  <!-- ref -->
  <details>
    <summary>📦 台灣（第1地帶）EMS 運費參考表 <span class="arr">▾</span></summary>
    <div class="ref-body">
      <table>
        <thead><tr><th>重量（以內）</th><th>運費（日圓）</th><th>×0.25（NT$）</th></tr></thead>
        <tbody id="refTable"></tbody>
      </table>
    </div>
  </details>

  <footer>
    日本現地採購 ・ 大量採購優惠 ・ 用心服務<br>
    EMS 快速寄送，最快 2〜3 天到台灣
    <br><a class="fb" href="#">立即 FB 私訊洽詢 →</a>
  </footer>

</div>

<script>
// ===== 日本郵便 EMS 第1地帯（台湾）実際運賃 =====
// 出典：日本郵便 EMS料金表（第1地帯：中国・韓国・台湾）／ 単位：円
const EMS = [
  {label:"0.5kg", limit:500,   yen:1450},
  {label:"0.6kg", limit:600,   yen:1600},
  {label:"0.7kg", limit:700,   yen:1750},
  {label:"0.8kg", limit:800,   yen:1900},
  {label:"0.9kg", limit:900,   yen:2050},
  {label:"1kg",   limit:1000,  yen:2200},
  {label:"1.25kg",limit:1250,  yen:2500},
  {label:"1.5kg", limit:1500,  yen:2800},
  {label:"1.75kg",limit:1750,  yen:3100},
  {label:"2kg",   limit:2000,  yen:3400},
  {label:"2.5kg", limit:2500,  yen:3900},
  {label:"3kg",   limit:3000,  yen:4400},
  {label:"3.5kg", limit:3500,  yen:4900},
  {label:"4kg",   limit:4000,  yen:5400},
  {label:"4.5kg", limit:4500,  yen:5900},
  {label:"5kg",   limit:5000,  yen:6400},
  {label:"5.5kg", limit:5500,  yen:6900},
  {label:"6kg",   limit:6000,  yen:7400},
  {label:"7kg",   limit:7000,  yen:8200},
  {label:"8kg",   limit:8000,  yen:9000},
  {label:"9kg",   limit:9000,  yen:9800},
  {label:"10kg",  limit:10000, yen:10600},
  {label:"11kg",  limit:11000, yen:11400},
  {label:"12kg",  limit:12000, yen:12200},
  {label:"13kg",  limit:13000, yen:13000},
  {label:"14kg",  limit:14000, yen:13800},
  {label:"15kg",  limit:15000, yen:14600},
  {label:"16kg",  limit:16000, yen:15400},
  {label:"17kg",  limit:17000, yen:16200},
  {label:"18kg",  limit:18000, yen:17000},
  {label:"19kg",  limit:19000, yen:17800},
  {label:"20kg",  limit:20000, yen:18600},
  {label:"21kg",  limit:21000, yen:19400},
  {label:"22kg",  limit:22000, yen:20200},
  {label:"23kg",  limit:23000, yen:21000},
  {label:"24kg",  limit:24000, yen:21800},
  {label:"25kg",  limit:25000, yen:22600},
  {label:"26kg",  limit:26000, yen:23400},
  {label:"27kg",  limit:27000, yen:24200},
  {label:"28kg",  limit:28000, yen:25000},
  {label:"29kg",  limit:29000, yen:25800},
  {label:"30kg",  limit:30000, yen:26600},
];

const EMS_RATE = 0.25; // EMS運費一律匯率

// ===== 商品匯率（依商品金額／日幣）=====
// 出典：チラシ「金額越單享優惠匯率」
function getRate(yen, isNew){
  let rate;
  if(yen >= 100000)      rate = 0.24;
  else if(yen >= 50000)  rate = 0.245;
  else                   rate = 0.25;
  if(isNew) rate = Math.min(rate, 0.23); // 新客首單最低 0.23
  return rate;
}

// ===== 重量プルダウン（写真の全区分）=====
let state = { amount:0, ems:EMS.find(e=>e.label==="1kg"), isNew:false };

// build weight select（全43区分）
const sel = document.getElementById('weightSelect');
EMS.forEach((w,i)=>{
  const opt=document.createElement('option');
  opt.value=i;
  opt.textContent=`${w.label} 以內 （${w.yen.toLocaleString()}円）`;
  if(w.label==="1kg") opt.selected=true; // 初期値 1kg
  sel.appendChild(opt);
});
sel.addEventListener('change',e=>{
  state.ems=EMS[parseInt(e.target.value)];
  render();
});

// new toggle
const toggle=document.getElementById('newToggle');
toggle.onclick=()=>{
  state.isNew=!state.isNew;
  toggle.classList.toggle('on',state.isNew);
  render();
};

// amount
document.getElementById('amount').addEventListener('input',e=>{
  state.amount=parseFloat(e.target.value)||0;
  render();
});

// ref table
const refBody=document.getElementById('refTable');
EMS.forEach(e=>{
  const tr=document.createElement('tr');
  tr.innerHTML=`<td>${e.label}</td><td>${e.yen.toLocaleString()}</td><td>NT$ ${Math.round(e.yen*EMS_RATE).toLocaleString()}</td>`;
  refBody.appendChild(tr);
});

const fmt=n=>Math.round(n).toLocaleString();

function render(){
  const {amount,ems,isNew}=state;
  const rate=getRate(amount,isNew);
  const goods=amount*rate;
  const emsFee=ems.yen*EMS_RATE;
  const total=goods+emsFee;

  document.getElementById('rateVal').textContent=rate.toFixed(rate===0.245?3:2);
  document.getElementById('rateNote').textContent =
    isNew ? "新客首單優惠" :
    amount>=100000 ? "10萬円以上" :
    amount>=50000 ? "5〜9.9萬円" : "未滿5萬円";

  document.getElementById('goodsVal').textContent="NT$ "+fmt(goods);
  document.getElementById('goodsFormula').textContent =
    amount>0 ? `${amount.toLocaleString()}円 × ${rate}` : "輸入金額後計算";

  document.getElementById('emsVal').textContent="NT$ "+fmt(emsFee);
  document.getElementById('emsFormula').textContent =
    `${ems.label} ／ ${ems.yen.toLocaleString()}円 × 0.25`;

  document.getElementById('totalVal').textContent=fmt(total);
}

render();
</script>
</body>
</html>
