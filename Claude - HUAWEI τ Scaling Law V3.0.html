<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>华为韬（τ）定律 · 深度知识库 v2</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@300;400;600;700;900&family=JetBrains+Mono:wght@300;400;600&family=Noto+Sans+SC:wght@300;400;500;700&family=EB+Garamond:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
<style>
:root {
  --ink: #0c0c14;
  --paper: #f6f3ee;
  --accent: #c8000a;
  --accent2: #b06b00;
  --accent3: #1b4f8a;
  --accent4: #1a7a3e;
  --muted: #6a6560;
  --border: #d8d3cb;
  --surface: #eeeae0;
  --code-bg: #161620;
  --code-text: #e0d8c8;
  --highlight: rgba(200,0,10,0.06);
  --gold: #9a7200;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{font-family:'Noto Serif SC','Songti SC',serif;background:var(--paper);color:var(--ink);font-size:15.5px;line-height:1.95;overflow-x:hidden;}

/* ───── EDIT MODE ───── */
#edit-toolbar{position:fixed;top:0;left:0;right:0;z-index:9999;background:var(--ink);color:#fff;height:50px;display:flex;align-items:center;padding:0 24px;gap:14px;font-family:'Noto Sans SC',sans-serif;font-size:12.5px;transform:translateY(-100%);transition:transform .3s ease;box-shadow:0 2px 24px rgba(0,0,0,.45);}
#edit-toolbar.visible{transform:translateY(0);}
#edit-toolbar .el{display:flex;align-items:center;gap:8px;font-weight:700;color:#f0a040;letter-spacing:.04em;}
#edit-toolbar .sep{flex:1;}
#edit-toolbar button{background:none;border:1px solid rgba(255,255,255,.25);color:#fff;padding:5px 14px;border-radius:4px;cursor:pointer;font-family:'Noto Sans SC',sans-serif;font-size:11.5px;transition:all .2s;}
#edit-toolbar button:hover{background:rgba(255,255,255,.1);}
#edit-toolbar .bs{border-color:#4caf50;color:#4caf50;}
#edit-toolbar .be{border-color:#f0a040;color:#f0a040;}
#edit-toggle-btn{position:fixed;top:16px;right:20px;z-index:10000;background:var(--ink);color:#fff;border:none;padding:8px 18px;border-radius:24px;cursor:pointer;font-family:'Noto Sans SC',sans-serif;font-size:12px;font-weight:700;letter-spacing:.05em;display:flex;align-items:center;gap:7px;box-shadow:0 3px 18px rgba(0,0,0,.3);transition:all .25s;user-select:none;}
#edit-toggle-btn:hover{transform:translateY(-1px);box-shadow:0 5px 22px rgba(0,0,0,.35);}
#edit-toggle-btn.active{background:#b06b00;}
#edit-toggle-btn .dot{width:8px;height:8px;border-radius:50%;background:rgba(255,255,255,.35);transition:background .25s;}
#edit-toggle-btn.active .dot{background:#fff;}
body.edit-mode [contenteditable="true"]{border:2px dashed #f0a040;background:rgba(240,160,0,.07);border-radius:3px;padding:2px 5px;outline:none;cursor:text;transition:background .2s;display:inline-block;min-width:10px;}
body.edit-mode [contenteditable="true"]:hover{background:rgba(240,160,0,.13);}
body.edit-mode [contenteditable="true"]:focus{background:rgba(240,160,0,.1);border-color:#c08000;box-shadow:0 0 0 3px rgba(240,160,0,.18);}
body.edit-mode [contenteditable="true"].bk{display:block;}
#toast{position:fixed;bottom:28px;left:50%;transform:translateX(-50%) translateY(80px);background:#1a1a26;color:#fff;padding:10px 26px;border-radius:8px;font-family:'Noto Sans SC',sans-serif;font-size:13px;z-index:99999;transition:transform .35s cubic-bezier(.34,1.56,.64,1);pointer-events:none;}
#toast.show{transform:translateX(-50%) translateY(0);}

/* ───── HERO ───── */
.hero{position:relative;min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:120px 40px 80px;overflow:hidden;background:var(--ink);}
.hero::before{content:'';position:absolute;inset:0;background:radial-gradient(ellipse 70% 55% at 50% 38%,rgba(200,0,10,.16) 0%,transparent 70%),radial-gradient(ellipse 35% 35% at 15% 85%,rgba(27,79,138,.13) 0%,transparent 60%),radial-gradient(ellipse 25% 25% at 85% 20%,rgba(176,107,0,.1) 0%,transparent 55%);}
.hero-tau-bg{position:absolute;font-size:clamp(200px,32vw,520px);font-family:'EB Garamond',serif;font-style:italic;font-weight:400;color:rgba(255,255,255,.022);line-height:1;top:50%;left:50%;transform:translate(-50%,-50%);pointer-events:none;user-select:none;}
.hero-badge{display:inline-flex;align-items:center;gap:8px;background:rgba(200,0,10,.18);border:1px solid rgba(200,0,10,.38);color:#ff7070;padding:5px 18px;border-radius:20px;font-size:11px;font-family:'Noto Sans SC',sans-serif;font-weight:600;letter-spacing:.12em;text-transform:uppercase;margin-bottom:28px;position:relative;}
.hero h1{font-size:clamp(34px,5.5vw,72px);font-weight:900;color:#fff;line-height:1.1;margin-bottom:14px;letter-spacing:-.02em;}
.hero h1 .t{color:var(--accent);font-style:italic;}
.hero .sub{font-size:clamp(13px,1.8vw,18px);color:rgba(255,255,255,.5);font-family:'Noto Sans SC',sans-serif;font-weight:300;max-width:620px;margin:0 auto 48px;line-height:1.65;}
.hero-meta{display:flex;gap:48px;justify-content:center;flex-wrap:wrap;position:relative;}
.hero-stat .num{font-size:clamp(26px,3.8vw,42px);font-weight:700;font-family:'JetBrains Mono',monospace;color:#fff;line-height:1;}
.hero-stat .num span{color:var(--accent);}
.hero-stat .lb{font-size:10.5px;color:rgba(255,255,255,.38);font-family:'Noto Sans SC',sans-serif;letter-spacing:.1em;text-transform:uppercase;margin-top:5px;}
.scroll-hint{position:absolute;bottom:30px;left:50%;transform:translateX(-50%);color:rgba(255,255,255,.28);font-size:11px;font-family:'Noto Sans SC',sans-serif;letter-spacing:.15em;display:flex;flex-direction:column;align-items:center;gap:6px;animation:bounce 2s ease-in-out infinite;}
.scroll-hint::after{content:'↓';font-size:17px;}
@keyframes bounce{0%,100%{transform:translateX(-50%) translateY(0);}50%{transform:translateX(-50%) translateY(7px);}}

/* ───── NAV ───── */
.toc-nav{position:sticky;top:0;z-index:800;background:rgba(246,243,238,.96);backdrop-filter:blur(12px);border-bottom:1px solid var(--border);}
.toc-list{display:flex;gap:0;list-style:none;overflow-x:auto;white-space:nowrap;padding:0 32px;}
.toc-list::-webkit-scrollbar{display:none;}
.toc-list a{display:block;padding:13px 16px;font-family:'Noto Sans SC',sans-serif;font-size:11.5px;font-weight:500;letter-spacing:.05em;color:var(--muted);text-decoration:none;border-bottom:2px solid transparent;transition:all .2s;}
.toc-list a:hover,.toc-list a.active{color:var(--accent);border-bottom-color:var(--accent);}

/* ───── LAYOUT ───── */
.pw{max-width:1120px;margin:0 auto;padding:0 40px;}
.section{padding:80px 0;border-bottom:1px solid var(--border);}
.section:last-child{border-bottom:none;}
.sh{display:flex;align-items:baseline;gap:16px;margin-bottom:44px;}
.sn{font-family:'JetBrains Mono',monospace;font-size:10.5px;font-weight:600;color:var(--accent);letter-spacing:.1em;text-transform:uppercase;min-width:36px;}
.st{font-size:clamp(22px,3.2vw,36px);font-weight:700;line-height:1.2;letter-spacing:-.01em;}
.st em{color:var(--accent);font-style:normal;}

/* ───── PROSE ───── */
.prose p{font-size:14.8px;line-height:2.05;margin-bottom:18px;color:#252018;}
.prose p:last-child{margin-bottom:0;}
.prose strong{color:var(--ink);}
.prose em{color:var(--accent);font-style:normal;font-weight:600;}

/* ───── CARDS ───── */
.cg{display:grid;grid-template-columns:repeat(auto-fit,minmax(255px,1fr));gap:18px;margin:28px 0;}
.card{background:var(--surface);border:1px solid var(--border);border-radius:8px;padding:26px;position:relative;overflow:hidden;}
.card::before{content:'';position:absolute;top:0;left:0;width:3px;height:100%;background:var(--cc,var(--accent));}
.card-ic{font-size:26px;margin-bottom:10px;display:block;}
.card h3{font-size:14.5px;font-weight:700;margin-bottom:7px;font-family:'Noto Sans SC',sans-serif;}
.card p{font-size:13px;color:var(--muted);line-height:1.85;font-family:'Noto Sans SC',sans-serif;}
.card .tag{display:inline-block;background:rgba(0,0,0,.05);border:1px solid var(--border);font-size:10px;padding:1px 7px;border-radius:2px;font-family:'JetBrains Mono',monospace;margin:4px 3px 0 0;color:var(--muted);}

/* ───── FORMULA ───── */
.fb{background:var(--code-bg);color:var(--code-text);border-radius:8px;padding:30px 36px;margin:28px 0;font-family:'JetBrains Mono',monospace;position:relative;overflow:hidden;}
.fb::before{content:'FORMULA';position:absolute;top:12px;right:16px;font-size:9.5px;letter-spacing:.15em;color:rgba(255,255,255,.18);}
.fm{font-size:clamp(16px,2.5vw,24px);color:#fff;text-align:center;line-height:2.2;margin-bottom:16px;}
.fv{color:#ffb06c;}.fo{color:#7ecece;}.fi{color:#a0c8a0;}
.fd{font-size:11.5px;color:rgba(255,255,255,.48);text-align:center;line-height:1.9;}
.fd span{color:rgba(255,255,255,.75);}

/* ───── COMPARE TABLE ───── */
.ct{width:100%;border-collapse:collapse;margin:28px 0;font-family:'Noto Sans SC',sans-serif;font-size:13.5px;}
.ct th{background:var(--ink);color:#fff;padding:13px 18px;text-align:left;font-weight:600;letter-spacing:.04em;font-size:11.5px;}
.ct th:last-child{color:#f0a040;}
.ct td{padding:13px 18px;border-bottom:1px solid var(--border);vertical-align:top;line-height:1.75;}
.ct tr:last-child td{border-bottom:none;}
.ct tr:nth-child(even) td{background:var(--surface);}
.ct td:first-child{font-weight:600;color:var(--muted);white-space:nowrap;}
.ct .ny{color:var(--accent);font-weight:500;}
.ct .od{color:var(--muted);}
.ct .na{color:var(--accent4);font-weight:500;}

/* ───── METRICS ───── */
.mr{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:14px;margin:28px 0;}
.mb{background:var(--ink);color:#fff;border-radius:8px;padding:22px 18px;text-align:center;}
.mb .v{font-size:clamp(22px,3.5vw,36px);font-weight:700;font-family:'JetBrains Mono',monospace;line-height:1;color:var(--accent);}
.mb .v .u{font-size:.52em;color:rgba(255,255,255,.45);font-weight:400;}
.mb .l{font-size:10.5px;color:rgba(255,255,255,.38);font-family:'Noto Sans SC',sans-serif;letter-spacing:.07em;margin-top:7px;line-height:1.5;}

/* ───── QUOTE ───── */
.qb{border-left:4px solid var(--accent);background:var(--highlight);padding:22px 30px;margin:28px 0;border-radius:0 6px 6px 0;}
.qb blockquote{font-size:15px;line-height:1.95;font-style:italic;color:var(--ink);margin-bottom:10px;font-family:'EB Garamond',serif;}
.qb cite{font-size:11.5px;color:var(--muted);font-style:normal;font-family:'Noto Sans SC',sans-serif;display:flex;align-items:center;gap:8px;}
.qb cite::before{content:'—';}

/* ───── PEER EVALUATION ───── */
.peer-grid{display:grid;gap:16px;margin:28px 0;}
.peer-item{background:var(--surface);border:1px solid var(--border);border-radius:8px;padding:22px 26px;position:relative;}
.peer-item::before{content:'';position:absolute;top:0;left:0;width:4px;height:100%;background:var(--pc,var(--accent3));border-radius:4px 0 0 4px;}
.peer-header{display:flex;align-items:center;gap:14px;margin-bottom:12px;}
.peer-logo{width:44px;height:44px;border-radius:8px;background:var(--pl,#1a5fa8);display:flex;align-items:center;justify-content:center;font-weight:900;font-family:'JetBrains Mono',monospace;font-size:12px;color:#fff;flex-shrink:0;}
.peer-title h4{font-size:15px;font-weight:700;font-family:'Noto Sans SC',sans-serif;}
.peer-title p{font-size:11px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;}
.peer-item blockquote{font-size:14px;line-height:1.9;color:var(--ink);font-style:italic;font-family:'EB Garamond',serif;margin-bottom:10px;}
.peer-item .analysis{font-size:12.5px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;line-height:1.85;}

/* ───── SUPPLY CHAIN ───── */
.sc-flow{display:grid;gap:0;margin:28px 0;border:1px solid var(--border);border-radius:8px;overflow:hidden;}
.sc-tier{padding:22px 24px;border-bottom:1px solid var(--border);display:grid;grid-template-columns:140px 1fr;gap:20px;align-items:start;}
.sc-tier:last-child{border-bottom:none;}
.sc-tier-name{font-family:'Noto Sans SC',sans-serif;font-size:13px;font-weight:700;color:var(--accent);padding-top:2px;}
.sc-content h4{font-size:14px;font-weight:700;font-family:'Noto Sans SC',sans-serif;margin-bottom:6px;}
.sc-content p{font-size:12.5px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;line-height:1.85;}
.sc-content .cos{display:flex;flex-wrap:wrap;gap:6px;margin-top:8px;}
.co-tag{display:inline-flex;align-items:center;gap:4px;background:#fff;border:1px solid var(--border);border-radius:4px;padding:3px 10px;font-size:11px;font-family:'Noto Sans SC',sans-serif;color:var(--ink);}
.co-tag .dot{width:6px;height:6px;border-radius:50%;background:var(--cd,var(--accent));}

/* ───── PACKAGING PRINCIPLE ───── */
.pkg-compare{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin:28px 0;}
.pkg-box{border:1px solid var(--border);border-radius:8px;padding:22px;position:relative;}
.pkg-box h4{font-size:14px;font-weight:700;font-family:'Noto Sans SC',sans-serif;margin-bottom:12px;padding-bottom:10px;border-bottom:1px solid var(--border);}
.pkg-box ul{list-style:none;font-family:'Noto Sans SC',sans-serif;font-size:12.5px;color:var(--muted);line-height:2.1;}
.pkg-box ul li::before{content:'→  ';color:var(--accent);}
.pkg-box.highlight{background:var(--ink);border-color:var(--accent);}
.pkg-box.highlight h4{color:#fff;border-color:rgba(255,255,255,.15);}
.pkg-box.highlight ul{color:rgba(255,255,255,.6);}
.pkg-box .badge{display:inline-block;background:var(--accent);color:#fff;font-size:10px;padding:2px 8px;border-radius:3px;font-family:'JetBrains Mono',monospace;margin-bottom:8px;letter-spacing:.06em;}
@media(max-width:640px){.pkg-compare{grid-template-columns:1fr;}}

/* ───── THERMAL ───── */
.thermal-box{background:#fff5e8;border:1px solid #f0d0a0;border-radius:8px;padding:24px 28px;margin:22px 0;}
.thermal-box h4{font-size:14px;font-weight:700;font-family:'Noto Sans SC',sans-serif;color:#8a4400;margin-bottom:10px;}
.thermal-box p{font-size:13px;font-family:'Noto Sans SC',sans-serif;color:#6a3800;line-height:1.9;}

/* ───── TIMELINE ───── */
.tl{position:relative;margin:36px 0;padding-left:40px;}
.tl::before{content:'';position:absolute;left:9px;top:0;bottom:0;width:2px;background:linear-gradient(to bottom,var(--accent),var(--accent3));}
.tl-item{position:relative;margin-bottom:32px;}
.tl-item::before{content:'';position:absolute;left:-34px;top:8px;width:12px;height:12px;border-radius:50%;background:var(--accent);border:3px solid var(--paper);box-shadow:0 0 0 2px var(--accent);}
.tl-year{font-family:'JetBrains Mono',monospace;font-size:11.5px;font-weight:600;color:var(--accent);letter-spacing:.07em;margin-bottom:3px;}
.tl-title{font-size:15.5px;font-weight:700;margin-bottom:5px;font-family:'Noto Sans SC',sans-serif;}
.tl-desc{font-size:13px;color:var(--muted);line-height:1.85;font-family:'Noto Sans SC',sans-serif;}

/* ───── ROADMAP ───── */
.rm{display:grid;grid-template-columns:repeat(auto-fit,minmax(185px,1fr));gap:0;border:1px solid var(--border);border-radius:8px;overflow:hidden;margin:28px 0;}
.rm-ph{padding:22px 18px;border-right:1px solid var(--border);}
.rm-ph:last-child{border-right:none;}
.rm-ph .py{font-family:'JetBrains Mono',monospace;font-size:10.5px;font-weight:600;color:var(--accent);letter-spacing:.09em;margin-bottom:7px;}
.rm-ph h4{font-size:13.5px;font-weight:700;font-family:'Noto Sans SC',sans-serif;margin-bottom:9px;}
.rm-ph ul{list-style:none;font-size:11.5px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;line-height:2.1;}
.rm-ph ul li::before{content:'·  ';color:var(--accent);}
.rm-ph.hl{background:var(--ink);color:#fff;}
.rm-ph.hl .py{color:#f0a040;}
.rm-ph.hl h4{color:#fff;}
.rm-ph.hl ul{color:rgba(255,255,255,.55);}

/* ───── RISK ───── */
.rg{display:grid;gap:14px;margin:28px 0;}
.ri{display:grid;grid-template-columns:26px 1fr 1fr;gap:15px;padding:18px 20px;background:var(--surface);border-radius:6px;border:1px solid var(--border);align-items:start;font-family:'Noto Sans SC',sans-serif;}
.rl{width:22px;height:22px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:9.5px;font-weight:700;color:#fff;margin-top:3px;flex-shrink:0;}
.rl.H{background:#c8000a;}.rl.M{background:#b06b00;}.rl.L{background:#1b4f8a;}
.ri h4{font-size:13.5px;font-weight:700;margin-bottom:3px;}
.ri p{font-size:12px;color:var(--muted);line-height:1.8;}
.ri .mt h5{font-size:10.5px;font-weight:700;color:#2a7a2a;letter-spacing:.07em;text-transform:uppercase;margin-bottom:3px;}
@media(max-width:640px){.ri{grid-template-columns:22px 1fr;}.ri .mt{grid-column:2;}}

/* ───── MEDIA EVAL ───── */
.media-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px;margin:28px 0;}
.media-card{background:var(--surface);border:1px solid var(--border);border-radius:8px;padding:22px;}
.media-card .source{font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:600;color:var(--accent);letter-spacing:.1em;text-transform:uppercase;margin-bottom:6px;}
.media-card .stance{display:inline-block;font-size:10px;padding:2px 8px;border-radius:3px;font-family:'Noto Sans SC',sans-serif;font-weight:700;margin-bottom:10px;}
.stance-neutral{background:#e8e8f0;color:#5050a0;}
.stance-positive{background:#e0f0e4;color:#1a6a2a;}
.stance-skeptical{background:#f8e8e0;color:#8a3000;}
.media-card p{font-size:12.5px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;line-height:1.85;}

/* ───── FINANCE ───── */
.ft{width:100%;border-collapse:collapse;font-family:'JetBrains Mono',monospace;font-size:12.5px;margin:20px 0;}
.ft th{background:var(--ink);color:#fff;padding:11px 15px;text-align:right;font-size:11px;letter-spacing:.05em;font-family:'Noto Sans SC',sans-serif;}
.ft th:first-child{text-align:left;}
.ft td{padding:10px 15px;text-align:right;border-bottom:1px solid var(--border);}
.ft td:first-child{text-align:left;font-family:'Noto Sans SC',sans-serif;font-size:13px;font-weight:500;}
.ft tr.sub td{font-weight:700;background:var(--surface);border-top:2px solid var(--border);}
.ft tr.tot td{font-weight:900;background:var(--ink);color:#fff;border-top:3px solid var(--accent);}
.ft .pos{color:#1a7a2a;}.ft .neg{color:var(--accent);}.ft .ac{color:var(--accent);}

/* ───── APPENDIX ───── */
.gloss{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:0;border:1px solid var(--border);border-radius:8px;overflow:hidden;margin:20px 0;}
.gl-item{padding:16px 20px;border-bottom:1px solid var(--border);border-right:1px solid var(--border);}
.gl-item:nth-child(even){border-right:none;}
.gl-term{font-family:'JetBrains Mono',monospace;font-size:12px;font-weight:600;color:var(--accent);margin-bottom:4px;}
.gl-def{font-size:12px;color:var(--muted);font-family:'Noto Sans SC',sans-serif;line-height:1.8;}

/* ───── ANALOGY ───── */
.an-box{border:1px solid var(--border);border-radius:8px;padding:26px 30px;margin:26px 0;position:relative;background:linear-gradient(135deg,var(--surface) 0%,var(--paper) 100%);}
.an-box::before{content:'类比';position:absolute;top:-10px;left:20px;background:var(--accent);color:#fff;font-size:10px;font-family:'Noto Sans SC',sans-serif;font-weight:700;padding:2px 10px;border-radius:3px;letter-spacing:.07em;}
.an-box p{font-size:13.5px;line-height:2;color:var(--muted);font-family:'Noto Sans SC',sans-serif;}
.an-box p strong{color:var(--ink);}

/* ───── REF ───── */
.ref-list{list-style:none;margin:16px 0;font-family:'Noto Sans SC',sans-serif;font-size:12.5px;color:var(--muted);counter-reset:ref;}
.ref-list li{counter-increment:ref;padding:8px 0 8px 32px;position:relative;border-bottom:1px solid var(--border);line-height:1.75;}
.ref-list li:last-child{border-bottom:none;}
.ref-list li::before{content:counter(ref)'.';position:absolute;left:0;font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--accent);font-weight:700;}
.ref-list a{color:var(--accent3);text-decoration:none;}
.ref-list a:hover{text-decoration:underline;}

/* ───── FOOTER ───── */
.footer{background:var(--ink);color:rgba(255,255,255,.38);text-align:center;padding:48px 40px;font-size:11.5px;font-family:'Noto Sans SC',sans-serif;line-height:2;}
.footer a{color:rgba(200,0,10,.7);text-decoration:none;}

/* ───── RESPONSIVE ───── */
@media(max-width:768px){.pw{padding:0 18px;}.hero{padding:80px 18px 60px;}.toc-list{padding:0 14px;}.sc-tier{grid-template-columns:1fr;}.sc-tier-name{border-bottom:1px solid var(--border);padding-bottom:6px;}.pkg-compare{grid-template-columns:1fr;}}
@media print{#edit-toolbar,#edit-toggle-btn,.toc-nav{display:none!important;}.hero{min-height:auto;}}
</style>
</head>
<body>

<div id="edit-toolbar">
  <span class="el">✏️ 编辑模式 · 点击任意文字直接修改</span>
  <div class="sep"></div>
  <button class="bs" onclick="saveContent()">💾 保存</button>
  <button class="be" onclick="exportHTML()">⬇ 导出 HTML</button>
  <button onclick="toggleEditMode()">✕ 退出</button>
</div>
<button id="edit-toggle-btn" onclick="toggleEditMode()"><span class="dot"></span>编辑模式</button>
<div id="toast"></div>

<!-- HERO -->
<section class="hero">
  <div class="hero-tau-bg">τ</div>
  <div class="hero-badge">IEEE ISCAS 2026 · 上海 · 2026年5月25日</div>
  <h1>华为<span class="t">韬（τ）</span>定律<br>深度知识库</h1>
  <p class="sub">从摩尔定律到时间缩微 — 论文精读、封装原理、产业链影响、同业评价、媒体与金融机构分析的全维度解读</p>
  <div class="hero-meta">
    <div class="hero-stat"><div class="num">381<span>款</span></div><div class="lb">已量产芯片</div></div>
    <div class="hero-stat"><div class="num">53.5<span>%</span></div><div class="lb">晶体管密度单代提升</div></div>
    <div class="hero-stat"><div class="num">1.5<span>μm</span></div><div class="lb">混合键合间距（麒麟2026）</div></div>
    <div class="hero-stat"><div class="num">1.4<span>nm</span></div><div class="lb">2031年等效目标</div></div>
  </div>
  <div class="scroll-hint">向下探索</div>
</section>

<!-- NAV -->
<nav class="toc-nav">
  <ul class="toc-list">
    <li><a href="#s1">01 理论框架</a></li>
    <li><a href="#s2">02 论文精读</a></li>
    <li><a href="#s3">03 封装原理</a></li>
    <li><a href="#s4">04 热管理</a></li>
    <li><a href="#s5">05 产业链影响</a></li>
    <li><a href="#s6">06 同业评价</a></li>
    <li><a href="#s7">07 媒体评价</a></li>
    <li><a href="#s8">08 金融分析</a></li>
    <li><a href="#s9">09 风险分析</a></li>
    <li><a href="#s10">10 路线图</a></li>
    <li><a href="#s11">11 财务模型</a></li>
    <li><a href="#s12">专业术语</a></li>
    <li><a href="#s13">参考文献</a></li>
  </ul>
</nav>

<div class="pw">

<!-- S1: THEORY -->
<section class="section" id="s1">
  <div class="sh"><span class="sn">01</span><h2 class="st">韬（τ）定律：<em>理论框架</em>与历史背景</h2></div>
  <div class="prose">
    <p>1965年，Gordon Moore提出晶体管密度大约每18至24个月翻倍的规律，成为此后60年半导体产业的核心指导原则。1974年，Robert Dennard进一步建立按比例缩小理论（Dennard Scaling），证明在保持电场强度不变的前提下，晶体管尺寸与电压可以同比例缩小，从而使得性能每代提升而功耗不增。这两项定律的叠加，驱动了半导体行业的指数级发展。</p>
    <p>然而，摩尔定律的工程基础在两个阶段相继崩解：2005年前后，Dennard Scaling失效，电压无法继续缩减而单位面积功耗开始上升，迫使行业从单核高频转向多核并行；2015年之后，几何缩微的边际收益持续递减，领先制程的晶圆厂建设成本突破千亿美元量级，单个晶体管成本在部分先进节点上不再继续下降，摩尔定律的"经济性"维度实质上开始失效。</p>
    <p>在此背景下，2026年5月25日，华为公司董事、半导体业务部总裁何庭波在IEEE ISCAS 2026国际电路与系统研讨会上正式提出<strong>韬（τ）定律（Tau Scaling Law）</strong>——以"时间缩微"（Time Scaling）替代"几何缩微"（Geometric Scaling），作为半导体与电子系统演进的新指导原则。</p>
  </div>

  <div class="fb">
    <div class="fm">
      <span class="fv">τ</span><span class="fo"> = </span><span class="fv">R</span><span class="fo"> × </span><span class="fv">C</span>
      &nbsp;&nbsp;&nbsp;&nbsp;
      <span class="fi">τ<sub>n+1</sub></span><span class="fo"> = </span><span class="fi">τ<sub>n</sub></span><span class="fo"> / </span><span class="fi">α</span>
    </div>
    <div class="fd">
      <span>τ</span>：时间常数，衡量电路中信号从一个逻辑状态切换到另一状态所需时间（RC延迟）<br>
      <span>R</span>：等效电阻 &nbsp;|&nbsp; <span>C</span>：等效寄生电容 &nbsp;|&nbsp; <span>α</span>：应用场景相关的代际缩放因子<br>
      论文披露：移动终端 α ≈ 1.3×/年 &nbsp;|&nbsp; 自动驾驶 α ≈ 1.5×/年 &nbsp;|&nbsp; AI工作负载 α 可达 10×/年<br>
      <span>系统总 τ = f(τ_晶体管, τ_电路, τ_芯片, τ_系统)</span> — 从皮秒到秒级的跨层统一优化目标
    </div>
  </div>

  <div class="prose">
    <p>韬定律的核心主张是：τ = RC 不仅是电路理论中的基础方程，更应成为整个半导体产业链的优化北极星。信号传播越慢（τ越大），芯片能效越低、延迟越高。传统摩尔定律通过缩小晶体管物理尺寸来间接降低τ；而韬定律则将直接优化τ作为目标，允许通过多种技术手段实现这一目标，包括但不限于改变光刻工艺节点。</p>
  </div>

  <table class="ct">
    <thead><tr><th>维度</th><th>摩尔定律（几何缩微路线）</th><th>韬定律（时间缩微路线）</th></tr></thead>
    <tbody>
      <tr><td>核心优化指标</td><td class="od">晶体管几何尺寸（nm/Å）</td><td class="ny">时间常数 τ（ps，各层级）</td></tr>
      <tr><td>性能提升路径</td><td class="od">缩小晶体管平面面积</td><td class="ny">LogicFolding垂直折叠、缩短信号路径</td></tr>
      <tr><td>关键制造依赖</td><td class="od">EUV光刻机（ASML主导）</td><td class="ny">混合键合设备、先进封装工艺</td></tr>
      <tr><td>代际进步节奏</td><td class="od">2年一代→3年一代（放缓）</td><td class="ny">α因子驱动，不同应用域节奏独立</td></tr>
      <tr><td>理论覆盖层级</td><td class="od">主要在器件/电路层</td><td class="ny">器件→电路→芯片→系统，全栈统一</td></tr>
      <tr><td>经济性趋势</td><td class="od">成本边际递减，研发支出超10亿美元/代</td><td class="ny">在已有节点上持续迭代，成本扩散更平缓</td></tr>
      <tr><td>代表性先验实践</td><td class="od">Intel 4/3A、TSMC N2/N14A、Samsung SF2</td><td class="ny">AMD 3D V-Cache、Intel Foveros、TSMC SoIC（均为局部实践）；韬定律将其系统化</td></tr>
    </tbody>
  </table>
</section>

<!-- S2: PAPER READING -->
<section class="section" id="s2">
  <div class="sh"><span class="sn">02</span><h2 class="st">论文精读：<em>《面向多层级电子系统的时间缩微理论》</em></h2></div>

  <div class="prose">
    <p>何庭波于2026年5月25日在中国科学院科技论文预发布平台（ChinaXiv，网址：chinaxiv.org/abs/202605.00224）发表署名论文《A Time Scaling Theory for Multi-Layer Electronic Systems》，全文将在《SCIENCE CHINA Information Sciences》正式发表。论文基于华为2020年5月至2026年5月六年间381款量产芯片的工程实践，从两个维度——科学方法论与产业路线图——系统阐述τ缩放技术体系。</p>
  </div>

  <div class="qb"><blockquote>论文开篇指出：从几何时代（目标：使晶体管更小）到时间时代（目标：使信号更快），存在一个清晰的历史分期。每层独立优化、时间成为"剩余项"的时代也已经结束。现在是时候将时间本身作为第一优化变量。</blockquote><cite>何庭波，ChinaXiv论文，2026年5月25日</cite></div>

  <div class="cg">
    <div class="card" style="--cc:#c8000a">
      <span class="card-ic">📐</span>
      <h3>分层 τ 定义</h3>
      <p>论文将τ定义为跨越四个层级的时间常数：<br>
      τ_晶体管（ps级）：器件开关延迟，由RC决定<br>
      τ_电路（ns级）：逻辑门关键路径传播延迟<br>
      τ_芯片（μs级）：片上存储访问与互连延迟<br>
      τ_系统（ms-s级）：数据中心工作负载响应时间<br>
      总系统τ = f(τ_T, τ_C, τ_chip, τ_sys)，各层均可独立优化。</p>
    </div>
    <div class="card" style="--cc:#1b4f8a">
      <span class="card-ic">📊</span>
      <h3>代际缩放关系</h3>
      <p>τ_(n+1) = τ_n / α，其中α为非固定通用参数，随应用场景而变：<br>
      移动终端：α ≈ 1.3×/年（功耗约束主导）<br>
      自动驾驶：α ≈ 1.5×/年（安全性驱动）<br>
      AI算力：α 可达 10×/年（算力直接转化为经济价值）<br>
      此设计允许不同产业垂直领域以独立节奏演进，而非强制统一时钟。</p>
    </div>
    <div class="card" style="--cc:#b06b00">
      <span class="card-ic">🔬</span>
      <h3>麒麟2026量化验证</h3>
      <p>论文披露具体工程数据：<br>
      晶体管密度：155 → 238 MTr/mm²（+53.5%，同代单步完成）<br>
      P核能效：+41%&nbsp;|&nbsp; 最大频率：+13%（3.1 GHz）<br>
      SRAM工作频率：+40%以上<br>
      NoC数据路径面积：-55%<br>
      时钟缓冲器数量：-50%+&nbsp;|&nbsp; 时钟偏斜：-25%<br>
      代表性核心布线长度：-30%</p>
    </div>
    <div class="card" style="--cc:#1a7a3e">
      <span class="card-ic">🤖</span>
      <h3>AI系统路径</h3>
      <p>论文指出：大规模AI集群中，>80%能量消耗于数据移动，>70%系统成本分配给数据存储。由此提出AI系统级τ路径：<br>
      UnifiedBus：统一内存语义互连<br>
      Hi-ONE：近封装光学I/O<br>
      3D Folding：芯片层面折叠<br>
      目标：到2035年，AI硬件集成度较2025年提升100倍以上</p>
    </div>
  </div>

  <div class="prose">
    <p>论文还特别指出麒麟2026的LogicFolding实施为"保守方案"（conservative implementation）：仅在关键路径上选择性应用，TSV着陆仅前进了顶层金属层以下一步，折叠层数尚有限。论文明确声明这是一个阶段性起点，而非终态。即便如此，CPU性能核心频率已重返3.1 GHz，是近年麒麟系列中的代际跳升。</p>
  </div>

  <div class="mr">
    <div class="mb"><div class="v">1.5<span class="u">μm</span></div><div class="l">混合键合间距<br>（麒麟2026实现值）</div></div>
    <div class="mb"><div class="v"><0.5<span class="u">μm</span></div><div class="l">套刻精度要求<br>（对准精度）</div></div>
    <div class="mb"><div class="v"><1.5<span class="u">μm</span></div><div class="l">TSV关键尺寸<br>目标值</div></div>
    <div class="mb"><div class="v"><6<span class="u">μm</span></div><div class="l">TSV间距目标<br>（含KOZ）</div></div>
    <div class="mb"><div class="v">≈2</div><div class="l">齿轮比（Gear Ratio）<br>键合间距/顶层金属间距</div></div>
    <div class="mb"><div class="v">~100<span class="u">%</span></div><div class="l">智能冗余方案<br>目标良率</div></div>
  </div>
</section>

<!-- S3: PACKAGING PRINCIPLE -->
<section class="section" id="s3">
  <div class="sh"><span class="sn">03</span><h2 class="st">封装原理：<em>LogicFolding</em>与先进封装技术体系</h2></div>

  <div class="prose">
    <p>要理解LogicFolding，必须首先明确它与现有3D先进封装技术的本质区别。现有技术（如TSMC的CoWoS/SoIC、Intel的Foveros、AMD的3D V-Cache）主要采用的是<strong>Die-to-Die堆叠</strong>（芯片到芯片堆叠）：在设计阶段，各Die（芯片单元）作为独立完整的功能模块分别设计制造，然后在封装阶段将其垂直集成。LogicFolding则不同，它属于<strong>Cell-to-Cell折叠</strong>（单元级折叠）：在设计阶段即将一颗芯片的内部电路——精确到逻辑门和触发器（Flip-Flop）层级——分配到垂直堆叠的多个有源层上，由混合键合连接，两层在电路设计上被视作一个连续的布局平面。</p>
  </div>

  <div class="pkg-compare">
    <div class="pkg-box">
      <div class="badge">传统 DIE-TO-DIE 堆叠</div>
      <h4>代表：TSMC SoIC / Intel Foveros / AMD 3D V-Cache</h4>
      <ul>
        <li>各Die独立完整设计，封装时集成</li>
        <li>主要用于：Logic+HBM、CPU+Cache等异质功能集成</li>
        <li>设计与制造流程相对成熟</li>
        <li>Die间界面为封装级互连（有协议开销）</li>
        <li>无法消除Die内部的关键路径延迟</li>
        <li>已有TSMC SoIC量产经验（始于约2017年）</li>
      </ul>
    </div>
    <div class="pkg-box highlight">
      <div class="badge">LOGICFOLDING：单元级折叠</div>
      <h4>代表：华为麒麟2026（首次商业化量产）</h4>
      <ul>
        <li>设计阶段即分配电路单元到多个有源层</li>
        <li>垂直互连参与布线如同额外金属层</li>
        <li>直接缩短关键路径（critical path）布线长度</li>
        <li>降低单元间RC负载，实现τ直接压缩</li>
        <li>时钟树在三维空间中重构，降低偏斜</li>
        <li>需要全新的3D-aware EDA工具链支持</li>
        <li>混合键合间距1.5μm（目标趋近顶层金属间距）</li>
      </ul>
    </div>
  </div>

  <div class="an-box">
    <p><strong>齿轮比（Gear Ratio）的物理意义：</strong>论文中提出的一个关键约束参数。齿轮比 = 混合键合间距 ÷ 顶层金属层间距。麒麟2026的顶层金属层间距约720nm，混合键合间距1.5μm，齿轮比约为2。当齿轮比趋近1时，两个有源层之间的互连可以与芯片内部单层布线同等密度地参与信号路径，键合界面处的"鸟笼式布线"（Bird-cage Routing）开销趋近于零。论文将齿轮比降至接近1视为LogicFolding成熟度的关键衡量指标。</p>
  </div>

  <div class="prose">
    <p>混合键合（Hybrid Bonding）是LogicFolding的物理基础。与传统的焊球（Solder Bump）或铜柱（Cu Pillar）封装不同，混合键合通过铜-铜直接原子键合，无需底部填充胶（Underfill），可将互连间距从传统封装的几十微米压缩至1-2微米量级。这要求极高的表面洁净度（任何大于1μm的颗粒均可导致界面空洞）、超精密的套刻对准（≤0.5μm）以及高度控制的晶圆薄化（Total Thickness Variation ≤5%甚至≤0.5μm绝对偏差）。</p>
    <p>北京大学在发布韬定律两天后（2026年5月27日），宣布开发出专为LogicFolding架构定制的3D EDA工具。该工具采用"真3D"（True-3D）方法，将多层芯片作为单一垂直结构整体优化，而非分层2D后堆叠。初步测试显示，相比传统EDA工作流，总内部布线长度减少约30%，并改善热管理效果。这是LogicFolding生态开始吸引学术界参与的早期信号。</p>
  </div>

  <div class="cg">
    <div class="card" style="--cc:#c8000a">
      <span class="card-ic">🔗</span>
      <h3>Hi-ONE：片上光互连</h3>
      <p>论文提出的系统层技术之一。通过在封装近侧集成光学I/O，实现近封装级的光电共封装（Co-Packaged Optics）。目标是绕过2.5D扇出困境，在AI超节点中将跨节点通信延迟大幅压缩。与传统铜互连相比，光互连可在更低能耗下实现更高带宽密度。</p>
      <span class="tag">CPO</span><span class="tag">光电集成</span><span class="tag">低延迟</span>
    </div>
    <div class="card" style="--cc:#1b4f8a">
      <span class="card-ic">🚌</span>
      <h3>UnifiedBus：统一总线协议</h3>
      <p>为AI计算系统重新定义互连协议。以原生内存语义（Native Memory Semantics）实现全系统统一内存寻址，消除传统PCIe/InfiniBand/NVLink等多层协议栈的转换开销。Atlas 960超节点（支持15,488张昇腾卡）即基于此架构，目标大幅降低跨节点通信延迟。</p>
      <span class="tag">统一内存</span><span class="tag">SuperPoD</span><span class="tag">低协议开销</span>
    </div>
    <div class="card" style="--cc:#1a7a3e">
      <span class="card-ic">🧠</span>
      <h3>后硅时钟偏移调整</h3>
      <p>（Post-Silicon Clock Skew Tuning）麒麟2026引入的技术之一。3D折叠后，时钟树的物理结构发生根本变化，传统EDA工具无法精确预测晶圆实际性能中的时钟偏斜分布。华为开发了后硅调整方案，可在芯片制造完成后对时钟偏移做细粒度调节。该方案独立贡献了超过5%的SoC整体性能提升。</p>
      <span class="tag">Clock Skew</span><span class="tag">后硅调整</span><span class="tag">+5%性能</span>
    </div>
  </div>
</section>

<!-- S4: THERMAL -->
<section class="section" id="s4">
  <div class="sh"><span class="sn">04</span><h2 class="st">热管理挑战：<em>液冷</em>与3D堆叠的热力学边界</h2></div>

  <div class="prose">
    <p>三维逻辑折叠带来的最主要工程挑战之一，是热管理（Thermal Management）。在传统2D芯片中，所有发热晶体管分布在单一平面上，直接与散热器接触；当多个有源逻辑层垂直堆叠时，底层（base die）被顶层（top die）覆盖，形成热毯效应（Thermal Blanket Effect），散热路径大幅增长，热阻（Thermal Resistance）急剧上升。</p>
  </div>

  <div class="thermal-box">
    <h4>⚠️ 热管理核心挑战（EE Times / TechSoda等机构技术分析综合）</h4>
    <p><strong>热密度倍增：</strong>逻辑层数每增加一层，同等封装面积内的总功耗密度近似倍增，局部热点（Hotspot）温度更难控制。底层芯片的散热路径须穿越顶层芯片材料，等效热阻大幅增加。</p>
    <p><strong>应力管理：</strong>不同材料（硅、铜、介质）热膨胀系数（CTE）差异在3D结构中叠加，高功耗场景下的温度循环可加剧分层（Delamination）和微裂纹风险，影响长期可靠性。</p>
    <p><strong>TSV热阻：</strong>尽管TSV直径目标值低于1.5μm，但大量密集TSV在高电流密度下自身也产生焦耳热（Joule Heating），需在设计阶段精细规划电流分布以避免局部过热。</p>
  </div>

  <div class="prose">
    <p><strong>液冷（Liquid Cooling）的产业意义：</strong>先进封装与3D堆叠的热密度大幅提升，是推动数据中心液冷渗透率加速的底层技术驱动力。AI数据中心（尤其是配备H100/H200/B200等高TDP GPU或昇腾等加速器的集群）的机架功密度已从传统5-10 kW/机架跃升至50-100 kW/机架以上。液冷方案分为：</p>
  </div>

  <table class="ct">
    <thead><tr><th>液冷类型</th><th>技术原理</th><th>适用场景</th><th>与LogicFolding的关联</th></tr></thead>
    <tbody>
      <tr><td>冷板式液冷（Cold Plate）</td><td class="od">液体在密封冷板内循环，通过导热接触芯片背面散热</td><td class="od">服务器/AI加速节点，机架功密度20-50 kW</td><td class="na">LogicFolding芯片面积减少但功密度更高，冷板设计需匹配热点分布</td></tr>
      <tr><td>浸没式液冷（Immersion）</td><td class="od">整体服务器浸没于电子氟化液或矿物油中，全面换热</td><td class="od">超高功密度机架（>50 kW），数据中心整体规划</td><td class="na">为超节点（Atlas 960）提供最优散热环境，降低芯片接合点温度</td></tr>
      <tr><td>近芯液冷（Near-Chip Cooling）</td><td class="od">微通道冷却结构集成于封装内部，液体在封装级别流通</td><td class="od">高密度3D堆叠封装的终极散热方案</td><td class="na">与LogicFolding多层结构未来深度整合的研究方向，可精确控制各层热点</td></tr>
    </tbody>
  </table>

  <div class="prose">
    <p>从供应链视角看，LogicFolding对热管理设备提出的新要求，将推动液冷产业规模进一步扩张。何庭波论文亦明确指出，解决3D折叠的热管理问题，需要"在封装与系统层面系统性地优化热阻和散热路径"——这意味着芯片设计、封装材料与液冷基础设施的协同演进将成为必要条件，而非可选项。国内液冷设备企业（英维克、申菱环境、曙光数创等）及散热材料供应商（导热硅脂、热界面材料等）均将随高密度封装需求扩大而获得增量市场。</p>
  </div>
</section>

<!-- S5: SUPPLY CHAIN -->
<section class="section" id="s5">
  <div class="sh"><span class="sn">05</span><h2 class="st">产业链全景：<em>上下游影响</em>与关键企业分析</h2></div>

  <div class="prose">
    <p>根据SEMI（国际半导体产业协会）2026年数据，全球先进封装市场规模预计达540亿美元，年增速超22%，首次超越传统封装成为封测行业主流；中国先进封装市场规模预计达900亿至1,000亿元人民币，是全球增速最快的核心市场。韬定律的产业化对以下各层级产业链均产生可观影响。</p>
  </div>

  <div class="sc-flow">
    <div class="sc-tier">
      <div class="sc-tier-name">上游：<br>设计工具与IP</div>
      <div class="sc-content">
        <h4>EDA工具链：最重要的软性瓶颈</h4>
        <p>LogicFolding的多层有源堆叠大幅增加设计复杂度，需要支持True-3D时序收敛（3D Timing Closure）、跨层寄生参数提取（3D Parasitic Extraction）、多层热仿真（Thermal Co-Simulation）以及3D时钟树综合（3D CTS）的全新EDA工具链。现有Synopsys Fusion Compiler、Cadence Innovus等主流工具对此支持有限，且受美国出口管制约束。北京大学2026年5月发布的定制3D EDA工具是首个公开的学术响应，显示出相关工具链需求的迫切性。何庭波在访谈中亦明确指出EDA工具是当前最大瓶颈。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>华大九天（国内EDA龙头）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>概伦电子</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>芯原股份（IP设计）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>Synopsys（受控）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>Cadence（受控）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1a7a3e"></span>北京大学（学术方案）</span>
        </div>
      </div>
    </div>
    <div class="sc-tier">
      <div class="sc-tier-name">上游：<br>晶圆代工</div>
      <div class="sc-content">
        <h4>成熟制程节点的价值重估</h4>
        <p>韬定律在理论上允许在固定制程节点（如SMIC的7nm级N+2工艺）上通过LogicFolding持续实现代际性能提升，这直接重估了原本被视为"落后"的成熟节点的战略价值。对于中芯国际、华虹半导体等国内代工厂而言，其DUV（深紫外）光刻产线在韬定律框架下具备参与主流逻辑设计迭代的新价值。中芯国际Q1 2026营收25.05亿美元，季度环比增长0.7%，并预计Q2营收环比增长14-16%。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>中芯国际（SMIC，最大受益方）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>华虹半导体</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>晶合集成</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>芯联集成</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>TSMC（CoWoS先进封装同向布局）</span>
        </div>
      </div>
    </div>
    <div class="sc-tier">
      <div class="sc-tier-name">核心：<br>先进封装（封测）</div>
      <div class="sc-content">
        <h4>产业价值链重心转移，封测从"后道辅助"升级为"性能决定性环节"</h4>
        <p>LogicFolding、Chiplet集成、3D异构封装均需要高端封测工艺支撑。封装环节从传统芯片产业链末端的配套工序，正式升级为决定芯片性能上限与成本高低的关键环节。国内封测龙头受益明显：<br>
        <strong>长电科技</strong>（JCET）：国内封测龙头，XDFOI®高密度扇出封装平台支持5层RDL和2μm线宽量产，为华为麒麟芯片核心封测供应商，2026年固定资产投资预算上调至约100亿元（同比+18%）。<br>
        <strong>通富微电</strong>：华为AI芯片（昇腾）主力封测厂，同时服务AMD，先进封装能力国内排名前二，已发布42.2亿元定增募资计划专项用于先进封装扩产。<br>
        <strong>华天科技</strong>：西安基地邻近华为研发，2.5D、UHDFO、SiP系统级封装技术积累扎实。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>长电科技（JCET）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>通富微电</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>华天科技</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>盛合晶微</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>甬矽电子</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>晶方科技</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>TSMC（SoIC自建封装）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>ASE Group</span>
        </div>
      </div>
    </div>
    <div class="sc-tier">
      <div class="sc-tier-name">上游：<br>设备与材料</div>
      <div class="sc-content">
        <h4>键合、刻蚀、CMP等关键设备需求拉动</h4>
        <p>华泰证券分析指出，工艺复杂度提升将催化刻蚀、薄膜、键合（Bonding）、CMP（化学机械研磨）等设备需求。混合键合设备（目前较为依赖EVG、SUSS MicroTec等欧洲厂商）、高精度量测设备（套刻对准≤0.5μm要求）、晶圆薄化设备（TTV控制）均是关键品类。国内设备龙头（中微公司、北方华创、拓荆科技、华海清科、中科飞测）具备部分细分领域的供应能力。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>中微公司（刻蚀）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>北方华创（薄膜/刻蚀）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>拓荆科技（CVD）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>华海清科（CMP）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>中科飞测（量测）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>EVG（键合，奥地利）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>SUSS MicroTec（键合）</span>
        </div>
      </div>
    </div>
    <div class="sc-tier">
      <div class="sc-tier-name">下游：<br>热管理与基础设施</div>
      <div class="sc-content">
        <h4>液冷基础设施：高密度封装的必要伴随需求</h4>
        <p>LogicFolding带来的热密度上升（逻辑层堆叠使单位封装面积功密度趋近翻倍），直接推动AI数据中心向液冷架构迁移。机架功密度从传统5-10 kW向30-100 kW跃升，空气冷却逐渐不足以满足需求。国内液冷解决方案提供商及散热材料供应商将随之受益。同时，Atlas 960等超节点（15,488张昇腾卡）的部署将需要专业级数据中心液冷规划。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>英维克（液冷）</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>申菱环境</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>曙光数创</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>导热硅脂/TIM材料商</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>Vertiv（全球液冷）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>Schneider Electric</span>
        </div>
      </div>
    </div>
    <div class="sc-tier">
      <div class="sc-tier-name">下游：<br>应用生态</div>
      <div class="sc-content">
        <h4>AI软件生态：生态系统完备性仍是关键变量</h4>
        <p>硬件突破需要软件生态的配套才能转化为完整的市场竞争力。昇腾AI平台的CANN算子库、MindSpore框架以及配套的开发者工具链，目前仍与NVIDIA CUDA生态存在差距。开发者迁移成本、模型适配工作量、ISV软件适配意愿，是LogicFolding技术能否在AI市场获得规模性接受的关键非技术变量。</p>
        <div class="cos">
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>华为CANN/MindSpore生态</span>
          <span class="co-tag"><span class="dot" style="--cd:#c8000a"></span>国内云厂商（阿里/腾讯/百度）</span>
          <span class="co-tag"><span class="dot" style="--cd:#1b4f8a"></span>NVIDIA CUDA（竞争参照）</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- S6: PEER EVALUATION -->
<section class="section" id="s6">
  <div class="sh"><span class="sn">06</span><h2 class="st">同业评价：<em>国际科技企业</em>对韬定律的技术判断</h2></div>

  <div class="prose">
    <p>以下评价均来自有据可查的公开声明与行业分析报告，力求如实呈现各方立场，不作过度解读。</p>
  </div>

  <div class="peer-grid">
    <div class="peer-item" style="--pc:#76b900">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#76b900">NV</div>
        <div class="peer-title"><h4>Jensen Huang / NVIDIA</h4><p>台北Computex媒体采访，2026年5月28日</p></div>
      </div>
      <blockquote>"这对华为而言是一项突破（a breakthrough for Huawei），但不会对台积电构成威胁。TSMC在3D封装和混合键合上已经研究了将近10年。"</blockquote>
      <div class="analysis">黄仁勋的评价既肯定了华为技术进步的实质性，也通过与TSMC现有能力的对比，指出韬定律所依赖的底层技术路线并非首创。他特别区分了"对华为是突破"与"对行业是新事物"这两个不同命题。值得注意的是，NVIDIA自身的Blackwell和下一代Rubin平台均高度依赖TSMC的CoWoS先进封装，黄仁勋的判断框架自然以台积电为参照系。</div>
    </div>
    <div class="peer-item" style="--pc:#0078d4">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#0078d4">IN</div>
        <div class="peer-title"><h4>Intel（产业观察分析，Futurum Research）</h4><p>Futurum Group技术分析报告，2026年5月</p></div>
      </div>
      <blockquote>"TSMC和Intel都在向同一个方向大量投资。制造业成熟度的差距仍然很大。Intel的Foveros Direct正在进入量产，目标密度与LogicFolding相近但时间线稍长。"</blockquote>
      <div class="analysis">Futurum分析指出：华为声称的1.5μm混合键合间距若在量产规模下成立，将是一个值得重视的技术断言，超过了Intel Foveros Direct和TSMC SoIC在相同时间节点的量产规格。Futurum同时强调这一断言仍待第三方大规模验证。Intel自身的Foveros系列（Foveros、Foveros Direct、Foveros Omni）是Die-to-Die封装，非Cell-to-Cell折叠，与LogicFolding的技术定位有所不同。</div>
    </div>
    <div class="peer-item" style="--pc:#cc0000">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#cc0000">AM</div>
        <div class="peer-title"><h4>Ian Cutress（前Anandtech，知名半导体分析师）</h4><p>X平台公开评论，2026年5月25日</p></div>
      </div>
      <blockquote>"这看起来并不像是一项巨大的突破……这是大家预期都会做的技术，因为华为无法扩展光刻工艺，所以它在加速路线图上的其他部分。"</blockquote>
      <div class="analysis">Cutress的观点代表了部分国际半导体分析社区的保守立场：LogicFolding的底层技术（混合键合、3D堆叠）行业早有实践，华为的贡献在于将其系统化为一套方法论并首次在商用手机SoC上量产落地，而非发明全新的物理原理。其批评的核心是"定律"这一称谓的适当性，而非对具体工程数据的否定。</div>
    </div>
    <div class="peer-item" style="--pc:#0070f3">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#0070f3">GG</div>
        <div class="peer-title"><h4>Google / Alphabet（行业背景参照）</h4><p>产业技术路线对比分析</p></div>
      </div>
      <blockquote>Google TPU系列（TPU v4/v5等）高度依赖TSMC先进制程及3D封装技术，并在数据中心层面积累了大量高密度液冷部署经验。Google未对韬定律作出公开评论，但其在系统级时延优化（包括内存带宽、互连延迟）上的长期投入，与韬定律的系统级τ框架存在方法论上的共鸣。</blockquote>
      <div class="analysis">Google Tensor Processing Unit路线图展示了与韬定律部分相似的系统级思维：TPU v4 Pod将4096芯片通过光互连组成超级计算机，强调系统总通信延迟（即系统级τ）而非单芯片峰值计算。两者均认为AI时代的性能竞争已从单芯片迁移到系统架构层面，但路径不同——Google依赖TSMC先进制程+定制互连，华为依赖成熟制程+3D折叠+统一总线。</div>
    </div>
    <div class="peer-item" style="--pc:#888">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#555">IDC</div>
        <div class="peer-title"><h4>IDC中国区总裁 霍锦洁（彭博社专访）</h4><p>彭博社报道，2026年5月</p></div>
      </div>
      <blockquote>"韬定律可以为中国半导体产业提供一个新的参考标准，帮助其克服工艺节点限制。"</blockquote>
      <div class="analysis">IDC的表态较为中性务实：新的参考标准提供了一种测量和讨论进步的新语言，具有产业指引价值；但霍锦洁刻意使用"参考标准"而非"解决方案"，隐含了对实际落地挑战的保留。这与韬定律的学术认可度和产业接受度之间存在时间差的客观判断相符。</div>
    </div>
    <div class="peer-item" style="--pc:#555">
      <div class="peer-header">
        <div class="peer-logo" style="--pl:#444">GCA</div>
        <div class="peer-title"><h4>全球计算联盟 苗福友（首席技术官）</h4><p>新华网专访，2026年5月</p></div>
      </div>
      <blockquote>"当前模块间通信时延已成为制约高端计算效率的核心因素，传统以半导体硬件资源数量衡量计算性能的标准，已难以反映产业实际状况。"</blockquote>
      <div class="analysis">这一判断与韬定律的核心论点高度吻合：当单芯片峰值算力不再是系统瓶颈时，系统级通信延迟（即系统τ）成为新的竞争焦点。从AI训练角度，当数千卡并行时，跨节点带宽与延迟往往比单卡算力更制约整体效率，这也是UnifiedBus等系统层创新的战略背景。</div>
    </div>
  </div>
</section>

<!-- S7: MEDIA -->
<section class="section" id="s7">
  <div class="sh"><span class="sn">07</span><h2 class="st">全球媒体评价：<em>多元视角</em>的技术解读</h2></div>

  <div class="media-grid">
    <div class="media-card">
      <div class="source">Reuters / 路透社</div>
      <span class="stance stance-neutral">中性观察</span>
      <p>报道华为过去数年已在系统芯片设计、光电子及先进封装上形成综合能力，并在移动、AI、通用处理器、通信、网络与消费电子等领域量产芯片，在华为2025年880.9亿元人民币（约1300亿美元）营收中发挥重要作用。报道侧重技术背景梳理，未作价值判断。</p>
    </div>
    <div class="media-card">
      <div class="source">Wall Street Journal / 华尔街日报</div>
      <span class="stance stance-neutral">战略分析</span>
      <p>指出华为近年已成为中国推动科技自主化战略的关键企业之一，在本土半导体供应链建设中发挥重要作用，不断加强在替代芯片架构、先进封装技术以及网络通信技术方面的研发。报道将韬定律置于中美科技竞争的宏观框架下审视，重点关注供应链影响。</p>
    </div>
    <div class="media-card">
      <div class="source">Bloomberg / 彭博社</div>
      <span class="stance stance-neutral">技术存疑</span>
      <p>指出：若华为能量产达到1.4nm制程性能水平的芯片，意味着大规模生产5nm以下先进芯片并不必然依赖EUV光刻机。同时引用IDC专家意见，表述较为审慎——使用"可以提供新的参考标准"而非定性的突破性判断。</p>
    </div>
    <div class="media-card">
      <div class="source">The Register（英国科技媒体）</div>
      <span class="stance stance-skeptical">批评性审视</span>
      <p>标题使用"Huawei's chip law looks less like Moore and more like marketing"（华为芯片定律更像摩尔，更像营销）。引用匿名芯片专家评价，认为类似技术行业早有实践，质疑"定律"称谓是否适当。报道提供了重要的技术怀疑论视角，但具体技术数据的核实仍有待产品上市后独立测试。</p>
    </div>
    <div class="media-card">
      <div class="source">Nikkei Asia / 日经亚洲</div>
      <span class="stance stance-neutral">地缘战略分析</span>
      <p>重点分析韬定律对日本半导体产业的潜在影响，关注先进封装设备供应商（包括部分日本精密设备商）的战略定位变化。分析框架侧重于亚洲半导体供应链重构，对技术本身持相对中立的"观察与等待"立场。</p>
    </div>
    <div class="media-card">
      <div class="source">EE Times（专业电子工程媒体）</div>
      <span class="stance stance-neutral">技术深度解析</span>
      <p>发表技术深度文章，指出τ缩放并非单一技术问题，而是贯穿整个栈（Stack）的系统工程问题。EE Times的立场是：韬定律的理论框架具有技术逻辑完整性，但热管理、EDA工具、良率和供应链协调等挑战均非技术论文能够解决，需要产业持续验证。</p>
    </div>
    <div class="media-card">
      <div class="source">Tom's Hardware（技术媒体）</div>
      <span class="stance stance-neutral">数据核查</span>
      <p>关注到一个值得注意的数据点：麒麟2026声称的238 MTr/mm²晶体管密度，与TSMC N3P节点的224 MTr/mm²相当，甚至略高。若经独立验证属实，则意味着在逻辑密度上缩小了与台积电先进节点之间的差距，但制造工艺路径不同（DUV+3D vs EUV+2D），成本结构也有根本差异。</p>
    </div>
    <div class="media-card">
      <div class="source">CGTN / 中国国际电视台</div>
      <span class="stance stance-positive">技术解读</span>
      <p>发表"From geometry to time: Decoding Huawei's Tau (τ) Scaling Law"深度解读文章，以"工厂装配线"类比晶体管与信号传播，为国际英语读者提供技术背景普及。立场偏正面，但技术表述基本准确，引用了外部专家观点进行补充。</p>
    </div>
    <div class="media-card">
      <div class="source">新华社特稿</div>
      <span class="stance stance-positive">产业意义报道</span>
      <p>以"中国企业勇探半导体发展新路径"为主题，引用彭博社、IDC及全球计算联盟等国际机构/外媒评价，呈现多元视角。总体倾向认可韬定律的产业意义，但行文中注意区分"目前已验证的工程数据"与"未来路线图目标"。</p>
    </div>
    <div class="media-card">
      <div class="source">人民日报专访</div>
      <span class="stance stance-positive">一手采访报道</span>
      <p>独家专访何庭波，获取其对韬定律动机、技术路径、行业观察的一手陈述，包括"笨信念、笨工夫"的研发文化描述，以及对2019年至今战略演变的完整叙述。是理解华为内部视角的最直接一手资料，技术层面的表述与论文原文一致。</p>
    </div>
  </div>
</section>

<!-- S8: FINANCIAL -->
<section class="section" id="s8">
  <div class="sh"><span class="sn">08</span><h2 class="st">金融机构分析：<em>市场反应</em>与机构研判</h2></div>

  <div class="prose">
    <p>韬定律发布当日（2026年5月25日），A股半导体板块大幅走强，科创50指数创历史新高。中芯国际（SMIC）港股在发布次日上涨7.6%。长电科技、华天科技实现两连板，通富微电一度触及涨停，甬矽电子等多股涨幅超10%。科创板半导体材料与设备指数市盈率一度升至142倍，市净率处于历史98分位，显现出极端情绪化估值特征。</p>
  </div>

  <div class="cg">
    <div class="card" style="--cc:#003366">
      <span class="card-ic">🏦</span>
      <h3>Goldman Sachs（高盛）</h3>
      <p>高盛此前（2026年4月）已上调台湾封装设备股All Ring Tech和Grand Plastic Technology的评级，理由是TSMC先进封装资本支出上行周期将延伸至2028年以上，SoIC、CPO、面板级封装等需求强劲。韬定律发布后，据中国媒体报道，高盛联同摩根士丹利于5月以来调研了长电科技、中芯国际等10家企业，给予"增持"评级，目标价上调幅度据报在30%-50%之间。上述具体数据来源于国内财经媒体引述，尚待高盛官方发布核实。</p>
    </div>
    <div class="card" style="--cc:#0050a0">
      <span class="card-ic">📈</span>
      <h3>Morgan Stanley（摩根士丹利）</h3>
      <p>摩根士丹利2026年半导体报告（2026年5月前发布）将SMIC评为中国AI GPU最大受益方，理由包括：国内主要芯片商均依赖SMIC先进节点，国内云厂商转向采购国产AI芯片（TCO较NVIDIA低30-60%）形成正反馈。同期报告列出AI GPU相关推荐股：昂扬（Cambricon）OW评级，燧原科技OW评级。SMIC Q1 2026营收环比增0.7%，Q2指引+14-16%（主要受AI驱动）。</p>
    </div>
    <div class="card" style="--cc:#b06b00">
      <span class="card-ic">🔬</span>
      <h3>国内券商三家综合研判</h3>
      <p><strong>华泰证券</strong>：建议关注中芯国际、华虹半导体，认为DUV产线可在韬定律框架下发挥新价值；同时提示先进封装（长电、通富）、EDA（华大九天）及CPO光互连方向。<br>
      <strong>国盛证券</strong>：覆盖面最宽，囊括半导体制造、前/后道设备、材料和封测，列出约18家核心受益标的。<br>
      <strong>中信证券</strong>：提示需防范半导体材料设备板块估值已处极端区间的风险，并关注封测在手订单/营收比达1.8的景气度信号。</p>
    </div>
    <div class="card" style="--cc:#555">
      <span class="card-ic">⚠️</span>
      <h3>估值风险提示</h3>
      <p>分析人士田丰（快思慢想研究院院长）接受《时代周报》采访时指出，并非所有半导体企业都能均等受益。"韬定律的重点是逻辑堆叠之后的系统工程能力，产业价值链将向EDA、先进封装、热管理等环节倾斜。"散热概念中存在一定炒作成分，需区分真实技术需求与市场情绪。同时，芯和半导体创始人代文亮指出：下一个十年的竞争胜负手不在光刻机节点，而在封装、存储带宽、互连和Fabric设计，以及支撑这一切的系统级EDA工具链。</p>
    </div>
  </div>

  <div class="prose">
    <p>需要特别指出的是：韬定律发布后短期内国内资本市场出现了明显的情绪化上涨，部分板块估值达到历史极端水平。从技术层面看，韬定律是一套具有工程验证基础的方法论，其从理论被行业广泛接受、到大规模产业链重构之间，存在较长的时间周期和大量工程挑战需要克服。摩尔定律从1965年提出到被行业完全接受历时约10年，何庭波自己也在专访中援引了这一时间参照。</p>
  </div>

  <h3 style="font-family:'Noto Sans SC',sans-serif;font-size:15px;font-weight:700;margin:36px 0 14px;color:var(--accent);">韬定律相关产业链股票市场反应（2026年5月25日，参考数据）</h3>
  <table class="ct">
    <thead><tr><th>公司</th><th>主要价值连接点</th><th>发布当日/次日涨幅（参考）</th><th>机构主流评级</th></tr></thead>
    <tbody>
      <tr><td>中芯国际（SMIC）</td><td class="na">DUV制程价值重估，韬定律代工基础</td><td class="ny">港股+7.6%</td><td class="ny">Overweight / 增持</td></tr>
      <tr><td>长电科技（JCET）</td><td class="na">核心封测供应商，XDFOI平台</td><td class="ny">两连板</td><td class="ny">增持，目标价+30-50%</td></tr>
      <tr><td>通富微电</td><td class="na">昇腾主力封测，AI芯片扩产</td><td class="ny">一度触涨停</td><td class="ny">增持</td></tr>
      <tr><td>华天科技</td><td class="na">西安基地邻近，SiP/3D封装</td><td class="ny">两连板</td><td class="ny">增持</td></tr>
      <tr><td>甬矽电子</td><td class="na">先进封测新秀，快速扩产</td><td class="ny">+10%+</td><td class="ny">关注</td></tr>
      <tr><td>华大九天</td><td class="na">国内EDA龙头，潜在受益</td><td class="ny">跟随板块上涨</td><td class="ny">增持</td></tr>
    </tbody>
  </table>
</section>

<!-- S9: RISK -->
<section class="section" id="s9">
  <div class="sh"><span class="sn">09</span><h2 class="st">风险分析与<em>技术不确定性</em></h2></div>

  <div class="rg">
    <div class="ri"><div class="rl H">H</div><div><h4>良率与量产稳定性</h4><p>LogicFolding的单颗芯片任何有源层的缺陷均可导致整体报废，良率管理难度随层数增加呈非线性上升。混合键合对洁净度要求极高（任何>1μm颗粒均可造成界面空洞），大规模量产的稳定性尚待麒麟2026上市后独立拆解验证。华为自称智能冗余方案下良率接近100%，第三方数据尚未披露。</p></div><div class="mt"><h5>缓解策略</h5><p>分步推进（保守方案优先）；引入冗余单元（Spare Cell）设计；后硅时钟偏移调整作为补偿；与长电科技等封测伙伴深度工艺协同开发。</p></div></div>
    <div class="ri"><div class="rl H">H</div><div><h4>EDA工具链缺口</h4><p>3D Cell-to-Cell折叠需要全新的True-3D EDA流程（3D布局布线、多层寄生提取、跨层时序收敛、3D时钟树综合）。现有主流EDA工具Synopsys/Cadence对此支持不完整，且受美国出口管制。国内EDA企业（华大九天等）尚处于布局阶段，距离支撑完整LogicFolding设计流程仍有差距。</p></div><div class="mt"><h5>缓解策略</h5><p>公开韬定律理论框架吸引学术界（已有北京大学响应）；国内EDA企业专项投入；短期以现有工具支持保守方案（选择性折叠），中期推进工具链升级。</p></div></div>
    <div class="ri"><div class="rl H">H</div><div><h4>热管理工程挑战</h4><p>逻辑层垂直堆叠使底层芯片的散热路径穿越顶层材料，热阻急剧上升，局部热点难以有效控制。在高频（3.1 GHz+）、高TDP（Thermal Design Power）场景下，多层结构的可靠性寿命预测模型尚不成熟。这也是手机SoC（功耗5-15W量级）相比AI加速卡（功耗300-700W量级）更早实现LogicFolding商业化的原因之一。</p></div><div class="mt"><h5>缓解策略</h5><p>近封装液冷研究（近芯微通道冷却）；热感知布局（Thermal-aware Placement）优化；引入低温混合键合材料；与液冷基础设施协同部署（尤其是AI超节点）。</p></div></div>
    <div class="ri"><div class="rl M">M</div><div><h4>行业接受与标准化周期</h4><p>一套新的指导原则从提出到被行业广泛接受需要时间。摩尔定律历时约10年才成为行业共识。韬定律作为方法论，需要足够多的独立实践者验证其跨平台适用性，才能真正成为产业标准。初期阶段，"华为专有框架"的标签可能限制其作为中立行业标准的接受度。</p></div><div class="mt"><h5>缓解策略</h5><p>在IEEE等国际顶级学术平台持续发表；主动邀请全球科学家、工程师共同参与；公开开放部分方法论细节（如论文全文）；通过实际产品量产验证积累信任资本。</p></div></div>
    <div class="ri"><div class="rl M">M</div><div><h4>供应链政策风险</h4><p>混合键合关键设备（EVG、SUSS等欧洲厂商）、特种键合材料、精密量测仪器等若遭受进一步出口管制扩展，将影响LogicFolding规模化量产节奏。前道制程节点受限（无法获取EUV）已是既定约束，后道封装设备依赖仍存在不确定性。</p></div><div class="mt"><h5>缓解策略</h5><p>加速关键封装设备国产替代（中微公司等）；多元化供应商（包括非管制地区）；建立战略备货；将韬定律国际化降低其单纯被视为中国技术路线的政治敏感性。</p></div></div>
    <div class="ri"><div class="rl L">L</div><div><h4>竞争对手技术跟进</h4><p>TSMC的SoIC已在量产，Intel Foveros Direct进入量产爬坡，Samsung X-Cube亦在推进。若上述主流厂商将Die-to-Die堆叠进一步向Cell-to-Cell粒度演进，LogicFolding的相对差异化可能随时间收窄。台积电、三星已有韬定律相关技术研发投入的行业报道。</p></div><div class="mt"><h5>缓解策略</h5><p>专利布局保护核心IP（LogicFolding架构、UnifiedBus协议等）；保持研发投入节奏；将系统级τ框架（跨层联合优化方法论）作为更难复制的竞争壁垒而非单一封装技术。</p></div></div>
  </div>
</section>

<!-- S10: ROADMAP -->
<section class="section" id="s10">
  <div class="sh"><span class="sn">10</span><h2 class="st">技术路线图：<em>论文披露</em>的演进规划</h2></div>

  <div class="rm">
    <div class="rm-ph"><div class="py">2020—2025</div><h4>理论形成与静默验证期</h4><ul><li>Dennard Scaling失效后回归基础理论</li><li>逻辑折叠核心概念形成</li><li>量产381款芯片（跨6大领域）</li><li>混合键合工艺开发启动</li><li>UnifiedBus协议原型验证</li></ul></div>
    <div class="rm-ph hl"><div class="py">2026 · 当前节点</div><h4>公开发布 · 首代商业化</h4><ul><li>IEEE ISCAS 2026发布韬定律</li><li>ChinaXiv论文全文公开</li><li>麒麟2026（保守方案，秋季）</li><li>密度238 MTr/mm²，3.1 GHz</li><li>昇腾950系列（950PR/950DT）</li><li>北大3D EDA工具响应</li></ul></div>
    <div class="rm-ph"><div class="py">2027</div><h4>频率提升与AI扩展</h4><ul><li>麒麟2027：CPU频率3.39 GHz</li><li>昇腾960发布</li><li>混合键合间距持续收窄</li><li>TSV着陆层级下移（M6目标）</li><li>生态合作伙伴扩展</li></ul></div>
    <div class="rm-ph"><div class="py">2028</div><h4>全面多层化扩展</h4><ul><li>CPU频率3.71 GHz</li><li>昇腾970发布</li><li>从选择性折叠→全面折叠</li><li>3-4个有源层封装</li><li>EDA工具链完善里程碑</li><li>键合间距目标→1μm以下</li></ul></div>
    <div class="rm-ph"><div class="py">2029—2031</div><h4>密度突破目标</h4><ul><li>CPU频率突破4 GHz</li><li>晶体管密度→400+ MTr/mm²</li><li>等效1.4nm（14Å）目标验证</li><li>Hi-ONE光互连规模部署</li><li>AI集成度较2025提升100×</li><li>产业标准化推进</li></ul></div>
  </div>

  <div class="prose">
    <p>以上路线图数据均来自何庭波论文原文及ISCAS 2026主旨演讲披露内容。需要说明的是，2031年"等效1.4nm"的目标指的是晶体管密度（MTr/mm²）和系统性能指标达到当时传统几何缩微路线下1.4nm工艺节点的等效水平，而非指制造工艺节点本身为1.4nm。这是两个不同维度的描述，论文中的表述为"transistor density equivalent to 14 Å (1.4nm) processes"——等效于，而非制造于。</p>
  </div>
</section>

<!-- S11: FINANCIAL MODEL -->
<section class="section" id="s11">
  <div class="sh"><span class="sn">11</span><h2 class="st">财务参考模型：<em>韬定律产业化</em>的商业影响估算</h2></div>

  <div class="prose">
    <p>以下财务模型基于已公开披露的行业数据、券商研究及市场估算构建，仅作结构性参考，不构成投资建议。华为半导体业务（含HiSilicon、昇腾、鲲鹏等）并未独立上市，相关数据为综合估算。</p>
  </div>

  <h3 style="font-family:'Noto Sans SC',sans-serif;font-size:14.5px;font-weight:700;margin:28px 0 12px;color:var(--accent);">全球先进封装市场规模预测（十亿美元，据SEMI数据）</h3>
  <table class="ft">
    <thead><tr><th>细分领域</th><th>2024A</th><th>2025E</th><th>2026E</th><th>2028E</th><th>2031E</th></tr></thead>
    <tbody>
      <tr><td>2.5D先进封装（CoWoS等）</td><td>12.0</td><td>16.5</td><td>22.0</td><td>38.0</td><td>65.0</td></tr>
      <tr><td>3D堆叠封装（SoIC/Foveros等）</td><td>6.5</td><td>9.8</td><td>14.5</td><td>26.0</td><td>52.0</td></tr>
      <tr><td>混合键合相关封装</td><td>2.0</td><td>3.5</td><td>6.0</td><td>14.0</td><td>35.0</td></tr>
      <tr><td>传统封装（Wirebond/Flip Chip）</td><td>42.0</td><td>44.0</td><td>46.0</td><td>50.0</td><td>55.0</td></tr>
      <tr class="sub"><td>全球封测市场合计</td><td>62.5</td><td>73.8</td><td>88.5</td><td>128.0</td><td>207.0</td></tr>
      <tr><td>先进封装占比</td><td class="ac">33%</td><td class="ac">40%</td><td class="ac">47%</td><td class="ac">61%</td><td class="ac">73%</td></tr>
    </tbody>
  </table>

  <h3 style="font-family:'Noto Sans SC',sans-serif;font-size:14.5px;font-weight:700;margin:36px 0 12px;color:var(--accent);">华为半导体相关业务收入结构估算（亿元人民币）</h3>
  <table class="ft">
    <thead><tr><th>业务线</th><th>2025E</th><th>2026E</th><th>2027E</th><th>2028E</th><th>2031E</th></tr></thead>
    <tbody>
      <tr><td>消费终端（麒麟/巴龙SoC）</td><td>420</td><td>580</td><td>760</td><td>990</td><td>1,750</td></tr>
      <tr><td>AI算力（昇腾/Atlas）</td><td>280</td><td>430</td><td>710</td><td>1,150</td><td>3,100</td></tr>
      <tr><td>通用计算（鲲鹏）</td><td>180</td><td>245</td><td>325</td><td>435</td><td>800</td></tr>
      <tr><td>通信基础设施芯片</td><td>350</td><td>385</td><td>425</td><td>475</td><td>660</td></tr>
      <tr><td>汽车/IoT/工业</td><td>90</td><td>145</td><td>215</td><td>320</td><td>740</td></tr>
      <tr class="sub"><td>半导体相关业务估算总计</td><td>1,320</td><td>1,785</td><td>2,435</td><td>3,370</td><td>7,050</td></tr>
      <tr><td>YoY增速</td><td class="ac">—</td><td class="pos">+35%</td><td class="pos">+36%</td><td class="pos">+38%</td><td class="pos">+28%CAGR</td></tr>
    </tbody>
  </table>

  <h3 style="font-family:'Noto Sans SC',sans-serif;font-size:14.5px;font-weight:700;margin:36px 0 12px;color:var(--accent);">韬定律驱动的R&D投入结构估算（亿元人民币）</h3>
  <table class="ft">
    <thead><tr><th>投入领域</th><th>2025E</th><th>2026E</th><th>2027E</th><th>2028E</th><th>说明</th></tr></thead>
    <tbody>
      <tr><td>基础理论研究（τ Scaling）</td><td>85</td><td>115</td><td>145</td><td>175</td><td>论文、IEEE发表、学术合作</td></tr>
      <tr><td>LogicFolding工程开发</td><td>125</td><td>165</td><td>205</td><td>255</td><td>核心制程、封装协同</td></tr>
      <tr><td>混合键合/封装工艺合作</td><td>60</td><td>95</td><td>135</td><td>185</td><td>与长电等深度工艺开发</td></tr>
      <tr><td>EDA工具链（国内替代）</td><td>40</td><td>68</td><td>95</td><td>120</td><td>华大九天等合作</td></tr>
      <tr><td>AI软件生态（CANN等）</td><td>95</td><td>125</td><td>155</td><td>185</td><td>算子库、框架、开发者</td></tr>
      <tr class="sub"><td>合计半导体R&D估算</td><td>405</td><td>568</td><td>735</td><td>920</td><td></td></tr>
      <tr class="tot"><td>R&D/收入比</td><td>30.7%</td><td>31.8%</td><td>30.2%</td><td>27.3%</td><td>高强度维持期</td></tr>
    </tbody>
  </table>
</section>

<!-- S12: GLOSSARY -->
<section class="section" id="s12">
  <div class="sh"><span class="sn">附录</span><h2 class="st"><em>专业术语</em>全面解释（Appendix: Terminology）</h2></div>

  <div class="gloss">
    <div class="gl-item"><div class="gl-term">τ (Tau, 时间常数)</div><div class="gl-def">电路从一个逻辑状态切换到另一逻辑状态所需时间的表征量。τ = RC，其中R为等效电阻，C为等效电容。τ越小，电路切换越快，性能越高。</div></div>
    <div class="gl-item"><div class="gl-term">Moore's Law（摩尔定律）</div><div class="gl-def">1965年Gordon Moore提出：集成电路上可容纳的晶体管数目约每18-24个月翻倍，性能随之提升。是过去60年半导体产业的核心指导原则。</div></div>
    <div class="gl-item"><div class="gl-term">Dennard Scaling（邓纳德缩放定律）</div><div class="gl-def">1974年Robert Dennard提出：晶体管尺寸缩小时，可以同比例降低电压，维持电场强度不变，使性能提升而功耗不增。约2005年后开始失效。</div></div>
    <div class="gl-item"><div class="gl-term">Geometric Scaling（几何缩微）</div><div class="gl-def">通过物理缩小晶体管尺寸（特征线宽，单位nm/Å）来提升集成度和性能的传统路线，依赖光刻技术进步。</div></div>
    <div class="gl-item"><div class="gl-term">Time Scaling（时间缩微）</div><div class="gl-def">韬定律提出的新优化目标：直接以压缩时间常数τ为指导，允许通过多种技术手段（不局限于缩小几何尺寸）实现性能提升。</div></div>
    <div class="gl-item"><div class="gl-term">LogicFolding（逻辑折叠）</div><div class="gl-def">华为提出的设计方法论：将数字、模拟、存储电路在设计阶段分配到垂直堆叠的多个有源层，通过混合键合连接，实现Cell-to-Cell级别的3D信号路径缩短。</div></div>
    <div class="gl-item"><div class="gl-term">Hybrid Bonding（混合键合）</div><div class="gl-def">通过铜-铜原子直接键合实现晶圆间超细间距互连的工艺，无需底部填充胶。间距可低至1-2μm，远优于传统焊球/铜柱封装。要求极高洁净度和套刻精度。</div></div>
    <div class="gl-item"><div class="gl-term">TSV（Through-Silicon Via，硅通孔）</div><div class="gl-def">垂直穿透硅衬底的导电通孔，用于3D堆叠结构中不同层之间的垂直电气连接。LogicFolding要求TSV关键尺寸<1.5μm，间距<6μm。</div></div>
    <div class="gl-item"><div class="gl-term">Gear Ratio（齿轮比）</div><div class="gl-def">论文定义的关键参数：混合键合间距÷顶层金属层间距。比值越接近1，两层之间的互连密度越接近芯片内部单层布线，界面布线开销趋零。麒麟2026约为2（1.5μm/0.72μm），目标趋近1。</div></div>
    <div class="gl-item"><div class="gl-term">Critical Path（关键路径）</div><div class="gl-def">数字电路中决定最高工作频率的信号传播路径，即从一个触发器（FF）到下一个FF之间延迟最长的路径。关键路径延迟决定了芯片的最大时钟频率。</div></div>
    <div class="gl-item"><div class="gl-term">Clock Skew（时钟偏斜）</div><div class="gl-def">时钟信号到达不同触发器的时间差异。偏斜越大，可用的有效时序裕量（Timing Slack）越小。LogicFolding通过3D时钟树重构，实现时钟偏斜减少约25%。</div></div>
    <div class="gl-item"><div class="gl-term">NoC（Network-on-Chip，片上网络）</div><div class="gl-def">芯片内部各功能模块间的高速通信网络。Hi-ONE技术在LogicFolding的上下层之间构建高速全局NoC，使数据路径面积减少55%，同时改善电源传递稳定性。</div></div>
    <div class="gl-item"><div class="gl-term">UnifiedBus（统一总线）</div><div class="gl-def">华为提出的跨节点互连协议，以原生内存语义实现AI超节点内所有加速卡的统一内存寻址，消除传统PCIe/InfiniBand/NVLink等多层协议栈开销，降低跨节点通信延迟。</div></div>
    <div class="gl-item"><div class="gl-term">Hi-ONE（光互连I/O）</div><div class="gl-def">华为提出的近封装光学I/O技术（Co-Packaged Optics，CPO的一种形态），在封装近侧集成光电转换，实现更高带宽密度和更低功耗的跨节点光互连。</div></div>
    <div class="gl-item"><div class="gl-term">SuperPoD（超级PoD）</div><div class="gl-def">华为Atlas 960超节点架构中的大规模AI集群单元，通过UnifiedBus实现15,488张昇腾卡的统一内存寻址和协同计算，是当前规模最大的单一内存寻址AI计算集群方案之一。</div></div>
    <div class="gl-item"><div class="gl-term">SoIC（System on Integrated Chips）</div><div class="gl-def">台积电的3D IC先进封装平台，通过直接铜-铜混合键合将不同芯片（Die）垂直堆叠，是Die-to-Die堆叠技术。用于NVIDIA AI芯片（CoWoS是其2.5D版本）和AMD服务器处理器。</div></div>
    <div class="gl-item"><div class="gl-term">Intel Foveros / Foveros Direct</div><div class="gl-def">Intel的3D封装技术体系。Foveros通过微凸块（Micro-bump）连接，Foveros Direct实现铜-铜直接键合，间距更小，主要用于Die-to-Die级集成（如Meteor Lake处理器）。</div></div>
    <div class="gl-item"><div class="gl-term">AMD 3D V-Cache</div><div class="gl-def">AMD将额外的SRAM Cache芯片通过混合键合堆叠在CPU计算Die之上的技术，用于服务器（EPYC Genoa X）和游戏处理器（Ryzen 7000X3D），是Die-to-Die的缓存堆叠应用。</div></div>
    <div class="gl-item"><div class="gl-term">CoWoS（Chip-on-Wafer-on-Substrate）</div><div class="gl-def">台积电的2.5D先进封装平台，通过硅中介层（Si Interposer）将逻辑芯片与HBM等高带宽存储芯片并排集成，是AI训练芯片（NVIDIA H100/H200/B200）的标准封装方式。</div></div>
    <div class="gl-item"><div class="gl-term">HBM（High Bandwidth Memory）</div><div class="gl-def">高带宽存储器，通过TSV垂直堆叠多层DRAM芯片，实现比传统GDDR更高的内存带宽（TB/s级别）。AI GPU（NVIDIA H100: 3.35 TB/s；H200: 4.8 TB/s）及昇腾系列均采用HBM。</div></div>
    <div class="gl-item"><div class="gl-term">EDA（Electronic Design Automation）</div><div class="gl-def">电子设计自动化工具，覆盖芯片设计全流程（RTL综合、布局布线、仿真、验证、时序分析等）。LogicFolding需要支持3D空间联合优化的全新EDA工具链，是当前最大的软性瓶颈。</div></div>
    <div class="gl-item"><div class="gl-term">MTr/mm²（Million Transistors per mm²）</div><div class="gl-def">晶体管面密度单位，用于衡量芯片集成度。麒麟2026：238 MTr/mm²；TSMC N3P（近似参考值）：约224 MTr/mm²；韬定律2031年目标：400+ MTr/mm²。</div></div>
    <div class="gl-item"><div class="gl-term">DUV / EUV（光刻技术）</div><div class="gl-def">DUV（深紫外，波长193nm ArF）：现行主流光刻技术，中芯国际等可获取；EUV（极紫外，波长13.5nm，ASML独家供应）：可实现7nm以下制程，受美国出口管制对华禁售。LogicFolding在DUV节点上实现等效进步是其核心价值。</div></div>
    <div class="gl-item"><div class="gl-term">Thermal Blanket Effect（热毯效应）</div><div class="gl-def">3D堆叠中，底层芯片被顶层芯片覆盖，散热路径延长，热阻急剧上升，导致底层芯片难以有效散热的物理现象。是LogicFolding热管理的核心挑战。</div></div>
    <div class="gl-item"><div class="gl-term">TTV（Total Thickness Variation）</div><div class="gl-def">晶圆总厚度变化，衡量超薄晶圆磨削后的平整度。混合键合工艺要求TTV控制在5%以内，甚至绝对偏差≤0.5μm，是实现平整键合界面的关键工艺参数。</div></div>
    <div class="gl-item"><div class="gl-term">Post-Silicon Tuning（后硅调整）</div><div class="gl-def">芯片制造完成后，在封装或测试阶段对特定参数（如时钟延迟、偏压）进行电调节的技术。麒麟2026的后硅时钟偏移调整方案独立贡献了>5%的SoC性能提升。</div></div>
    <div class="gl-item"><div class="gl-term">Bird-cage Routing（鸟笼布线）</div><div class="gl-def">论文中描述的LogicFolding键合界面处的布线方式，指在混合键合接触点附近额外引入的绕线开销。当齿轮比趋近1时，此开销趋向消失，是衡量LogicFolding成熟度的技术指标之一。</div></div>
    <div class="gl-item"><div class="gl-term">α（缩放因子）</div><div class="gl-def">韬定律代际公式τ_(n+1) = τ_n / α中的应用场景参数，量化每年（或每代）的τ改善速率。非摩尔定律的固定系数，因应用域不同而显著差异：移动约1.3×/年，AI工作负载可达10×/年。</div></div>
    <div class="gl-item"><div class="gl-term">ISCAS（IEEE国际电路与系统研讨会）</div><div class="gl-def">IEEE主办的顶级学术会议（International Symposium on Circuits and Systems），是模拟/混合信号、数字电路设计领域最重要的国际学术论坛之一。2026年于上海举办，韬定律在此正式发布。</div></div>
  </div>
</section>

<!-- S13: REFERENCES -->
<section class="section" id="s13">
  <div class="sh"><span class="sn">参考</span><h2 class="st">参考文献与<em>主要信息来源</em></h2></div>
  <ol class="ref-list">
    <li>He Tingbo (何庭波), "A Time Scaling Theory for Multi-Layer Electronic Systems," ChinaXiv preprint, May 25, 2026. <a href="https://chinaxiv.org/abs/202605.00224" target="_blank">chinaxiv.org/abs/202605.00224</a></li>
    <li>HUAWEI Official Press Release, "HUAWEI Presents the Tau (τ) Scaling Law, Enabling Breakthroughs in Transistor Density and System Performance," May 25, 2026. <a href="https://www.huawei.com/en/news/2026/5/ieee-iscas-tau-scaling" target="_blank">huawei.com</a></li>
    <li>人民日报专访何庭波，"一直往前走，终归可以找到桥和路"，于洋、谷业凯，2026年5月27日。<a href="https://www.peopleapp.com/column/30052247440-500007515768" target="_blank">peopleapp.com</a></li>
    <li>Leon Liao, "Huawei Unveils Tau (τ) Scaling Law: Aiming for 1.4nm-Equivalent Chip Density Within Five Years," China as a System Substack, May 2026. <a href="https://leonliao.substack.com/p/tau-scaling-law-vs-moores-law-from" target="_blank">leonliao.substack.com</a></li>
    <li>Global Semi Research, "Huawei's Tau Scaling Law: A Technical Deep Dive Beyond the Hype," May 2026. <a href="https://globalsemiresearch.substack.com/p/huaweis-tau-scaling-law-a-technical" target="_blank">globalsemiresearch.substack.com</a></li>
    <li>Futurum Group, "Does Huawei's Tau Scaling Law Challenge the Logic Leadership of Intel and TSMC?", May 2026. <a href="https://futurumgroup.com/insights/does-huaweis-tau-scaling-law-challenge-the-logic-leadership-of-intel-and-tsmc/" target="_blank">futurumgroup.com</a></li>
    <li>TechWire Asia, "Huawei's Tau Scaling Law: The end of Moore's Law era?", May 2026. <a href="https://techwireasia.com/2026/05/huawei-tau-scaling-law-moores-law/" target="_blank">techwireasia.com</a></li>
    <li>Tom's Hardware, "Huawei claims sanctions-busting breakthrough with 1.4nm-class chips by 2031, claims 55% higher transistor density," May 2026. <a href="https://www.tomshardware.com/tech-industry/semiconductors/huawei-claims-sanctions-busting-breakthrough" target="_blank">tomshardware.com</a></li>
    <li>Tom's Hardware, "Peking University builds 3D chip design tool tailored to Huawei's LogicFolding architecture," May 2026. <a href="https://www.tomshardware.com/tech-industry/semiconductors/peking-university-builds-3d-chip-design-tool" target="_blank">tomshardware.com</a></li>
    <li>The Register, "Huawei's chip law looks less like Moore and more like marketing," May 2026. <a href="https://www.theregister.com/systems/2026/05/26/huaweis-chip-law-looks-less-like-moore-and-more-like-marketing/" target="_blank">theregister.com</a></li>
    <li>CGTN, "From geometry to time: Decoding Huawei's Tau (τ) Scaling Law," May 2026. <a href="https://news.cgtn.com/news/2026-05-26/From-geometry-to-time-Decoding-Huawei-s-Tau-Scaling-Law-1NstzXY8iDC/p.html" target="_blank">cgtn.com</a></li>
    <li>CGTN, "Jensen Huang on Huawei's Tau Scaling Law: A breakthrough, but no threat to TSMC," May 30, 2026. <a href="https://news.cgtn.com/news/2026-05-30/Jensen-Huang-on-Huawei-s-Tau-Scaling-Law-No-threat-to-TSMC--1NzomLReBK8/p.html" target="_blank">cgtn.com</a></li>
    <li>EE Times, "From Shrinking Transistors to Compressing Time: Huawei's τ Law," May 2026. <a href="https://www.eetimes.com/from-shrinking-transistors-to-compressing-time-deciphering-huaweis-%CF%84-law/" target="_blank">eetimes.com</a></li>
    <li>新华社特稿，"'韬定律'引全球关注 中国企业勇探半导体发展新路径"，2026年5月27日。<a href="https://www.news.cn/20260527/61e64944601142aaafe0a7242873994c/c.html" target="_blank">news.cn</a></li>
    <li>PANews, "How can Huawei break through in the high-end chip market without advanced lithography machines?", 2026. <a href="https://www.panewslab.com/en/articles/019e5dd1-b523-73ba-ab70-2118a0137c0b" target="_blank">panewslab.com</a></li>
    <li>新浪财经，华泰证券/国盛证券/中信证券研究报告整理，"华为'韬定律'重塑半导体叙事，先进封装、代工与成熟制程迎景气度新窗口"，2026年5月26日。</li>
    <li>新浪科技，"韬定律问世，先进封装成破局关键！长电科技能否吃透千亿市场红利？"，2026年5月27日。</li>
    <li>《时代周报》，"华为'韬定律'刷屏背后：散热概念炒作成分大，国产EDA厂商机会来了"，2026年5月26日。</li>
    <li>BigGo Finance, "Huawei's τ-Law Shakes Up Chip Packaging: Advanced Packaging Leaps from Supporting Role to Core Engine," May 2026. <a href="https://finance.biggo.com/news/7mSBZ54BX0tZvRTv8vz6" target="_blank">finance.biggo.com</a></li>
    <li>SEMI Industry Report, "Global Advanced Packaging Market Forecast 2026-2031," SEMI, 2026.</li>
    <li>Morgan Stanley, "2026 Semiconductor Report: Buy Packaging, Buy Testing, Buy Chinese Chips," referenced via PANews, May 2026.</li>
    <li>Goldman Sachs, Upgrade of All Ring Tech and Grand Plastic Technology, April 2026, via Investing.com.</li>
    <li>TrendForce, "NVIDIA Jensen Huang Calls Huawei's Tau Scaling Law a Breakthrough, But Sees No Challenge to TSMC," May 29, 2026. <a href="https://www.trendforce.com/news/2026/05/29/news-nvidia-jensen-huang-calls-huaweis-tau-scaling-law-a-breakthrough-but-sees-no-challenge-to-tsmc/" target="_blank">trendforce.com</a></li>
    <li>SMIC Q1 2026 Earnings Release, May 14, 2026, via StockAnalysis.</li>
    <li>Moore, Gordon E., "Cramming more components onto integrated circuits," Electronics, Vol. 38, No. 8, April 19, 1965.</li>
    <li>Dennard, Robert H. et al., "Design of ion-implanted MOSFET's with very small physical dimensions," IEEE JSSC, Vol. 9, No. 5, October 1974.</li>
  </ol>
</section>

</div><!-- /pw -->

<footer class="footer">
  <div>
    <strong style="color:rgba(255,255,255,.65)">华为韬（τ）定律 · 深度知识库 v2.0</strong><br>
    主参考：<a href="https://www.huawei.com/en/news/2026/5/ieee-iscas-tau-scaling">华为官方发布</a> · <a href="https://chinaxiv.org/abs/202605.00224">ChinaXiv论文</a> · <a href="https://www.peopleapp.com/column/30052247440-500007515768">人民日报专访</a> · IEEE ISCAS 2026 · 多源国际媒体及金融机构报告<br>
    本知识库以"只阐述，不激变"为原则，所有数据来自可核查的公开一手或权威二手来源，财务模型为结构性估算，不构成投资建议。<br>
    <span style="opacity:.35;font-size:10.5px;">编制日期：2026年6月 · 支持文字编辑功能 · 点击右上角"编辑模式"按钮</span>
  </div>
</footer>

<script>
let editMode=false,savedData={},editableEls=[];
function loadSaved(){try{const d=sessionStorage.getItem('tau_v2_edits');if(d){savedData=JSON.parse(d);applyEdits();}}catch(e){}}
function applyEdits(){Object.keys(savedData).forEach(id=>{const el=document.querySelector(`[data-eid="${id}"]`);if(el)el.innerHTML=savedData[id];});}
function toggleEditMode(){
  editMode=!editMode;
  const tb=document.getElementById('edit-toolbar'),btn=document.getElementById('edit-toggle-btn');
  if(editMode){makeEditable();tb.classList.add('visible');btn.classList.add('active');btn.innerHTML='<span class="dot"></span>退出编辑';document.body.classList.add('edit-mode');showToast('✏️ 编辑模式开启 — 点击任意文字即可修改');}
  else{disableEditable();tb.classList.remove('visible');btn.classList.remove('active');btn.innerHTML='<span class="dot"></span>编辑模式';document.body.classList.remove('edit-mode');showToast('✓ 已退出编辑模式');}
}
function makeEditable(){
  const sels=['p','h1','h2','h3','h4','blockquote','cite','.hero-badge','.sub','.card h3','.card p','.tl-title','.tl-desc','.tl-year','.mb .l','.rm-ph h4','.rm-ph ul li','.ri h4','.ri p','.ri .mt p','.st','.peer-item blockquote','.peer-item .analysis','.media-card p','td','th','.an-box p','.ft td','.gl-def','.gl-term','.sc-content h4','.sc-content p','.thermal-box p','.prose p','.fd'];
  editableEls=[];
  sels.forEach(sel=>{document.querySelectorAll(sel).forEach((el,i)=>{if(!el.closest('#edit-toolbar')&&!el.closest('#edit-toggle-btn')&&!el.closest('#toast')){if(!el.dataset.eid)el.dataset.eid=`e_${sel.replace(/[^a-z0-9]/g,'_')}_${i}`;el.setAttribute('contenteditable','true');el.classList.add('bk');editableEls.push(el);}});});
}
function disableEditable(){editableEls.forEach(el=>{el.removeAttribute('contenteditable');el.classList.remove('bk');});}
function saveContent(){
  editableEls.forEach(el=>{if(el.dataset.eid)savedData[el.dataset.eid]=el.innerHTML;});
  try{sessionStorage.setItem('tau_v2_edits',JSON.stringify(savedData));showToast('💾 已保存到本地会话！');}catch(e){showToast('⚠️ 保存失败，请导出HTML');}
}
function exportHTML(){
  const wasEditing=editMode;
  if(wasEditing){disableEditable();document.body.classList.remove('edit-mode');document.getElementById('edit-toolbar').classList.remove('visible');}
  const clone=document.documentElement.cloneNode(true);
  ['edit-toolbar','edit-toggle-btn','toast'].forEach(id=>{const el=clone.querySelector('#'+id);if(el)el.remove();});
  clone.querySelectorAll('[contenteditable]').forEach(el=>{el.removeAttribute('contenteditable');el.classList.remove('bk');});
  const html='<!DOCTYPE html>\n'+clone.outerHTML;
  const blob=new Blob([html],{type:'text/html;charset=utf-8'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');a.href=url;a.download=`huawei_tau_law_${new Date().toISOString().slice(0,10)}.html`;a.click();URL.revokeObjectURL(url);
  if(wasEditing){makeEditable();document.body.classList.add('edit-mode');document.getElementById('edit-toolbar').classList.add('visible');}
  showToast('⬇ HTML已导出，包含全部修改内容');
}
function showToast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),3200);}

// Nav active state
const sections=document.querySelectorAll('.section');
const navLinks=document.querySelectorAll('.toc-list a');
const obs=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting){const id=e.target.id;navLinks.forEach(a=>a.classList.toggle('active',a.getAttribute('href')==='#'+id));}});},{threshold:0.25,rootMargin:'-55px 0px -40% 0px'});
sections.forEach(s=>obs.observe(s));

// Hero numbers animation
function animNums(){document.querySelectorAll('.hero-stat .num').forEach(el=>{const txt=el.innerHTML;const m=txt.match(/^([<≈]?)([\d.]+)/);if(!m)return;const pref=m[1],target=parseFloat(m[2]),dec=(m[2].split('.')[1]||'').length,suf=txt.slice(m[0].length);let start=0,step=target/60;const t=setInterval(()=>{start=Math.min(start+step,target);el.innerHTML=pref+start.toFixed(dec)+suf;if(start>=target)clearInterval(t);},16);});}
setTimeout(animNums,400);

loadSaved();
</script>
</body>
</html>
