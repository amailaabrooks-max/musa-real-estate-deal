<title>Investment Deal Room</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=IBM+Plex+Mono:wght@400;500;600&family=IBM+Plex+Sans:wght@400;500;600&display=swap">
<style>
/* Layout concept: one narrow deal-sheet column. A dark green hero carries the three
   profit figures; below it a locked file list and the unlock form; unlocking swaps in
   the full file. Owners get a second view with ranked leads. */
:root{
  --bg:#EEF2EC; --surface:#FFFFFF; --surface-2:#E3EAE1; --ink:#0E2218; --muted:#52645A; --line:#CCD6CB;
  --brand:#0F4A32; --brand-ink:#F3F7F1; --gold:#E3BF55; --gold-soft:#F2E6BC; --gold-ink:#5A4408;
  --hero:#0B3524; --hero-2:#14472F; --hero-ink:#F1F6F2; --hero-muted:#A9C2B4;
  --good:#17794A; --good-bg:#DCEFE4; --warn:#8A5C0E; --warn-bg:#F6E9C8; --bad:#A93329; --bad-bg:#F6DAD6;
  --focus:#1D6B4A; --scrim:rgba(4,10,7,.94); --scrim-ink:#F1F6F2;
  --font-display:'Bricolage Grotesque','Avenir Next','Segoe UI',system-ui,sans-serif;
  --font-body:'IBM Plex Sans','Segoe UI',system-ui,sans-serif;
  --font-mono:'IBM Plex Mono',ui-monospace,Menlo,Consolas,monospace;
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#09130D; --surface:#12201A; --surface-2:#19291F; --ink:#E6EEE8; --muted:#97AB9F; --line:#24382C;
    --brand:#4DAA7E; --brand-ink:#07130C; --gold:#E3BF55; --gold-soft:#3A3115; --gold-ink:#F2E6BC;
    --hero:#0D2A1D; --hero-2:#143826; --hero-ink:#EEF5F0; --hero-muted:#9DB9A9;
    --good:#4CC38A; --good-bg:#12382A; --warn:#E0B04A; --warn-bg:#3A3115; --bad:#EF7B6F; --bad-bg:#3E1D1A;
    --focus:#6CCB9D; color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#09130D; --surface:#12201A; --surface-2:#19291F; --ink:#E6EEE8; --muted:#97AB9F; --line:#24382C;
  --brand:#4DAA7E; --brand-ink:#07130C; --gold:#E3BF55; --gold-soft:#3A3115; --gold-ink:#F2E6BC;
  --hero:#0D2A1D; --hero-2:#143826; --hero-ink:#EEF5F0; --hero-muted:#9DB9A9;
  --good:#4CC38A; --good-bg:#12382A; --warn:#E0B04A; --warn-bg:#3A3115; --bad:#EF7B6F; --bad-bg:#3E1D1A;
  --focus:#6CCB9D; color-scheme:dark;
}
*,*::before,*::after{box-sizing:border-box}
[hidden]{display:none!important}
body{
  background:var(--bg); color:var(--ink); font-family:var(--font-body); font-size:16px; line-height:1.55;
  padding-block:0;
  padding-left:max(16px,env(safe-area-inset-left,0px));
  padding-right:max(16px,env(safe-area-inset-right,0px));
}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--bg);z-index:10}
h1,h2,h3,p,dl,dd,ul,figure{margin:0}
h1,h2,h3{font-family:var(--font-display);text-wrap:balance;line-height:1.1;letter-spacing:-0.01em}
button,input,select,textarea{font:inherit;color:inherit}
:focus-visible{outline:3px solid var(--focus);outline-offset:2px}
.mono{font-family:var(--font-mono);font-variant-numeric:tabular-nums}
.page{max-width:980px;margin:0 auto;display:flex;flex-direction:column;gap:20px;padding-block:16px 56px}
.page > *{min-width:0}

/* top bar */
.topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;flex-wrap:wrap}
.tag{display:inline-flex;align-items:center;gap:8px;font-family:var(--font-mono);font-size:12px;letter-spacing:.08em;text-transform:uppercase;color:var(--muted)}
.tag svg{flex:none}

