<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Phiếu Ghi Danh Lớp Ôn Thi V-ACT – ĐHQG TP.HCM</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@300;400;500;600&family=Playfair+Display:ital,wght@0,600;1,500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --blue-900: #042C53;
    --blue-800: #0C447C;
    --blue-600: #185FA5;
    --blue-400: #378ADD;
    --blue-100: #B5D4F4;
    --blue-50:  #E6F1FB;
    --teal-800: #085041;
    --teal-600: #0F6E56;
    --teal-400: #1D9E75;
    --teal-100: #9FE1CB;
    --teal-50:  #E1F5EE;
    --amber-800: #633806;
    --amber-600: #854F0B;
    --amber-50:  #FAEEDA;
    --purple-800: #3C3489;
    --purple-600: #534AB7;
    --purple-50:  #EEEDFE;
    --red-400: #E24B4A;
    --gray-900: #1a1a2e;
    --gray-800: #2C2C2A;
    --gray-600: #5F5E5A;
    --gray-300: #D3D1C7;
    --gray-100: #F1EFE8;
    --white: #ffffff;
    --radius-sm: 6px;
    --radius-md: 10px;
    --radius-lg: 16px;
    --radius-xl: 24px;
    --shadow-sm: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.04);
    --shadow-md: 0 4px 16px rgba(0,0,0,0.08), 0 2px 6px rgba(0,0,0,0.05);
    --shadow-lg: 0 12px 40px rgba(0,0,0,0.12), 0 4px 12px rgba(0,0,0,0.06);
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Be Vietnam Pro', sans-serif;
    background: #f0f4f8;
    min-height: 100vh;
    padding: 2rem 1rem 4rem;
    color: var(--gray-800);
    line-height: 1.6;
  }

  /* ── PAGE WRAPPER ── */
  .page {
    max-width: 720px;
    margin: 0 auto;
  }

  /* ── HERO HEADER ── */
  .hero {
    background: var(--blue-800);
    border-radius: var(--radius-xl);
    padding: 2.5rem 2.5rem 2rem;
    margin-bottom: 1.5rem;
    position: relative;
    overflow: hidden;
  }
  .hero-deco {
    position: absolute;
    border-radius: 50%;
    border: 1.5px solid rgba(255,255,255,0.08);
  }
  .hero-deco.d1 { width:200px;height:200px;top:-60px;right:-60px; }
  .hero-deco.d2 { width:110px;height:110px;bottom:-30px;left:100px; }
  .hero-deco.d3 { width:60px;height:60px;top:30px;right:120px; }

  .hero-top {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 1rem;
    margin-bottom: 1.25rem;
  }

  .hero-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
  }
  .hb {
    display: inline-flex;
    align-items: center;
    gap: 5px;
    background: rgba(255,255,255,0.12);
    border: 0.5px solid rgba(255,255,255,0.25);
    border-radius: 20px;
    padding: 3px 10px;
    font-size: 11px;
    font-weight: 500;
    color: rgba(255,255,255,0.9);
    letter-spacing: 0.03em;
  }

  .hero-logo {
    background: rgba(255,255,255,0.15);
    border: 0.5px solid rgba(255,255,255,0.25);
    border-radius: var(--radius-md);
    padding: 6px 14px;
    font-size: 13px;
    font-weight: 600;
    color: #fff;
    letter-spacing: 0.06em;
    white-space: nowrap;
    flex-shrink: 0;
  }

  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 26px;
    font-weight: 600;
    color: #fff;
    line-height: 1.25;
    margin-bottom: 0.5rem;
  }
  .hero p {
    font-size: 13px;
    color: rgba(255,255,255,0.68);
    font-weight: 300;
    max-width: 480px;
  }

  .hero-stats {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 8px;
    margin-top: 1.5rem;
    padding-top: 1.5rem;
    border-top: 0.5px solid rgba(255,255,255,0.12);
  }
  .hs-item { text-align: center; }
  .hs-val {
    display: block;
    font-size: 20px;
    font-weight: 600;
    color: #fff;
    line-height: 1.1;
  }
  .hs-lbl {
    display: block;
    font-size: 10px;
    color: rgba(255,255,255,0.55);
    margin-top: 3px;
    letter-spacing: 0.03em;
  }

  /* ── PART OVERVIEW STRIP ── */
  .parts-strip {
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 8px;
    margin-bottom: 1.5rem;
  }
  .ps-item {
    background: var(--white);
    border: 0.5px solid var(--gray-300);
    border-radius: var(--radius-md);
    padding: 10px 10px 8px;
    text-align: center;
    box-shadow: var(--shadow-sm);
  }
  .ps-icon {
    width: 32px; height: 32px;
    border-radius: var(--radius-sm);
    display: flex; align-items: center; justify-content: center;
    font-size: 15px;
    margin: 0 auto 6px;
  }
  .ps-icon.tv  { background: var(--blue-50);   color: var(--blue-600); }
  .ps-icon.en  { background: var(--teal-50);   color: var(--teal-600); }
  .ps-icon.ma  { background: var(--amber-50);  color: var(--amber-600); }
  .ps-icon.sci { background: var(--purple-50); color: var(--purple-600); }
  .ps-name  { font-size: 11px; font-weight: 500; color: var(--gray-800); line-height: 1.3; }
  .ps-score { font-size: 10px; color: var(--gray-600); margin-top: 1px; }

  /* ── PROGRESS STEPPER ── */
  .stepper {
    display: flex;
    align-items: center;
    gap: 0;
    margin-bottom: 1.5rem;
  }
  .step-node {
    display: flex;
    align-items: center;
    gap: 8px;
    flex: 1;
  }
  .step-node:last-child { flex: none; }
  .step-circle {
    width: 34px; height: 34px;
    border-radius: 50%;
    border: 1.5px solid var(--gray-300);
    background: var(--white);
    display: flex; align-items: center; justify-content: center;
    font-size: 12px;
    font-weight: 500;
    color: var(--gray-600);
    flex-shrink: 0;
    transition: all 0.3s;
  }
  .step-node.active .step-circle {
    background: var(--blue-600);
    border-color: var(--blue-600);
    color: #fff;
  }
  .step-node.done .step-circle {
    background: var(--teal-600);
    border-color: var(--teal-600);
    color: #fff;
    font-size: 14px;
  }
  .step-label {
    display: flex;
    flex-direction: column;
  }
  .step-label .sn {
    font-size: 10px;
    color: var(--gray-600);
    letter-spacing: 0.04em;
    font-weight: 400;
  }
  .step-label .sl {
    font-size: 12px;
    font-weight: 500;
    color: var(--gray-800);
  }
  .step-node.active .step-label .sl { color: var(--blue-800); }
  .step-node.done   .step-label .sl { color: var(--teal-800); }
  .step-line {
    flex: 1;
    height: 1.5px;
    background: var(--gray-300);
    margin: 0 8px;
    transition: background 0.3s;
  }
  .step-line.done { background: var(--teal-400); }

  /* ── CARD SECTION ── */
  .sec-card {
    background: var(--white);
    border: 0.5px solid var(--gray-300);
    border-radius: var(--radius-lg);
    padding: 1.75rem 2rem;
    margin-bottom: 1.25rem;
    box-shadow: var(--shadow-sm);
    display: none;
  }
  .sec-card.visible { display: block; }

  .sec-header {
    display: flex;
    align-items: center;
    gap: 12px;
    padding-bottom: 1rem;
    margin-bottom: 1.5rem;
    border-bottom: 1px solid var(--gray-100);
  }
  .sec-icon {
    width: 38px; height: 38px;
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
  }
  .ic-blue   { background: var(--blue-50);   color: var(--blue-600); }
  .ic-teal   { background: var(--teal-50);   color: var(--teal-600); }
  .ic-amber  { background: var(--amber-50);  color: var(--amber-600); }

  .sec-header h2 { font-size: 15px; font-weight: 500; color: var(--gray-800); }
  .sec-header p  { font-size: 12px; color: var(--gray-600); margin-top: 1px; font-weight: 300; }

  /* ── FORM FIELDS ── */
  .frow { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; margin-bottom: 1.1rem; }
  .fg   { margin-bottom: 1.1rem; }
  .fg:last-child { margin-bottom: 0; }

  label.lbl {
    display: block;
    font-size: 11.5px;
    font-weight: 500;
    color: var(--gray-600);
    margin-bottom: 5px;
    letter-spacing: 0.02em;
  }
  .req {
    display: inline-block;
    width: 4px; height: 4px;
    border-radius: 50%;
    background: var(--red-400);
    vertical-align: middle;
    margin-left: 3px;
    margin-bottom: 2px;
  }

  input[type="text"],
  input[type="email"],
  input[type="tel"],
  input[type="date"],
  select,
  textarea {
    width: 100%;
    font-family: 'Be Vietnam Pro', sans-serif;
    font-size: 13px;
    color: var(--gray-800);
    background: #fff;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    padding: 9px 12px;
    outline: none;
    transition: border-color 0.15s, box-shadow 0.15s;
    appearance: none;
  }
  input:focus, select:focus, textarea:focus {
    border-color: var(--blue-400);
    box-shadow: 0 0 0 3px rgba(55, 138, 221, 0.12);
  }
  textarea { resize: vertical; min-height: 80px; line-height: 1.6; }
  select {
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='12' height='8' viewBox='0 0 12 8'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%235F5E5A' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");
    background-repeat: no-repeat;
    background-position: right 12px center;
    padding-right: 34px;
    cursor: pointer;
  }

  .hint { font-size: 11px; color: var(--gray-600); margin-top: 4px; font-weight: 300; line-height: 1.5; }

  /* ── RADIO / CHECKBOX ── */
  .radio-g, .chk-g { display: flex; flex-direction: column; gap: 7px; }
  .radio-g.row { flex-direction: row; flex-wrap: wrap; }
  .ro, .co {
    display: flex; align-items: center; gap: 10px;
    padding: 8px 13px;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    cursor: pointer;
    font-size: 13px;
    color: var(--gray-800);
    transition: all 0.15s;
    user-select: none;
  }
  .ro:hover, .co:hover { border-color: var(--blue-400); background: var(--blue-50); }
  .ro input, .co input {
    width: auto; flex-shrink: 0;
    accent-color: var(--blue-600);
    width: 15px; height: 15px;
  }
  .ro.flex1 { flex: 1; min-width: 160px; }

  /* ── TAGS ── */
  .tag-g { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 6px; }
  .tag {
    padding: 5px 13px;
    border: 1px solid var(--gray-300);
    border-radius: 20px;
    background: #fff;
    font-size: 12px;
    cursor: pointer;
    color: var(--gray-600);
    transition: all 0.15s;
    font-family: 'Be Vietnam Pro', sans-serif;
    font-weight: 400;
  }
  .tag:hover { border-color: var(--blue-400); color: var(--blue-600); }
  .tag.sel {
    background: var(--blue-50);
    border-color: var(--blue-600);
    color: var(--blue-800);
    font-weight: 500;
  }

  /* ── SELF-ASSESS CARDS ── */
  .assess-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 6px; }
  .ac {
    background: #fafafa;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    padding: 12px 13px;
  }
  .ac-head {
    display: flex; align-items: center; gap: 8px;
    margin-bottom: 8px;
  }
  .ac-dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    flex-shrink: 0;
  }
  .ac-dot.tv  { background: var(--blue-600); }
  .ac-dot.en  { background: var(--teal-600); }
  .ac-dot.ma  { background: var(--amber-600); }
  .ac-dot.sci { background: var(--purple-600); }
  .ac-name  { font-size: 12px; font-weight: 500; color: var(--gray-800); }
  .ac-score { font-size: 10px; color: var(--gray-600); }
  .scale-row { display: flex; gap: 4px; }
  .sb {
    flex: 1;
    padding: 5px 3px;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-sm);
    background: #fff;
    font-size: 12px;
    font-weight: 500;
    cursor: pointer;
    text-align: center;
    color: var(--gray-600);
    transition: all 0.15s;
    font-family: 'Be Vietnam Pro', sans-serif;
  }
  .sb:hover { border-color: var(--blue-400); color: var(--blue-600); }
  .sb.sel   { background: var(--blue-600); border-color: var(--blue-600); color: #fff; }
  .sb.sel.teal   { background: var(--teal-600); border-color: var(--teal-600); }
  .sb.sel.amber  { background: var(--amber-600); border-color: var(--amber-600); }
  .sb.sel.purple { background: var(--purple-600); border-color: var(--purple-600); }
  .scale-lbl {
    display: flex; justify-content: space-between;
    margin-top: 3px;
    font-size: 10px; color: var(--gray-600);
  }

  /* ── SINGLE SCALE (for motivation) ── */
  .scale-full { display: flex; gap: 5px; margin-top: 6px; }
  .scale-full .sb { flex: 1; padding: 7px 4px; font-size: 13px; }

  /* ── TARGET RANGE BUTTONS ── */
  .target-grid { display: grid; grid-template-columns: repeat(5,1fr); gap: 6px; margin-top: 6px; }
  .tg-btn {
    padding: 9px 4px;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    background: #fff;
    text-align: center;
    cursor: pointer;
    transition: all 0.15s;
    font-family: 'Be Vietnam Pro', sans-serif;
  }
  .tg-btn .tv { display: block; font-size: 13px; font-weight: 500; color: var(--gray-800); }
  .tg-btn .ts { display: block; font-size: 10px; color: var(--gray-600); margin-top: 1px; }
  .tg-btn:hover { border-color: var(--blue-400); background: var(--blue-50); }
  .tg-btn.sel   { border-color: var(--blue-600); background: var(--blue-50); }
  .tg-btn.sel .tv { color: var(--blue-800); }

  /* ── INFO BOX ── */
  .info-box {
    display: flex; align-items: flex-start; gap: 10px;
    background: var(--blue-50);
    border: 0.5px solid var(--blue-100);
    border-radius: var(--radius-md);
    padding: 11px 14px;
    font-size: 12px;
    color: var(--blue-800);
    margin-bottom: 1.25rem;
    line-height: 1.6;
  }
  .info-box svg { flex-shrink: 0; margin-top: 1px; }

  /* ── COMMITMENT SECTION ── */
  .commit-box {
    background: var(--gray-100);
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    padding: 14px 16px;
    font-size: 12.5px;
    color: var(--gray-800);
    line-height: 1.7;
    margin-bottom: 1.1rem;
  }
  .commit-box h4 { font-size: 13px; font-weight: 500; margin-bottom: 8px; color: var(--blue-800); }
  .commit-box ul { padding-left: 16px; }
  .commit-box ul li { margin-bottom: 3px; }

  .sign-row { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }

  /* ── NAV BUTTONS ── */
  .nav {
    display: flex; gap: 10px;
    justify-content: flex-end;
    margin-top: 1.75rem;
    padding-top: 1.25rem;
    border-top: 1px solid var(--gray-100);
  }
  .btn-prev {
    padding: 9px 20px;
    border: 1px solid var(--gray-300);
    border-radius: var(--radius-md);
    background: #fff;
    font-size: 13px;
    font-weight: 500;
    cursor: pointer;
    color: var(--gray-600);
    font-family: 'Be Vietnam Pro', sans-serif;
    transition: all 0.15s;
    display: flex; align-items: center; gap: 6px;
  }
  .btn-prev:hover { background: var(--gray-100); }
  .btn-next {
    padding: 9px 24px;
    border: none;
    border-radius: var(--radius-md);
    background: var(--blue-600);
    font-size: 13px;
    font-weight: 500;
    cursor: pointer;
    color: #fff;
    font-family: 'Be Vietnam Pro', sans-serif;
    display: flex; align-items: center; gap: 6px;
    transition: all 0.15s;
    box-shadow: 0 2px 8px rgba(24,95,165,0.25);
  }
  .btn-next:hover { background: var(--blue-800); }
  .btn-submit {
    padding: 10px 28px;
    border: none;
    border-radius: var(--radius-md);
    background: var(--teal-600);
    font-size: 13px;
    font-weight: 500;
    cursor: pointer;
    color: #fff;
    font-family: 'Be Vietnam Pro', sans-serif;
    display: flex; align-items: center; gap: 6px;
    transition: all 0.15s;
    box-shadow: 0 2px 8px rgba(15,110,86,0.25);
  }
  .btn-submit:hover { background: var(--teal-800); }

  /* ── SUCCESS ── */
  .success-card {
    background: #fff;
    border: 0.5px solid var(--teal-100);
    border-radius: var(--radius-xl);
    padding: 3rem 2rem;
    text-align: center;
    display: none;
    box-shadow: var(--shadow-md);
  }
  .ok-ring {
    width: 68px; height: 68px;
    border-radius: 50%;
    background: var(--teal-50);
    border: 2px solid var(--teal-100);
    display: flex; align-items: center; justify-content: center;
    margin: 0 auto 1.25rem;
    font-size: 28px;
  }
  .success-card h2 {
    font-family: 'Playfair Display', serif;
    font-size: 22px; font-weight: 600;
    color: var(--teal-800);
    margin-bottom: 0.5rem;
  }
  .success-card p {
    font-size: 13px; color: var(--gray-600);
    line-height: 1.7; max-width: 400px; margin: 0 auto;
  }
  .success-card .link-btn {
    display: inline-flex; align-items: center; gap: 6px;
    margin-top: 1.5rem;
    padding: 9px 22px;
    border-radius: var(--radius-md);
    border: 1px solid var(--blue-100);
    background: var(--blue-50);
    color: var(--blue-800);
    font-size: 12px; font-weight: 500;
    text-decoration: none;
    transition: all 0.15s;
  }
  .success-card .link-btn:hover { background: var(--blue-100); }

  /* ── FOOTER ── */
  .form-footer {
    text-align: center;
    margin-top: 2rem;
    font-size: 11px;
    color: var(--gray-600);
    font-weight: 300;
    line-height: 1.7;
  }
  .form-footer a { color: var(--blue-600); text-decoration: none; }

  /* ── RESPONSIVE ── */
  @media (max-width: 600px) {
    body { padding: 1rem 0.75rem 3rem; }
    .hero { padding: 1.75rem 1.5rem 1.5rem; }
    .hero h1 { font-size: 20px; }
    .hero-stats { grid-template-columns: repeat(2, 1fr); }
    .parts-strip { grid-template-columns: repeat(2, 1fr); }
    .sec-card { padding: 1.25rem 1.25rem; }
    .frow { grid-template-columns: 1fr; }
    .assess-grid { grid-template-columns: 1fr; }
    .target-grid { grid-template-columns: repeat(3, 1fr); }
    .sign-row { grid-template-columns: 1fr; }
    .stepper .step-label { display: none; }
    .hero-top { flex-direction: column; gap: 0.75rem; }
  }
</style>
</head>
<body>
<div class="page">

  <!-- HERO -->
  <div class="hero">
    <div class="hero-deco d1"></div>
    <div class="hero-deco d2"></div>
    <div class="hero-deco d3"></div>
    <div class="hero-top">
      <div class="hero-badges">
        <span class="hb">&#127891; Kỳ thi V-ACT</span>
        <span class="hb">&#127968; ĐHQG TP.HCM</span>
        <span class="hb">&#128218; Học sinh lớp 12</span>
      </div>
      <div class="hero-logo">V-ACT 2026</div>
    </div>
    <h1 style="text-transform:uppercase;letter-spacing:0.04em;">Phiếu ghi danh lớp ôn thi<br>Đánh giá Năng lực TVIM</h1>
    <p>Điền đầy đủ để thầy/cô xây dựng lộ trình ôn thi phù hợp — bám sát cấu trúc đề V-ACT 2025–2026 của ĐHQG TP.HCM.</p>
    <div class="hero-stats">
      <div class="hs-item"><span class="hs-val">120</span><span class="hs-lbl">câu trắc nghiệm</span></div>
      <div class="hs-item"><span class="hs-val">150'</span><span class="hs-lbl">thời gian làm bài</span></div>
      <div class="hs-item"><span class="hs-val">1.200</span><span class="hs-lbl">điểm tối đa</span></div>
      <div class="hs-item"><span class="hs-val">111+</span><span class="hs-lbl">trường dùng kết quả</span></div>
    </div>
  </div>

  <!-- 4 PARTS -->
  <div class="parts-strip">
    <div class="ps-item">
      <div class="ps-icon tv">&#128214;</div>
      <div class="ps-name">Tiếng Việt</div>
      <div class="ps-score">tối đa 300 điểm</div>
    </div>
    <div class="ps-item">
      <div class="ps-icon en">&#127758;</div>
      <div class="ps-name">Tiếng Anh</div>
      <div class="ps-score">tối đa 300 điểm</div>
    </div>
    <div class="ps-item">
      <div class="ps-icon ma">&#10133;</div>
      <div class="ps-name">Toán học</div>
      <div class="ps-score">tối đa 300 điểm</div>
    </div>
    <div class="ps-item">
      <div class="ps-icon sci">&#128300;</div>
      <div class="ps-name">Tư duy khoa học</div>
      <div class="ps-score">tối đa 300 điểm</div>
    </div>
  </div>

  <!-- STEPPER -->
  <div class="stepper" id="stepper">
    <div class="step-node active" id="sn1">
      <div class="step-circle" id="sc1">1</div>
      <div class="step-label"><span class="sn">Bước 1</span><span class="sl">Cá nhân</span></div>
    </div>
    <div class="step-line" id="sl1"></div>
    <div class="step-node" id="sn2">
      <div class="step-circle" id="sc2">2</div>
      <div class="step-label"><span class="sn">Bước 2</span><span class="sl">Năng lực</span></div>
    </div>
    <div class="step-line" id="sl2"></div>
    <div class="step-node" id="sn3">
      <div class="step-circle" id="sc3">3</div>
      <div class="step-label"><span class="sn">Bước 3</span><span class="sl">Mục tiêu</span></div>
    </div>
    <div class="step-line" id="sl3"></div>
    <div class="step-node" id="sn4">
      <div class="step-circle" id="sc4">4</div>
      <div class="step-label"><span class="sn">Bước 4</span><span class="sl">Đăng ký</span></div>
    </div>
    <div class="step-line" id="sl4"></div>
    <div class="step-node" id="sn5">
      <div class="step-circle" id="sc5">5</div>
      <div class="step-label"><span class="sn">Bước 5</span><span class="sl">Cam kết</span></div>
    </div>
  </div>

  <!-- ===== STEP 1: THÔNG TIN CÁ NHÂN ===== -->
  <div class="sec-card visible" id="step-1">
    <div class="sec-header">
      <div class="sec-icon ic-blue">&#128100;</div>
      <div>
        <h2>Thông tin cá nhân</h2>
        <p>Để thầy/cô liên hệ và lập hồ sơ học sinh</p>
      </div>
    </div>

    <div class="frow">
      <div class="fg">
        <label class="lbl">Họ và tên học sinh <span class="req"></span></label>
        <input type="text" id="hoten" placeholder="Nguyễn Văn A" />
      </div>
      <div class="fg">
        <label class="lbl">Ngày sinh <span class="req"></span></label>
        <input type="date" id="ngaysinh" />
      </div>
    </div>

    <div class="frow">
      <div class="fg">
        <label class="lbl">Số điện thoại học sinh <span class="req"></span></label>
        <input type="tel" id="sdt_hs" placeholder="09x xxx xxxx" />
      </div>
      <div class="fg">
        <label class="lbl">Email</label>
        <input type="email" id="email" placeholder="email@example.com" />
      </div>
    </div>

    <div class="frow">
      <div class="fg">
        <label class="lbl">Số điện thoại phụ huynh <span class="req"></span></label>
        <input type="tel" id="sdt_ph" placeholder="09x xxx xxxx" />
      </div>
      <div class="fg">
        <label class="lbl">Địa chỉ / Quận – Tỉnh thành</label>
        <input type="text" id="diachi" placeholder="Q.1, TP.HCM" />
      </div>
    </div>

    <div class="frow">
      <div class="fg">
        <label class="lbl">Trường THPT đang học <span class="req"></span></label>
        <input type="text" id="truong" placeholder="THPT Nguyễn Thị Minh Khai" />
      </div>
      <div class="fg">
        <label class="lbl">Tỉnh / Thành phố</label>
        <select id="tinh">
          <option value="" disabled selected>Chọn tỉnh thành</option>
          <option>TP. Hồ Chí Minh</option>
          <option>Bình Dương</option>
          <option>Đồng Nai</option>
          <option>Long An</option>
          <option>Tây Ninh</option>
          <option>Bà Rịa – Vũng Tàu</option>
          <option>Tiền Giang</option>
          <option>Khánh Hòa</option>
          <option>Đà Nẵng</option>
          <option>Tỉnh khác</option>
        </select>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Tổ hợp môn đang học (chương trình GDPT 2018)</label>
      <div class="radio-g row">
        <label class="ro flex1"><input type="radio" name="tohop" /> Tự nhiên (Lý – Hóa – Sinh / Toán)</label>
        <label class="ro flex1"><input type="radio" name="tohop" /> Xã hội (Sử – Địa – KTPL)</label>
        <label class="ro flex1"><input type="radio" name="tohop" /> Kết hợp tự nhiên & xã hội</label>
        <label class="ro flex1"><input type="radio" name="tohop" /> Tổ hợp khác / chưa xác định</label>
      </div>
      <p class="hint">V-ACT không phụ thuộc tổ hợp môn — đề thi đánh giá năng lực tổng quát, phù hợp mọi thí sinh.</p>
    </div>

    <div class="fg">
      <label class="lbl">Học lực học kỳ gần nhất</label>
      <div class="radio-g row">
        <label class="ro flex1"><input type="radio" name="hocl" /> Giỏi (8.0 – 10)</label>
        <label class="ro flex1"><input type="radio" name="hocl" /> Khá (6.5 – 7.9)</label>
        <label class="ro flex1"><input type="radio" name="hocl" /> Trung bình (5.0 – 6.4)</label>
        <label class="ro flex1"><input type="radio" name="hocl" /> Dưới TB</label>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Bạn biết đến lớp học qua kênh nào?</label>
      <div class="tag-g">
        <button class="tag" onclick="tog(this)">Facebook / Mạng xã hội</button>
        <button class="tag" onclick="tog(this)">Bạn bè giới thiệu</button>
        <button class="tag" onclick="tog(this)">Giáo viên tư vấn</button>
        <button class="tag" onclick="tog(this)">Website / Zalo trung tâm</button>
        <button class="tag" onclick="tog(this)">TikTok / YouTube</button>
        <button class="tag" onclick="tog(this)">Khác</button>
      </div>
    </div>

    <div class="nav">
      <button class="btn-next" onclick="go(2)">Tiếp theo &#8594;</button>
    </div>
  </div>

  <!-- ===== STEP 2: KHẢO SÁT NĂNG LỰC ===== -->
  <div class="sec-card" id="step-2">
    <div class="sec-header">
      <div class="sec-icon ic-teal">&#129504;</div>
      <div>
        <h2>Khảo sát năng lực theo 4 phần thi V-ACT</h2>
        <p>Đánh giá trung thực để có lộ trình ôn luyện chính xác</p>
      </div>
    </div>

    <div class="info-box">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg>
      <span>Cấu trúc V-ACT 2025–2026: <strong>Tiếng Việt (300đ) · Tiếng Anh (300đ) · Toán học (300đ) · Tư duy khoa học (300đ)</strong> — 120 câu · 150 phút · thi trên giấy.</span>
    </div>

    <div class="fg">
      <label class="lbl">Tự đánh giá năng lực từng phần thi (1 = còn yếu, 5 = tự tin)</label>
      <div class="assess-grid">
        <div class="ac">
          <div class="ac-head">
            <div class="ac-dot tv"></div>
            <div><div class="ac-name">Tiếng Việt</div><div class="ac-score">300 điểm · đọc hiểu, nghị luận</div></div>
          </div>
          <div class="scale-row" id="sc-tv">
            <button class="sb" onclick="scl(this,'sc-tv','')">1</button>
            <button class="sb" onclick="scl(this,'sc-tv','')">2</button>
            <button class="sb" onclick="scl(this,'sc-tv','')">3</button>
            <button class="sb" onclick="scl(this,'sc-tv','')">4</button>
            <button class="sb" onclick="scl(this,'sc-tv','')">5</button>
          </div>
          <div class="scale-lbl"><span>Còn yếu</span><span>Tự tin</span></div>
        </div>
        <div class="ac">
          <div class="ac-head">
            <div class="ac-dot en"></div>
            <div><div class="ac-name">Tiếng Anh</div><div class="ac-score">300 điểm · từ vựng, đọc hiểu</div></div>
          </div>
          <div class="scale-row" id="sc-en">
            <button class="sb" onclick="scl(this,'sc-en','teal')">1</button>
            <button class="sb" onclick="scl(this,'sc-en','teal')">2</button>
            <button class="sb" onclick="scl(this,'sc-en','teal')">3</button>
            <button class="sb" onclick="scl(this,'sc-en','teal')">4</button>
            <button class="sb" onclick="scl(this,'sc-en','teal')">5</button>
          </div>
          <div class="scale-lbl"><span>Còn yếu</span><span>Tự tin</span></div>
        </div>
        <div class="ac">
          <div class="ac-head">
            <div class="ac-dot ma"></div>
            <div><div class="ac-name">Toán học</div><div class="ac-score">300 điểm · đại số, hình học, logic</div></div>
          </div>
          <div class="scale-row" id="sc-ma">
            <button class="sb" onclick="scl(this,'sc-ma','amber')">1</button>
            <button class="sb" onclick="scl(this,'sc-ma','amber')">2</button>
            <button class="sb" onclick="scl(this,'sc-ma','amber')">3</button>
            <button class="sb" onclick="scl(this,'sc-ma','amber')">4</button>
            <button class="sb" onclick="scl(this,'sc-ma','amber')">5</button>
          </div>
          <div class="scale-lbl"><span>Còn yếu</span><span>Tự tin</span></div>
        </div>
        <div class="ac">
          <div class="ac-head">
            <div class="ac-dot sci"></div>
            <div><div class="ac-name">Tư duy khoa học</div><div class="ac-score">300 điểm · suy luận, phân tích</div></div>
          </div>
          <div class="scale-row" id="sc-sci">
            <button class="sb" onclick="scl(this,'sc-sci','purple')">1</button>
            <button class="sb" onclick="scl(this,'sc-sci','purple')">2</button>
            <button class="sb" onclick="scl(this,'sc-sci','purple')">3</button>
            <button class="sb" onclick="scl(this,'sc-sci','purple')">4</button>
            <button class="sb" onclick="scl(this,'sc-sci','purple')">5</button>
          </div>
          <div class="scale-lbl"><span>Còn yếu</span><span>Tự tin</span></div>
        </div>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Bạn đã ôn thi V-ACT ở đâu chưa?</label>
      <div class="radio-g">
        <label class="ro"><input type="radio" name="onthi" /> Chưa ôn ở đâu, đây là lần đầu</label>
        <label class="ro"><input type="radio" name="onthi" /> Tự ôn tại nhà (sách, YouTube, đề mạng)</label>
        <label class="ro"><input type="radio" name="onthi" /> Đã học ở trung tâm khác</label>
        <label class="ro"><input type="radio" name="onthi" /> Đã thi thật hoặc thi thử V-ACT rồi</label>
      </div>
    </div>

    <div class="frow">
      <div class="fg">
        <label class="lbl">Điểm thi thử V-ACT gần nhất (nếu có)</label>
        <input type="text" placeholder="Ví dụ: 720/1200" />
        <p class="hint">Bỏ qua nếu chưa thi thử lần nào.</p>
      </div>
      <div class="fg">
        <label class="lbl">Mỗi ngày bạn có thể học thêm bao lâu?</label>
        <select>
          <option value="" disabled selected>Chọn thời gian</option>
          <option>Dưới 1 tiếng / ngày</option>
          <option>1 – 2 tiếng / ngày</option>
          <option>2 – 3 tiếng / ngày</option>
          <option>Trên 3 tiếng / ngày</option>
        </select>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Dạng câu hỏi / kỹ năng bạn còn yếu nhất trong đề V-ACT</label>
      <div class="tag-g">
        <button class="tag" onclick="tog(this)">Đọc hiểu Tiếng Việt</button>
        <button class="tag" onclick="tog(this)">Từ vựng & ngữ pháp Tiếng Anh</button>
        <button class="tag" onclick="tog(this)">Reading Comprehension (Anh)</button>
        <button class="tag" onclick="tog(this)">Toán tư duy & logic số</button>
        <button class="tag" onclick="tog(this)">Hình học & đại số</button>
        <button class="tag" onclick="tog(this)">Tư duy khoa học thực nghiệm</button>
        <button class="tag" onclick="tog(this)">Phân tích số liệu / biểu đồ</button>
        <button class="tag" onclick="tog(this)">Quản lý thời gian 150 phút</button>
      </div>
    </div>

    <div class="nav">
      <button class="btn-prev" onclick="go(1)">&#8592; Quay lại</button>
      <button class="btn-next" onclick="go(3)">Tiếp theo &#8594;</button>
    </div>
  </div>

  <!-- ===== STEP 3: MỤC TIÊU ===== -->
  <div class="sec-card" id="step-3">
    <div class="sec-header">
      <div class="sec-icon ic-amber">&#127919;</div>
      <div>
        <h2>Mục tiêu & định hướng xét tuyển</h2>
        <p>Điểm đến quyết định cường độ và lộ trình ôn luyện</p>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Điểm V-ACT mục tiêu bạn muốn đạt <span class="req"></span></label>
      <div class="target-grid" id="tg-grid">
        <button class="tg-btn" onclick="selTarget(this)"><span class="tv">≤ 700</span><span class="ts">nhập môn</span></button>
        <button class="tg-btn" onclick="selTarget(this)"><span class="tv">700–800</span><span class="ts">khá tốt</span></button>
        <button class="tg-btn" onclick="selTarget(this)"><span class="tv">800–900</span><span class="ts">tốt</span></button>
        <button class="tg-btn" onclick="selTarget(this)"><span class="tv">900–1000</span><span class="ts">xuất sắc</span></button>
        <button class="tg-btn" onclick="selTarget(this)"><span class="tv">1000+</span><span class="ts">top đầu</span></button>
      </div>
      <p class="hint">Điểm trung bình V-ACT năm 2025 khoảng 600–700. Mục tiêu 900+ cần ôn luyện chuyên sâu ít nhất 3–4 tháng.</p>
    </div>

    <div class="fg">
      <label class="lbl">Ngành / lĩnh vực bạn muốn xét tuyển bằng điểm V-ACT</label>
      <div class="tag-g">
        <button class="tag" onclick="tog(this)">Kinh tế / Quản trị kinh doanh</button>
        <button class="tag" onclick="tog(this)">Công nghệ thông tin</button>
        <button class="tag" onclick="tog(this)">Kỹ thuật – Công nghệ</button>
        <button class="tag" onclick="tog(this)">Y – Dược</button>
        <button class="tag" onclick="tog(this)">Luật</button>
        <button class="tag" onclick="tog(this)">Sư phạm</button>
        <button class="tag" onclick="tog(this)">Ngôn ngữ / Báo chí</button>
        <button class="tag" onclick="tog(this)">Khoa học xã hội & Nhân văn</button>
        <button class="tag" onclick="tog(this)">Kiến trúc / Thiết kế</button>
        <button class="tag" onclick="tog(this)">Chưa xác định</button>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Trường đại học đang nhắm tới</label>
      <input type="text" placeholder="Ví dụ: HCMUS, HCMUT, UEL, HCMULAW, UIT, BKU..." />
      <p class="hint">Hơn 111 trường ĐH, CĐ trên cả nước sử dụng kết quả V-ACT để xét tuyển năm 2025.</p>
    </div>

    <div class="fg">
      <label class="lbl">Bạn có kết hợp phương thức xét tuyển nào khác không?</label>
      <div class="chk-g">
        <label class="co"><input type="checkbox" /> Điểm thi tốt nghiệp THPT 2026</label>
        <label class="co"><input type="checkbox" /> Học bạ (xét điểm GPA)</label>
        <label class="co"><input type="checkbox" /> Chứng chỉ ngoại ngữ quốc tế (IELTS, TOEFL, SAT…)</label>
        <label class="co"><input type="checkbox" /> Chỉ dùng V-ACT</label>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Mức độ quyết tâm chinh phục V-ACT</label>
      <div class="scale-full" id="sc-quyet">
        <button class="sb" onclick="scl(this,'sc-quyet','')">1</button>
        <button class="sb" onclick="scl(this,'sc-quyet','')">2</button>
        <button class="sb" onclick="scl(this,'sc-quyet','')">3</button>
        <button class="sb" onclick="scl(this,'sc-quyet','')">4</button>
        <button class="sb" onclick="scl(this,'sc-quyet','')">5</button>
      </div>
      <div class="scale-lbl"><span>Còn phân vân</span><span>Quyết tâm 100%</span></div>
    </div>

    <div class="fg">
      <label class="lbl">Bạn kỳ vọng điều gì nhất từ lớp học?</label>
      <div class="tag-g">
        <button class="tag" onclick="tog(this)">Tăng điểm nhanh, hiệu quả</button>
        <button class="tag" onclick="tog(this)">Nắm chắc cấu trúc đề V-ACT</button>
        <button class="tag" onclick="tog(this)">Luyện đề thực chiến nhiều</button>
        <button class="tag" onclick="tog(this)">Chiến lược phân bổ 150 phút</button>
        <button class="tag" onclick="tog(this)">Được giải thích kỹ từng dạng bài</button>
        <button class="tag" onclick="tog(this)">Hỗ trợ sát sao từ thầy/cô</button>
        <button class="tag" onclick="tog(this)">Lộ trình cá nhân hóa từng phần</button>
        <button class="tag" onclick="tog(this)">Học cùng nhóm bạn cùng mục tiêu</button>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Bạn muốn nhắn gì thêm với thầy/cô tư vấn?</label>
      <textarea placeholder="Tình hình học tập, câu hỏi cụ thể, điều kiện đặc biệt hoặc bất kỳ điều gì bạn muốn chia sẻ..."></textarea>
    </div>

    <div class="nav">
      <button class="btn-prev" onclick="go(2)">&#8592; Quay lại</button>
      <button class="btn-next" onclick="go(4)">Tiếp theo &#8594;</button>
    </div>
  </div>

  <!-- ===== STEP 4: HÌNH THỨC & THỜI GIAN HỌC ===== -->
  <div class="sec-card" id="step-4">
    <div class="sec-header">
      <div class="sec-icon ic-blue">&#128197;</div>
      <div>
        <h2>Hình thức & thời gian học</h2>
        <p>Chọn hình thức phù hợp với lịch sinh hoạt của bạn</p>
      </div>
    </div>

    <div class="fg">
      <label class="lbl">Hình thức đăng ký <span class="req"></span></label>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:6px;">

        <label style="cursor:pointer;">
          <input type="radio" name="hinhthuc" value="offline" style="display:none;" onchange="selectHinhThuc('offline')" />
          <div class="ht-card" id="ht-offline" onclick="this.previousElementSibling.click()" style="border:1.5px solid var(--gray-300);border-radius:var(--radius-md);padding:16px 14px;transition:all .2s;background:#fff;">
            <div style="display:flex;align-items:center;gap:8px;margin-bottom:10px;">
              <div style="width:34px;height:34px;border-radius:8px;background:var(--blue-50);display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0;">&#127979;</div>
              <div>
                <div style="font-size:14px;font-weight:500;color:var(--gray-800);">OFFLINE</div>
                <div style="font-size:11px;color:var(--gray-600);">Học trực tiếp tại trung tâm</div>
              </div>
            </div>
            <div style="background:var(--blue-50);border-radius:var(--radius-sm);padding:10px 12px;">
              <div style="display:flex;align-items:center;gap:6px;margin-bottom:5px;">
                <span style="font-size:11px;font-weight:500;color:var(--blue-800);">&#128197; Ngày học</span>
              </div>
              <div style="font-size:12px;color:var(--blue-800);font-weight:500;">Thứ 7 & Chủ nhật</div>
              <div style="display:flex;align-items:center;gap:6px;margin-top:7px;margin-bottom:4px;">
                <span style="font-size:11px;font-weight:500;color:var(--blue-800);">&#128336; Giờ học</span>
              </div>
              <div style="font-size:13px;font-weight:600;color:var(--blue-800);">15:30 – 17:30</div>
            </div>
          </div>
        </label>

        <label style="cursor:pointer;">
          <input type="radio" name="hinhthuc" value="online" style="display:none;" onchange="selectHinhThuc('online')" />
          <div class="ht-card" id="ht-online" onclick="this.previousElementSibling.click()" style="border:1.5px solid var(--gray-300);border-radius:var(--radius-md);padding:16px 14px;transition:all .2s;background:#fff;">
            <div style="display:flex;align-items:center;gap:8px;margin-bottom:10px;">
              <div style="width:34px;height:34px;border-radius:8px;background:var(--teal-50);display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0;">&#128187;</div>
              <div>
                <div style="font-size:14px;font-weight:500;color:var(--gray-800);">ONLINE</div>
                <div style="font-size:11px;color:var(--gray-600);">Học qua Zoom / Google Meet</div>
              </div>
            </div>
            <div style="background:var(--teal-50);border-radius:var(--radius-sm);padding:10px 12px;">
              <div style="display:flex;align-items:center;gap:6px;margin-bottom:5px;">
                <span style="font-size:11px;font-weight:500;color:var(--teal-800);">&#128197; Ngày học</span>
              </div>
              <div style="font-size:12px;color:var(--teal-800);font-weight:500;">Thứ 7 & Chủ nhật</div>
              <div style="display:flex;align-items:center;gap:6px;margin-top:7px;margin-bottom:4px;">
                <span style="font-size:11px;font-weight:500;color:var(--teal-800);">&#128336; Giờ học</span>
              </div>
              <div style="font-size:13px;font-weight:600;color:var(--teal-800);">19:30 – 21:30</div>
            </div>
          </div>
        </label>

      </div>
    </div>

    <div class="nav">
      <button class="btn-prev" onclick="go(3)">&#8592; Quay lại</button>
      <button class="btn-next" onclick="go(5)">Tiếp theo &#8594;</button>
    </div>
  </div>

  <!-- ===== STEP 5: CAM KẾT & XÁC NHẬN ===== -->
  <div class="sec-card" id="step-5">
    <div class="sec-header">
      <div class="sec-icon ic-amber">&#128221;</div>
      <div>
        <h2>Cam kết & xác nhận đăng ký</h2>
        <p>Đọc kỹ và ký xác nhận trước khi hoàn tất</p>
      </div>
    </div>

    <div class="commit-box">
      <h4>&#9989; Cam kết của học sinh khi tham gia lớp</h4>
      <ul>
        <li>Tham gia đầy đủ các buổi học theo lịch đã được sắp xếp.</li>
        <li>Hoàn thành bài tập và đề luyện được giao sau mỗi buổi học.</li>
        <li>Thông báo trước cho thầy/cô khi không thể tham gia buổi học.</li>
        <li>Không sao chép, chia sẻ tài liệu độc quyền của trung tâm ra ngoài.</li>
        <li>Chủ động hỏi thầy/cô khi có thắc mắc về bài học hoặc lộ trình.</li>
      </ul>
    </div>

    <div class="fg">
      <label class="co" style="cursor:pointer;">
        <input type="checkbox" id="agree" style="width:auto;accent-color:var(--blue-600);width:15px;height:15px;" />
        Tôi đã đọc, hiểu và đồng ý với các cam kết trên. Thông tin tôi cung cấp là trung thực và chính xác.
      </label>
    </div>

    <div class="nav">
      <button class="btn-prev" onclick="go(4)">&#8592; Quay lại</button>
      <button class="btn-submit" onclick="sub()">&#10003; Hoàn tất đăng ký</button>
    </div>
  </div>

  <!-- SUCCESS -->
  <div class="success-card" id="ok">
    <div class="ok-ring">&#10003;</div>
    <h2>Đăng ký thành công!</h2>
    <p>
      Cảm ơn bạn đã hoàn thành phiếu ghi danh lớp ôn thi V-ACT.<br>
      Thầy/cô sẽ liên hệ với bạn trong vòng <strong>24 giờ</strong> để xác nhận
      và tư vấn lộ trình ôn luyện phù hợp nhất.<br><br>
      Trong lúc chờ, bạn có thể tham khảo thông tin chính thức kỳ thi tại:
    </p>
    <a class="link-btn" href="https://thinangluc.vnuhcm.edu.vn" target="_blank">
      thinangluc.vnuhcm.edu.vn &#8599;
    </a>
  </div>

  <div class="form-footer">
    Phiếu đăng ký V-ACT 2026 · ĐHQG TP.HCM<br>
    Đăng ký thi chính thức tại <a href="https://thinangluc.vnuhcm.edu.vn" target="_blank">thinangluc.vnuhcm.edu.vn</a>
  </div>

</div>

<script>
  function go(n) {
    for (let i = 1; i <= 5; i++) {
      document.getElementById('step-' + i).classList.remove('visible');
      const sn = document.getElementById('sn' + i);
      sn.classList.remove('active', 'done');
      if (i < n) {
        sn.classList.add('done');
        document.getElementById('sc' + i).textContent = '✓';
        if (i < 5) document.getElementById('sl' + i).classList.add('done');
      }
    }
    document.getElementById('step-' + n).classList.add('visible');
    document.getElementById('sn' + n).classList.add('active');
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function selectHinhThuc(val) {
    const offCard = document.getElementById('ht-offline');
    const onCard  = document.getElementById('ht-online');
    offCard.style.borderColor = val === 'offline' ? 'var(--blue-600)' : 'var(--gray-300)';
    offCard.style.background  = val === 'offline' ? 'var(--blue-50)'  : '#fff';
    onCard.style.borderColor  = val === 'online'  ? 'var(--teal-600)' : 'var(--gray-300)';
    onCard.style.background   = val === 'online'  ? 'var(--teal-50)'  : '#fff';
  }

  function tog(b) { b.classList.toggle('sel'); }

  function scl(b, id, color) {
    document.getElementById(id).querySelectorAll('.sb').forEach(x => {
      x.classList.remove('sel', 'teal', 'amber', 'purple');
    });
    b.classList.add('sel');
    if (color) b.classList.add(color);
  }

  function selTarget(b) {
    document.getElementById('tg-grid').querySelectorAll('.tg-btn').forEach(x => x.classList.remove('sel'));
    b.classList.add('sel');
  }

  function sub() {
    const agree = document.getElementById('agree');
    if (!agree.checked) {
      alert('Vui lòng đọc và đồng ý với các cam kết trước khi hoàn tất đăng ký.');
      return;
    }
    for (let i = 1; i <= 5; i++) {
      document.getElementById('step-' + i).classList.remove('visible');
      const sn = document.getElementById('sn' + i);
      sn.classList.remove('active');
      sn.classList.add('done');
      document.getElementById('sc' + i).textContent = '✓';
      if (i < 5) document.getElementById('sl' + i).classList.add('done');
    }
    document.getElementById('ok').style.display = 'block';
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  // Set today's date as default for signing date
  const today = new Date().toISOString().split('T')[0];
  const ngayky = document.getElementById('ngayky');
  if (ngayky) ngayky.value = today;
</script>
</body>
</html>
