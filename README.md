<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Jerome Andrew K — Black Hat Aesthetic (Portfolio)</title>
<style>
  :root{
    --bg:#020202;
    --neon:#00ff66;
    --accent:#00ffa8;
    --muted:#091012;
    --glass: rgba(255,255,255,0.03);
  }
  html,body{height:100%;margin:0;background:linear-gradient(180deg,#000 0%, #020202 60%);font-family: "Segoe UI", Roboto, "Fira Code", monospace;color:var(--neon);overflow:hidden;}
  /* Canvas covers background */
  #matrixCanvas{position:fixed;inset:0;z-index:0;}
  .container{position:relative;z-index:2;display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;gap:18px;padding:28px;}
  .card{
    width:930px;max-width:94%;background:linear-gradient(180deg, rgba(0,0,0,0.45), rgba(0,0,0,0.25));border:1px solid rgba(0,255,102,0.08);box-shadow:0 10px 40px rgba(0,0,0,0.6);backdrop-filter: blur(6px);border-radius:12px;padding:22px;display:flex;gap:20px;align-items:center;
  }
  .left{width:48%;min-width:260px;}
  .right{flex:1;display:flex;flex-direction:column;gap:10px;}
  h1{font-size:34px;margin:0;letter-spacing:1px;color:var(--neon);text-shadow:0 0 12px rgba(0,255,102,0.14), 0 0 28px rgba(0,255,102,0.06);}
  .glitch{
    position:relative;
    font-weight:700;
  }
  .glitch:before, .glitch:after{
    content:attr(data-text);
    position:absolute;left:0;top:0;right:0;
    clip-path: inset(0 0 0 0);
    opacity:0.8;
  }
  .glitch:before{transform:translate(-2px, -1px);color:#00ff99;mix-blend-mode:screen;filter:blur(0.6px);animation:glitchTop 2.1s infinite linear;}
  .glitch:after{transform:translate(2px,1px);color:#00e6b8;mix-blend-mode:screen;filter:blur(0.8px);animation:glitchBot 2.7s infinite linear;}
  @keyframes glitchTop{0%{clip-path:inset(0 0 80% 0)}10%{clip-path:inset(10% 0 55% 0)}20%{clip-path:inset(30% 0 40% 0)}30%{clip-path:inset(15% 0 60% 0)}40%{clip-path:inset(0 0 80% 0)}100%{clip-path:inset(0 0 80% 0)}}
  @keyframes glitchBot{0%{clip-path:inset(80% 0 0 0)}10%{clip-path:inset(55% 0 10% 0)}20%{clip-path:inset(40% 0 30% 0)}30%{clip-path:inset(60% 0 15% 0)}40%{clip-path:inset(80% 0 0 0)}100%{clip-path:inset(80% 0 0 0)}}

  .subtitle{color:#9affc9;margin-top:6px;font-size:13px;opacity:0.95;}
  .terminal{
    background:linear-gradient(180deg, rgba(0,0,0,0.35), rgba(0,0,0,0.15));
    border-radius:8px;padding:12px;border:1px solid rgba(0,255,102,0.06);font-family:'Fira Code', monospace;color:var(--neon);box-shadow:0 8px 30px rgba(0,255,102,0.03);
  }
  .cursor{display:inline-block;width:11px;height:18px;background:var(--neon);margin-left:6px;vertical-align:middle;animation:blink 1s steps(2) infinite;}
  @keyframes blink{0%{opacity:1}50%{opacity:0}100%{opacity:1}}

  .actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px;}
  .btn{background:linear-gradient(90deg, rgba(0,255,102,0.06), rgba(0,255,102,0.02));border:1px solid rgba(0,255,102,0.08);padding:8px 12px;border-radius:8px;color:var(--neon);text-decoration:none;font-size:13px;}
  .btn:hover{box-shadow:0 6px 22px rgba(0,255,102,0.05);transform:translateY(-2px);}

  .stats{display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-top:6px;}
  .stat{background:linear-gradient(180deg, rgba(0,0,0,0.2), rgba(0,0,0,0.05));padding:8px 10px;border-radius:8px;border:1px solid rgba(0,255,102,0.03);font-size:13px;}
  .skill-grid{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px;}

  /* small animated bars */
  .bar{width:110px;height:6px;border-radius:4px;background:rgba(0,255,102,0.08);overflow:hidden}
  .bar > i{display:block;height:100%;background:linear-gradient(90deg,#00ff99,#00e6b8);width:0%;animation:fill 2s forwards;}
  .bar[data-p="90"] > i{animation-delay:.15s;width:90%}
  .bar[data-p="80"] > i{animation-delay:.25s;width:80%}
  .bar[data-p="70"] > i{animation-delay:.35s;width:70%}
  @keyframes fill{from{width:0} to{width:100%}}

  /* footer */
  .footer{position:fixed;left:18px;bottom:18px;color:#00331a;font-size:12px;background:rgba(0,0,0,0.35);padding:8px 10px;border-radius:8px;border:1px solid rgba(0,255,102,0.04);backdrop-filter: blur(4px);z-index:3}
  .small{font-size:12px;color:#9affc9;opacity:0.9}

  /* responsive */
  @media (max-width:800px){
    .card{flex-direction:column;align-items:flex-start;padding:16px;}
    .left{width:100%}
  }
</style>
</head>
<body>
<canvas id="matrixCanvas"></canvas>
<div class="container">
  <div class="card" role="region" aria-label="Profile card">
    <div class="left">
      <h1 class="glitch" data-text="Jerome Andrew K">Jerome Andrew K</h1>
      <div class="subtitle">Black-hat aesthetic • Cyber-hacker vibe • Ethical craft</div>
      <div style="height:8px"></div>
      <div class="terminal" aria-live="polite">
        <div id="terminalLine">&gt; Initializing neural probe</div><span class="cursor" id="cursor"></span>
      </div>
      <div class="actions">
        <a class="btn" href="https://github.com/Jery0843" target="_blank" rel="noopener">GitHub</a>
        <a class="btn" href="https://jerome.co.in" target="_blank" rel="noopener">Portfolio</a>
        <a class="btn" href="mailto:jerome@example.com" target="_blank" rel="noopener">Contact</a>
      </div>
    </div>
    <div class="right" aria-hidden="false">
      <div class="stats">
        <div class="stat">CTFs: <strong>Top finishes</strong></div>
        <div class="stat">Experience: <strong>Red Team / Forensics</strong></div>
        <div class="stat">Focus: <strong>AD / Memory / AI</strong></div>
      </div>
      <div class="skill-grid">
        <div style="min-width:160px">
          <div class="small">Python</div>
          <div class="bar" data-p="90"><i></i></div>
        </div>
        <div style="min-width:160px">
          <div class="small">Active Directory</div>
          <div class="bar" data-p="80"><i></i></div>
        </div>
        <div style="min-width:160px">
          <div class="small">Memory Forensics</div>
          <div class="bar" data-p="70"><i></i></div>
        </div>
        <div style="min-width:160px">
          <div class="small">Exploit Dev</div>
          <div class="bar" data-p="75"><i></i></div>
        </div>
      </div>

      <div style="height:10px"></div>
      <div style="color:#8affc9;font-size:13px">Selected Projects</div>
      <div style="display:flex;flex-direction:column;gap:8px;margin-top:6px">
        <a class="btn" href="https://jerome.co.in/projects" target="_blank">HTB Walkthroughs</a>
        <a class="btn" href="https://0xjerry.jerome.co.in" target="_blank">0xJerry Lab</a>
      </div>
    </div>
  </div>
</div>

<div class="footer">⚠️ Aesthetic theme only — I do not support or promote illegal hacking.</div>

<script>
// MATRIX CANVAS
const canvas = document.getElementById('matrixCanvas');
const ctx = canvas.getContext('2d');
let W = canvas.width = innerWidth;
let H = canvas.height = innerHeight;
const cols = Math.floor(W / 16);
const drops = Array(cols).fill(0);

const letters = '01ABCDEF789234567890XYZ@#$%^&*()';

function resize(){W = canvas.width = innerWidth; H = canvas.height = innerHeight; cols = Math.floor(W / 16); drops.length = cols; for(let i=0;i<cols;i++) drops[i]=Math.random()*H;}
window.addEventListener('resize', ()=>{
  resize();
});

function draw(){
  ctx.fillStyle = 'rgba(0,0,0,0.15)';
  ctx.fillRect(0,0,W,H);
  ctx.font = '14px "Courier New", monospace';
  for(let i=0;i<drops.length;i++){
    const text = letters.charAt(Math.floor(Math.random() * letters.length));
    const x = i * 16;
    const y = drops[i] * 16;
    // neon glow
    ctx.shadowColor = '#00ff99';
    ctx.shadowBlur = 8;
    ctx.fillStyle = '#00ff66';
    ctx.fillText(text, x, y);
    ctx.fillStyle = '#bfffd8';
    ctx.fillText(text, x, y - 2);
    drops[i] += 0.8 + Math.random()*0.6;
    if(drops[i] * 16 > H) drops[i] = 0;
  }
}
setInterval(draw, 35);

// Terminal typing effect
const lines = [
  '> Initializing neural probe...',
  '> Scanning memory regions...',
  '> Correlating telemetry streams...',
  '> Unlocking insights: pattern found.'
];
let li = 0, pos = 0;
const term = document.getElementById('terminalLine');
function type(){
  if(pos < lines[li].length){
    term.textContent = lines[li].slice(0,pos+1);
    pos++;
    setTimeout(type, 28 + Math.random()*40);
  } else {
    setTimeout(()=>{ pos = 0; li = (li+1) % lines.length; setTimeout(type, 800); }, 1200);
  }
}
type();

// accessibility: stop canvas on user interaction to reduce motion
document.addEventListener('keydown', ()=>{ canvas.style.display='none'; });
document.addEventListener('touchstart', ()=>{ canvas.style.display='none'; });

</script>
</body>
</html>