/* owner bar */
.ownerbar{position:sticky;top:env(safe-area-inset-top,0px);z-index:11;display:flex;gap:8px;flex-wrap:wrap;align-items:center;justify-content:space-between;
  background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:8px 10px}
.ownerbar .label{font-size:13px;color:var(--muted)}
.seg{display:inline-flex;border:1px solid var(--line);border-radius:8px;overflow:hidden}
.seg button{background:transparent;border:0;padding:8px 14px;cursor:pointer;font-weight:500;min-height:40px}
.seg button[aria-pressed="true"]{background:var(--brand);color:var(--brand-ink)}

/* hero */
.hero{background:var(--hero);color:var(--hero-ink);border-radius:14px;padding:clamp(20px,4vw,36px);display:flex;flex-direction:column;gap:22px;
  border-bottom:4px solid var(--gold)}
.hero .eyebrow{font-family:var(--font-mono);font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--gold)}
.hero h1{font-size:clamp(28px,5.2vw,46px);font-weight:800;max-width:18ch}
.stats{display:grid;grid-template-columns:1.25fr 1fr 1fr;gap:12px}
.stat{background:var(--hero-2);border-radius:10px;padding:18px;display:flex;flex-direction:column;gap:6px;min-width:0}
.stat-num{font-family:var(--font-display);font-weight:800;font-size:clamp(34px,6vw,52px);line-height:1;color:var(--gold);font-variant-numeric:tabular-nums;overflow-wrap:anywhere}
.stat.main .stat-num{font-size:clamp(44px,9vw,76px)}
.stat-label{font-weight:600}
.stat-sub{font-size:14px;color:var(--hero-muted)}

/* teaser photos */
.teaser h2,.snap h2{font-size:24px;font-weight:700}
.tgrid{display:grid;gap:8px;margin-top:14px}
.tgrid figure{margin:0;min-width:0;overflow:hidden;border-radius:10px;background:var(--surface-2)}
.tgrid img{width:100%;height:100%;object-fit:cover;display:block}
.tgrid.n1{grid-template-columns:1fr;grid-auto-rows:clamp(200px,38vw,380px)}
.tgrid.n2{grid-template-columns:3fr 2fr;grid-auto-rows:clamp(190px,32vw,320px)}
.tgrid.many{grid-template-columns:repeat(3,minmax(0,1fr));grid-auto-rows:clamp(110px,19vw,190px)}
.tgrid.many figure:first-child{grid-column:span 2;grid-row:span 2}

/* market snapshot */
.snap .lead{color:var(--muted);margin-top:6px;max-width:62ch}
.bars{display:flex;flex-direction:column;gap:10px;margin-top:16px}
.brow{display:grid;grid-template-columns:190px 1fr 76px;gap:12px;align-items:center}
.bl{font-weight:600}
.bt{height:14px;border-radius:99px;background:var(--surface-2);overflow:hidden}
.bt i{display:block;height:100%;background:var(--brand);border-radius:99px}
.bt i.alt{background:var(--muted)}
.brow b{font-family:var(--font-mono);font-variant-numeric:tabular-nums;text-align:right}
.pts{list-style:none;padding:0;margin:20px 0 0;display:flex;flex-direction:column;gap:14px}
.pts li{border-top:1px solid var(--line);padding-top:12px}
.pts .src{font-size:13px;color:var(--muted);margin-top:4px}
.pts a,.snap .foot a{color:var(--brand);text-decoration:underline;text-underline-offset:2px}
.snap .foot{font-size:13px;color:var(--muted);margin-top:16px;max-width:75ch}

/* locked list */
.card{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:clamp(16px,3vw,26px)}
.locked h2,.gate h2{font-size:24px;font-weight:700}
.locked .lead,.gate .lead{color:var(--muted);margin-top:6px;max-width:60ch}
.locks{list-style:none;padding:0;margin:16px 0 0;display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}
.locks li{display:flex;align-items:center;gap:12px;border:1px dashed var(--line);border-radius:10px;padding:12px;min-width:0}
.locks svg{flex:none;color:var(--muted)}
.locks .t{display:flex;flex-direction:column;min-width:0}
.locks .t b{font-weight:600}
.locks .blur{font-family:var(--font-mono);font-size:13px;color:var(--muted);filter:blur(5px);user-select:none;white-space:nowrap;overflow:hidden}

