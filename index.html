<!DOCTYPE html>
<html lang="sv">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TABASCO</title>
<style>
  :root{
    --bg:#fafafa;
    --card:#ffffff;
    --border:#eceef1;
    --text:#16181c;
    --muted:#8a8f98;
    --accent:#1f6f5c;
    --accent-dark:#154f41;
    --accent-soft:#eaf3f0;
    --warn:#c98a1f;
    --danger:#d64545;
    --radius:14px;
  }
  * { box-sizing:border-box; }
  body{
    margin:0;
    background:var(--bg);
    color:var(--text);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Inter, Roboto, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing:antialiased;
    letter-spacing:-0.005em;
  }
  .wrap{ max-width:1040px; margin:0 auto; padding:40px 22px 90px; }

  /* Header */
  header{
    display:flex; align-items:flex-end; justify-content:space-between; gap:16px;
    margin-bottom:30px; flex-wrap:wrap; padding-bottom:22px; border-bottom:1px solid var(--border);
  }
  .brand h1{ font-size:21px; margin:0; letter-spacing:-0.02em; font-weight:700; }
  .brand .sub{ font-size:13px; color:var(--muted); margin-top:3px; }

  .week-pill{ font-size:13px; color:var(--muted); text-align:right; }
  .week-pill b{ color:var(--text); font-weight:600; }

  /* Acting-as switcher */
  .switcher{ margin-bottom:26px; }
  .switcher label{ display:block; font-size:11.5px; color:var(--muted); font-weight:600; text-transform:uppercase; letter-spacing:.06em; margin-bottom:10px; }
  .avatar-row{ display:flex; gap:8px; flex-wrap:wrap; }
  .avatar-btn{
    border:1px solid var(--border); background:var(--card); border-radius:10px;
    padding:6px 12px 6px 6px; display:flex; align-items:center; gap:8px;
    cursor:pointer; font-size:13px; color:var(--text); transition:.15s;
    position:relative;
  }
  .avatar-btn:hover{ border-color:var(--accent); }
  .avatar-btn.active{ border-color:var(--accent); background:var(--accent-soft); font-weight:600; }
  .avatar{
    width:26px; height:26px; border-radius:8px; display:flex; align-items:center; justify-content:center;
    font-size:11px; font-weight:700; color:#fff; flex-shrink:0;
  }

  /* Layout */
  .grid{ display:grid; grid-template-columns: 1.5fr 1fr; gap:26px; align-items:start; }
  @media (max-width: 860px){
    .grid{ grid-template-columns:1fr; }
    .panel{ order:-1; position:static; margin-bottom:8px; }
  }

  .section-title{ font-size:11.5px; font-weight:700; color:var(--muted); text-transform:uppercase; letter-spacing:.06em; margin:0 0 14px 1px; }

  /* Team grid of cards */
  .team-grid{ display:grid; grid-template-columns: repeat(auto-fill, minmax(225px,1fr)); gap:12px; }
  .member-card{
    background:var(--card); border:1px solid var(--border); border-radius:var(--radius);
    padding:16px; transition:.15s;
  }
  .member-card.self{ border-color:var(--accent); }
  .mc-top{ display:flex; align-items:center; gap:10px; margin-bottom:13px; }
  .mc-name{ font-weight:600; font-size:14px; }
  .mc-name .you{ color:var(--accent); font-weight:600; font-size:10.5px; margin-left:5px; text-transform:uppercase; letter-spacing:.03em; }
  .mc-streak{ font-size:11.5px; color:var(--muted); margin-top:2px; }
  .mc-streak b{ color:var(--warn); font-weight:700; }

  .ring-wrap{ position:relative; width:38px; height:38px; margin-left:auto; flex-shrink:0; }
  .ring-wrap svg{ transform:rotate(-90deg); }
  .ring-pct{ position:absolute; inset:0; display:flex; align-items:center; justify-content:center; font-size:10px; font-weight:700; }

  .mc-cats{ display:flex; flex-direction:column; gap:6px; margin-bottom:13px; }
  .mc-cat{ display:flex; align-items:center; gap:8px; font-size:12px; color:var(--muted); }
  .mc-cat .dot{ width:6px; height:6px; border-radius:50%; background:var(--border); flex-shrink:0; }
  .mc-cat.done .dot{ background:var(--accent); }
  .mc-cat.done{ color:var(--text); }

  .mini-btn{
    width:100%; padding:7px; border-radius:9px; border:1px solid var(--border);
    background:transparent; color:var(--text); font-size:12px; font-weight:500; cursor:pointer;
    transition:.15s; text-align:center;
  }
  .mini-btn:hover{ border-color:var(--accent); color:var(--accent-dark); }

  /* My check-in panel */
  .panel{
    background:var(--card); border:1px solid var(--border); border-radius:var(--radius);
    padding:20px; position:sticky; top:20px;
  }
  .panel h2{ font-size:15.5px; margin:0 0 3px; font-weight:600; }
  .panel .panel-sub{ font-size:12.5px; color:var(--muted); margin-bottom:16px; line-height:1.5; }

  .checklist{ display:flex; flex-direction:column; gap:7px; margin-bottom:14px; }
  .check-item{
    display:flex; align-items:center; gap:9px; padding:10px 11px; border-radius:11px;
    border:1px solid var(--border); background:transparent; cursor:pointer; transition:.15s;
  }
  .check-item:hover{ border-color:var(--accent); }
  .check-item.on{ background:var(--accent-soft); border-color:var(--accent); }
  .box{
    width:18px; height:18px; border-radius:6px; border:1.5px solid var(--border);
    display:flex; align-items:center; justify-content:center; flex-shrink:0; background:#fff;
    font-size:11px; color:#fff; transition:.15s;
  }
  .check-item.on .box{ background:var(--accent); border-color:var(--accent); }
  .ci-label{ flex:1; font-size:13px; }
  .ci-label-input{
    flex:1; font-size:13px; border:none; border-bottom:1px solid var(--accent); background:transparent;
    outline:none; font-family:inherit; padding:0 0 1px;
  }
  .ci-streak{ font-size:11px; color:var(--warn); font-weight:700; white-space:nowrap; }
  .ci-icon-btn{ background:none; border:none; color:var(--muted); font-size:13px; cursor:pointer; padding:2px 3px; line-height:1; border-radius:5px; }
  .ci-icon-btn:hover{ color:var(--accent-dark); background:var(--accent-soft); }
  .ci-icon-btn.danger:hover{ color:var(--danger); background:#fbeaea; }

  .add-row{ display:flex; gap:8px; margin-top:4px; }
  .add-row input{
    flex:1; padding:9px 12px; border-radius:9px; border:1px solid var(--border);
    font-size:13px; outline:none; background:transparent; font-family:inherit;
  }
  .add-row input:focus{ border-color:var(--accent); }
  .add-row button{
    padding:9px 15px; border-radius:9px; border:none; background:var(--accent); color:#fff;
    font-size:13px; font-weight:600; cursor:pointer;
  }
  .add-row button:hover{ background:var(--accent-dark); }

  .footnote{ font-size:11.5px; color:var(--muted); margin-top:12px; line-height:1.5; }

  .feed{ margin-top:28px; }
  .feed-item{
    display:flex; gap:10px; align-items:flex-start; font-size:13px; color:var(--muted);
    padding:9px 0; border-bottom:1px solid var(--border);
  }
  .feed-item:last-child{ border-bottom:none; }
  .feed-item .t{ color:var(--text); }
  .feed-time{ font-size:11px; color:#b3b7bf; white-space:nowrap; margin-left:auto; }

  .toast{
    position:fixed; bottom:24px; left:50%; transform:translateX(-50%) translateY(20px);
    background:#16181c; color:#fff; padding:10px 18px; border-radius:10px; font-size:13px;
    box-shadow:0 8px 24px rgba(0,0,0,.18); opacity:0; pointer-events:none; transition:.2s;
    z-index:60;
  }
  .toast.show{ opacity:1; transform:translateX(-50%) translateY(0); }

  .empty{ font-size:13px; color:var(--muted); padding:8px 2px; }

  .conn-banner{
    background:#fbeaea; border:1px solid #f0c4c4; color:#9a3a3a; font-size:12.5px;
    border-radius:11px; padding:10px 14px; margin-bottom:18px; line-height:1.5;
  }
  .conn-banner code{ background:#ffffff90; padding:1px 5px; border-radius:5px; }

  /* Stats modal */
  .modal-backdrop{
    position:fixed; inset:0; background:rgba(20,22,26,0.45); display:flex; align-items:center; justify-content:center;
    padding:20px; z-index:70; opacity:0; pointer-events:none; transition:.15s;
  }
  .modal-backdrop.open{ opacity:1; pointer-events:auto; }
  .modal{
    background:var(--card); border-radius:16px; max-width:600px; width:100%; max-height:86vh; overflow-y:auto;
    padding:24px; border:1px solid var(--border);
  }
  .modal-head{ display:flex; align-items:center; gap:12px; margin-bottom:18px; }
  .modal-head .avatar{ width:34px; height:34px; border-radius:9px; font-size:13px; }
  .modal-head h3{ margin:0; font-size:16.5px; font-weight:700; }
  .modal-head .close{ margin-left:auto; background:none; border:none; font-size:18px; color:var(--muted); cursor:pointer; }
  .modal-head .close:hover{ color:var(--text); }

  .stat-summary{ display:grid; grid-template-columns:repeat(3,1fr); gap:10px; margin-bottom:20px; }
  .stat-box{ background:var(--bg); border:1px solid var(--border); border-radius:11px; padding:12px; text-align:center; }
  .stat-box .num{ font-size:19px; font-weight:700; }
  .stat-box .lbl{ font-size:11px; color:var(--muted); margin-top:3px; }

  table.stat-table{ width:100%; border-collapse:collapse; font-size:12px; }
  table.stat-table th, table.stat-table td{ padding:7px 6px; text-align:center; border-bottom:1px solid var(--border); }
  table.stat-table th{ color:var(--muted); font-weight:600; font-size:10.5px; }
  table.stat-table td:first-child, table.stat-table th:first-child{ text-align:left; }
  .cell-yes{ color:var(--accent); font-weight:700; }
  .cell-no{ color:#d7d9de; }
  .row-archived td{ opacity:.5; }
  .status-btn{
    padding:5px 10px; border-radius:8px; border:1px solid var(--border); background:var(--card);
    font-size:11px; font-weight:600; cursor:pointer; white-space:nowrap;
  }
  .status-btn:hover{ border-color:var(--accent); color:var(--accent-dark); }
  .status-btn.is-archived{ color:var(--accent-dark); background:var(--accent-soft); border-color:var(--accent); }
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute">
  <defs>
    <linearGradient id="ringGrad" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2be26a"/>
      <stop offset="100%" stop-color="#9b5de5"/>
    </linearGradient>
  </defs>
</svg>

<div class="wrap">

  <header>
    <div class="brand">
      <h1>TABASCO</h1>
      <div class="sub">Håll varandra på tårna, en vecka i taget</div>
    </div>
    <div class="week-pill">Vecka <b id="weekLabel">—</b></div>
  </header>

  <div id="connBanner" class="conn-banner" style="display:none"></div>

  <div class="switcher">
    <label>Du är</label>
    <div class="avatar-row" id="avatarRow"></div>
  </div>

  <div class="grid">
    <div>
      <div class="section-title">Den här veckan — gänget</div>
      <div class="team-grid" id="teamGrid"></div>

      <div class="feed">
        <div class="section-title">Senaste aktivitet</div>
        <div id="feedList"></div>
      </div>
    </div>

    <div class="panel">
      <h2 id="panelName">Din incheckning</h2>
      <div class="panel-sub">Klicka för att markera som klar. Klicka på pennan för att redigera texten.</div>
      <div class="checklist" id="checklist"></div>
      <div class="add-row">
        <input type="text" id="newGoalInput" placeholder="Lägg till ett eget mål…" maxlength="40">
        <button id="addGoalBtn">Lägg till</button>
      </div>
      <div class="footnote">Dina mål sparas automatiskt till nästa vecka — du behöver aldrig skriva om dem, bara checka av på nytt. Tar du bort ett mål kan du aktivera det igen under Statistik.</div>
    </div>
  </div>

</div>

<div class="modal-backdrop" id="modalBackdrop">
  <div class="modal" id="modalContent"></div>
</div>

<div class="toast" id="toast"></div>

<script type="module">
/* ---------- Firebase Realtime Database (delad, live-synkad lagring) ----------
   1. Skapa ett gratis projekt på https://console.firebase.google.com
   2. Vänstermenyn -> Build -> Realtime Database -> Create Database -> välj plats -> starta i "test mode"
      (du kan strama åt reglerna senare, se längst ner i denna kommentar)
   3. Project settings -> General -> "Your apps" -> Add app -> Web -> kopiera configet
      (måste innehålla "databaseURL", t.ex. https://DITT-PROJEKT-default-rtdb.europe-west1.firebasedatabase.app)
   4. Klistra in config-objektet i FIREBASE_CONFIG nedan och ladda om sidan

   Exempel på säkrare regler när ni är klara att låsa ner det lite (Realtime Database -> Rules):
   {
     "rules": {
       "tabasco": { ".read": true, ".write": true }
     }
   }
   (öppet för läs/skriv utan inloggning — okej för en liten privat grupp, men dela aldrig configet publikt)
------------------------------------------------------------- */
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.14.1/firebase-app.js";
import { getDatabase, ref, onValue, set } from "https://www.gstatic.com/firebasejs/10.14.1/firebase-database.js";

const FIREBASE_CONFIG = {
  apiKey: "AIzaSyB1dnkBRtBBKZRVslBZmBXk5AInXf-9c4c",
  authDomain: "tabasco-324f0.firebaseapp.com",
  // TODO: byt ut raden nedan mot din riktiga databaseURL (se kommentaren ovan för var du hittar den)
  databaseURL: "https://tabasco-324f0-default-rtdb.europe-west1.firebasedatabase.app",
  projectId: "tabasco-324f0",
  storageBucket: "tabasco-324f0.firebasestorage.app",
  messagingSenderId: "867680374654",
  appId: "1:867680374654:web:b4ac04de8be09272d96d2f"
};
const FIREBASE_CONFIGURED = FIREBASE_CONFIG.apiKey !== "DIN_API_KEY";

let db = null;
let stateDocRef = null;
if(FIREBASE_CONFIGURED){
  const fbApp = initializeApp(FIREBASE_CONFIG);
  db = getDatabase(fbApp);
  stateDocRef = ref(db, "tabasco/shared");
}

function showConnBanner(html){
  const el = document.getElementById('connBanner');
  el.innerHTML = html;
  el.style.display = html ? '' : 'none';
}

/* ---------- Setup & data model ---------- */
const COLORS = ['#1f6f5c','#b8763a','#5a6bb0','#a94f7d','#3f8f8a','#c0703a','#6a5aa8','#4c8a52','#3a7ea6','#b04a5a'];
const PRESET_CATS = [
  { id:'train', label:'Tränat den här veckan' },
  { id:'nocandy', label:'Hållit mig borta från godis/skräpmat' },
  { id:'water', label:'Druckit tillräckligt med vatten' },
  { id:'partner', label:'Gjort något snällt för partnern' },
];

function isoWeekId(d){
  const date = new Date(Date.UTC(d.getFullYear(), d.getMonth(), d.getDate()));
  const day = (date.getUTCDay() + 6) % 7;
  date.setUTCDate(date.getUTCDate() - day + 3);
  const firstThursday = new Date(Date.UTC(date.getUTCFullYear(),0,4));
  const week = 1 + Math.round(((date - firstThursday) / 86400000 - 3 + ((firstThursday.getUTCDay()+6)%7)) / 7);
  return `${date.getUTCFullYear()}-W${String(week).padStart(2,'0')}`;
}
function weeksAgoId(n){
  const d = new Date();
  d.setDate(d.getDate() - n*7);
  return isoWeekId(d);
}
function weekRangeLabel(){
  const now = new Date();
  const day = (now.getDay()+6)%7;
  const monday = new Date(now); monday.setDate(now.getDate()-day);
  const sunday = new Date(monday); sunday.setDate(monday.getDate()+6);
  const opts = {month:'short', day:'numeric'};
  return `${monday.toLocaleDateString('sv-SE',opts)} – ${sunday.toLocaleDateString('sv-SE',opts)}`;
}

const CURRENT_WEEK = isoWeekId(new Date());
const HISTORY_WEEKS = 8;
const NAMES = ['Jake','Marcus','Owen','Ravi','Tom','Diego','Sam','Ben'];

function seedState(){
  const members = NAMES.map((name,i)=>({
    id:'m'+i,
    name,
    initials: name.slice(0,2).toUpperCase(),
    color: COLORS[i % COLORS.length],
    categories: PRESET_CATS.map(c=>({...c, archived:false})),
    logs: {},        // weekId -> { catId: bool }
  }));

  members.forEach((m, mi) => {
    for(let w=HISTORY_WEEKS; w>=1; w--){
      const wk = weeksAgoId(w);
      const log = {};
      m.categories.forEach((c,ci)=>{
        const bias = 0.55 + (mi%3)*0.1 - (ci===1?0.15:0);
        log[c.id] = Math.random() < bias;
      });
      m.logs[wk] = log;
    }
    m.logs[CURRENT_WEEK] = m.logs[CURRENT_WEEK] || {};
  });

  return {
    members,
    activeId: members[0].id,
    feed: [
      { text:'TABASCO är igång 🎉', ts: Date.now() - 1000*60*60*24 }
    ]
  };
}

function normalizeState(data){
  data.members.forEach(m => {
    if(!m.logs[CURRENT_WEEK]) m.logs[CURRENT_WEEK] = {};
    m.categories.forEach(c => { if(c.archived === undefined) c.archived = false; });
  });
  return data;
}
function saveState(){
  if(!FIREBASE_CONFIGURED){
    localStorage.setItem('tabascoState_offline', JSON.stringify(state));
    return;
  }
  set(stateDocRef, state).catch(err=>{
    console.error(err);
    toast('Kunde inte spara — kolla internetuppkopplingen');
  });
}

let state = null;
let editingCatId = null;
let statsOpenFor = null;

/* ---------- Helpers ---------- */
function getMember(id){ return state.members.find(m=>m.id===id); }
function activeMember(){ return getMember(state.activeId); }
function activeCats(member){ return member.categories.filter(c=>!c.archived); }

function streakFor(member, catId){
  let streak = 0;
  for(let w=0; w<52; w++){
    const wk = w===0 ? CURRENT_WEEK : weeksAgoId(w);
    const log = member.logs[wk];
    if(log && log[catId]) streak++;
    else if (wk === CURRENT_WEEK && (!log || log[catId] === undefined)) continue;
    else break;
  }
  return streak;
}
function bestStreak(member){
  return Math.max(0, ...activeCats(member).map(c=>streakFor(member,c.id)));
}
function weekProgress(member, weekId){
  const log = member.logs[weekId || CURRENT_WEEK] || {};
  const cats = activeCats(member);
  const total = cats.length || 1;
  const done = cats.filter(c=>log[c.id]).length;
  return { done, total, pct: Math.round((done/total)*100) };
}
function overallCompletionRate(member){
  let done=0, total=0;
  for(let w=0; w<=HISTORY_WEEKS; w++){
    const wk = w===0 ? CURRENT_WEEK : weeksAgoId(w);
    const log = member.logs[wk];
    if(!log) continue;
    member.categories.forEach(c=>{ if(log[c.id]!==undefined){ total++; if(log[c.id]) done++; } });
  }
  return total ? Math.round((done/total)*100) : 0;
}
function timeAgo(ts){
  const s = Math.floor((Date.now()-ts)/1000);
  if(s<60) return 'just nu';
  const m = Math.floor(s/60); if(m<60) return m+'min sedan';
  const h = Math.floor(m/60); if(h<24) return h+'tim sedan';
  const d = Math.floor(h/24); return d+'d sedan';
}
function addFeed(text){
  state.feed.unshift({text, ts:Date.now()});
  state.feed = state.feed.slice(0,25);
}
function toast(msg){
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  clearTimeout(window._toastTimer);
  window._toastTimer = setTimeout(()=>t.classList.remove('show'), 2200);
}

/* ---------- Rendering ---------- */
function ringSvg(pct){
  const r = 16, c = 2*Math.PI*r;
  const offset = c - (pct/100)*c;
  return `<svg width="38" height="38" viewBox="0 0 38 38">
    <circle cx="19" cy="19" r="${r}" stroke="#eef0f2" stroke-width="3.5" fill="none"/>
    <circle cx="19" cy="19" r="${r}" stroke="url(#ringGrad)" stroke-width="3.5" fill="none"
      stroke-dasharray="${c}" stroke-dashoffset="${offset}" stroke-linecap="round"/>
  </svg>`;
}

function render(){
  document.getElementById('weekLabel').textContent = weekRangeLabel();

  const avatarRow = document.getElementById('avatarRow');
  avatarRow.innerHTML = state.members.map(m=>{
    return `<button class="avatar-btn ${m.id===state.activeId?'active':''}" data-switch="${m.id}">
      <span class="avatar" style="background:${m.color}">${m.initials}</span>
      ${m.name}
    </button>`;
  }).join('');

  const me = activeMember();
  const teamGrid = document.getElementById('teamGrid');
  teamGrid.innerHTML = state.members.map(m=>{
    const isSelf = m.id === state.activeId;
    const prog = weekProgress(m);
    const streak = bestStreak(m);
    const log = m.logs[CURRENT_WEEK] || {};
    const catsHtml = activeCats(m).map(c=>{
      const done = !!log[c.id];
      return `<div class="mc-cat ${done?'done':''}"><span class="dot"></span>${c.label}</div>`;
    }).join('');
    return `<div class="member-card ${isSelf?'self':''}">
      <div class="mc-top">
        <span class="avatar" style="background:${m.color}">${m.initials}</span>
        <div>
          <div class="mc-name">${m.name}${isSelf?'<span class="you">DU</span>':''}</div>
          <div class="mc-streak">🔥 <b>${streak}</b> v. streak</div>
        </div>
        <div class="ring-wrap">
          ${ringSvg(prog.pct)}
          <div class="ring-pct">${prog.done}/${prog.total}</div>
        </div>
      </div>
      <div class="mc-cats">${catsHtml}</div>
      <button class="mini-btn" data-stats="${m.id}">📊 Statistik</button>
    </div>`;
  }).join('');

  document.getElementById('panelName').textContent = `${me.name}s incheckning`;
  const checklist = document.getElementById('checklist');
  const meLog = me.logs[CURRENT_WEEK] || {};
  checklist.innerHTML = activeCats(me).map(c=>{
    const on = !!meLog[c.id];
    const s = streakFor(me, c.id);
    const isEditing = editingCatId === c.id;
    const labelHtml = isEditing
      ? `<input class="ci-label-input" data-edit-input="${c.id}" value="${c.label.replace(/"/g,'&quot;')}" maxlength="40">`
      : `<div class="ci-label">${c.label}</div>`;
    return `<div class="check-item ${on?'on':''}" data-toggle="${isEditing?'':c.id}">
      <div class="box">${on?'✓':''}</div>
      ${labelHtml}
      ${s>0 && !isEditing?`<div class="ci-streak">🔥${s}</div>`:''}
      <button class="ci-icon-btn" data-edit="${c.id}" title="Redigera">${isEditing?'💾':'✎'}</button>
      <button class="ci-icon-btn danger" data-remove="${c.id}" title="Ta bort">×</button>
    </div>`;
  }).join('') || '<div class="empty">Inga mål ännu — lägg till ett nedan.</div>';

  if(editingCatId){
    const input = document.querySelector(`[data-edit-input="${editingCatId}"]`);
    if(input){ input.focus(); input.setSelectionRange(input.value.length, input.value.length); }
  }

  document.getElementById('feedList').innerHTML = state.feed.map(f=>`
    <div class="feed-item"><span class="t">${f.text}</span><span class="feed-time">${timeAgo(f.ts)}</span></div>
  `).join('') || '<div class="empty">Ingen aktivitet ännu.</div>';

  if(statsOpenFor) openStatsModal(statsOpenFor, true);
}

function openStatsModal(memberId, silent){
  statsOpenFor = memberId;
  const m = getMember(memberId);
  const isSelf = memberId === state.activeId;
  const rate = overallCompletionRate(m);
  const best = Math.max(0, ...m.categories.map(c=>streakFor(m,c.id)));
  const current = bestStreak(m);

  const weekIds = [];
  for(let w=HISTORY_WEEKS; w>=0; w--){ weekIds.push(w===0?CURRENT_WEEK:weeksAgoId(w)); }

  const rows = m.categories.map(c=>{
    const cells = weekIds.map(wk=>{
      const log = m.logs[wk];
      if(!log || log[c.id]===undefined) return '<td class="cell-no">–</td>';
      return log[c.id] ? '<td class="cell-yes">✓</td>' : '<td class="cell-no">·</td>';
    }).join('');
    const statusCell = isSelf
      ? `<td><button class="status-btn ${c.archived?'is-archived':''}" data-toggle-archive="${c.id}">${c.archived?'Aktivera':'Avaktivera'}</button></td>`
      : '';
    return `<tr class="${c.archived?'row-archived':''}"><td>${c.label}</td>${cells}${statusCell}</tr>`;
  }).join('');

  const headerCells = weekIds.map(wk=>`<th>${wk.split('-W')[1]}</th>`).join('');
  const statusHeader = isSelf ? '<th>Denna vecka</th>' : '';

  document.getElementById('modalContent').innerHTML = `
    <div class="modal-head">
      <span class="avatar" style="background:${m.color}">${m.initials}</span>
      <h3>${m.name} — statistik</h3>
      <button class="close" id="closeModal">×</button>
    </div>
    <div class="stat-summary">
      <div class="stat-box"><div class="num">${rate}%</div><div class="lbl">Snitt, ${HISTORY_WEEKS+1} veckor</div></div>
      <div class="stat-box"><div class="num">🔥 ${current}</div><div class="lbl">Nuvarande streak</div></div>
      <div class="stat-box"><div class="num">${best}</div><div class="lbl">Bästa streak</div></div>
    </div>
    <table class="stat-table">
      <thead><tr><th>Mål</th>${headerCells}${statusHeader}</tr></thead>
      <tbody>${rows}</tbody>
    </table>
  `;
  if(!silent) document.getElementById('modalBackdrop').classList.add('open');
}
function closeStatsModal(){
  document.getElementById('modalBackdrop').classList.remove('open');
  statsOpenFor = null;
}

/* ---------- Events ---------- */
document.addEventListener('click', (e)=>{
  const switchBtn = e.target.closest('[data-switch]');
  if(switchBtn){
    editingCatId = null;
    state.activeId = switchBtn.dataset.switch;
    saveState(); render();
    return;
  }
  const statsBtn = e.target.closest('[data-stats]');
  if(statsBtn){
    openStatsModal(statsBtn.dataset.stats);
    return;
  }
  if(e.target.id === 'closeModal' || e.target.id === 'modalBackdrop'){
    closeStatsModal();
    return;
  }
  const toggleArchiveBtn = e.target.closest('[data-toggle-archive]');
  if(toggleArchiveBtn){
    const me = activeMember();
    const catId = toggleArchiveBtn.dataset.toggleArchive;
    const cat = me.categories.find(c=>c.id===catId);
    if(cat){
      cat.archived = !cat.archived;
      addFeed(cat.archived
        ? `<b>${me.name}</b> avaktiverade målet "${cat.label}"`
        : `<b>${me.name}</b> aktiverade målet "${cat.label}" igen`);
      toast(cat.archived ? `"${cat.label}" avaktiverat` : `"${cat.label}" är tillbaka!`);
    }
    saveState(); render();
    return;
  }
  const editBtn = e.target.closest('[data-edit]');
  if(editBtn){
    const catId = editBtn.dataset.edit;
    if(editingCatId === catId){
      const input = document.querySelector(`[data-edit-input="${catId}"]`);
      const val = input ? input.value.trim() : '';
      if(val){
        const me = activeMember();
        const cat = me.categories.find(c=>c.id===catId);
        cat.label = val;
      }
      editingCatId = null;
      saveState();
    } else {
      editingCatId = catId;
    }
    render();
    return;
  }
  const toggle = e.target.closest('[data-toggle]');
  if(toggle && toggle.dataset.toggle){
    const me = activeMember();
    const catId = toggle.dataset.toggle;
    me.logs[CURRENT_WEEK] = me.logs[CURRENT_WEEK] || {};
    const wasOn = !!me.logs[CURRENT_WEEK][catId];
    me.logs[CURRENT_WEEK][catId] = !wasOn;
    if(!wasOn){
      const cat = me.categories.find(c=>c.id===catId);
      addFeed(`<b>${me.name}</b> checkade av "${cat.label}" ✅`);
    }
    saveState(); render();
    return;
  }
  const removeBtn = e.target.closest('[data-remove]');
  if(removeBtn){
    const me = activeMember();
    const catId = removeBtn.dataset.remove;
    const cat = me.categories.find(c=>c.id===catId);
    if(cat) cat.archived = true;
    if(editingCatId === catId) editingCatId = null;
    addFeed(`<b>${me.name}</b> tog bort målet "${cat ? cat.label : ''}" — kan aktiveras igen under Statistik`);
    saveState(); render();
    return;
  }
});

document.addEventListener('keydown', (e)=>{
  if(e.key === 'Escape') closeStatsModal();
  if(e.key === 'Enter' && editingCatId){
    const input = document.querySelector(`[data-edit-input="${editingCatId}"]`);
    if(input && document.activeElement === input){
      const me = activeMember();
      const cat = me.categories.find(c=>c.id===editingCatId);
      const val = input.value.trim();
      if(val) cat.label = val;
      editingCatId = null;
      saveState(); render();
    }
  }
});

document.getElementById('addGoalBtn').addEventListener('click', addGoal);
document.getElementById('newGoalInput').addEventListener('keydown', (e)=>{ if(e.key==='Enter') addGoal(); });
function addGoal(){
  const input = document.getElementById('newGoalInput');
  const label = input.value.trim();
  if(!label) return;
  const me = activeMember();
  const id = 'custom_' + Date.now();
  me.categories.push({ id, label, archived:false });
  input.value = '';
  addFeed(`<b>${me.name}</b> lade till ett nytt mål: "${label}"`);
  saveState(); render();
}

/* ---------- Init ---------- */
if(!FIREBASE_CONFIGURED){
  showConnBanner('Ingen delad server ikopplad ännu — appen sparar just nu bara lokalt i den här webbläsaren. Klistra in ditt Firebase-config i koden (se kommentar högst upp i &lt;script&gt;) för att alla ska se samma data.');
  const raw = localStorage.getItem('tabascoState_offline');
  state = raw ? normalizeState(JSON.parse(raw)) : seedState();
  render();
} else {
  onValue(stateDocRef, (snap) => {
    if(snap.exists()){
      state = normalizeState(snap.val());
    } else {
      state = seedState();
      set(stateDocRef, state);
    }
    showConnBanner('');
    render();
  }, (err) => {
    console.error(err);
    showConnBanner('Kunde inte ansluta till servern just nu. Kontrollera internetuppkopplingen — dina ändringar sparas när anslutningen är tillbaka.');
  });
}
</script>
</body>
</html>
