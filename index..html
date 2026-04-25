<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zoho Developer Intern Assessment</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Segoe UI',sans-serif;background:#eef2f7;color:#1a2a4a;min-height:100vh;user-select:none}
/* ── Blocker ── */
#blocker{position:fixed;inset:0;background:rgba(10,20,60,.97);z-index:99999;display:none;flex-direction:column;align-items:center;justify-content:center;color:#fff;text-align:center;padding:30px}
#blocker h2{font-size:22px;margin-bottom:12px;color:#f87171}
#blocker p{font-size:14px;opacity:.8;margin-bottom:20px;max-width:400px;line-height:1.6}
#blocker .b-count{font-size:56px;font-weight:800;color:#f87171;margin-bottom:8px}
#blocker .b-btn{background:#fff;color:#1e3a8a;border:none;padding:12px 32px;border-radius:8px;font-size:14px;font-weight:700;cursor:pointer;font-family:inherit}
/* ── Header ── */
.hdr{background:#1e3a8a;color:#fff;padding:12px 22px;display:flex;justify-content:space-between;align-items:center;position:sticky;top:0;z-index:500;box-shadow:0 2px 8px rgba(0,0,0,.2)}
.hdr-l .sl{font-size:10px;opacity:.65;text-transform:uppercase;letter-spacing:.5px}
.hdr-l .st{font-size:14px;font-weight:700}
.hdr-r{display:flex;align-items:center;gap:12px}
.timer{background:rgba(255,255,255,.15);padding:6px 14px;border-radius:6px;font-size:16px;font-weight:700;letter-spacing:1px;min-width:74px;text-align:center}
.timer.warn{background:#dc2626;animation:pulse 1s infinite}
.cam-dot{width:10px;height:10px;border-radius:50%;background:#22c55e;flex-shrink:0;animation:blink 1.5s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.6}}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
.prog-bar{height:4px;background:#c7d2fe}
.prog-fill{height:100%;background:#6366f1;transition:width .4s}
/* ── Camera PiP ── */
#cam-pip{position:fixed;bottom:16px;right:16px;z-index:600;border-radius:10px;overflow:hidden;border:2px solid #22c55e;box-shadow:0 4px 20px rgba(0,0,0,.4);display:none;background:#000;cursor:move}
#cam-pip video{width:160px;height:110px;object-fit:cover;display:block}
.cam-label{background:#22c55e;color:#fff;font-size:10px;font-weight:700;text-align:center;padding:2px 0;letter-spacing:.4px}
/* ── Cards / layout ── */
.card{background:#fff;border-radius:14px;box-shadow:0 2px 12px rgba(0,0,0,.07);padding:28px;max-width:820px;margin:24px auto}
.info-wrap{max-width:580px;margin:40px auto;padding:0 16px}
.logo{text-align:center;margin-bottom:24px}
.logo h1{font-size:20px;font-weight:800;color:#1e3a8a}
.logo p{color:#64748b;margin-top:4px;font-size:13px}
/* ── Form elements ── */
.form-group{margin-bottom:14px;position:relative}
.form-group label{display:block;font-size:11px;font-weight:700;color:#475569;margin-bottom:4px;text-transform:uppercase;letter-spacing:.4px}
input[type=text],input[type=email],input[type=tel],input[type=url],select{width:100%;padding:9px 13px;border:1.5px solid #e2e8f0;border-radius:8px;font-size:13px;outline:none;font-family:inherit;transition:border .2s;background:#fff;color:#1e293b}
input:focus,select:focus{border-color:#3b82f6;box-shadow:0 0 0 3px rgba(59,130,246,.1)}
input.err,select.err{border-color:#ef4444 !important}
.err-msg{color:#dc2626;font-size:11px;margin-top:3px;display:none;font-weight:600}
.err-msg.show{display:block}
.radio-row{display:flex;gap:14px;flex-wrap:wrap;margin-top:5px}
.radio-row label{display:flex;align-items:center;gap:6px;font-size:13px;cursor:pointer;color:#334155;font-weight:400;text-transform:none;letter-spacing:0}
.radio-row input[type=radio]{width:auto;accent-color:#1e3a8a}
/* ── Upload ── */
.upload-zone{border:2px dashed #cbd5e1;border-radius:10px;padding:20px;text-align:center;cursor:pointer;transition:all .2s}
.upload-zone:hover{border-color:#3b82f6;background:#f8faff}
.upload-zone p{font-size:13px;color:#64748b;pointer-events:none}
.upload-zone .fname{font-size:12px;color:#22c55e;margin-top:6px;font-weight:600}
/* ── Boxes ── */
.rules-box{background:#fffbeb;border:1.5px solid #fde68a;border-radius:10px;padding:14px;margin:16px 0}
.rules-box h3{font-size:11px;font-weight:800;color:#92400e;margin-bottom:7px;text-transform:uppercase;letter-spacing:.4px}
.rules-box li{font-size:12px;color:#78350f;margin-bottom:4px}
.rules-box ul{padding-left:16px}
.cam-req{background:#f0fdf4;border:1.5px solid #86efac;border-radius:10px;padding:14px;margin:12px 0;font-size:12px;color:#15803d;line-height:1.6}
.cam-req.denied{background:#fef2f2;border-color:#fca5a5;color:#dc2626}
.mobile-warn{background:#fff7ed;border:1.5px solid #fed7aa;border-radius:10px;padding:12px 14px;margin-bottom:14px;font-size:13px;color:#9a3412;display:none}
/* ── Buttons ── */
.btn-row{display:flex;justify-content:flex-end;gap:10px;margin-top:20px}
.btn{padding:9px 20px;border-radius:8px;font-size:13px;font-weight:700;cursor:pointer;border:none;transition:all .2s;font-family:inherit}
.btn-primary{background:#1e3a8a;color:#fff}
.btn-primary:hover{background:#1d4ed8;transform:translateY(-1px)}
.btn-primary:disabled{background:#94a3b8;cursor:not-allowed;transform:none}
.btn-secondary{background:#f1f5f9;color:#475569}
/* ── Section / questions ── */
.sec-badge{display:inline-block;background:#eff6ff;color:#1d4ed8;padding:4px 12px;border-radius:20px;font-size:11px;font-weight:800;margin-bottom:16px;letter-spacing:.4px;text-transform:uppercase}
.question{margin-bottom:22px;padding-bottom:22px;border-bottom:1px solid #f1f5f9}
.question:last-of-type{border-bottom:none;margin-bottom:0;padding-bottom:0}
.q-num{font-size:10px;font-weight:800;color:#94a3b8;margin-bottom:3px;letter-spacing:.5px}
.q-text{font-size:14px;color:#1e293b;font-weight:600;line-height:1.6;margin-bottom:4px}
.q-hint{font-size:11px;color:#94a3b8;font-style:italic;margin-bottom:7px}
textarea{width:100%;min-height:80px;border:1.5px solid #e2e8f0;border-radius:8px;padding:10px;font-size:13px;font-family:inherit;resize:vertical;outline:none;transition:border .2s;color:#1e293b;user-select:text}
textarea:focus{border-color:#3b82f6;box-shadow:0 0 0 3px rgba(59,130,246,.08)}
/* ── Section warning ── */
.sec-warn{background:#fffbeb;border:1.5px solid #fde68a;border-radius:10px;padding:14px;margin-bottom:16px;font-size:13px;color:#92400e;display:none}
/* ── Loading ── */
.loading{text-align:center;padding:60px 20px}
.spinner{width:48px;height:48px;border:4px solid #dbeafe;border-top-color:#2563eb;border-radius:50%;animation:spin .8s linear infinite;margin:0 auto 18px}
@keyframes spin{to{transform:rotate(360deg)}}
.loading h2{color:#1e3a8a;margin-bottom:8px;font-size:20px}
.loading p{color:#64748b;font-size:14px}
/* ── Results ── */
.res-wrap{max-width:820px;margin:0 auto;padding:20px 14px}
.score-hero{background:linear-gradient(135deg,#1e3a8a,#3b82f6);color:#fff;border-radius:14px;padding:28px;text-align:center;margin-bottom:18px;box-shadow:0 4px 20px rgba(30,58,138,.3)}
.sc-num{font-size:68px;font-weight:800;line-height:1}
.sc-den{font-size:32px;opacity:.8}
.sc-pct{font-size:16px;font-weight:600;margin-top:6px}
.verdict-pass{color:#86efac;font-weight:800}
.verdict-fail{color:#fca5a5;font-weight:800}
.sec-scores{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:10px;margin-bottom:18px}
.ssc{background:#fff;border-radius:10px;padding:12px;text-align:center;box-shadow:0 1px 6px rgba(0,0,0,.06)}
.ssc .sn{font-size:10px;color:#64748b;font-weight:700;text-transform:uppercase;margin-bottom:3px}
.ssc .sv{font-size:20px;font-weight:800;color:#1e3a8a}
.eval-section{margin-bottom:22px}
.eval-section h3{font-size:13px;font-weight:800;color:#1e3a8a;margin-bottom:10px;padding-bottom:7px;border-bottom:2px solid #dbeafe}
.eq{background:#f8fafc;border-radius:9px;padding:12px 14px;margin-bottom:8px;border-left:4px solid #e2e8f0;border-radius:0 8px 8px 0}
.eq.full{border-left-color:#22c55e;background:#f0fdf4}
.eq.half{border-left-color:#f59e0b;background:#fffbeb}
.eq.zero{border-left-color:#ef4444;background:#fef2f2}
.eq-hdr{display:flex;align-items:center;gap:8px;margin-bottom:5px}
.eq-num{font-size:10px;font-weight:800;color:#64748b}
.eq-sc{font-size:12px;font-weight:800}
.s-full{color:#16a34a}.s-half{color:#d97706}.s-zero{color:#dc2626}
.eq-ans{font-size:12px;color:#334155;background:#fff;padding:7px 9px;border-radius:6px;margin:5px 0;border:1px solid #e2e8f0;line-height:1.5;max-height:72px;overflow-y:auto}
.eq-reason{font-size:12px;color:#475569;line-height:1.5}
/* ── Sheet ── */
.nav-tabs{display:flex;gap:2px;background:#e2e8f0;border-radius:8px;padding:3px;max-width:820px;margin:14px auto 0}
.nav-tab{flex:1;text-align:center;padding:7px;border-radius:6px;font-size:12px;font-weight:700;cursor:pointer;transition:all .2s;color:#64748b}
.nav-tab.active{background:#fff;color:#1e3a8a;box-shadow:0 1px 4px rgba(0,0,0,.1)}
.sheet-wrap{max-width:98vw;overflow-x:auto;margin:0 auto;padding:16px}
.sheet-table{width:100%;border-collapse:collapse;font-size:12px;background:#fff;border-radius:10px;overflow:hidden;box-shadow:0 2px 10px rgba(0,0,0,.07)}
.sheet-table th{background:#1e3a8a;color:#fff;padding:9px 12px;text-align:left;font-size:11px;white-space:nowrap}
.sheet-table td{padding:8px 12px;border-bottom:1px solid #f1f5f9;max-width:200px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.sheet-table tr:last-child td{border-bottom:none}
.sheet-table tr:hover td{background:#f8fafc}
.tag{display:inline-block;padding:2px 8px;border-radius:10px;font-size:10px;font-weight:700}
.tag-pass{background:#dcfce7;color:#16a34a}
.tag-fail{background:#fee2e2;color:#dc2626}
.divider{height:1px;background:#e2e8f0;margin:14px 0}
/* ── Toast ── */
#toast{position:fixed;bottom:90px;left:50%;transform:translateX(-50%);background:#1e293b;color:#fff;padding:10px 22px;border-radius:24px;font-size:13px;font-weight:600;z-index:9999;opacity:0;transition:opacity .3s;pointer-events:none}
</style>
</head>
<body>

<!-- ══ Blocker overlay ══ -->
<div id="blocker">
  <div class="b-count" id="blk-count">1</div>
  <h2>⚠️ Tab switch detected!</h2>
  <p>This violation is permanently recorded and will be visible to the reviewer. Repeated violations may lead to disqualification.</p>
  <button class="b-btn" onclick="dismissBlocker()">I understand — Resume Test</button>
</div>

<!-- ══ Camera PiP ══ -->
<div id="cam-pip">
  <div class="cam-label">● RECORDING</div>
  <video id="camvid" autoplay muted playsinline></video>
</div>

<!-- ══ Toast ══ -->
<div id="toast"></div>

<div id="hdr-area"></div>
<div id="nav-area"></div>
<div id="app"></div>

<script>
// ─────────────────────────────────────────────
//  CONFIG — paste your Apps Script URL here
// ─────────────────────────────────────────────
const BACKEND_URL = "https://script.google.com/macros/s/AKfycbzTVwXJUJ3wdli6w-q1BfAQ0axOeDumapnje-zkdK3rGH5E0OPj70g3Ld5k969mwWqz/exec";

// ─────────────────────────────────────────────
//  Data
// ─────────────────────────────────────────────
const SECTIONS = [
  {title:"CRM & Lead Management",short:"CRM",
   questions:["You have 100 leads coming daily. Only 3 salespeople are available. How will you distribute leads and why?","A customer filled the form 3 times with slightly different names. What will you do to handle this?","Leads are coming but no one is converting them. List 3 possible reasons and what you would check first.","Two salespeople contacted the same customer and confused them. How would you prevent this in a system?","You want every new lead to get a welcome email automatically. Explain the logic (not tool steps).","Some leads don't have phone numbers. What process would you put in place?","A lead becomes a paying customer. What data changes should happen?","Manager wants daily report of new leads. What data would you include?"],
   hints:["Think about prioritization, fairness, and lead scoring","Consider deduplication — email match, fuzzy name matching, merge strategy","Think CRM data quality, follow-up cadence, and lead qualification criteria","Consider lead ownership rules, assignment lock, and activity tracking","Describe trigger → condition → action in plain logic, no tool names","Validation at entry, enrichment tools, alternative contact channels","Status change, deal creation, contact record update, history preservation","Count, source, stage, owner, conversion rate, pending follow-ups"]},
  {title:"SQL",short:"SQL",
   questions:["Get all customers who have placed at least one order. (Write SQL query)","Find total amount spent by each customer. (Write SQL query)","Find top 3 customers by total spend. (Write SQL query)","Find customers who never placed any order. (Write SQL query)","Get latest order for each customer. (Write SQL query)","Explain the difference between INNER JOIN and LEFT JOIN using the customers/orders example. (2–4 lines)","Why might GROUP BY give wrong results sometimes? (2–4 lines)","You see duplicate rows in query results. What could be the reason? (2–4 lines)","Filter orders placed in the last 7 days. (Write SQL query)","If a query is running slow, what will you check first? (2–4 lines)"],
   hints:["Use JOIN or EXISTS/IN subquery","Use GROUP BY with SUM()","Use ORDER BY DESC with LIMIT 3","Use LEFT JOIN ... WHERE IS NULL, or NOT IN / NOT EXISTS","Use MAX(order_date) with GROUP BY or a window function","Explain what each returns when no match exists","Think about non-aggregated columns in SELECT","Think about missing DISTINCT, bad JOINs, or duplicate source data","Use date functions like CURDATE() or NOW()","Think indexes, query plan / EXPLAIN, full table scan vs index scan"]},
  {title:"Python",short:"Python",
   questions:["What is a list in Python? Give an example.","Given data = [1,2,2,3,4,4], return the frequency of each element. Explain the approach you would take.","What is a dictionary? How is it different from a list?","What will this output and why?\n  a = [1,2,3]\n  b = a\n  b.append(4)\n  print(a)\n(2–4 lines explanation)","You get a list of numbers. Return only the even numbers. Explain your approach.","You have a list of numbers. Explain the logic to remove duplicates."],
   hints:["Include definition and a short code example","Think loops, dict counter, or collections.Counter","Key-value pairs vs indexed sequence — access, use cases","Think about references vs copies (mutable objects)","Think modulo operator and list comprehension or filter()","Think about sets or a 'seen' tracking approach"]},
  {title:"Math & Aptitude",short:"Quant",
   questions:["20% of a number is 80. Find the number. Show all steps.","A product's price increases by 10%, then decreases by 10%. What is the final impact? Show all steps.","Boys to girls ratio = 2:3, total students = 50. Find the number of boys. Show steps.","Find the average of 10, 20, 30 and explain the steps.","Daily sales for 5 days: 100, 200, 150, 250, 300. What is the average? Show steps.","Find the next number in the sequence: 2, 6, 12, 20, ? — Explain your reasoning."],
   hints:["Set up: (20/100) × N = 80, solve for N","Start with ₹100 as base price, apply % changes one by one","Total ratio parts = 2+3 = 5, boys = (2/5) × 50","Add all values, divide by count","Sum all 5 values, divide by 5","Look at differences: 4, 6, 8, 10 — what's the pattern?"]}
];

const EVAL_SYSTEM = `You are an evaluation engine for an intern assessment. Evaluate candidate responses and assign marks strictly.

SCORING: Each question = 1 mark. Use 0, 0.5, or 1.
- 1 = correct logic, clear reasoning, relevant answer
- 0.5 = partially correct, vague but directionally right  
- 0 = incorrect, irrelevant, no reasoning shown

RULES:
- SQL: logically correct (minor syntax issues okay)
- Python: evaluate logic not syntax perfection
- CRM: must show real-world thinking, not generic statements
- Quant: must include steps — final answer alone = 0
- AI-generated check: if answer appears AI-generated (overly perfect, no personalization, textbook tone), reduce by 0.5 and note in Reason

OUTPUT FORMAT — follow exactly for all 30 questions:
Q1:
Score: <0 / 0.5 / 1>
Answer: <exact candidate answer>
Reason: <1-2 line justification>

Q2:
...continue through Q30...

TOTAL: <sum>/30

No extra commentary. Return only the evaluation in the exact format above.`;

// ─────────────────────────────────────────────
//  State
// ─────────────────────────────────────────────
let state = 'info', viewTab = 'assessment';
let candidate = {name:'',email:'',phone:'',location:'',linkedin:'',fulltime:'',startdate:'',isstudent:'',resumeName:'',resumeData:null};
let answers = Array(30).fill('');
let curSec = 0, timeLeft = 5400, timerInt = null;
let violations = 0, proctorActive = false;
let evalResult = null, responses = [];
let camStream = null, mediaRecorder = null, recChunks = [], camGranted = false;

const totalQ = SECTIONS.reduce((a,s) => a + s.questions.length, 0);
function secOff(si){ return SECTIONS.slice(0,si).reduce((a,s) => a + s.questions.length, 0); }
function fmt(s){ const m=Math.floor(s/60),sc=s%60; return `${String(m).padStart(2,'0')}:${String(sc).padStart(2,'0')}`; }

// ─────────────────────────────────────────────
//  Toast
// ─────────────────────────────────────────────
function toast(msg, dur=2800){
  const t = document.getElementById('toast');
  t.textContent = msg; t.style.opacity='1';
  setTimeout(()=>t.style.opacity='0', dur);
}

// ─────────────────────────────────────────────
//  Proctor — only activated AFTER test starts
// ─────────────────────────────────────────────
function activateProctor(){
  proctorActive = true;
  document.addEventListener('visibilitychange', onVis);
  window.addEventListener('blur', onBlur);
  document.addEventListener('contextmenu', e => { if(proctorActive) e.preventDefault(); });
  document.addEventListener('keydown', e => {
    if(!proctorActive) return;
    if((e.ctrlKey||e.metaKey) && ['c','v','a','u','s','p'].includes(e.key.toLowerCase())) e.preventDefault();
    if(e.key==='F12' || (e.ctrlKey&&e.shiftKey&&['i','j','c'].includes(e.key.toLowerCase()))) e.preventDefault();
  });
}
function onVis(){ if(document.hidden && proctorActive){ violations++; showBlocker(); } }
function onBlur(){ if(proctorActive){ violations++; showBlocker(); } }
function showBlocker(){ document.getElementById('blk-count').textContent=violations; document.getElementById('blocker').style.display='flex'; }
function dismissBlocker(){ document.getElementById('blocker').style.display='none'; }

// ─────────────────────────────────────────────
//  Camera
// ─────────────────────────────────────────────
async function startCam(){
  try {
    camStream = await navigator.mediaDevices.getUserMedia({video:true,audio:true});
    document.getElementById('camvid').srcObject = camStream;
    document.getElementById('cam-pip').style.display = 'block';
    camGranted = true;
    if(window.MediaRecorder){
      const opts = MediaRecorder.isTypeSupported('video/webm;codecs=vp9') ? {mimeType:'video/webm;codecs=vp9'} : {};
      mediaRecorder = new MediaRecorder(camStream, opts);
      mediaRecorder.ondataavailable = e => { if(e.data.size>0) recChunks.push(e.data); };
      mediaRecorder.start(2000);
    }
    updateCamUI(true);
  } catch(err) {
    camGranted = false;
    updateCamUI(false);
  }
}

function updateCamUI(ok){
  const el = document.getElementById('cam-status-box');
  if(!el) return;
  if(ok){
    el.className='cam-req';
    el.innerHTML=`<strong>📷 Camera active & recording</strong> — your session is being monitored. Keep your face visible at all times.<br><span style="font-size:11px;margin-top:4px;display:block;opacity:.8">Audio is also being recorded.</span>`;
  } else {
    el.className='cam-req denied';
    el.innerHTML=`<strong>📷 Camera access denied.</strong> You must allow camera access to take this assessment. Please refresh the page and click Allow when prompted.<br><button class="btn btn-primary" style="margin-top:8px;font-size:12px;padding:6px 14px" onclick="startCam()">Try Again</button>`;
  }
}

function stopCam(){
  if(mediaRecorder && mediaRecorder.state !== 'inactive') mediaRecorder.stop();
  if(camStream) camStream.getTracks().forEach(t => t.stop());
  document.getElementById('cam-pip').style.display = 'none';
}

function downloadRecording(){
  if(!recChunks.length){ toast('No recording available.'); return; }
  const blob = new Blob(recChunks, {type:'video/webm'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href=url; a.download=`${candidate.name.replace(/\s+/g,'_')}_cam_recording.webm`; a.click();
  toast('Recording download started!');
}

// ─────────────────────────────────────────────
//  Auto-save answers to sessionStorage
// ─────────────────────────────────────────────
function autoSave(){
  try { sessionStorage.setItem('zass_answers', JSON.stringify(answers)); } catch(e){}
}
function loadSaved(){
  try {
    const s = sessionStorage.getItem('zass_answers');
    if(s){ answers = JSON.parse(s); toast('Draft answers restored from last session.'); }
  } catch(e){}
}

// ─────────────────────────────────────────────
//  Timer
// ─────────────────────────────────────────────
function startTimer(){
  timerInt = setInterval(()=>{
    timeLeft--;
    const el = document.getElementById('timer');
    if(el){ el.textContent=fmt(timeLeft); if(timeLeft<600) el.classList.add('warn'); }
    if(timeLeft<=0){ clearInterval(timerInt); toast('Time is up! Submitting...'); doSubmit(); }
    if(timeLeft % 60 === 0) autoSave();
  }, 1000);
}

// ─────────────────────────────────────────────
//  Render
// ─────────────────────────────────────────────
function renderHdr(){
  const ha = document.getElementById('hdr-area');
  if(state==='info'){ ha.innerHTML=''; return; }
  if(state==='evaluating'){
    ha.innerHTML=`<div class="hdr"><div class="hdr-l"><div class="st">Zoho Intern Assessment — Evaluating...</div></div></div>`;
    return;
  }
  if(state==='results'){
    ha.innerHTML=`<div class="hdr"><div class="hdr-l"><div class="st">Assessment Complete — ${candidate.name}</div></div><div class="hdr-r"><button class="btn" style="background:rgba(255,255,255,.15);color:#fff;font-size:11px;padding:6px 14px;border:none" onclick="downloadRecording()">↓ Download Recording</button></div></div>`;
    return;
  }
  const sec = SECTIONS[curSec];
  const pct = Math.round((secOff(curSec)/totalQ)*100);
  ha.innerHTML=`<div class="hdr">
    <div class="hdr-l"><div class="sl">Section ${curSec+1} of ${SECTIONS.length}</div><div class="st">${sec.title}</div></div>
    <div class="hdr-r">
      ${camGranted?'<div class="cam-dot" title="Camera recording active"></div>':''}
      <span style="font-size:11px;opacity:.7">${candidate.name}</span>
      <div class="timer" id="timer">${fmt(timeLeft)}</div>
    </div>
  </div>
  <div class="prog-bar"><div class="prog-fill" style="width:${pct}%"></div></div>`;
}

function renderNav(){
  const na = document.getElementById('nav-area');
  if(state!=='results'){ na.innerHTML=''; return; }
  na.innerHTML=`<div class="nav-tabs">
    <div class="nav-tab ${viewTab==='assessment'?'active':''}" onclick="setTab('assessment')">📊 Evaluation Report</div>
    <div class="nav-tab ${viewTab==='sheet'?'active':''}" onclick="setTab('sheet')">📋 All Responses (${responses.length})</div>
  </div>`;
}

function setTab(t){ viewTab=t; renderNav(); renderApp(); }

function renderApp(){
  const app = document.getElementById('app');
  if(state==='info') app.innerHTML = renderInfo();
  else if(state==='section') app.innerHTML = renderSection();
  else if(state==='evaluating') app.innerHTML = renderLoading();
  else if(state==='results') app.innerHTML = (viewTab==='sheet') ? renderSheet() : renderResults();
}

function render(){ renderHdr(); renderNav(); renderApp(); }

// ─────────────────────────────────────────────
//  Mobile detection
// ─────────────────────────────────────────────
function isMobile(){ return window.innerWidth < 768; }

// ─────────────────────────────────────────────
//  Info form
// ─────────────────────────────────────────────
function renderInfo(){
  const mw = isMobile() ? `<div class="mobile-warn" style="display:block">⚠️ <strong>Desktop recommended.</strong> This assessment is best taken on a laptop or desktop computer. Mobile experience may be limited.</div>` : '';
  return `<div class="info-wrap">
  ${mw}
  <div class="card">
    <div class="logo"><h1>🧩 Zoho Developer Intern Assessment</h1><p>Complete all fields carefully before starting</p></div>

    <div class="divider"></div>
    <p style="font-size:11px;font-weight:700;color:#94a3b8;text-transform:uppercase;letter-spacing:.5px;margin-bottom:12px">Personal Information</p>

    <div class="form-group">
      <label>Full Name *</label>
      <input type="text" id="cname" placeholder="Your full name" oninput="clearErr(this)">
      <div class="err-msg" id="err-name">Please enter your full name</div>
    </div>
    <div class="form-group">
      <label>Email Address *</label>
      <input type="email" id="cemail" placeholder="your@email.com" oninput="clearErr(this)">
      <div class="err-msg" id="err-email">Please enter a valid email address</div>
    </div>
    <div class="form-group">
      <label>Phone Number *</label>
      <input type="tel" id="cphone" placeholder="+91 9XXXXXXXXX" oninput="clearErr(this)">
      <div class="err-msg" id="err-phone">Please enter your phone number</div>
    </div>
    <div class="form-group">
      <label>Current Location (City, State) *</label>
      <input type="text" id="cloc" placeholder="e.g. Mumbai, Maharashtra" oninput="clearErr(this)">
      <div class="err-msg" id="err-loc">Please enter your current location</div>
    </div>
    <div class="form-group">
      <label>LinkedIn Profile URL</label>
      <input type="url" id="clinkedin" placeholder="https://linkedin.com/in/yourprofile">
    </div>

    <div class="divider"></div>
    <p style="font-size:11px;font-weight:700;color:#94a3b8;text-transform:uppercase;letter-spacing:.5px;margin-bottom:12px">Availability</p>

    <div class="form-group">
      <label>Are you available for a full-time, in-office internship in Mumbai for 6 months? *</label>
      <div class="radio-row" id="rg-fulltime">
        <label><input type="radio" name="fulltime" value="Yes"> Yes, fully available</label>
        <label><input type="radio" name="fulltime" value="No"> No</label>
        <label><input type="radio" name="fulltime" value="Maybe"> Maybe (open to discuss)</label>
      </div>
      <div class="err-msg" id="err-fulltime">Please select an option</div>
    </div>
    <div class="form-group">
      <label>When can you start? *</label>
      <select id="cstart" oninput="clearErr(this)">
        <option value="">— Select —</option>
        <option>Immediately</option>
        <option>Within 2 weeks</option>
        <option>Within 1 month</option>
        <option>After 1–2 months</option>
        <option>After 3+ months</option>
      </select>
      <div class="err-msg" id="err-start">Please select when you can start</div>
    </div>
    <div class="form-group">
      <label>Are you currently a student? *</label>
      <div class="radio-row" id="rg-student">
        <label><input type="radio" name="isstudent" value="Yes, currently studying"> Yes, currently studying</label>
        <label><input type="radio" name="isstudent" value="No, graduated"> No, graduated</label>
        <label><input type="radio" name="isstudent" value="No, currently working"> No, currently working</label>
      </div>
      <div class="err-msg" id="err-student">Please select an option</div>
    </div>

    <div class="divider"></div>
    <p style="font-size:11px;font-weight:700;color:#94a3b8;text-transform:uppercase;letter-spacing:.5px;margin-bottom:12px">Resume</p>

    <div class="form-group">
      <label>Upload Your Resume (PDF preferred) *</label>
      <div class="upload-zone" onclick="document.getElementById('resumefile').click()">
        <input type="file" id="resumefile" accept=".pdf,.doc,.docx" style="display:none" onchange="handleResume(event)">
        <p>📄 Click to upload your resume</p>
        <p style="font-size:11px;color:#94a3b8;margin-top:4px">PDF, DOC or DOCX — max 5 MB</p>
        <div class="fname" id="fname-disp"></div>
      </div>
      <div class="err-msg" id="err-resume">Please upload your resume before starting</div>
    </div>

    <div class="divider"></div>
    <p style="font-size:11px;font-weight:700;color:#94a3b8;text-transform:uppercase;letter-spacing:.5px;margin-bottom:12px">Camera & Proctoring</p>

    <div id="cam-status-box" class="cam-req">
      <strong>📷 Camera access is required</strong> for this assessment. You will be recorded throughout. Please click below to enable your camera before starting.
      <div style="margin-top:10px">
        <button class="btn btn-primary" style="font-size:12px;padding:6px 16px" onclick="startCam()">Enable Camera</button>
      </div>
    </div>
    <div class="err-msg" id="err-cam" style="margin-top:4px">Camera access is required. Please enable your camera above.</div>

    <div class="rules-box" style="margin-top:14px">
      <h3>📋 Assessment Rules</h3>
      <ul>
        <li>30 questions across 4 sections — CRM, SQL, Python & Aptitude</li>
        <li>Time limit: <strong>90 minutes</strong> — the timer starts when you click Start</li>
        <li>Tab switching triggers a full-screen blocker and records a violation</li>
        <li>Right-click, copy, paste and DevTools are disabled during the test</li>
        <li>Your camera records the entire session — keep your face visible</li>
        <li>AI-generated and copied answers will be penalized by the evaluator</li>
        <li>You cannot go back to a previous section once you move forward</li>
      </ul>
    </div>

    <div class="btn-row">
      <button class="btn btn-primary" id="start-btn" onclick="startAssessment()">Start Proctored Assessment →</button>
    </div>
  </div>
  </div>`;
}

function clearErr(el){ el.classList.remove('err'); }

function handleResume(e){
  const f = e.target.files[0];
  if(!f) return;
  if(f.size > 5*1024*1024){ toast('File too large — max 5 MB.'); return; }
  candidate.resumeName = f.name;
  const r = new FileReader();
  r.onload = () => { candidate.resumeData = r.result; };
  r.readAsDataURL(f);
  document.getElementById('fname-disp').textContent = '✓ ' + f.name;
  document.getElementById('err-resume').classList.remove('show');
}

function showErr(id, inputId){
  const em = document.getElementById(id);
  if(em) em.classList.add('show');
  if(inputId){
    const el = document.getElementById(inputId);
    if(el) el.classList.add('err');
  }
}

function startAssessment(){
  // Clear old errors
  document.querySelectorAll('.err-msg').forEach(e=>e.classList.remove('show'));
  document.querySelectorAll('.err').forEach(e=>e.classList.remove('err'));

  let ok = true;
  const n = document.getElementById('cname').value.trim();
  const em = document.getElementById('cemail').value.trim();
  const ph = document.getElementById('cphone').value.trim();
  const lo = document.getElementById('cloc').value.trim();
  const ft = document.querySelector('input[name=fulltime]:checked');
  const st = document.getElementById('cstart').value;
  const is = document.querySelector('input[name=isstudent]:checked');

  if(!n){ showErr('err-name','cname'); ok=false; }
  if(!em || !/\S+@\S+\.\S+/.test(em)){ showErr('err-email','cemail'); ok=false; }
  if(!ph){ showErr('err-phone','cphone'); ok=false; }
  if(!lo){ showErr('err-loc','cloc'); ok=false; }
  if(!ft){ showErr('err-fulltime',null); ok=false; }
  if(!st){ showErr('err-start','cstart'); ok=false; }
  if(!is){ showErr('err-student',null); ok=false; }
  if(!candidate.resumeData){ showErr('err-resume',null); ok=false; }
  if(!camGranted){ showErr('err-cam',null); ok=false; }

  if(!ok){
    // Scroll to first error
    const first = document.querySelector('.err-msg.show');
    if(first) first.scrollIntoView({behavior:'smooth', block:'center'});
    return;
  }

  candidate = {...candidate, name:n, email:em, phone:ph, location:lo,
    linkedin: document.getElementById('clinkedin').value.trim(),
    fulltime: ft.value, startdate:st, isstudent:is.value };

  loadSaved();
  activateProctor(); // ← proctor starts ONLY here
  state = 'section'; curSec = 0;
  startTimer();
  render();
  window.scrollTo(0,0);
}

// ─────────────────────────────────────────────
//  Section
// ─────────────────────────────────────────────
function renderSection(){
  const sec = SECTIONS[curSec];
  const off = secOff(curSec);
  const isLast = curSec === SECTIONS.length-1;
  const qs = sec.questions.map((q,i) => `
    <div class="question">
      <div class="q-num">Q${off+i+1} of ${totalQ}</div>
      <div class="q-text">${q.replace(/\n/g,'<br>')}</div>
      <div class="q-hint">💡 Hint: ${sec.hints[i]}</div>
      <textarea id="ta${i}" placeholder="Write your answer here..." oninput="autoSaveTa()">${answers[off+i]||''}</textarea>
    </div>`).join('');
  return `<div class="card">
    <div class="sec-warn" id="sec-warn">⚠️ You have left most answers in this section empty. Are you sure you want to continue? <button class="btn btn-secondary" style="font-size:11px;padding:4px 12px;margin-left:10px" onclick="dismissSecWarn()">Go back</button> <button class="btn btn-primary" style="font-size:11px;padding:4px 12px;margin-left:6px" onclick="forceNext()">Continue anyway</button></div>
    <span class="sec-badge">Section ${curSec+1} of ${SECTIONS.length} — ${sec.title}</span>
    ${qs}
    <div class="btn-row">
      ${isLast
        ? `<button class="btn btn-primary" onclick="confirmSubmit()">Submit Assessment ✓</button>`
        : `<button class="btn btn-primary" onclick="nextSection()">Next Section →</button>`}
    </div>
  </div>`;
}

let forceNextAllowed = false;
function dismissSecWarn(){ document.getElementById('sec-warn').style.display='none'; forceNextAllowed=false; }
function forceNext(){ forceNextAllowed=true; nextSection(); }

function autoSaveTa(){ saveAns(); autoSave(); }

function saveAns(){
  const off = secOff(curSec);
  SECTIONS[curSec].questions.forEach((_,i) => {
    const ta = document.getElementById(`ta${i}`);
    if(ta) answers[off+i] = ta.value;
  });
}

function nextSection(){
  saveAns();
  // Check if too many empty — warn user
  const off = secOff(curSec);
  const count = SECTIONS[curSec].questions.length;
  const empty = answers.slice(off, off+count).filter(a => !a.trim()).length;
  if(!forceNextAllowed && empty > Math.floor(count*0.7)){
    document.getElementById('sec-warn').style.display='block';
    window.scrollTo(0,0);
    return;
  }
  forceNextAllowed = false;
  curSec++;
  render();
  window.scrollTo(0,0);
}

function confirmSubmit(){
  saveAns();
  const empty = answers.filter(a=>!a.trim()).length;
  const msg = empty > 0
    ? `You have ${empty} unanswered question${empty>1?'s':''}. Submit anyway? This cannot be undone.`
    : 'Submit your assessment? This cannot be undone.';
  if(confirm(msg)) doSubmit();
}

// ─────────────────────────────────────────────
//  Loading
// ─────────────────────────────────────────────
function renderLoading(){
  return `<div class="loading">
    <div class="spinner"></div>
    <h2>Evaluating your responses…</h2>
    <p>Our AI is carefully reviewing all 30 answers. This may take up to 30 seconds.</p>
  </div>`;
}

// ─────────────────────────────────────────────
//  Submit
// ─────────────────────────────────────────────
async function doSubmit(){
  clearInterval(timerInt);
  proctorActive = false;
  stopCam();
  state = 'evaluating'; render();

  // Build prompt
  let prompt = `Candidate: ${candidate.name} | Email: ${candidate.email} | Phone: ${candidate.phone} | Location: ${candidate.location} | LinkedIn: ${candidate.linkedin||'N/A'} | Available full-time Mumbai 6mo: ${candidate.fulltime} | Can start: ${candidate.startdate} | Student: ${candidate.isstudent} | Tab violations: ${violations}\n\n`;
  let qn = 1;
  SECTIONS.forEach((sec,si) => {
    prompt += `=== SECTION ${si+1}: ${sec.title.toUpperCase()} ===\n\n`;
    sec.questions.forEach((q,qi) => {
      prompt += `Q${qn}: ${q}\nAnswer: ${answers[qn-1]||'[No answer provided]'}\n\n`;
      qn++;
    });
  });

  // Upload resume to backend (if configured)
  let resumeLink = '—';
  if(BACKEND_URL && candidate.resumeData){
    try {
      const b64 = candidate.resumeData.split(',')[1];
      const ext = candidate.resumeName.split('.').pop().toLowerCase();
      const mime = ext==='pdf'?'application/pdf':'application/msword';
      await fetch(BACKEND_URL, {
        method:'POST', mode:'no-cors',
        headers:{'Content-Type':'text/plain'},
        body: JSON.stringify({type:'resume', fileName:`${candidate.name.replace(/\s+/g,'_')}_resume.${ext}`, fileData:b64, mimeType:mime, candidateName:candidate.name, candidateEmail:candidate.email})
      });
      resumeLink = 'Uploaded (see Drive)';
    } catch(e){ console.warn('Resume upload failed', e); }
  }

  // Call Anthropic for evaluation
  try {
    const res = await fetch('https://api.anthropic.com/v1/messages', {
      method:'POST',
      headers:{'Content-Type':'application/json'},
      body: JSON.stringify({model:'claude-sonnet-4-20250514', max_tokens:8000, system:EVAL_SYSTEM, messages:[{role:'user',content:prompt}]})
    });
    const data = await res.json();
    const text = data.content?.[0]?.text || '';
    evalResult = parseEval(text);
  } catch(e){
    evalResult = {questions:[], total:0, error:e.message};
  }

  // Build response row
  const row = {
    timestamp: new Date().toLocaleString('en-IN'),
    name:candidate.name, email:candidate.email, phone:candidate.phone,
    location:candidate.location, linkedin:candidate.linkedin||'—',
    fulltime:candidate.fulltime, startdate:candidate.startdate, isstudent:candidate.isstudent,
    resumeLink, score:evalResult.total,
    pct:Math.round((evalResult.total/30)*100),
    violations, pass: evalResult.total>=15?'Pass':'Fail'
  };
  responses.push(row);

  // Save to Google Sheet (if configured)
  if(BACKEND_URL){
    try {
      await fetch(BACKEND_URL, {
        method:'POST', mode:'no-cors',
        headers:{'Content-Type':'text/plain'},
        body: JSON.stringify({type:'response', ...row, answers: answers})
      });
      toast('✓ Results sent to Google Sheet');
    } catch(e){ console.warn('Sheet save failed', e); }
  }

  // Clear session storage
  try { sessionStorage.removeItem('zass_answers'); } catch(e){}

  state = 'results'; viewTab = 'assessment';
  render();
  window.scrollTo(0,0);
}

// ─────────────────────────────────────────────
//  Parse evaluation
// ─────────────────────────────────────────────
function parseEval(text){
  const blocks = text.split(/\n(?=Q\d+:)/);
  const questions = [];
  for(const blk of blocks){
    const nm = blk.match(/^Q(\d+):/);
    if(!nm) continue;
    const sc = blk.match(/Score:\s*([\d.]+)/);
    const an = blk.match(/Answer:\s*([\s\S]*?)(?=\nReason:|\nScore:|$)/);
    const re = blk.match(/Reason:\s*([\s\S]*?)(?=\nQ\d+:|$)/);
    if(nm && sc) questions.push({num:parseInt(nm[1]), score:parseFloat(sc[1]), answer:an?an[1].trim():'', reason:re?re[1].trim():''});
  }
  const tm = text.match(/TOTAL:\s*([\d.]+)/);
  const total = tm ? parseFloat(tm[1]) : Math.round(questions.reduce((a,q)=>a+q.score,0)*10)/10;
  return {questions, total};
}

// ─────────────────────────────────────────────
//  Results
// ─────────────────────────────────────────────
function renderResults(){
  const {questions,total,error} = evalResult;
  const pct = Math.round((total/30)*100);
  const passed = total >= 15;

  const secCards = SECTIONS.map((sec,si)=>{
    const off = secOff(si);
    const qs = questions.filter(q=>q.num>off&&q.num<=off+sec.questions.length);
    const s = Math.round(qs.reduce((a,q)=>a+q.score,0)*10)/10;
    return `<div class="ssc"><div class="sn">${sec.short}</div><div class="sv">${s}<span style="font-size:12px;color:#94a3b8">/${sec.questions.length}</span></div></div>`;
  }).join('');

  const secDetails = SECTIONS.map((sec,si)=>{
    const off = secOff(si);
    const qs = questions.filter(q=>q.num>off&&q.num<=off+sec.questions.length);
    const st = Math.round(qs.reduce((a,q)=>a+q.score,0)*10)/10;
    const qHTML = qs.map(q=>{
      const cls = q.score===1?'full':q.score===0.5?'half':'zero';
      const scCls = q.score===1?'s-full':q.score===0.5?'s-half':'s-zero';
      const ans = (q.answer||'[No answer]').substring(0,240) + (q.answer?.length>240?'…':'');
      return `<div class="eq ${cls}"><div class="eq-hdr"><span class="eq-num">Q${q.num}</span><span class="eq-sc ${scCls}">${q.score}/1</span></div><div class="eq-ans">${ans.replace(/</g,'&lt;')}</div><div class="eq-reason">💬 ${q.reason||'—'}</div></div>`;
    }).join('');
    return `<div class="eval-section"><h3>Section ${si+1}: ${sec.title} — ${st}/${sec.questions.length}</h3>${qHTML}</div>`;
  }).join('');

  const candidateSummary = `<div class="card" style="margin-bottom:16px">
    <p style="font-size:11px;font-weight:700;color:#94a3b8;text-transform:uppercase;letter-spacing:.4px;margin-bottom:12px">Candidate Profile</p>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:10px;font-size:13px">
      ${[['Name',candidate.name],['Email',candidate.email],['Phone',candidate.phone],['Location',candidate.location],['LinkedIn',candidate.linkedin||'—'],['Full-time Mumbai',candidate.fulltime],['Start date',candidate.startdate],['Student',candidate.isstudent],['Tab violations',violations],['Time taken',fmt(5400-timeLeft)]].map(([k,v])=>`<div style="background:#f8fafc;padding:8px 10px;border-radius:8px"><div style="font-size:10px;color:#94a3b8;font-weight:700;text-transform:uppercase;margin-bottom:2px">${k}</div><div style="font-weight:700;color:#1e293b">${v}</div></div>`).join('')}
    </div>
    ${candidate.resumeData?`<div style="margin-top:12px"><a href="${candidate.resumeData}" download="${candidate.resumeName}" style="font-size:12px;color:#1e3a8a;font-weight:700;text-decoration:none;background:#eff6ff;padding:6px 14px;border-radius:6px">↓ Download Resume — ${candidate.resumeName}</a></div>`:''}
  </div>`;

  const errorNote = error ? `<div style="background:#fef2f2;border:1px solid #fecaca;border-radius:8px;padding:12px;margin-bottom:16px;font-size:13px;color:#dc2626"><strong>Note:</strong> AI evaluation failed (${error}). This usually means the Anthropic API key is not configured for this deployment. Scores show as 0. Please set up the Apps Script backend.</div>` : '';

  return `<div class="res-wrap">
    ${errorNote}
    <div class="score-hero">
      <div style="font-size:11px;opacity:.75;margin-bottom:8px">${candidate.name} · ${candidate.email}</div>
      <div><span class="sc-num">${total}</span><span class="sc-den">/30</span></div>
      <div class="sc-pct">${pct}% · <span class="${passed?'verdict-pass':'verdict-fail'}">${passed?'✓ PASS':'✗ NEEDS IMPROVEMENT'}</span></div>
      ${violations>0?`<div style="font-size:11px;margin-top:8px;opacity:.8">⚠️ ${violations} tab violation${violations>1?'s':''} recorded</div>`:''}
    </div>
    ${candidateSummary}
    <div class="sec-scores">${secCards}</div>
    <div class="card">${secDetails}</div>
  </div>`;
}

// ─────────────────────────────────────────────
//  Sheet view
// ─────────────────────────────────────────────
function renderSheet(){
  if(!responses.length) return `<div class="card" style="max-width:820px;margin:24px auto;text-align:center;padding:40px;color:#64748b">No responses collected yet in this session.</div>`;
  const rows = responses.map((r,i)=>`<tr>
    <td>${i+1}</td>
    <td title="${r.name}"><strong>${r.name}</strong></td>
    <td title="${r.email}">${r.email}</td>
    <td>${r.phone}</td>
    <td>${r.location}</td>
    <td>${r.fulltime}</td>
    <td>${r.startdate}</td>
    <td>${r.student||r.isstudent||'—'}</td>
    <td>${r.resumeLink!=='—'?`<a href="${r.resumeLink}" target="_blank" style="color:#1e3a8a;font-weight:700">View</a>`:r.resumeLink}</td>
    <td><strong>${r.score}/30</strong></td>
    <td>${r.pct}%</td>
    <td><span class="tag ${r.pass==='Pass'?'tag-pass':'tag-fail'}">${r.pass}</span></td>
    <td>${r.violations}</td>
    <td style="font-size:11px">${r.timestamp}</td>
  </tr>`).join('');
  return `<div class="sheet-wrap">
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;max-width:820px;margin-left:auto;margin-right:auto">
      <h2 style="font-size:15px;font-weight:800;color:#1e3a8a">All Responses — This Session</h2>
      <button class="btn btn-primary" style="font-size:11px;padding:6px 14px" onclick="exportCSV()">↓ Export CSV</button>
    </div>
    <table class="sheet-table">
      <thead><tr><th>#</th><th>Name</th><th>Email</th><th>Phone</th><th>Location</th><th>Full-time?</th><th>Start</th><th>Student</th><th>Resume</th><th>Score</th><th>%</th><th>Result</th><th>Violations</th><th>Submitted</th></tr></thead>
      <tbody>${rows}</tbody>
    </table>
    <p style="font-size:11px;color:#94a3b8;margin-top:10px;text-align:center">Responses are also saved to Google Sheets if BACKEND_URL is configured.</p>
  </div>`;
}

function exportCSV(){
  const h = ['#','Name','Email','Phone','Location','Full-time','Start','Student','Resume','Score','Percent','Result','Violations','Timestamp'];
  const rows = responses.map((r,i)=>[i+1,r.name,r.email,r.phone,r.location,r.fulltime,r.startdate,r.isstudent,r.resumeLink,`${r.score}/30`,`${r.pct}%`,r.pass,r.violations,r.timestamp]);
  const csv = [h,...rows].map(r=>r.map(v=>`"${String(v).replace(/"/g,'""')}"`).join(',')).join('\n');
  const blob = new Blob([csv],{type:'text/csv'});
  const a = document.createElement('a');
  a.href=URL.createObjectURL(blob); a.download='zoho_intern_responses.csv'; a.click();
  toast('CSV exported!');
}

// ─────────────────────────────────────────────
//  Boot
// ─────────────────────────────────────────────
render();
</script>
</body>
</html>