/* gate form */
.gate{border-color:var(--brand);border-width:2px}
form.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px;margin-top:16px}
.field{display:flex;flex-direction:column;gap:6px;min-width:0}
.field.full{grid-column:1/-1}
.field label{font-weight:600;font-size:14px}
.field input,.field select,.field textarea{background:var(--bg);border:1px solid var(--line);border-radius:8px;padding:11px 12px;min-height:46px;width:100%}
.field textarea{min-height:84px;resize:vertical}
.field input[aria-invalid="true"]{border-color:var(--bad)}
.err{color:var(--bad);font-size:13px;min-height:0}
.field .check{display:flex;gap:10px;align-items:flex-start;font-size:14px;font-weight:400;color:var(--muted)}
.check input{margin-top:3px;width:18px;height:18px;flex:none}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;border-radius:8px;border:1px solid var(--brand);background:var(--brand);color:var(--brand-ink);
  padding:12px 20px;min-height:46px;font-weight:600;cursor:pointer;text-decoration:none}
.btn:hover{filter:brightness(1.08)}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--line)}
.btn.ghost:hover{border-color:var(--brand)}
.btn.small{min-height:36px;padding:6px 12px;font-size:14px}
.fine{font-size:13px;color:var(--muted)}

/* private file */
.private{display:flex;flex-direction:column;gap:20px}
.notice{background:var(--warn-bg);color:var(--ink);border:1px solid var(--warn);border-radius:10px;padding:12px 14px;font-size:15px}
.property{display:grid;grid-template-columns:1.1fr 1fr;gap:clamp(16px,3vw,28px);align-items:start}
.property img{width:100%;aspect-ratio:588/260;object-fit:cover;border-radius:10px;display:block}
.gallery{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:8px;margin-top:8px}
.gallery img{aspect-ratio:4/3}
.eyebrow-dark{font-family:var(--font-mono);font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--muted)}
.address{font-size:clamp(24px,4vw,34px);font-weight:700;margin-top:6px;overflow-wrap:anywhere}
.btn-row{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}
.facts{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px 16px;margin-top:18px}
.facts div{border-top:1px solid var(--line);padding-top:8px}
.facts dt{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:.06em}
.facts dd{font-weight:600}

