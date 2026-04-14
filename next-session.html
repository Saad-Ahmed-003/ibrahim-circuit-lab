<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Session 03 — Power, Inductors, Diodes & the Transistor</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #09111f;
    --card: #0f1c30;
    --card2: #122035;
    --border: #1a2e4a;
    --green: #4ade80;
    --green-dim: #22863a;
    --amber: #f5a523;
    --blue: #38bdf8;
    --red: #f87171;
    --purple: #c084fc;
    --teal: #2dd4bf;
    --pink: #f472b6;
    --orange: #fb923c;
    --text: #dde6f0;
    --muted: #6b82a0;
    --white: #ffffff;
  }
  * { margin:0; padding:0; box-sizing:border-box; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Nunito', sans-serif;
    font-size: 17px;
    line-height: 1.8;
    min-height: 100vh;
  }

  /* ── TOP HEADER ── */
  .top-bar {
    background: linear-gradient(135deg, #0a1a10 0%, #09111f 60%, #0d1a0a 100%);
    border-bottom: 2px solid var(--green);
    padding: 2.5rem 3rem;
    position: relative;
    overflow: hidden;
  }
  .top-bar::before {
    content: '03';
    font-family: 'Orbitron', monospace;
    font-size: 13rem;
    font-weight: 900;
    color: rgba(74,222,128,0.04);
    position: absolute;
    right: 1rem;
    top: -2rem;
    line-height: 1;
    pointer-events: none;
  }
  .top-bar::after {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse at 80% 50%, rgba(74,222,128,0.04) 0%, transparent 70%);
    pointer-events: none;
  }
  .session-label {
    font-family: 'Orbitron', monospace;
    font-size: 0.68rem;
    font-weight: 700;
    letter-spacing: 0.25em;
    color: var(--green);
    text-transform: uppercase;
    margin-bottom: 0.5rem;
  }
  .session-title {
    font-family: 'Orbitron', monospace;
    font-size: 2rem;
    font-weight: 900;
    color: var(--white);
    max-width: 720px;
    line-height: 1.15;
  }
  .session-title span { color: var(--green); }
  .session-meta { margin-top: 1.2rem; display: flex; gap: 1.5rem; flex-wrap: wrap; }
  .meta-pill {
    background: rgba(74,222,128,0.1);
    border: 1px solid rgba(74,222,128,0.3);
    border-radius: 999px;
    padding: 0.3rem 1rem;
    font-size: 0.82rem;
    font-weight: 700;
    color: var(--green);
    letter-spacing: 0.04em;
  }

  /* ── LAYOUT ── */
  .content { max-width: 880px; margin: 0 auto; padding: 3rem 2rem 6rem; }

  /* ── SECTION HEADERS ── */
  .section { margin-bottom: 4rem; }
  .section-header { display: flex; align-items: center; gap: 1rem; margin-bottom: 1.8rem; }
  .section-num {
    background: var(--green);
    color: var(--bg);
    font-family: 'Orbitron', monospace;
    font-weight: 900;
    font-size: 0.72rem;
    width: 2.1rem; height: 2.1rem;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .section-title {
    font-family: 'Orbitron', monospace;
    font-size: 1.05rem;
    font-weight: 700;
    color: var(--white);
    letter-spacing: 0.03em;
  }
  .subsection { margin: 2rem 0 1rem; }
  .subsection-title {
    font-family: 'Orbitron', monospace;
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    border-left: 3px solid var(--green);
    padding-left: 0.8rem;
    margin-bottom: 0.8rem;
    color: var(--green);
  }
  .subsection-title.amber  { color: var(--amber);  border-left-color: var(--amber);  }
  .subsection-title.blue   { color: var(--blue);   border-left-color: var(--blue);   }
  .subsection-title.red    { color: var(--red);    border-left-color: var(--red);    }
  .subsection-title.purple { color: var(--purple); border-left-color: var(--purple); }
  .subsection-title.orange { color: var(--orange); border-left-color: var(--orange); }
  .subsection-title.teal   { color: var(--teal);   border-left-color: var(--teal);   }

  /* ── TEXT ── */
  p { margin-bottom: 1.1rem; }
  strong { color: var(--white); font-weight: 800; }
  em { color: var(--green); font-style: normal; font-weight: 700; }
  .hl  { background: rgba(74,222,128,0.12);  border-radius:4px; padding:1px 5px; color:var(--green);  font-weight:700; }
  .hla { background: rgba(245,165,35,0.14);  border-radius:4px; padding:1px 5px; color:var(--amber);  font-weight:700; }
  .hlb { background: rgba(56,189,248,0.12);  border-radius:4px; padding:1px 5px; color:var(--blue);   font-weight:700; }
  .hlr { background: rgba(248,113,113,0.12); border-radius:4px; padding:1px 5px; color:var(--red);    font-weight:700; }
  .hlp { background: rgba(192,132,252,0.12); border-radius:4px; padding:1px 5px; color:var(--purple); font-weight:700; }
  .hlo { background: rgba(251,146,60,0.12);  border-radius:4px; padding:1px 5px; color:var(--orange); font-weight:700; }

  /* ── CALLOUTS ── */
  .callout { border-radius:12px; padding:1.3rem 1.6rem; margin:1.8rem 0; border-left:4px solid; }
  .callout.green  { background:rgba(74,222,128,0.06);  border-color:var(--green);  }
  .callout.amber  { background:rgba(245,165,35,0.07);  border-color:var(--amber);  }
  .callout.blue   { background:rgba(56,189,248,0.06);  border-color:var(--blue);   }
  .callout.red    { background:rgba(248,113,113,0.07); border-color:var(--red);    }
  .callout.teal   { background:rgba(45,212,191,0.06);  border-color:var(--teal);   }
  .callout.purple { background:rgba(192,132,252,0.06); border-color:var(--purple); }
  .callout.orange { background:rgba(251,146,60,0.07);  border-color:var(--orange); }
  .callout-title { font-weight:800; font-size:0.82rem; letter-spacing:0.09em; text-transform:uppercase; margin-bottom:0.6rem; }
  .callout.green  .callout-title { color:var(--green);  }
  .callout.amber  .callout-title { color:var(--amber);  }
  .callout.blue   .callout-title { color:var(--blue);   }
  .callout.red    .callout-title { color:var(--red);    }
  .callout.teal   .callout-title { color:var(--teal);   }
  .callout.purple .callout-title { color:var(--purple); }
  .callout.orange .callout-title { color:var(--orange); }

  /* ── DIAGRAMS ── */
  .diagram-box {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 1.8rem 1.5rem 1.3rem;
    margin: 2rem 0;
    text-align: center;
  }
  .diagram-box svg { max-width:100%; height:auto; }
  .diagram-caption { font-size:0.8rem; color:var(--muted); margin-top:0.9rem; font-style:italic; line-height:1.5; }

  /* ── STEPS ── */
  .steps { counter-reset:step; list-style:none; margin:1.2rem 0; }
  .steps li { counter-increment:step; display:flex; gap:1.1rem; margin-bottom:1.1rem; align-items:flex-start; }
  .steps li::before {
    content: counter(step);
    background: var(--card2);
    border: 2px solid var(--green);
    color: var(--green);
    font-family: 'Orbitron', monospace;
    font-weight: 900; font-size: 0.72rem;
    width: 2.1rem; height: 2.1rem;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0; margin-top: 0.1rem;
  }
  .steps li span { flex:1; }

  /* ── NEEDS GRID ── */
  .needs-grid { display:flex; flex-wrap:wrap; gap:0.6rem; margin:1.2rem 0; }
  .need-item {
    background:var(--card); border:1px solid var(--border); border-radius:8px;
    padding:0.45rem 1.1rem; font-size:0.88rem; font-weight:700; color:var(--text);
    display:flex; align-items:center; gap:0.5rem;
  }
  .need-item .dot { width:8px; height:8px; background:var(--green); border-radius:50%; flex-shrink:0; }
  .need-item .dot.new { background:var(--orange); }

  /* ── FORMULA CARDS ── */
  .formula-grid-3 { display:grid; grid-template-columns:repeat(3,1fr); gap:1rem; margin:1.5rem 0; }
  @media(max-width:560px){ .formula-grid-3 { grid-template-columns:1fr; } }
  .formula-card {
    background:var(--card); border:1px solid var(--border);
    border-radius:13px; padding:1.4rem; text-align:center;
    position:relative; overflow:hidden;
    transition:border-color 0.2s, transform 0.2s;
  }
  .formula-card:hover { transform:translateY(-2px); }
  .formula-card::before { content:''; position:absolute; top:0; left:0; right:0; height:3px; }
  .formula-card.p::before  { background:var(--green); }
  .formula-card.p2::before { background:var(--orange); }
  .formula-card.p3::before { background:var(--teal); }
  .formula-equation { font-family:'Orbitron',monospace; font-size:1.2rem; font-weight:900; margin:0.5rem 0; }
  .formula-card.p  .formula-equation { color:var(--green); }
  .formula-card.p2 .formula-equation { color:var(--orange); }
  .formula-card.p3 .formula-equation { color:var(--teal); }
  .formula-label { font-size:0.82rem; color:var(--muted); margin-top:0.4rem; }
  .formula-card-title { font-family:'Orbitron',monospace; font-size:0.7rem; font-weight:700; letter-spacing:0.08em; color:var(--muted); margin-bottom:0.3rem; }

  /* ── INTERACTIVE CALCULATOR ── */
  .calc-box { background:var(--card); border:1px solid var(--border); border-radius:16px; padding:2rem; margin:2rem 0; }
  .calc-title { font-family:'Orbitron',monospace; font-size:0.82rem; font-weight:700; color:var(--green); letter-spacing:0.1em; text-transform:uppercase; margin-bottom:1.4rem; }
  .calc-inputs { display:flex; gap:1rem; flex-wrap:wrap; align-items:flex-end; margin-bottom:1.2rem; }
  .calc-field { display:flex; flex-direction:column; gap:0.4rem; flex:1; min-width:110px; }
  .calc-field label { font-family:'Orbitron',monospace; font-size:0.62rem; font-weight:700; letter-spacing:0.1em; text-transform:uppercase; }
  .calc-field.p  label { color:var(--green); }
  .calc-field.v  label { color:var(--amber); }
  .calc-field.i  label { color:var(--blue); }
  .calc-field.r  label { color:var(--red); }
  .calc-field input {
    background:var(--card2); border:1px solid var(--border); border-radius:8px;
    color:var(--white); font-family:'Orbitron',monospace; font-size:0.95rem; font-weight:700;
    padding:0.6rem 0.8rem; width:100%; outline:none; transition:border-color 0.2s;
  }
  .calc-field.p  input:focus { border-color:var(--green); }
  .calc-field.v  input:focus { border-color:var(--amber); }
  .calc-field.i  input:focus { border-color:var(--blue); }
  .calc-field.r  input:focus { border-color:var(--red); }
  .calc-field input.solved { border-color:var(--green); background:rgba(74,222,128,0.06); color:var(--green); }
  .calc-field input::placeholder { color:var(--muted); font-size:0.78rem; }
  .calc-unit { font-size:0.75rem; color:var(--muted); text-align:center; margin-top:0.2rem; }
  .calc-btn-row { display:flex; gap:0.6rem; align-self:flex-end; }
  .calc-btn {
    background:var(--green); border:none; border-radius:8px; color:var(--bg);
    font-family:'Orbitron',monospace; font-size:0.75rem; font-weight:900;
    letter-spacing:0.08em; padding:0.7rem 1.4rem; cursor:pointer;
    transition:opacity 0.2s, transform 0.1s;
  }
  .calc-btn:hover { opacity:0.85; transform:translateY(-1px); }
  .calc-btn.clear { background:transparent; border:1px solid var(--border); color:var(--muted); }
  .calc-result { background:var(--card2); border:1px solid rgba(74,222,128,0.3); border-radius:10px; padding:1rem 1.3rem; display:none; align-items:center; gap:1rem; flex-wrap:wrap; }
  .calc-result.show { display:flex; }
  .calc-result-value { font-family:'Orbitron',monospace; font-size:1.6rem; font-weight:900; color:var(--green); }
  .calc-result-label { font-size:0.88rem; color:var(--muted); }
  .calc-result-formula { font-family:'Orbitron',monospace; font-size:0.8rem; color:var(--muted); margin-left:auto; }
  .calc-error { font-family:'Orbitron',monospace; font-size:0.78rem; color:var(--red); padding:0.6rem 0; display:none; }
  .calc-error.show { display:block; }

  /* ── MINI EXPERIMENT ── */
  .mini-exp {
    background:linear-gradient(135deg, rgba(74,222,128,0.07), rgba(74,222,128,0.01));
    border:2px solid var(--green); border-radius:16px; padding:1.8rem; margin:2.5rem 0;
    position:relative; overflow:hidden;
  }
  .mini-exp::after { content:'🧪'; position:absolute; right:1.5rem; top:1.2rem; font-size:2.8rem; opacity:0.12; }
  .mini-exp-badge {
    display:inline-flex; align-items:center; gap:0.5rem;
    background:rgba(74,222,128,0.15); border:1px solid rgba(74,222,128,0.4); border-radius:999px;
    padding:0.2rem 0.9rem; font-family:'Orbitron',monospace; font-size:0.62rem; font-weight:700;
    color:var(--green); letter-spacing:0.15em; text-transform:uppercase; margin-bottom:0.7rem;
  }
  .mini-exp-title { font-family:'Orbitron',monospace; font-size:1rem; font-weight:900; color:var(--white); margin-bottom:0.8rem; }
  .mini-exp-steps { counter-reset:mstep; list-style:none; margin:0.8rem 0; }
  .mini-exp-steps li { counter-increment:mstep; display:flex; gap:0.9rem; margin-bottom:0.9rem; align-items:flex-start; font-size:0.95rem; }
  .mini-exp-steps li::before {
    content:counter(mstep);
    background:rgba(74,222,128,0.15); border:2px solid var(--green);
    color:var(--green); font-family:'Orbitron',monospace; font-weight:900; font-size:0.68rem;
    width:1.9rem; height:1.9rem; border-radius:50%;
    display:flex; align-items:center; justify-content:center; flex-shrink:0; margin-top:0.1rem;
  }
  .mini-exp-steps li span { flex:1; }
  .observe-box { background:rgba(74,222,128,0.06); border:1px solid rgba(74,222,128,0.25); border-radius:10px; padding:1rem 1.2rem; margin-top:1.2rem; }
  .observe-title { font-family:'Orbitron',monospace; font-size:0.65rem; font-weight:700; letter-spacing:0.12em; text-transform:uppercase; color:var(--green); margin-bottom:0.5rem; }

  /* ── MATHS WORKSHEET ── */
  .math-ws { background:var(--card2); border:1px solid var(--border); border-radius:14px; padding:1.6rem; margin:1.8rem 0; }
  .math-ws-title { font-family:'Orbitron',monospace; font-size:0.72rem; font-weight:700; letter-spacing:0.1em; color:var(--green); text-transform:uppercase; margin-bottom:1.2rem; }
  .math-problem { background:var(--card); border:1px solid var(--border); border-radius:10px; padding:1.1rem 1.3rem; margin-bottom:0.9rem; display:flex; gap:1rem; align-items:flex-start; flex-wrap:wrap; }
  .math-problem-num { font-family:'Orbitron',monospace; font-size:0.72rem; font-weight:900; color:var(--green); background:rgba(74,222,128,0.12); border-radius:6px; padding:0.25rem 0.55rem; flex-shrink:0; margin-top:0.2rem; }
  .math-problem-text { flex:1; font-size:0.94rem; min-width:200px; }
  .math-problem-text strong { color:var(--green); }
  .math-answer-wrap { display:flex; align-items:center; gap:0.5rem; flex-wrap:wrap; margin-top:0.4rem; width:100%; }
  .math-input { background:transparent; border:none; border-bottom:2px dashed var(--border); color:var(--green); font-family:'Orbitron',monospace; font-size:0.88rem; font-weight:700; width:110px; outline:none; padding:3px 5px; text-align:center; transition:border-bottom-color 0.2s; }
  .math-input:focus { border-bottom-color:var(--green); }
  .math-input.correct { border-bottom-color:var(--green); background:rgba(74,222,128,0.06); border-radius:4px; }
  .math-input.wrong   { border-bottom-color:var(--red);   background:rgba(248,113,113,0.06); border-radius:4px; }
  .math-unit { font-size:0.8rem; color:var(--muted); }
  .math-check-btn { background:rgba(74,222,128,0.15); border:1px solid rgba(74,222,128,0.4); border-radius:6px; color:var(--green); font-family:'Orbitron',monospace; font-size:0.62rem; font-weight:700; padding:0.3rem 0.7rem; cursor:pointer; letter-spacing:0.08em; transition:background 0.2s; }
  .math-check-btn:hover { background:rgba(74,222,128,0.25); }
  .math-feedback { font-size:0.82rem; margin-top:0.5rem; padding:0.3rem 0.6rem; border-radius:6px; display:none; width:100%; }
  .math-feedback.correct { color:var(--green); background:rgba(74,222,128,0.08); display:block; }
  .math-feedback.wrong   { color:var(--red);   background:rgba(248,113,113,0.08); display:block; }

  /* ── TRANSISTOR ANATOMY ── */
  .transistor-pins {
    display:grid; grid-template-columns:repeat(3,1fr); gap:1rem; margin:1.5rem 0;
  }
  .pin-card { background:var(--card); border:1px solid var(--border); border-radius:12px; padding:1.2rem; text-align:center; }
  .pin-card::before { content:''; display:block; width:3px; height:3px; margin:0 auto 0.8rem; border-radius:50%; }
  .pin-card.base     { border-top:3px solid var(--orange); }
  .pin-card.collector{ border-top:3px solid var(--red); }
  .pin-card.emitter  { border-top:3px solid var(--blue); }
  .pin-name { font-family:'Orbitron',monospace; font-size:0.88rem; font-weight:900; margin-bottom:0.2rem; }
  .pin-card.base      .pin-name { color:var(--orange); }
  .pin-card.collector .pin-name { color:var(--red); }
  .pin-card.emitter   .pin-name { color:var(--blue); }
  .pin-symbol { font-family:'Orbitron',monospace; font-size:0.72rem; color:var(--muted); margin-bottom:0.7rem; }
  .pin-desc { font-size:0.88rem; line-height:1.55; }

  /* ── COMPARISON TABLE ── */
  .compare-table { width:100%; border-collapse:collapse; margin:1.5rem 0; }
  .compare-table th { font-family:'Orbitron',monospace; font-size:0.66rem; letter-spacing:0.1em; color:var(--muted); text-transform:uppercase; padding:0.7rem 1rem; text-align:left; border-bottom:1px solid var(--border); }
  .compare-table td { padding:0.6rem 1rem; font-size:0.9rem; border-bottom:1px solid rgba(26,46,74,0.6); vertical-align:middle; }
  .compare-table tr:last-child td { border-bottom:none; }
  .compare-table .row-head { font-weight:800; color:var(--white); width:28%; }
  .compare-table .good { color:var(--green); font-weight:700; }
  .compare-table .bad  { color:var(--red);   font-weight:700; }
  .compare-table .neutral { color:var(--amber); font-weight:700; }

  /* ── TRANSISTOR SWITCH DIAGRAM ── */
  .exp-table { width:100%; border-collapse:collapse; margin:1rem 0; }
  .exp-table th { font-family:'Orbitron',monospace; font-size:0.65rem; letter-spacing:0.1em; color:var(--muted); text-transform:uppercase; padding:0.6rem 0.8rem; text-align:left; border-bottom:1px solid var(--border); }
  .exp-table td { padding:0.55rem 0.8rem; font-size:0.9rem; border-bottom:1px solid rgba(26,46,74,0.6); vertical-align:middle; }
  .exp-table td input { background:transparent; border:none; border-bottom:1px dashed var(--border); color:var(--green); font-family:'Orbitron',monospace; font-size:0.8rem; width:110px; outline:none; padding:2px 4px; }
  .exp-table td input:focus { border-bottom-color:var(--green); }
  .exp-table .row-label { font-weight:800; color:var(--text); }

  /* ── PREDICT BOX ── */
  .predict-box { background:rgba(74,222,128,0.04); border:1px solid rgba(74,222,128,0.2); border-radius:10px; padding:1.1rem 1.3rem; margin:1.2rem 0; }
  .predict-title { font-family:'Orbitron',monospace; font-size:0.65rem; font-weight:700; letter-spacing:0.12em; text-transform:uppercase; color:var(--green); margin-bottom:0.6rem; }
  .predict-input { background:transparent; border:none; border-bottom:1px dashed rgba(74,222,128,0.4); color:var(--green); font-family:'Nunito',sans-serif; font-size:0.92rem; font-weight:700; width:90px; outline:none; padding:3px 4px; }
  .predict-input:focus { border-bottom-color:var(--green); }

  /* ── DIODE IV CHART ── */
  .diode-region { display:grid; grid-template-columns:1fr 1fr; gap:1rem; margin:1.5rem 0; }
  @media(max-width:500px){ .diode-region { grid-template-columns:1fr; } }
  .region-card { background:var(--card); border:1px solid var(--border); border-radius:12px; padding:1.2rem; }
  .region-card::before { content:''; display:block; height:3px; border-radius:2px; margin-bottom:0.9rem; }
  .region-card.forward::before  { background:var(--green); }
  .region-card.reverse::before  { background:var(--red); }
  .region-card.breakdown::before{ background:var(--purple); }
  .region-card.ideal::before    { background:var(--amber); }
  .region-title { font-family:'Orbitron',monospace; font-size:0.78rem; font-weight:900; margin-bottom:0.5rem; }
  .region-card.forward   .region-title { color:var(--green); }
  .region-card.reverse   .region-title { color:var(--red); }
  .region-card.breakdown .region-title { color:var(--purple); }
  .region-card.ideal     .region-title { color:var(--amber); }
  .region-card p { font-size:0.9rem; margin:0; }

  /* ── CHALLENGE ── */
  .challenge {
    background:linear-gradient(135deg, rgba(74,222,128,0.08), rgba(74,222,128,0.01));
    border:2px solid var(--green); border-radius:18px; padding:2.2rem;
    margin-top:3.5rem; position:relative; overflow:hidden;
  }
  .challenge::before { content:'⚡'; position:absolute; right:1.5rem; top:1rem; font-size:4rem; opacity:0.08; }
  .challenge-label { font-family:'Orbitron',monospace; font-size:0.62rem; letter-spacing:0.2em; color:var(--green); font-weight:700; margin-bottom:0.5rem; text-transform:uppercase; }
  .challenge-title { font-family:'Orbitron',monospace; font-size:1.2rem; font-weight:900; color:var(--white); margin-bottom:1.2rem; }

  /* ── FOOTER ── */
  .session-footer { margin-top:3.5rem; border-top:1px solid var(--border); padding-top:2.2rem; }
  .footer-title { font-family:'Orbitron',monospace; font-size:0.68rem; letter-spacing:0.15em; color:var(--muted); text-transform:uppercase; margin-bottom:1.1rem; }
  .learned-grid { display:grid; grid-template-columns:repeat(auto-fit, minmax(195px,1fr)); gap:0.8rem; }
  .learned-item { background:var(--card); border:1px solid var(--border); border-radius:9px; padding:0.75rem 1rem; font-size:0.86rem; font-weight:700; color:var(--text); display:flex; align-items:center; gap:0.65rem; }
  .learned-item::before { content:'✓'; color:var(--green); font-weight:900; }
  .prog-bar { display:flex; gap:0.5rem; margin-top:1.8rem; }
  .prog-dot { height:6px; border-radius:3px; flex:1; }
  .prog-dot.done   { background:var(--amber); }
  .prog-dot.done2  { background:var(--blue); }
  .prog-dot.active { background:var(--green); }
  .prog-dot.future { background:var(--border); }

  /* ── INDUCTOR COMPARE ── */
  .rlc-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:1rem; margin:1.5rem 0; }
  @media(max-width:560px){ .rlc-grid { grid-template-columns:1fr; } }
  .rlc-card { background:var(--card); border:1px solid var(--border); border-radius:13px; padding:1.3rem; text-align:center; position:relative; overflow:hidden; }
  .rlc-card::before { content:''; position:absolute; top:0; left:0; right:0; height:3px; }
  .rlc-card.r::before { background:var(--red); }
  .rlc-card.c::before { background:var(--purple); }
  .rlc-card.l::before { background:var(--teal); }
  .rlc-symbol { font-family:'Orbitron',monospace; font-size:2rem; font-weight:900; margin:0.5rem 0; }
  .rlc-card.r .rlc-symbol { color:var(--red); }
  .rlc-card.c .rlc-symbol { color:var(--purple); }
  .rlc-card.l .rlc-symbol { color:var(--teal); }
  .rlc-name { font-family:'Orbitron',monospace; font-size:0.7rem; font-weight:700; letter-spacing:0.08em; color:var(--muted); margin-bottom:0.5rem; }
  .rlc-property { font-size:0.86rem; color:var(--text); padding:0.2rem 0; border-top:1px solid var(--border); margin-top:0.5rem; }

  /* ── INLINE INPUT ── */
  .inline-input { background:transparent; border:none; border-bottom:2px dashed var(--border); color:var(--green); font-family:'Orbitron',monospace; font-size:0.85rem; font-weight:700; width:90px; outline:none; padding:2px 4px; display:inline; }
  .inline-input:focus { border-bottom-color:var(--green); }

  /* ── POWER METER VISUAL ── */
  .power-viz { background:var(--card2); border:1px solid var(--border); border-radius:12px; padding:1.4rem; margin:1.5rem 0; }
  .power-viz-title { font-family:'Orbitron',monospace; font-size:0.7rem; font-weight:700; color:var(--orange); letter-spacing:0.1em; text-transform:uppercase; margin-bottom:1rem; }
  .power-sliders { display:flex; flex-direction:column; gap:0.9rem; }
  .power-slider-row { display:flex; align-items:center; gap:1rem; flex-wrap:wrap; }
  .power-slider-label { font-family:'Orbitron',monospace; font-size:0.7rem; font-weight:700; letter-spacing:0.08em; min-width:50px; }
  .power-slider-label.v-lbl { color:var(--amber); }
  .power-slider-label.i-lbl { color:var(--blue); }
  input[type=range] { flex:1; min-width:120px; accent-color:var(--green); cursor:pointer; }
  .power-slider-val { font-family:'Orbitron',monospace; font-size:0.85rem; font-weight:700; min-width:60px; }
  .power-result-row { display:flex; align-items:center; gap:1.5rem; margin-top:1.1rem; flex-wrap:wrap; }
  .power-result-big { font-family:'Orbitron',monospace; font-size:1.8rem; font-weight:900; color:var(--green); }
  .power-result-label { font-size:0.88rem; color:var(--muted); }
  .heat-bar-track { flex:1; min-width:120px; height:14px; background:var(--bg); border-radius:7px; overflow:hidden; border:1px solid var(--border); }
  .heat-bar-fill { height:100%; border-radius:7px; transition:width 0.3s ease, background 0.3s; }

  /* ── NEW BADGE ── */
  .new-badge { display:inline-block; background:rgba(251,146,60,0.2); border:1px solid rgba(251,146,60,0.5); border-radius:999px; padding:0.1rem 0.7rem; font-family:'Orbitron',monospace; font-size:0.58rem; font-weight:900; color:var(--orange); letter-spacing:0.12em; text-transform:uppercase; vertical-align:middle; margin-left:0.5rem; }
