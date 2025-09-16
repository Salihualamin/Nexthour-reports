# Nexthour-reports
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>NextHour Reports — Fresh news every hour</title>
  <meta name="description" content="NextHour Reports — Breaking stories, global and local updates, posted hourly." />
  <style>
    :root{--brand:#0b63c6;--accent:#d62828;--muted:#6b7280;--bg:#f7f9fb}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, Arial; margin:0; background:var(--bg); color:#0f1724}
    header{background:#fff; padding:18px 20px; box-shadow:0 2px 6px rgba(10,10,10,0.04); position:sticky; top:0; z-index:40}
    .container{max-width:1100px; margin:0 auto}
    .brand{display:flex; align-items:center; gap:12px}
    .logo{width:48px; height:48px; border-radius:8px; background:linear-gradient(135deg,var(--brand),#1177ee); display:flex; align-items:center; justify-content:center; color:#fff; font-weight:700}
    nav{margin-top:8px}
    .navlinks{display:flex; gap:14px; flex-wrap:wrap; align-items:center}
    .navlinks a{color:var(--muted); text-decoration:none; font-weight:600}
    .hero{background:#fff; padding:18px; margin-top:18px; border-radius:10px; display:flex; gap:18px; align-items:center}
    .breaking{flex:1}
    .breaking h1{margin:0; font-size:20px}
    .ticker{background:#0b63c6; color:#fff; padding:8px 12px; border-radius:8px; display:inline-block; font-weight:700}
    .grid{display:grid; gap:18px; grid-template-columns:2fr 1fr; margin-top:18px}
    .card{background:#fff; padding:12px; border-radius:10px}
    .article{display:flex; gap:12px}
    .thumb{width:160px; height:100px; background:#e6eefc; border-radius:8px; flex-shrink:0; display:flex; align-items:center; justify-content:center; color:var(--muted)}
    .meta{font-size:12px; color:var(--muted)}
    .title{font-weight:700; margin:6px 0}
    .excerpt{color:#334155}
    .categories{display:flex; gap:8px; flex-wrap:wrap}
    .cat{padding:6px 10px; background:#f1f5f9; border-radius:999px; font-weight:600; color:var(--muted); cursor:pointer}
    .sidebar h3{margin:0 0 12px 0}
    .list-item{display:flex; gap:10px; margin-bottom:10px}
    footer{margin-top:26px; padding:20px 0; text-align:center; color:var(--muted)}
    @media (max-width:900px){.grid{grid-template-columns:1fr}.thumb{width:120px}}
    .btn{display:inline-block; padding:8px 12px; border-radius:8px; font-weight:700; text-decoration:none}
    .btn-primary{background:var(--brand); color:#fff}
    .share{display:flex; gap:8px}
    .small{font-size:13px}
    .timestamp{color:var(--muted); font-size:12px}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="brand">
        <div class="logo">NH</div>
        <div>
          <div style="font-weight:800; font-size:18px">NextHour Reports</div>
          <div style="font-size:12px; color:var(--muted)">Fresh news. Updated hourly.</div>
        </div>
        <div style="margin-left:auto">
          <a href="#" class="btn btn-primary">Subscribe</a>
        </div>
      </div>
      <nav style="margin-top:12px">
        <div class="navlinks">
          <a href="#">Home</a>
          <a href="#">Politics</a>
          <a href="#">Business</a>
          <a href="#">Tech</a>
          <a href="#">Sports</a>
          <a href="#">Entertainment</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="breaking">
        <div class="ticker">BREAKING</div>
        <h1>Hour-by-hour updates: Stay ahead with the latest headlines</h1>
        <div class="small timestamp">Updated: 2025-09-16</div>
      </div>
    </section>

    <div class="grid">
      <div>
        <div class="card article">
          <div class="thumb">IMG</div>
          <div>
            <div