.tabs{display:flex;gap:8px;flex-wrap:wrap}
.tab{background:transparent;border:1px solid var(--line);border-radius:999px;padding:9px 18px;font-weight:600;cursor:pointer;min-height:42px}
.tab[aria-selected="true"]{background:var(--brand);color:var(--brand-ink);border-color:var(--brand)}
.panel{margin-top:16px;display:flex;flex-direction:column;gap:18px}
.two{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
.two > *{min-width:0}
.tbl-wrap{overflow-x:auto}
table{border-collapse:collapse;width:100%}
caption{text-align:left;font-weight:600;padding-bottom:8px;font-family:var(--font-display);font-size:18px}
th,td{padding:9px 0;border-bottom:1px solid var(--line);text-align:left;font-weight:400}
td:last-child{text-align:right;font-family:var(--font-mono);font-variant-numeric:tabular-nums;white-space:nowrap}
tr.total td{font-weight:600;border-bottom:2px solid var(--brand)}
.results{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px}
.res{background:var(--surface-2);border-radius:10px;padding:14px;min-width:0}
.res .n{font-family:var(--font-display);font-weight:800;font-size:clamp(22px,4vw,32px);font-variant-numeric:tabular-nums;overflow-wrap:anywhere}
.res .l{font-size:13px;color:var(--muted)}
.slider{display:flex;flex-direction:column;gap:8px}
.slider .row{display:flex;justify-content:space-between;gap:12px;align-items:baseline;flex-wrap:wrap}
input[type=range]{width:100%;accent-color:var(--brand);min-height:32px}
.big-profit{background:var(--surface-2);border-radius:10px;padding:18px}
.big-profit .n{font-family:var(--font-display);font-weight:800;font-size:clamp(34px,6vw,52px);font-variant-numeric:tabular-nums}

.comps{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin-top:14px}
.comp{border:1px solid var(--line);border-radius:10px;overflow:hidden;min-width:0}
.comp img{width:100%;aspect-ratio:340/156;object-fit:cover;display:block}
.comp div{padding:10px 12px}
.comp b{font-family:var(--font-mono);font-size:18px}
.comp span.addr{color:var(--ink);font-weight:600;overflow-wrap:anywhere;margin:2px 0 4px}
.comp span{display:block;font-size:14px;color:var(--muted)}
.checks{list-style:none;padding:0;margin:14px 0 0;display:flex;flex-direction:column;gap:10px}
.checks li{display:flex;gap:10px;align-items:flex-start}
.checks svg{flex:none;margin-top:3px;color:var(--good)}
.status{margin-top:12px;font-weight:600}

/* dashboard */
.dash{display:flex;flex-direction:column;gap:16px}
.sumrow{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px}
.sum{background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:14px;min-width:0}
.sum .n{font-family:var(--font-display);font-weight:800;font-size:30px;font-variant-numeric:tabular-nums}
.sum .l{font-size:13px;color:var(--muted)}
.lead-card{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:16px;display:flex;flex-direction:column;gap:14px;min-width:0}
.lead-top{display:flex;gap:14px;align-items:center;justify-content:space-between;flex-wrap:wrap}
.lead-name{font-family:var(--font-display);font-weight:700;font-size:22px;overflow-wrap:anywhere}
.badge{display:inline-flex;align-items:center;gap:8px;border-radius:999px;padding:4px 12px;font-weight:700;font-size:14px}
.badge.hot{background:var(--good-bg);color:var(--good)}
.badge.warm{background:var(--warn-bg);color:var(--warn)}
.badge.lukewarm{background:var(--surface-2);color:var(--ink)}
.badge.cold{background:var(--bad-bg);color:var(--bad)}
.scorebar{height:8px;border-radius:99px;background:var(--surface-2);overflow:hidden}
.scorebar i{display:block;height:100%;background:var(--brand)}
.contacts{display:flex;flex-wrap:wrap;gap:8px 18px;align-items:center}
.contacts span{display:inline-flex;gap:8px;align-items:center;overflow-wrap:anywhere;min-width:0}
.metrics{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:10px}
.metrics div{border-top:1px solid var(--line);padding-top:6px}
.metrics dt{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:.06em}
.metrics dd{font-family:var(--font-mono);font-weight:500;font-variant-numeric:tabular-nums}
.sec-bars{display:flex;flex-direction:column;gap:6px}
.sec-bars .r{display:grid;grid-template-columns:110px 1fr 56px;gap:8px;align-items:center;font-size:14px}
.sec-bars .bar{height:8px;background:var(--surface-2);border-radius:99px;overflow:hidden}
.sec-bars .bar i{display:block;height:100%;background:var(--brand)}
.chips{display:flex;flex-wrap:wrap;gap:6px}
.chip{background:var(--surface-2);border-radius:999px;padding:3px 10px;font-size:13px}
.parts{display:grid;grid-template-columns:repeat(auto-fit,minmax(110px,1fr));gap:8px;font-size:13px;color:var(--muted)}
.parts b{display:block;color:var(--ink);font-family:var(--font-mono);font-weight:500}
.empty{border:1px dashed var(--line);border-radius:12px;padding:28px;text-align:center;color:var(--muted)}
details.note{background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:12px 14px}
details.note summary{cursor:pointer;font-weight:600}
details.note p{margin-top:8px;color:var(--muted);font-size:15px}
.legal{font-size:13px;color:var(--muted);max-width:75ch}

/* collapsible market info */
.snap summary{list-style:none;cursor:pointer;display:flex;align-items:center;justify-content:space-between;gap:12px;min-height:44px}
.snap summary::-webkit-details-marker{display:none}
.snap summary .sn{display:block;font-family:var(--font-display);font-size:22px;font-weight:700;line-height:1.15;margin-top:2px}
.snap summary svg{flex:none;transition:transform .2s}
.snap[open] summary svg{transform:rotate(180deg)}
.snap .snapbody{margin-top:10px}

/* photos and viewer */
.lbitem{display:block;width:100%;height:100%;padding:0;border:0;background:none;cursor:zoom-in;border-radius:inherit;overflow:hidden}
.hero-photo{display:flex;flex-direction:column;gap:8px;min-width:0}
.hero-photo .main-photo{border-radius:10px;overflow:hidden}
.thumbs{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:6px}
.thumbs .lbitem{aspect-ratio:4/3;border-radius:8px}
.thumbs .lbitem img{width:100%;height:100%;aspect-ratio:auto;object-fit:cover}
.viewall{align-self:flex-start}
.lb{position:fixed;inset:0;z-index:50;background:var(--scrim);color:var(--scrim-ink);display:flex;flex-direction:column;
  padding:env(safe-area-inset-top,0px) max(12px,env(safe-area-inset-right,0px)) env(safe-area-inset-bottom,0px) max(12px,env(safe-area-inset-left,0px))}
.lb-bar{display:flex;justify-content:space-between;align-items:center;padding:10px 0}
.lb-btn{background:transparent;border:1px solid currentColor;color:inherit;border-radius:8px;padding:8px 16px;min-height:44px;cursor:pointer;font-weight:600}
.lb-stage{flex:1;min-height:0;display:flex;align-items:center;justify-content:center;position:relative}
.lb-stage img{max-width:100%;max-height:100%;object-fit:contain;border-radius:6px}
.lb-nav{position:absolute;top:50%;transform:translateY(-50%);width:48px;height:48px;border-radius:50%;border:1px solid currentColor;background:var(--scrim);color:inherit;font-size:26px;line-height:1;cursor:pointer}
.lb-nav.prev{left:4px}.lb-nav.next{right:4px}
.lb-hint{text-align:center;font-size:13px;opacity:.75;padding:10px 0}

/* systems checklist */
.sys{list-style:none;padding:0;margin:14px 0 0;display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px}
.sys li{display:flex;align-items:center;gap:12px;border:1px solid var(--line);border-radius:10px;padding:12px;min-width:0}
.sys .ic{flex:none;width:30px;height:30px;border-radius:50%;display:inline-flex;align-items:center;justify-content:center;background:var(--surface-2);color:var(--ink)}
.sys .nm{font-weight:600;display:block}
.sys .st{display:block;font-size:14px;color:var(--good)}
.sys li.fix .ic{background:var(--warn-bg);color:var(--warn)}
.sys li.fix .st{color:var(--warn)}

/* investment summary */
.sumhead{background:var(--surface-2);border-radius:10px;padding:16px}
.sumhead .n{font-family:var(--font-display);font-weight:800;font-size:clamp(32px,6vw,48px);font-variant-numeric:tabular-nums;line-height:1.05}
.sumhead .l{font-size:14px;color:var(--muted);margin-top:4px}
.summary .checks{margin-top:0}

/* offer */
.flag{display:inline-flex;align-items:center;gap:8px;align-self:flex-start;background:var(--gold);color:#2B2005;border-radius:999px;padding:6px 14px;font-weight:700;font-size:14px}
.offerflag{background:var(--gold-soft);color:var(--gold-ink);border:1px solid var(--gold);border-radius:10px;padding:12px 14px;margin-top:12px;font-weight:600}
.field .hint{font-size:13px;color:var(--muted)}
.field .pre{position:relative}
.dep{background:var(--surface-2);border-radius:10px;padding:12px 14px;font-size:15px}

@media (max-width:760px){
  .stats{grid-template-columns:1fr}
  .property,.two{grid-template-columns:1fr}
  .comps{grid-template-columns:1fr}
  .results{grid-template-columns:1fr}
  .locks,form.fields{grid-template-columns:1fr}
  .tgrid.n2{grid-template-columns:1fr 1fr;grid-auto-rows:170px}
  .thumbs{grid-template-columns:repeat(3,minmax(0,1fr))}
  .sys{grid-template-columns:1fr}
  .brow{grid-template-columns:1fr auto}
  .brow .bt{grid-column:1/-1;order:3}
  .sumrow{grid-template-columns:repeat(2,minmax(0,1fr))}
  .sec-bars .r{grid-template-columns:90px 1fr 48px}
}
@media (prefers-reduced-motion:reduce){*{scroll-behavior:auto!important;transition:none!important}}
</style>