</style>
</head>
<body>

<!-- ═══ HEADER ═══ -->
<div class="top-bar">
  <div class="session-label">Electronics Lab · Session</div>
  <div class="session-title">Power, Inductors, Diodes<br><span>&amp; The Transistor</span></div>
  <div class="session-meta">
    <div class="meta-pill">📅 Session 03</div>
    <div class="meta-pill">⚡ The Hardest Session Yet</div>
    <div class="meta-pill">🧮 6 Calculations + 5 Experiments</div>
    <div class="meta-pill">🔱 New component: Transistor</div>
  </div>
</div>

<div class="content">

  <!-- WHAT YOU NEED -->
  <div class="section">
    <div class="section-header">
      <div class="section-num">★</div>
      <div class="section-title">What You'll Need Today</div>
    </div>
    <div class="needs-grid">
      <div class="need-item"><div class="dot"></div>Breadboard</div>
      <div class="need-item"><div class="dot"></div>3–4 LEDs</div>
      <div class="need-item"><div class="dot"></div>330Ω resistor (×2)</div>
      <div class="need-item"><div class="dot"></div>1kΩ resistor (×2)</div>
      <div class="need-item"><div class="dot"></div>10kΩ resistor</div>
      <div class="need-item"><div class="dot"></div>100µF capacitor</div>
      <div class="need-item"><div class="dot"></div>9V battery + connector</div>
      <div class="need-item"><div class="dot"></div>Multimeter</div>
      <div class="need-item"><div class="dot new"></div>NPN transistor (BC547 or 2N2222) <span class="new-badge">NEW</span></div>
      <div class="need-item"><div class="dot new"></div>1N4007 diode <span class="new-badge">NEW</span></div>
      <div class="need-item"><div class="dot new"></div>Small inductor 10mH–100mH (optional) <span class="new-badge">NEW</span></div>
      <div class="need-item"><div class="dot"></div>Pen &amp; paper for calculations</div>
    </div>
    <div class="callout green">
      <div class="callout-title">📌 Where This Session Fits</div>
      Sessions 1 &amp; 2 covered the three passive components — resistors, capacitors, and (in a moment) inductors. Those are the building blocks. Today you meet your first truly <em>active</em> component: the <strong>transistor</strong>. A transistor can amplify or switch a signal — it can control a large current using a tiny one. This is the single most important invention in electronics history. Every computer, phone, and microcontroller is built from billions of them. Once you understand the transistor, you understand the root of all digital electronics.
    </div>
  </div>

  <!-- ═══ SECTION 1: POWER ═══ -->
  <div class="section">
    <div class="section-header">
      <div class="section-num">1</div>
      <div class="section-title">Electrical Power — How Much Energy is Actually Being Used?</div>
    </div>

    <p>You've used voltage (V), current (I), and resistance (R). But there's a fourth quantity that ties everything together: <strong>power (P)</strong>. Power tells you how much electrical energy is being converted into heat, light, or motion <em>every second</em>. It's measured in <strong>Watts (W)</strong>.</p>

    <p>You already experienced power in Session 1 — you felt the 330Ω resistor get warm. That warmth is power being dissipated as heat. If you left it on long enough and used a resistor too small for the job, it would get hot enough to burn or fail. Power is why components have ratings like "¼ Watt resistor" — it's the maximum power they can dissipate safely.</p>

    <div class="subsection">
      <div class="subsection-title">1.1 — The Three Power Formulas</div>
    </div>

    <p>There are three ways to calculate power depending on which values you know. They all come from combining P = V × I with Ohm's Law (V = I × R):</p>

    <div class="formula-grid-3">
      <div class="formula-card p">
        <div class="formula-card-title">KNOW V AND I</div>
        <div class="formula-equation">P = V × I</div>
        <div class="formula-label">Watts = Volts × Amps<br>The most fundamental form</div>
      </div>
      <div class="formula-card p2">
        <div class="formula-card-title">KNOW I AND R</div>
        <div class="formula-equation">P = I² × R</div>
        <div class="formula-label">Watts = Amps² × Ohms<br>Use when you know the current</div>
      </div>
      <div class="formula-card p3">
        <div class="formula-card-title">KNOW V AND R</div>
        <div class="formula-equation">P = V² ÷ R</div>
        <div class="formula-label">Watts = Volts² ÷ Ohms<br>Use when you know the voltage</div>
      </div>
    </div>

    <div class="callout amber">
      <div class="callout-title">🧮 Worked Example — Our LED Circuit</div>
      330Ω resistor, 9V battery, red LED (2V forward voltage).<br><br>
      <strong>Voltage across resistor:</strong> 9 − 2 = 7V<br>
      <strong>Current:</strong> 7V ÷ 330Ω = 0.0212A = 21.2mA<br>
      <strong>Power in resistor:</strong> P = V × I = 7 × 0.0212 = <strong>0.148 W ≈ 0.15W</strong><br><br>
      Standard resistors are rated at <strong>¼W (0.25W)</strong>. Our resistor dissipates 0.15W — safely under its rating. If we had used a 33Ω resistor by mistake, current would be ~212mA and power would be 7 × 0.212 = <strong>1.5W</strong> — six times the rating. It would get dangerously hot very quickly.
    </div>

    <div class="subsection">
      <div class="subsection-title">1.2 — Interactive Power Calculator &amp; Heat Visualiser</div>
    </div>

    <p>Drag the sliders to set voltage and current. Watch how the power calculation and "heat bar" change. Notice how doubling the current quadruples the power (because P = I² × R).</p>

    <div class="power-viz">
      <div class="power-viz-title">⚡ Power = V × I — Live Calculator</div>
      <div class="power-sliders">
        <div class="power-slider-row">
          <span class="power-slider-label v-lbl">V</span>
          <input type="range" id="pwr-v" min="0" max="12" step="0.1" value="7" oninput="updatePower()">
          <span class="power-slider-val" id="pwr-v-val">7.0 V</span>
        </div>
        <div class="power-slider-row">
          <span class="power-slider-label i-lbl">I</span>
          <input type="range" id="pwr-i" min="0" max="0.5" step="0.001" value="0.021" oninput="updatePower()">
          <span class="power-slider-val" id="pwr-i-val">21 mA</span>
        </div>
      </div>
      <div class="power-result-row">
        <div>
          <div class="power-result-big" id="pwr-result">0.147 W</div>
          <div class="power-result-label" id="pwr-label">= P = V × I · Safe for ¼W resistor</div>
        </div>
        <div style="flex:1; min-width:120px;">
          <div style="font-family:'Orbitron',monospace; font-size:0.62rem; color:var(--muted); letter-spacing:0.1em; margin-bottom:0.4rem;">HEAT LEVEL</div>
          <div class="heat-bar-track">
            <div class="heat-bar-fill" id="heat-bar" style="width:15%; background:var(--green);"></div>
          </div>
          <div style="display:flex; justify-content:space-between; margin-top:0.2rem;">
            <span style="font-size:0.7rem; color:var(--green);">Cool</span>
            <span style="font-size:0.7rem; color:var(--amber);">Warm ¼W</span>
            <span style="font-size:0.7rem; color:var(--red);">Danger 1W+</span>
          </div>
        </div>
      </div>
    </div>

    <div class="subsection">
      <div class="subsection-title">1.3 — Power Worksheet</div>
    </div>

    <div class="math-ws">
      <div class="math-ws-title">📝 Power Calculation Problems</div>

      <div class="math-problem">
        <div class="math-problem-num">Q1</div>
        <div class="math-problem-text">A <strong>1kΩ resistor</strong> has <strong>5V</strong> across it. How much power does it dissipate? (Use P = V² ÷ R)</div>
        <div class="math-answer-wrap">
          <input class="math-input" id="pa1" placeholder="?" onkeydown="if(event.key==='Enter') chkP(1, 25/1000, 'W', 5)">
          <span class="math-unit">W</span>
          <button class="math-check-btn" onclick="chkP(1, 25/1000, 'W', 5)">CHECK</button>
          <div class="math-feedback" id="pfb1"></div>
        </div>
      </div>

      <div class="math-problem">
        <div class="math-problem-num">Q2</div>
        <div class="math-problem-text">A current of <strong>50 mA</strong> flows through a <strong>330Ω resistor</strong>. How much power? Will a standard ¼W resistor survive? (P = I² × R)</div>
        <div class="math-answer-wrap">
          <input class="math-input" id="pa2" placeholder="?" onkeydown="if(event.key==='Enter') chkP(2, 0.05*0.05*330, 'W', 5)">
          <span class="math-unit">W</span>
          <button class="math-check-btn" onclick="chkP(2, 0.05*0.05*330, 'W', 5)">CHECK</button>
          <div class="math-feedback" id="pfb2"></div>
        </div>
      </div>

      <div class="math-problem">
        <div class="math-problem-num">Q3</div>
        <div class="math-problem-text">Your 9V battery supplies <strong>21 mA</strong> to the whole LED circuit. What is the total power drawn from the battery?</div>
        <div class="math-answer-wrap">
          <input class="math-input" id="pa3" placeholder="?" onkeydown="if(event.key==='Enter') chkP(3, 9*0.021*1000, 'mW', 5)">
          <span class="math-unit">mW</span>
          <button class="math-check-btn" onclick="chkP(3, 9*0.021*1000, 'mW', 5)">CHECK</button>
          <div class="math-feedback" id="pfb3"></div>
        </div>
      </div>

      <div class="math-problem">
        <div class="math-problem-num">Q4 ⭐</div>
        <div class="math-problem-text">You want to run a motor that needs <strong>12V</strong> and draws <strong>2A</strong>. What power rating (in Watts) must your power supply be able to deliver?</div>
        <div class="math-answer-wrap">
          <input class="math-input" id="pa4" placeholder="?" onkeydown="if(event.key==='Enter') chkP(4, 12*2, 'W', 5)">
          <span class="math-unit">W</span>
          <button class="math-check-btn" onclick="chkP(4, 12*2, 'W', 5)">CHECK</button>
          <div class="math-feedback" id="pfb4"></div>
        </div>
      </div>

      <div class="math-problem">
        <div class="math-problem-num">Q5 ⭐⭐</div>
        <div class="math-problem-text">An LED in a circuit draws 20mA. The LED drops 2V across it. The resistor drops 7V. How much power is dissipated by <em>just the LED</em>, and how much by just the resistor? Which gets warmer?</div>
        <div class="math-answer-wrap" style="flex-direction:column; align-items:flex-start;">
          <div style="display:flex; gap:0.5rem; align-items:center; flex-wrap:wrap;">
            LED power: <input class="math-input" id="pa5a" placeholder="?" style="width:90px;" onkeydown="if(event.key==='Enter') chkP('5a', 2*0.02*1000, 'mW', 5)"> mW
            <button class="math-check-btn" onclick="chkP('5a', 2*0.02*1000, 'mW', 5)">CHECK</button>
          </div>
          <div style="display:flex; gap:0.5rem; align-items:center; flex-wrap:wrap; margin-top:0.4rem;">
            Resistor power: <input class="math-input" id="pa5b" placeholder="?" style="width:90px;" onkeydown="if(event.key==='Enter') chkP('5b', 7*0.02*1000, 'mW', 5)"> mW
            <button class="math-check-btn" onclick="chkP('5b', 7*0.02*1000, 'mW', 5)">CHECK</button>
          </div>
          <div class="math-feedback" id="pfb5a"></div>
          <div class="math-feedback" id="pfb5b"></div>
        </div>
      </div>

    </div>

    <!-- MINI EXP 1 -->
    <div class="mini-exp">
      <div class="mini-exp-badge">🧪 Mini-Experiment 1</div>
      <div class="mini-exp-title">Measure Power Dissipation — Compare Resistors Getting Warm</div>
      <p style="margin-bottom:0.8rem;">You'll measure the actual voltage and current in a circuit and calculate real power. Then you'll feel the difference.</p>
      <ol class="mini-exp-steps">
        <li><span>Build a circuit: 9V battery → 330Ω resistor → LED → ground. Connect the battery and let it run for 90 seconds.</span></li>
        <li><span>Measure with your multimeter: voltage across the resistor (V<sub>R</sub>), voltage across the LED (V<sub>LED</sub>). Write them down.</span></li>
        <li><span>Calculate current: I = V<sub>R</sub> ÷ 330. Calculate resistor power: P = V<sub>R</sub> × I. Calculate LED power: P = V<sub>LED</sub> × I.</span></li>
        <li><span><strong>Disconnect battery</strong>. Gently touch the resistor with your fingertip. Note the warmth.</span></li>
        <li><span>Rebuild with a <strong>33Ω resistor</strong> if you have one, or wire two 330Ω in parallel to roughly halve the resistance. Run for 30 seconds only. Disconnect and touch it. Much hotter? Calculate the power to confirm.</span></li>
      </ol>
      <div style="overflow-x:auto; margin:1rem 0;">
        <table class="exp-table">
          <thead><tr><th>Resistor</th><th>V across R</th><th>Calc. Current</th><th>Power in R</th><th>Felt warm?</th></tr></thead>
          <tbody>
            <tr><td class="row-label">330Ω</td><td><input placeholder="V"></td><td><input placeholder="mA"></td><td><input placeholder="mW"></td><td><input placeholder="yes/no"></td></tr>
            <tr><td class="row-label">~165Ω (2× 330Ω ∥)</td><td><input placeholder="V"></td><td><input placeholder="mA"></td><td><input placeholder="mW"></td><td><input placeholder="yes/no"></td></tr>
          </tbody>
        </table>
      </div>
      <div class="observe-box">
        <div class="observe-title">🔍 The Physics Here</div>
        <p style="margin:0; font-size:0.92rem;">More current flows through the lower resistance. Since power scales with I² (not just I), halving the resistance roughly doubles the current but <em>quadruples</em> the power. This is why current ratings on components matter so much — going slightly over doubles the heat going four times over.</p>
      </div>
    </div>
  </div>

  <!-- ═══ SECTION 2: INDUCTORS ═══ -->
  <div class="section">
    <div class="section-header">
      <div class="section-num">2</div>
      <div class="section-title">Inductors — The Third Passive Component</div>
    </div>

    <p>At the end of Session 2 you were asked to predict: if a capacitor resists changes in voltage, what does an inductor resist? The answer is: an inductor resists changes in <strong>current</strong>. This single sentence is everything you need to understand inductors.</p>

    <p>An inductor is simply a coil of wire — sometimes wound around a core material. When current flows through it, it creates a magnetic field around the coil. The energy is stored in that magnetic field, not in an electric field like a capacitor. When you try to change the current (increase it or decrease it), the magnetic field pushes back — it opposes the change. This behaviour is called <strong>inductance</strong>, measured in <strong>Henrys (H)</strong>.</p>

    <div class="diagram-box">
      <svg viewBox="0 0 680 210" xmlns="http://www.w3.org/2000/svg" style="max-height:210px">
        <rect width="680" height="210" fill="#0f1c30" rx="10"/>
        <text x="340" y="20" text-anchor="middle" font-family="Orbitron,monospace" font-size="10" fill="#6b82a0" letter-spacing="2">INDUCTOR — COIL OF WIRE, MAGNETIC ENERGY STORAGE</text>

        <!-- Leads -->
        <line x1="40" y1="105" x2="130" y2="105" stroke="#aaa" stroke-width="2.5"/>
        <line x1="310" y1="105" x2="400" y2="105" stroke="#aaa" stroke-width="2.5"/>

        <!-- Coil body — series of arcs -->
        <path d="M 130,105 Q 145,80 160,105 Q 175,130 190,105 Q 205,80 220,105 Q 235,130 250,105 Q 265,80 280,105 Q 295,130 310,105"
              fill="none" stroke="#2dd4bf" stroke-width="3" stroke-linecap="round"/>

        <!-- Core line below -->
        <line x1="130" y1="115" x2="310" y2="115" stroke="#6b82a0" stroke-width="2"/>
        <text x="220" y="130" text-anchor="middle" font-family="Nunito,sans-serif" font-size="9" fill="#6b82a0">Iron / ferrite core (increases inductance)</text>

        <!-- Magnetic field rings -->
        <ellipse cx="220" cy="105" rx="110" ry="45" fill="none" stroke="rgba(45,212,191,0.2)" stroke-width="1.5" stroke-dasharray="5,3"/>
        <ellipse cx="220" cy="105" rx="140" ry="60" fill="none" stroke="rgba(45,212,191,0.12)" stroke-width="1" stroke-dasharray="5,4"/>
        <ellipse cx="220" cy="105" rx="165" ry="72" fill="none" stroke="rgba(45,212,191,0.06)" stroke-width="1" stroke-dasharray="4,5"/>
        <text x="220" y="62" text-anchor="middle" font-family="Nunito,sans-serif" font-size="10" fill="#2dd4bf" font-weight="700">Magnetic field stored here</text>

        <!-- Current arrow -->
        <text x="85" y="100" text-anchor="middle" font-size="12" font-family="Nunito,sans-serif" fill="#f87171" font-weight="900">→</text>
        <text x="355" y="100" text-anchor="middle" font-size="12" font-family="Nunito,sans-serif" fill="#f87171" font-weight="900">→</text>
        <text x="220" y="196" text-anchor="middle" font-family="Nunito,sans-serif" font-size="11" fill="#2dd4bf" font-weight="800">Opposes changes in current — stores energy in a magnetic field</text>

        <!-- Schematic symbol -->
        <text x="520" y="55" text-anchor="middle" font-family="Orbitron,monospace" font-size="9" fill="#6b82a0" letter-spacing="1">SYMBOL</text>
        <line x1="460" y1="90" x2="490" y2="90" stroke="#aaa" stroke-width="2"/>
        <path d="M 490,90 Q 498,70 506,90 Q 514,110 522,90 Q 530,70 538,90 Q 546,110 554,90" fill="none" stroke="#2dd4bf" stroke-width="2.5"/>
        <line x1="554" y1="90" x2="584" y2="90" stroke="#aaa" stroke-width="2"/>
        <text x="522" y="118" text-anchor="middle" font-family="Nunito,sans-serif" font-size="10" fill="#2dd4bf" font-weight="700">L (Henrys)</text>
      </svg>
      <div class="diagram-caption">An inductor is a coil of wire. Current flowing through it creates a magnetic field. The field stores energy and opposes any change in the current flowing through the coil — resisting both increases and decreases in current.</div>
    </div>

    <div class="subsection">
      <div class="subsection-title">2.1 — Comparing R, C, and L: The Complete Passive Component Set</div>
    </div>

    <div class="rlc-grid">
      <div class="rlc-card r">
        <div class="rlc-name">RESISTOR</div>
        <div class="rlc-symbol">R</div>
        <div class="rlc-property" style="color:var(--muted);">Ohms (Ω)</div>
        <div class="rlc-property">Dissipates energy as heat</div>
        <div class="rlc-property">Opposes current always</div>
        <div class="rlc-property" style="color:var(--amber);">No polarity</div>
        <div class="rlc-property" style="color:var(--green);">Instant response</div>
      </div>
      <div class="rlc-card c">
        <div class="rlc-name">CAPACITOR</div>
        <div class="rlc-symbol">C</div>
        <div class="rlc-property" style="color:var(--muted);">Farads (F)</div>
        <div class="rlc-property">Stores energy in electric field</div>
        <div class="rlc-property">Opposes voltage changes</div>
        <div class="rlc-property" style="color:var(--red);">Can be polarised</div>
        <div class="rlc-property" style="color:var(--purple);">Charges/discharges over time (τ = RC)</div>
      </div>
      <div class="rlc-card l">
        <div class="rlc-name">INDUCTOR</div>
        <div class="rlc-symbol">L</div>
        <div class="rlc-property" style="color:var(--muted);">Henrys (H)</div>
        <div class="rlc-property">Stores energy in magnetic field</div>
        <div class="rlc-property">Opposes current changes</div>
        <div class="rlc-property" style="color:var(--green);">No polarity (usually)</div>
        <div class="rlc-property" style="color:var(--teal);">Current builds/decays over time (τ = L/R)</div>
      </div>
    </div>

    <div class="subsection">
      <div class="subsection-title">2.2 — The RL Time Constant</div>
    </div>

    <p>Just like an RC circuit has a time constant τ = R×C, an RL circuit (resistor + inductor) also has a time constant — but this time it controls how fast <em>current</em> builds up or falls, not voltage. The formula is:</p>

    <div class="callout teal">
      <div class="callout-title">⏱ RL Time Constant</div>
      <div style="text-align:center; margin:0.6rem 0;">
        <span style="font-family:Orbitron,monospace; font-size:1.4rem; color:var(--teal); font-weight:900;">τ = L ÷ R</span>
      </div>
      Where L is in Henrys and R is in Ohms. Result is in seconds.<br><br>
      After 1τ, current has reached 63% of its final value. After 5τ, it's essentially at full current.<br><br>
      <strong>Example:</strong> L = 100mH (0.1H), R = 100Ω → τ = 0.1 ÷ 100 = <strong>0.001 seconds (1 ms)</strong>. Very fast — RL circuits usually operate in microseconds to milliseconds, not the seconds of RC circuits.
    </div>

    <div class="subsection">
      <div class="subsection-title teal">2.3 — The Back-EMF Spike: The Dangerous Side of Inductors</div>
    </div>

    <p>Here's something critical to understand about inductors: when you suddenly cut the current — by opening a switch — the inductor's magnetic field collapses <em>instantly</em>. As it collapses, it tries to keep the current flowing by generating a voltage. This is called <strong>back-EMF</strong> (Electromotive Force), and it can be enormous — many times larger than your supply voltage — even from a small inductor.</p>

    <p>In practice, <strong>any coil of wire is an inductor</strong>: motors, relays, solenoids, electromagnets. When you switch them off suddenly, the back-EMF spike can destroy transistors, microcontrollers, and other sensitive components connected nearby. The solution is a <strong>flyback diode</strong> (also called a freewheeling or snubber diode), which provides a path for that spike to dissipate safely. You'll use one in the challenge at the end of this session.</p>

    <div class="callout red">
      <div class="callout-title">⚠️ Golden Rule: Always Put a Flyback Diode Across Inductive Loads</div>
      Whenever you connect a transistor (or any switch) to a motor, relay, or solenoid, <strong>always place a diode across the coil</strong> — oriented in reverse (cathode to +, anode to −). During normal operation, the diode is reverse-biased and does nothing. The moment the back-EMF spike appears, the diode becomes forward-biased and safely clamps the spike. Without it, the spike can reach hundreds of volts and destroy your transistor in microseconds. You'll build this exact protection in the grand challenge.
    </div>

  </div>

  <!-- ═══ SECTION 3: DIODES ═══ -->
  <div class="section">
    <div class="section-header">
      <div class="section-num">3</div>
      <div class="section-title">Diodes — The One-Way Valve of Electronics</div>
    </div>

    <p>You've already used a diode every session — the LED is a diode that emits light. But a standard diode like the <strong>1N4007</strong> doesn't emit light; it's just a pure one-way valve for current. Let's understand exactly how it works and why it's so useful.</p>

    <p>A diode is made from a semiconductor (usually silicon) where one half is doped to have extra electrons (N-type material) and the other half is doped to have "holes" where electrons are missing (P-type material). At the junction between these two, a tiny electric field forms that normally blocks current. Apply voltage in the forward direction and you overcome this field — current flows. Apply it in reverse and you reinforce the field — no current flows.</p>

    <div class="diagram-box">
      <svg viewBox="0 0 680 200" xmlns="http://www.w3.org/2000/svg" style="max-height:200px">
        <rect width="680" height="200" fill="#0f1c30" rx="10"/>
        <text x="340" y="20" text-anchor="middle" font-family="Orbitron,monospace" font-size="10" fill="#6b82a0" letter-spacing="2">DIODE — I/V CHARACTERISTIC CURVE</text>

        <!-- Axes -->
        <line x1="340" y1="30" x2="340" y2="178" stroke="#2a4060" stroke-width="2"/>
        <line x1="60"  y1="130" x2="630" y2="130" stroke="#2a4060" stroke-width="2"/>

        <!-- Labels -->
        <text x="350" y="26" font-family="Orbitron,monospace" font-size="9" fill="#6b82a0">Current (I) ↑</text>
        <text x="620" y="143" font-family="Orbitron,monospace" font-size="9" fill="#6b82a0">Voltage →</text>
        <text x="100" y="143" font-family="Orbitron,monospace" font-size="9" fill="#6b82a0">← Reverse</text>
        <text x="430" y="143" font-family="Orbitron,monospace" font-size="9" fill="#6b82a0">Forward →</text>

        <!-- Forward bias curve (right side, shoots up) -->
        <path d="M 340,130 Q 390,128 420,126 Q 450,124 470,115 Q 490,100 510,70 Q 520,50 525,35"
              fill="none" stroke="#4ade80" stroke-width="3" stroke-linecap="round"/>

        <!-- Reverse bias (flat, almost zero current) -->
        <path d="M 340,130 Q 280,131 220,131.5 Q 170,132 130,133"
              fill="none" stroke="#f87171" stroke-width="2.5" stroke-linecap="round"/>

        <!-- Breakdown knee (sudden current at high reverse voltage) -->
        <path d="M 130,133 Q 115,135 110,140 Q 108,150 107,165 Q 106,175 105,185"
              fill="none" stroke="#c084fc" stroke-width="2.5" stroke-linecap="round" stroke-dasharray="5,3"/>

        <!-- Forward voltage marker -->
        <line x1="470" y1="115" x2="470" y2="130" stroke="#f5a523" stroke-width="1.5" stroke-dasharray="4,3"/>
        <text x="468" y="148" text-anchor="middle" font-family="Orbitron,monospace" font-size="8" fill="#f5a523">~0.7V</text>
        <text x="468" y="158" text-anchor="middle" font-family="Nunito,sans-serif" font-size="9" fill="#f5a523">Forward</text>
        <text x="468" y="168" text-anchor="middle" font-family="Nunito,sans-serif" font-size="9" fill="#f5a523">voltage</text>

        <!-- Breakdown voltage marker -->
        <line x1="110" y1="130" x2="110" y2="165" stroke="#c084fc" stroke-width="1.5" stroke-dasharray="4,3"/>
        <text x="85" y="124" font-family="Orbitron,monospace" font-size="8" fill="#c084fc">−400V+</text>
        <text x="70" y="135" font-family="Nunito,sans-serif" font-size="9" fill="#c084fc">Breakdown</text>

        <!-- Region labels -->
        <text x="230" y="120" font-family="Nunito,sans-serif" font-size="10" fill="#f87171" font-weight="700">Almost zero current</text>
        <text x="230" y="110" font-family="Nunito,sans-serif" font-size="10" fill="#f87171">(reverse bias blocks)</text>
        <text x="540" y="80" font-family="Nunito,sans-serif" font-size="10" fill="#4ade80" font-weight="700">Current</text>
        <text x="540" y="93" font-family="Nunito,sans-serif" font-size="10" fill="#4ade80">flows freely</text>
        <text x="540" y="106" font-family="Nunito,sans-serif" font-size="10" fill="#4ade80">(forward bias)</text>
      </svg>
      <div class="diagram-caption">The diode I/V curve. On the right (forward bias): almost no current until ~0.7V threshold, then current rises steeply — this threshold is the "forward voltage". On the left (reverse bias): almost zero current even at high voltages. Far left (breakdown): at very high reverse voltages, the diode breaks down and conducts — this destroys standard diodes but is deliberately used in Zener diodes.</div>
    </div>

    <div class="subsection">
      <div class="subsection-title">3.1 — Forward Voltage: Why It Matters</div>
    </div>

    <p>Every diode has a forward voltage threshold — the minimum voltage needed before current can flow. For a silicon diode like the 1N4007, this is about <strong>0.6–0.7V</strong>. For LEDs it depends on colour (red ≈ 2V, blue ≈ 3.2V). This voltage is "used up" by the diode and isn't available to the rest of the circuit — you've been subtracting it from your LED calculations since Session 2.</p>

    <div class="diode-region">
      <div class="region-card forward">
        <div class="region-title">✓ Forward Biased</div>
        <p>Anode (+) connected to higher voltage than cathode (−). Current flows freely once past the ~0.7V threshold. This is normal operation. Current flows from anode to cathode inside the diode.</p>
      </div>
      <div class="region-card reverse">
        <div class="region-title">✗ Reverse Biased</div>
        <p>Cathode connected to higher voltage. Current is blocked — only a tiny leakage current of nanoamps flows. This is what makes a diode a one-way valve. 1N4007 can withstand up to 1000V in reverse.</p>
      </div>
      <div class="region-card breakdown">
        <div class="region-title">⚠️ Breakdown (Avoid!)</div>
        <p>Apply too much reverse voltage and the diode breaks down conductung in reverse — usually destroying it. The 1N4007 rating of "1000V reverse" means it can safely block up to 1000V reversed before breakdown.</p>
      </div>
      <div class="region-card ideal">
        <div class="region-title">💡 Identifying a 1N4007</div>
        <p>It's a black cylindrical component. One end has a <strong>silver stripe</strong> — this is the cathode (−). The other end (no stripe) is the anode (+). Current flows from anode → cathode.</p>
      </div>
    </div>

    <div class="subsection">
      <div class="subsection-title">3.2 — What Diodes Are Used For</div>
    </div>

    <div class="callout blue">
      <div class="callout-title">🔧 Five Key Uses of Diodes</div>
      <strong>1. Rectification:</strong> Converting AC (alternating current, like from the wall) into DC (direct current, like from a battery). This is how every power adapter in your home works — it uses diodes to make AC usable.<br><br>
      <strong>2. Reverse polarity protection:</strong> Put a diode in series with your power supply. If you accidentally connect the battery backwards, the diode blocks the current and protects your circuit. Without it, reversed polarity can instantly destroy chips.<br><br>
      <strong>3. Flyback protection (freewheeling):</strong> Placed across inductive loads (motors, relays) to safely absorb back-EMF spikes. You'll build this today.<br><br>
      <strong>4. Signal clamping:</strong> Prevent signals from going higher than a certain voltage by routing the excess current through a diode to the supply rail.<br><br>
      <strong>5. Zener regulation:</strong> A special type (Zener diode) breaks down at a precise voltage — this is used as a simple voltage regulator to keep a supply stable.
    </div>

    <!-- MINI EXP 2 -->
    <div class="mini-exp">
      <div class="mini-exp-badge">🧪 Mini-Experiment 2</div>
      <div class="mini-exp-title">Measure Diode Forward Voltage &amp; Test Reverse Blocking</div>
      <p style="margin-bottom:0.8rem;">You'll confirm the 0.7V forward voltage and prove the reverse-blocking behaviour with your multimeter.</p>
      <ol class="mini-exp-steps">
        <li><span><strong>Diode mode:</strong> Set your multimeter to diode test mode (symbol: →|). Touch red probe to the anode (no stripe end), black probe to cathode (stripe end). The display should show approximately <strong>0.550–0.700</strong> — this is the forward voltage in Volts.</span></li>
        <li><span><strong>Reverse test:</strong> Swap the probes (red to cathode, black to anode). The display should show "1" or "OL" (open loop — no conduction). This confirms reverse blocking.</span></li>
        <li><span>Now test an LED the same way (red → long leg, black → short leg). Write down the forward voltage. Does it match the expected value for its colour?</span></li>
        <li><span><strong>Build a reverse-polarity protection circuit:</strong> Place the 1N4007 in series between the battery's + terminal and your LED + resistor circuit (anode toward battery, cathode toward circuit). Power it on — does the LED light up? Now flip the battery (swap + and − wires). Does the LED light up? It shouldn't.</span></li>
      </ol>
      <div style="overflow-x:auto; margin:1rem 0;">
        <table class="exp-table">
          <thead><tr><th>Component</th><th>Forward Voltage (V<sub>f</sub>)</th><th>Reverse blocks?</th><th>Notes</th></tr></thead>
          <tbody>
            <tr><td class="row-label">1N4007 diode</td><td><input placeholder="V"></td><td><input placeholder="yes/no"></td><td><input placeholder=""></td></tr>
            <tr><td class="row-label">Red LED</td><td><input placeholder="V"></td><td><input placeholder="yes/no"></td><td><input placeholder=""></td></tr>
            <tr><td class="row-label">Green/other LED</td><td><input placeholder="V"></td><td><input placeholder="yes/no"></td><td><input placeholder=""></td></tr>
          </tbody>
        </table>
      </div>
      <div class="observe-box">
        <div class="observe-title">🔍 Key Insight</div>
        <p style="margin:0; font-size:0.92rem;">Notice the 1N4007 has a lower forward voltage than your LEDs. When you add a protection diode in series, you're also losing ~0.7V from your supply — so you might need to recalculate your current-limiting resistor if precision matters. In battery-powered circuits designers often use Schottky diodes instead (forward voltage ~0.3V) to lose less voltage to protection.</p>
      </div>
    </div>

  </div>

  <!-- ═══ SECTION 4: TRANSISTORS ═══ -->
  <div class="section">
    <div class="section-header">
      <div class="section-num" style="background:var(--orange); color:var(--bg);">4</div>
      <div class="section-title" style="color:var(--orange);">The Transistor — The Most Important Invention in History</div>
    </div>

    <p>In 1947, three physicists at Bell Labs invented the transistor. By 2024 the world was producing roughly <strong>twenty quintillion transistors per year</strong> — about 2.5 billion for every person on Earth. They are in every smartphone, laptop, car, and household appliance. They enable the entire digital world. And the fundamental principle is something you can understand completely right now.</p>

    <p>A transistor does one of two things: it <strong>amplifies</strong> (a small current controls a large current) or it <strong>switches</strong> (a small current turns a large current on or off). Today you'll focus on the switch behaviour — it's simpler to understand and directly useful for Arduino projects.</p>

    <div class="subsection">
      <div class="subsection-title amber">4.1 — Inside the NPN Transistor</div>
    </div>

    <p>The transistor you have (BC547 or 2N2222) is an <strong>NPN bipolar junction transistor (BJT)</strong>. "NPN" refers to how the semiconductor layers are arranged. It has three legs, each with a name and a specific role:</p>

    <div class="transistor-pins">
      <div class="pin-card base">
        <div class="pin-name">BASE</div>
        <div class="pin-symbol">B — The Control Input</div>
        <div class="pin-desc">This is the "gate". A small current flowing into the base turns the transistor on and allows a much larger current to flow between collector and emitter. In a BC547: typically the <strong>middle leg</strong> when the flat face points toward you.</div>
      </div>
      <div class="pin-card collector">
        <div class="pin-name">COLLECTOR</div>
        <div class="pin-symbol">C — The Input Side</div>
        <div class="pin-desc">The "top" of the switch. This leg connects to the positive supply (via the load — the thing you're switching, like an LED or motor). Current enters from here. In a BC547: the <strong>left leg</strong> when flat face points toward you.</div>
      </div>
      <div class="pin-card emitter">
        <div class="pin-name">EMITTER</div>
        <div class="pin-symbol">E — The Output Side</div>
        <div class="pin-desc">The "bottom" of the switch. This leg always connects to ground. Current exits here. In a BC547: the <strong>right leg</strong> when flat face points toward you. (Always confirm with your transistor's datasheet — pin order varies by model.)</div>
      </div>
    </div>

    <div class="callout orange">
      <div class="callout-title">🔑 The Key Rule for NPN as a Switch</div>
      When a small current flows from Base to Emitter (via a base resistor), the transistor <strong>saturates</strong> — it switches fully ON and allows a much larger current to flow from Collector to Emitter.<br><br>
      When no current flows into the Base, the transistor is <strong>cut off</strong> — it's fully OFF, and no current flows from Collector to Emitter.<br><br>
      <strong>The ratio of collector current to base current is the transistor's gain (hFE or β). For a BC547, gain is typically 100–800. So 0.1mA into the base can control up to ~80mA through the collector.</strong>
    </div>

    <div class="diagram-box">
      <svg viewBox="0 0 680 240" xmlns="http://www.w3.org/2000/svg" style="max-height:240px">
        <rect width="680" height="240" fill="#0f1c30" rx="10"/>
        <text x="340" y="20" text-anchor="middle" font-family="Orbitron,monospace" font-size="10" fill="#6b82a0" letter-spacing="2">NPN TRANSISTOR — SWITCH CIRCUIT</text>

        <!-- LEFT: Transistor OFF -->
        <text x="168" y="40" text-anchor="middle" font-family="Orbitron,monospace" font-size="10" fill="#f87171">TRANSISTOR OFF</text>
        <text x="168" y="54" text-anchor="middle" font-family="Nunito,sans-serif" font-size="10" fill="#6b82a0">No base current</text>

        <!-- Battery left -->
        <rect x="20" y="65" width="32" height="55" rx="5" fill="#0a0e1a" stroke="#f5a523" stroke-width="1.5"/>
        <text x="36" y="83" text-anchor="middle" font-size="9" fill="#f5a523" font-family="Nunito,sans-serif" font-weight="800">9V</text>
        <text x="36" y="100" text-anchor="middle" font-size="14" fill="#f87171" font-family="Nunito,sans-serif">+</text>

        <!-- Top wire to LED+resistor -->
        <line x1="52" y1="75" x2="100" y2="75" stroke="#f5a523" stroke-width="2"/>
        <!-- Resistor -->
        <rect x="100" y="68" width="36" height="14" rx="7" fill="#c47e10" stroke="#f5a523" stroke-width="1.5"/>
        <line x1="136" y1="75" x2="155" y2="75" stroke="#f5a523" stroke-width="2"/>
        <!-- LED (off) -->
        <ellipse cx="172" cy="75" rx="16" ry="13" fill="#0a1a0a" stroke="#3a5a3a" stroke-width="1.5"/>
        <text x="172" y="79" text-anchor="middle" font-size="11" font-family="Nunito,sans-serif">○</text>
        <line x1="188" y1="75" x2="218" y2="75" stroke="#f5a523" stroke-width="2"/>

        <!-- Transistor symbol (left) -->
        <!-- Body circle -->
        <circle cx="240" cy="105" r="28" fill="#0a0e1a" stroke="#6b82a0" stroke-width="1.5"/>
        <!-- Base line -->
        <line x1="200" y1="105" x2="224" y2="105" stroke="#6b82a0" stroke-width="2.5"/>
        <!-- Collector line up-right -->
        <line x1="224" y1="105" x2="238" y2="75" stroke="#f87171" stroke-width="2.5"/>
        <line x1="238" y1="75" x2="218" y2="75" stroke="#f87171" stroke-width="2.5"/>
        <!-- Emitter line down-right -->
        <line x1="224" y1="105" x2="238" y2="135" stroke="#38bdf8" stroke-width="2.5"/>
        <!-- Arrow on emitter -->
        <polygon points="234,130 242,138 228,138" fill="#38bdf8"/>
        <line x1="238" y1="138" x2="238" y2="155" stroke="#38bdf8" stroke-width="2.5"/>
        <!-- Ground left -->
        <line x1="52" y1="120" x2="238" y2="155" stroke="#38bdf8" stroke-width="2" stroke-dasharray="4,3"/>
        <!-- Base resistor (open circuit) -->
        <line x1="200" y1="105" x2="180" y2="105" stroke="#6b82a0" stroke-width="2" stroke-dasharray="4,3"/>
        <text x="175" y="100" text-anchor="middle" font-family="Nunito,sans-serif" font-size="9" fill="#6b82a0">no signal</text>
        <!-- OFF state label -->
        <text x="265" y="102" font-family="Nunito,sans-serif" font-size="10" fill="#f87171" font-weight="800">OPEN</text>
        <text x="265" y="114" font-family="Nunito,sans-serif" font-size="10" fill="#f87171">(no current)</text>
        <!-- Pin labels left -->
        <text x="195" y="117" font-family="Orbitron,monospace" font-size="7" fill="#fb923c">B</text>
        <text x="245" y="70" font-family="Orbitron,monospace" font-size="7" fill="#f87171">C</text>
        <text x="245" y="148" font-family="Orbitron,monospace" font-size="7" fill="#38bdf8">E</text>

        <!-- DIVIDER -->
        <line x1="340" y1="30" x2="340" y2="210" stroke="#1a2e4a" stroke-width="2" stroke-dasharray="5,4"/>

        <!-- RIGHT: Transistor ON -->
        <text x="514" y="40" text-anchor="middle" font-family="Orbitron,monospace" font-size="10" fill="#4ade80">TRANSISTOR ON</text>
        <text x="514" y="54" text-anchor="middle" font-family="Nunito,sans-serif" font-size="10" fill="#6b82a0">Small base current → large collector current</text>

        <!-- Battery right -->
        <rect x="366" y="65" width="32" height="55" rx="5" fill="#0a0e1a" stroke="#f5a523" stroke-width="1.5"/>
        <text x="382" y="83" text-anchor="middle" font-size="9" fill="#f5a523" font-family="Nunito,sans-serif" font-weight="800">9V</text>
        <text x="382" y="100" text-anchor="middle" font-size="14" fill="#f87171" font-family="Nunito,sans-serif">+</text>

        <!-- Top wire right -->
        <line x1="398" y1="75" x2="446" y2="75" stroke="#f87171" stroke-width="2.5"/>
        <!-- Resistor right -->
        <rect x="446" y="68" width="36" height="14" rx="7" fill="#c47e10" stroke="#f5a523" stroke-width="1.5"/>
        <line x1="482" y1="75" x2="504" y2="75" stroke="#f87171" stroke-width="2.5"/>
        <!-- LED ON -->
        <ellipse cx="520" cy="75" rx="16" ry="13" fill="#0a1a0a" stroke="#4ade80" stroke-width="2"/>
        <text x="520" y="79" text-anchor="middle" font-size="11" font-family="Nunito,sans-serif">💡</text>
        <line x1="536" y1="75" x2="560" y2="75" stroke="#f87171" stroke-width="2.5"/>

        <!-- Transistor right ON -->
        <circle cx="582" cy="105" r="28" fill="#0a1a0a" stroke="#4ade80" stroke-width="2"/>
        <line x1="560" y1="75" x2="572" y2="75" stroke="#f87171" stroke-width="2.5"/>
        <line x1="572" y1="75" x2="586" y2="105" stroke="#f87171" stroke-width="2.5"/>
        <line x1="586" y1="105" x2="566" y2="135" stroke="#38bdf8" stroke-width="2.5"/>
        <polygon points="562,130 570,138 556,138" fill="#38bdf8"/>
        <line x1="566" y1="138" x2="566" y2="158" stroke="#38bdf8" stroke-width="2.5"/>
        <line x1="566" y1="105" x2="544" y2="105" stroke="#fb923c" stroke-width="2.5"/>
        <!-- Base signal from small resistor (right side) -->
        <line x1="544" y1="105" x2="520" y2="105" stroke="#fb923c" stroke-width="2"/>
        <rect x="490" y="98" width="30" height="14" rx="7" fill="rgba(251,146,60,0.2)" stroke="#fb923c" stroke-width="1.5"/>
        <text x="505" y="122" text-anchor="middle" font-family="Nunito,sans-serif" font-size="8" fill="#fb923c">1kΩ base R</text>
        <line x1="490" y1="105" x2="475" y2="105" stroke="#fb923c" stroke-width="2"/>
        <line x1="475" y1="105" x2="475" y2="85" stroke="#fb923c" stroke-width="2" stroke-dasharray="3,2"/>
        <text x="455" y="82" font-family="Nunito,sans-serif" font-size="9" fill="#fb923c" font-weight="800">Control</text>
        <text x="455" y="92" font-family="Nunito,sans-serif" font-size="9" fill="#fb923c">signal</text>
        <!-- Ground right -->
        <line x1="398" y1="120" x2="566" y2="158" stroke="#38bdf8" stroke-width="2" stroke-dasharray="4,3"/>
        <!-- ON label -->
        <text x="615" y="102" font-family="Nunito,sans-serif" font-size="10" fill="#4ade80" font-weight="800">CLOSED</text>
        <text x="615" y="114" font-family="Nunito,sans-serif" font-size="10" fill="#4ade80">(current flows)</text>
        <!-- Pin labels right -->
        <text x="540" y="118" font-family="Orbitron,monospace" font-size="7" fill="#fb923c">B</text>
        <text x="592" y="73" font-family="Orbitron,monospace" font-size="7" fill="#f87171">C</text>
        <text x="572" y="152" font-family="Orbitron,monospace" font-size="7" fill="#38bdf8">E</text>

        <!-- Current flow arrows -->
        <text x="422" y="68" font-family="Nunito,sans-serif" font-size="11" fill="#f87171" font-weight="900">→</text>
        <text x="499" y="68" font-family="Nunito,sans-serif" font-size="11" fill="#f87171" font-weight="900">→</text>

        <!-- Bottom explanation -->
        <text x="340" y="225" text-anchor="middle" font-family="Nunito,sans-serif" font-size="11" fill="#6b82a0">The base current (~0.1 mA) controls the collector current (~20mA) — a gain of 200×</text>
      </svg>
      <div class="diagram-caption">Left: No current into the Base → transistor is OFF, no current flows through LED (open circuit between C and E). Right: Small current into Base via 1kΩ → transistor saturates → large current flows through LED. The transistor acts as an electronically controlled switch.</div>
    </div>

    <div class="subsection">
      <div class="subsection-title amber">4.2 — Calculating the Base Resistor</div>
    </div>

    <p>When you use a transistor as a switch, you don't just wire the base directly — you put a resistor in series. This limits the base current to a safe value and ensures the transistor goes into saturation (fully ON). Here's how to calculate it:</p>

    <div class="callout amber">
      <div class="callout-title">🧮 Base Resistor Calculation</div>
      <strong>Step 1:</strong> Decide the collector current you want (i.e., the LED current). Let's say 20mA.<br>
      <strong>Step 2:</strong> Find minimum base current needed. If gain (hFE) = 100, then I<sub>B(min)</sub> = I<sub>C</sub> ÷ hFE = 20mA ÷ 100 = 0.2mA.<br>
      <strong>Step 3:</strong> Use 5–10× overdrive to guarantee saturation. I<sub>B</sub> = 1mA.<br>
      <strong>Step 4:</strong> Calculate base resistor. V<sub>be</sub> ≈ 0.7V (base-emitter forward voltage).<br>
      R<sub>B</sub> = (V<sub>signal</sub> − V<sub>be</sub>) ÷ I<sub>B</sub> = (5V − 0.7V) ÷ 0.001 = 4300Ω → use <strong>4.7kΩ</strong> or 1kΩ for reliable switching.<br><br>
      With Arduino (5V signal) and a 1kΩ base resistor: I<sub>B</sub> = (5 − 0.7) ÷ 1000 = 4.3mA — more than enough overdrive.
    </div>

    <div class="subsection">
      <div class="subsection-title amber">4.3 — NPN vs PNP: A Quick Note</div>
    </div>
    <p>There are two flavours of BJT transistor: <strong>NPN</strong> (what you have) and <strong>PNP</strong>. They're mirror images of each other. In NPN, a positive signal at the base turns it ON and current flows from collector to emitter (downward, toward ground). In PNP, a low/negative signal at the base turns it ON and current flows from emitter to collector (upward, toward the supply). You'll mostly use NPN as beginners — it's more intuitive since the control signal and the load share a common ground.</p>

    <!-- MINI EXP 3 -->
    <div class="mini-exp">
      <div class="mini-exp-badge">🧪 Mini-Experiment 3</div>
      <div class="mini-exp-title">Your First Transistor Switch — Controlled by Your Finger</div>
      <p style="margin-bottom:0.8rem;">You'll use a transistor to switch an LED on and off. The "control signal" will be your finger touching a wire — your body's resistance (roughly 1–10MΩ) will pass just enough current to turn the transistor on. This is exactly how touch-sensitive circuits work.</p>

      <div class="predict-box">
        <div class="predict-title">✏️ Calculate the Base Current First</div>
        If your finger has ~1MΩ resistance and V = 9V: I<sub>B</sub> = 9V ÷ 1,000,000Ω = <input class="predict-input" style="width:80px;" placeholder="? µA"> µA.<br>
        With transistor gain of 200, max collector current = I<sub>B</sub> × 200 = <input class="predict-input" style="width:80px;" placeholder="? µA"> µA.<br>
        Is that enough to visibly light an LED (which needs ~20,000µA)? <input class="predict-input" style="width:60px;" placeholder="yes/no">
      </div>

      <ol class="mini-exp-steps">
        <li><span>Look up the pinout for your transistor (BC547 or 2N2222) — confirm which leg is Base, Collector, and Emitter. Place the transistor on the breadboard with legs in three separate columns.</span></li>
        <li><span><strong>Collector circuit:</strong> Connect the + rail → 330Ω resistor → LED → Collector leg. The LED's cathode (short leg) goes to the Collector.</span></li>
        <li><span><strong>Emitter:</strong> Connect the Emitter leg to the − rail (ground).</span></li>
        <li><span><strong>Base circuit:</strong> Connect a 1kΩ resistor between the Base leg and a free point on the breadboard (a "control wire"). Leave the other end of this resistor unconnected for now. Connect the battery.</span></li>
        <li><span>LED should be OFF. Now touch the free end of the base resistor with your finger while holding another wire that's connected to the + rail with your other hand. (Safe — it's only 9V.) Does the LED turn on?</span></li>
        <li><span>Replace your finger with a direct wire from the + rail to the base resistor. LED should now be fully bright. Measure: voltage at the Base, voltage at the Collector, voltage at the Emitter.</span></li>
        <li><span>Remove the base wire. LED goes off. Reconnect. On. Off. You've built a manual electronic switch.</span></li>
      </ol>

      <div style="overflow-x:auto; margin:1rem 0;">
        <table class="exp-table">
          <thead><tr><th>State</th><th>V at Base</th><th>V at Collector</th><th>V at Emitter</th><th>LED</th></tr></thead>
          <tbody>
            <tr><td class="row-label">Transistor OFF (no base signal)</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="on/off"></td></tr>
            <tr><td class="row-label">Transistor ON (base connected to +)</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="on/off"></td></tr>
            <tr><td class="row-label">Transistor ON via finger</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="dim/bright/off"></td></tr>
          </tbody>
        </table>
      </div>

      <div class="observe-box">
        <div class="observe-title">🔍 What the Voltages Tell You</div>
        <p style="margin:0; font-size:0.92rem;">When OFF: collector sits near full battery voltage (9V) because no current flows — no voltage drop across the LED/resistor. When ON (saturated): collector drops to near 0V (called V<sub>CE(sat)</sub> ≈ 0.2V) because the transistor is acting like a closed switch. The base sits at ~0.7V above emitter. These are the exact voltages engineers measure to confirm a transistor is switching correctly.</p>
      </div>
    </div>

    <!-- MINI EXP 4 -->
    <div class="mini-exp">
      <div class="mini-exp-badge">🧪 Mini-Experiment 4</div>
      <div class="mini-exp-title">Transistor + Capacitor = Automatic Timed Switch</div>
      <p style="margin-bottom:0.8rem;">Now you'll combine what you learned in Session 2 (RC circuits) with the transistor switch. The capacitor will slowly charge up and then trigger the transistor, making the LED turn on automatically after a delay.</p>

      <div class="predict-box">
        <div class="predict-title">✏️ Predict the Delay</div>
        Using 10kΩ charging resistor and 100µF capacitor: τ = <input class="predict-input" style="width:70px;" placeholder="?"> seconds.<br>
        NPN transistor turns on when base reaches ~0.7V. This happens at approximately 0.7 ÷ 9V ≈ 7.8% of charge, which is about <input class="predict-input" style="width:70px;" placeholder="?"> seconds after power-on. (Hint: use the formula t = −τ × ln(1 − 0.078))
      </div>

      <ol class="mini-exp-steps">
        <li><span><strong>Build the delay circuit:</strong> From + rail → 10kΩ → junction point A. From junction point A → 100µF capacitor positive leg → ground (negative leg). Also from junction point A → 1kΩ base resistor → transistor Base. Transistor Collector → 330Ω → LED → + rail. Transistor Emitter → ground.</span></li>
        <li><span>Make sure the capacitor is fully discharged before starting — touch both legs together briefly (safe: it's only charged to 9V). Disconnect battery.</span></li>
        <li><span>Connect the battery and start a timer. Watch the LED — at what point does it start to glow?</span></li>
        <li><span>Note how the LED starts very faint and gradually brightens as the capacitor charges further above 0.7V. This is not a perfect on/off switch here — it shows the gradual turn-on as V<sub>BE</sub> increases.</span></li>
        <li><span>Try replacing the 100µF cap with the 1000µF cap. How much longer is the delay? Does it match the 10× prediction from τ = RC?</span></li>
      </ol>

      <div class="observe-box">
        <div class="observe-title">🔍 What's Happening</div>
        <p style="margin:0; font-size:0.92rem;">The capacitor charges exponentially. Once it crosses ~0.6–0.7V, the base-emitter junction becomes forward biased and the transistor begins to conduct. This is a rudimentary timer. With a Schmitt trigger (which you'll study later), you can make the transition sharp — either fully OFF or fully ON with no gradual dimming. This principle powers 555 timer circuits, which you'll build in a future session.</p>
      </div>
    </div>

    <div class="subsection">
      <div class="subsection-title amber">4.4 — Transistor vs Manual Switch: A Comparison</div>
    </div>

    <table class="compare-table">
      <thead>
        <tr><th>Property</th><th>Manual Switch</th><th>NPN Transistor Switch</th></tr>
      </thead>
      <tbody>
        <tr><td class="row-head">How it switches</td><td>Physical finger press</td><td class="good">Electrical signal (0.7V + small current)</td></tr>
        <tr><td class="row-head">Switching speed</td><td class="bad">~100ms (limited by human reflexes)</td><td class="good">Nanoseconds (millions of times per second)</td></tr>
        <tr><td class="row-head">Can be controlled by microcontroller?</td><td class="bad">No</td><td class="good">Yes — this is how Arduino controls motors, LEDs, relays</td></tr>
        <tr><td class="row-head">Wears out?</td><td class="bad">Yes — mechanical switches wear out</td><td class="good">No moving parts — essentially unlimited switching cycles</td></tr>
        <tr><td class="row-head">Size</td><td class="bad">Large</td><td class="good">Microscopic (chips have billions)</td></tr>
        <tr><td class="row-head">Isolates control from load?</td><td class="bad">No (same circuit)</td><td class="good">Yes — small signal circuit fully separate from switched circuit</td></tr>
      </tbody>
    </table>

  </div>

  <!-- ═══ GRAND CHALLENGE ═══ -->
  <div class="challenge">
    <div class="challenge-label">⚡ Grand Challenge — Session 03</div>
    <div class="challenge-title">Build a Transistor-Controlled Motor Driver with Protection</div>

    <p style="margin-bottom:1.5rem;">This is the most complex circuit you've built. You will use everything from all three sessions to design, calculate, build, and verify a complete transistor switch circuit that controls a load safely — with flyback protection. If you don't have a motor, substitute a buzzer or a relay (both are inductive loads) — if you have none of these, use two LEDs in parallel as your load.</p>

    <div class="subsection">
      <div class="subsection-title green">Part A — Design the Circuit on Paper First</div>
    </div>

    <p>Before touching any components, draw the full circuit. Your circuit must include:</p>

    <ol class="steps">
      <li><span>A <strong>9V power supply</strong> (battery).</span></li>
      <li><span>A <strong>load</strong> (motor / buzzer / relay / two parallel LEDs) connected between the + rail and the Collector of the transistor.</span></li>
      <li><span>A <strong>flyback diode</strong> (1N4007) placed across the load — <strong>cathode (stripe) to + rail, anode to Collector</strong>. This is reverse-biased during normal operation.</span></li>
      <li><span>A <strong>current-limiting resistor</strong> in series with the load if it's LEDs (calculate this — target 20mA per LED).</span></li>
      <li><span>An <strong>NPN transistor</strong> (BC547 or 2N2222) with Emitter to ground.</span></li>
      <li><span>A <strong>base resistor</strong> (calculate this — target 1–5mA base current for reliable saturation). Control voltage is 9V.</span></li>
      <li><span>A <strong>manual control wire</strong> at the base resistor input (touch to + rail = ON, disconnected = OFF).</span></li>
    </ol>

    <div class="predict-box" style="margin:1.5rem 0;">
      <div class="predict-title">✏️ Your Calculations (fill before building)</div>
      Load current (I<sub>C</sub>): <input class="predict-input" style="width:70px;" placeholder="? mA"> mA &nbsp;·&nbsp;
      Desired base current: <input class="predict-input" style="width:70px;" placeholder="? mA"> mA &nbsp;·&nbsp;
      Base resistor needed: R<sub>B</sub> = (9 − 0.7) ÷ I<sub>B</sub> = <input class="predict-input" style="width:80px;" placeholder="? Ω"> Ω<br><br>
      Nearest standard resistor from kit: <input class="predict-input" style="width:80px;" placeholder="? Ω"> Ω &nbsp;·&nbsp;
      Load resistor (if LEDs): <input class="predict-input" style="width:80px;" placeholder="? Ω"> Ω
    </div>

    <div class="subsection">
      <div class="subsection-title green">Part B — Build and Verify</div>
    </div>

    <ol class="steps">
      <li><span>Build your designed circuit on the breadboard exactly as drawn. Double-check: diode orientation (stripe to +), transistor pinout, capacitor polarity if used.</span></li>
      <li><span>Connect the battery. Load should be OFF (no control signal at base).</span></li>
      <li><span>Measure and record: V<sub>CE</sub> (collector to emitter), V<sub>BE</sub> (base to emitter), I<sub>C</sub> (you'll need to measure voltage across the load resistor and divide by R).</span></li>
      <li><span>Apply the control signal (touch base resistor input to + rail). Load should turn ON. Measure same three voltages again.</span></li>
    </ol>

    <div style="overflow-x:auto; margin:1rem 0;">
      <table class="exp-table">
        <thead><tr><th>Measurement</th><th>Transistor OFF</th><th>Transistor ON</th><th>Expected (ON)</th></tr></thead>
        <tbody>
          <tr><td class="row-label">V<sub>CE</sub> (Collector−Emitter)</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td style="color:var(--muted);">≈ 0.2V (saturated)</td></tr>
          <tr><td class="row-label">V<sub>BE</sub> (Base−Emitter)</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td style="color:var(--muted);">≈ 0.65–0.7V</td></tr>
          <tr><td class="row-label">V across load resistor</td><td><input placeholder="V"></td><td><input placeholder="V"></td><td><input placeholder="calculated"></td></tr>
          <tr><td class="row-label">Calculated I<sub>C</sub></td><td><input placeholder="mA"></td><td><input placeholder="mA"></td><td><input placeholder="target mA"></td></tr>
        </tbody>
      </table>
    </div>

    <div class="subsection">
      <div class="subsection-title green">Part C — Upgrade: Add a Capacitor-Based Time Delay ⭐⭐</div>
    </div>

    <p>Extend the circuit from Part B: instead of manually touching a wire to turn it on, use an RC delay circuit (from Experiment 4 earlier) to automatically trigger the transistor base after a calculated delay. Design the RC values so the load turns on approximately 3 seconds after power is connected.</p>

    <ol class="steps">
      <li><span>Choose R and C values so that τ = RC gives 3 seconds at the ~7.8% threshold. Rearrange: t<sub>threshold</sub> = −τ × ln(1 − 0.078) ≈ 0.081τ. So to get 3 seconds: τ = 3 ÷ 0.081 ≈ <strong>37 seconds</strong>. Nearest with your kit components?</span></li>
      <li><span>Add the delay RC circuit to the base of your transistor (capacitor charges via resistor from + rail, charges up to base until transistor triggers).</span></li>
      <li><span>Connect battery. Time the delay. How close is it to 3 seconds?</span></li>
      <li><span>Try different RC combinations. What's the longest delay you can create with your available components?</span></li>
    </ol>

    <div class="callout orange" style="margin-top:1.5rem;">
      <div class="callout-title">🎓 What You've Just Built</div>
      You've assembled a <strong>complete transistor-controlled switching circuit with flyback protection and automatic triggering</strong>. This exact circuit (scaled up with a power transistor or MOSFET) is how microcontrollers like Arduino drive motors, solenoids, relays, and high-power LEDs. The base resistor, flyback diode, and timing circuit are all real engineering decisions. You didn't just assemble a kit — you designed and calculated this from first principles.
    </div>
  </div>

  <!-- ═══ FOOTER ═══ -->
  <div class="session-footer">
    <div class="footer-title">✓ What You Learned Today</div>
    <div class="learned-grid">
      <div class="learned-item">Power: P = V×I, P = I²R, P = V²÷R</div>
      <div class="learned-item">Why resistor wattage ratings matter</div>
      <div class="learned-item">Inductors: magnetic energy storage</div>
      <div class="learned-item">RL time constant (τ = L÷R)</div>
      <div class="learned-item">Back-EMF and flyback diodes</div>
      <div class="learned-item">Diode I/V curve and forward voltage</div>
      <div class="learned-item">Reverse bias and breakdown voltage</div>
      <div class="learned-item">Five uses of diodes in real circuits</div>
      <div class="learned-item">NPN transistor: Base, Collector, Emitter</div>
      <div class="learned-item">Transistor as a switch (saturation/cutoff)</div>
      <div class="learned-item">Calculating base and collector resistors</div>
      <div class="learned-item">RC + transistor timing circuit</div>
    </div>

    <div class="callout green" style="margin-top:1.8rem;">
      <div class="callout-title">📚 Before Session 4 — Think About This</div>
      You've now built circuits that <em>switch</em> using a transistor. Session 4 will explore what happens when you use a transistor not as a binary switch (fully ON or fully OFF) but in the region between — where it amplifies signals. You'll also meet the <strong>MOSFET</strong>, a different type of transistor that is controlled by voltage rather than current and is how virtually all modern digital logic works. Meanwhile, look at something in your house — a fan, a lamp dimmer, a phone charger — and ask yourself: where do you think the transistors are, and what are they switching?
    </div>

    <div class="prog-bar" style="margin-top:2rem;">
      <div class="prog-dot done"></div>
      <div class="prog-dot done2"></div>
      <div class="prog-dot active"></div>
      <div class="prog-dot future"></div>
    </div>
    <div style="font-size:0.75rem; color:var(--muted); margin-top:0.6rem; font-family:'Orbitron',monospace; letter-spacing:0.05em;">SESSION 3 OF 4 (this round)</div>
  </div>

</div>

<script>
/* ──────────────── POWER VISUALISER ──────────────── */
function updatePower() {
  const v = parseFloat(document.getElementById('pwr-v').value);
  const i = parseFloat(document.getElementById('pwr-i').value);
  const p = v * i;

  document.getElementById('pwr-v-val').textContent = v.toFixed(1) + ' V';
  document.getElementById('pwr-i-val').textContent = (i * 1000).toFixed(0) + ' mA';
  document.getElementById('pwr-result').textContent = p.toFixed(3) + ' W';

  const maxP = 2.0;
  const pct  = Math.min(p / maxP * 100, 100);
  const bar  = document.getElementById('heat-bar');
  bar.style.width = pct + '%';

  let barColor, labelText;
  if (p < 0.05)       { barColor = '#4ade80'; labelText = 'Very cool — barely any dissipation'; }
  else if (p < 0.15)  { barColor = '#4ade80'; labelText = '= P = V × I · Safe for ¼W resistor'; }
  else if (p < 0.25)  { barColor = '#f5a523'; labelText = 'Approaching ¼W limit — getting warm'; }
  else if (p < 0.5)   { barColor = '#fb923c'; labelText = '⚠ Over ¼W — need a higher-rated resistor'; }
  else if (p < 1.0)   { barColor = '#f87171'; labelText = '⚠ Very hot — needs 1W+ resistor'; }
  else                { barColor = '#f87171'; labelText = '🔥 Danger! Standard resistors will fail'; }

  bar.style.background = barColor;
  document.getElementById('pwr-label').textContent = labelText;
}
updatePower();

/* ──────────────── POWER WORKSHEET CHECKER ──────────────── */
function chkP(qNum, correct, unit, tol) {
  const inputId = `pa${qNum}`;
  const fbId    = `pfb${qNum}`;
  const input   = document.getElementById(inputId);
  const fb      = document.getElementById(fbId);
  if (!input || !fb) return;

  const val = parseFloat(input.value);
  if (isNaN(val)) {
    fb.textContent = '⚠ Enter a number first.';
    fb.className = 'math-feedback wrong';
    return;
  }
  const pct = Math.abs(val - correct) / correct * 100;
  if (pct <= tol) {
    input.classList.add('correct'); input.classList.remove('wrong');
    fb.textContent = `✓ Correct! Exact answer: ${correct.toFixed(3)} ${unit}.`;
    fb.className = 'math-feedback correct';
  } else {
    input.classList.add('wrong'); input.classList.remove('correct');
    const hint = unit === 'W'  ? 'Use P = V² ÷ R  or  P = I² × R  or  P = V × I.' :
                 unit === 'mW' ? 'Convert to amps first (mA ÷ 1000), then P = V × I. Result in watts × 1000 = mW.' : '';
    fb.textContent = `✗ Not quite. ${hint}`;
    fb.className = 'math-feedback wrong';
  }
}
</script>
</body>
</html>
