

<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>株式会社KP Company｜全体最適で、未来を設計する。</title>
  <meta name="description" content="株式会社KP Company。部分最適の積み上げではなく、構造全体を見渡す視点で、企業の本質的な変革を支援します。" />
  <style>
    :root{
      --bg:#0b1220;--paper:#0f172a;--card:rgba(255,255,255,.06);
      --text:rgba(255,255,255,.92);--muted:rgba(255,255,255,.70);--faint:rgba(255,255,255,.55);
      --line:rgba(255,255,255,.12);--accent:#ff3b4e;--accent2:#4aa3ff;--accent3:#34d4a0;--accent4:#E8976A;
      --shadow:0 14px 40px rgba(0,0,0,.35);--radius:18px;--radius2:26px;--max:1120px;
      --font:ui-sans-serif,system-ui,-apple-system,"Segoe UI","Hiragino Kaku Gothic ProN","Noto Sans JP","Yu Gothic",sans-serif;
      --serif:ui-serif,"Noto Serif JP","Hiragino Mincho ProN","Yu Mincho",serif;
      --mono:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,monospace;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;font-family:var(--font);color:var(--text);
      background:radial-gradient(1000px 700px at 15% 10%,rgba(74,163,255,.20),transparent 60%),
        radial-gradient(900px 600px at 85% 15%,rgba(255,59,78,.18),transparent 55%),
        linear-gradient(180deg,#070b14 0%,#0b1220 55%,#070b14 100%);
      letter-spacing:.2px;}
    a{color:inherit;text-decoration:none}
    .wrap{max-width:var(--max);margin:0 auto;padding:0 24px}
    .topbar{position:sticky;top:0;z-index:50;backdrop-filter:blur(10px);background:rgba(7,11,20,.72);border-bottom:1px solid var(--line)}
    .nav{display:flex;align-items:center;justify-content:space-between;height:74px}
    .brand{display:flex;align-items:center;gap:14px;min-width:220px}
    .brand .name{display:flex;flex-direction:column;line-height:1.15}
    .brand .name strong{font-weight:650;font-size:15px;letter-spacing:.6px}
    .brand .name span{color:var(--faint);font-size:12px;font-family:var(--mono)}
    .links{display:flex;align-items:center;gap:14px}
    .links a{color:var(--muted);font-size:13px;padding:8px 10px;border-radius:12px;transition:.2s ease}
    .links a:hover{color:var(--text);background:rgba(255,255,255,.06)}
    .cta{display:flex;align-items:center;gap:10px}
    .btn{display:inline-flex;align-items:center;justify-content:center;border:1px solid var(--line);background:rgba(255,255,255,.04);color:var(--text);padding:10px 14px;border-radius:14px;font-size:13px;transition:.2s ease}
    .btn:hover{transform:translateY(-1px);background:rgba(255,255,255,.07)}
    .btn.primary{border-color:rgba(255,59,78,.35);background:linear-gradient(135deg,rgba(255,59,78,.22),rgba(74,163,255,.14))}
    .btn.warm{border-color:rgba(232,151,106,.35);background:linear-gradient(135deg,rgba(232,151,106,.22),rgba(74,163,255,.14))}

    /* HERO */
    .hero{padding:74px 0 34px}
    .hero-grid{display:grid;grid-template-columns:1.08fr .92fr;gap:28px;align-items:stretch}
    .kicker{color:var(--faint);font-size:12px;letter-spacing:2px;text-transform:uppercase;font-family:var(--mono);margin:0 0 14px}
    h1{margin:0 0 18px;font-family:var(--serif);font-weight:650;font-size:46px;letter-spacing:.4px;line-height:1.2}
    .lead{margin:0 0 22px;color:var(--muted);font-size:16px;line-height:1.9;max-width:58ch}
    .hero-actions{display:flex;gap:12px;align-items:center;flex-wrap:wrap;margin:18px 0 0}
    .meta-row{display:flex;gap:16px;flex-wrap:wrap;margin-top:26px;color:var(--faint);font-size:12px}
    .pill{display:inline-flex;align-items:center;gap:8px;padding:9px 12px;border-radius:999px;border:1px solid var(--line);background:rgba(255,255,255,.03)}
    .dot{width:8px;height:8px;border-radius:50%;background:linear-gradient(135deg,var(--accent),var(--accent2));box-shadow:0 0 0 4px rgba(255,255,255,.05)}
    .dot.green{background:linear-gradient(135deg,var(--accent3),var(--accent2))}
    .dot.warm{background:linear-gradient(135deg,var(--accent4),#E8A44A)}
    .hero-card{border:1px solid var(--line);background:linear-gradient(180deg,rgba(255,255,255,.06),rgba(255,255,255,.03));border-radius:var(--radius2);box-shadow:var(--shadow);overflow:hidden;position:relative}
    .hero-card::before{content:"";position:absolute;inset:-40%;background:radial-gradient(closest-side at 30% 20%,rgba(74,163,255,.22),transparent 60%),radial-gradient(closest-side at 70% 30%,rgba(255,59,78,.18),transparent 62%);transform:rotate(10deg);pointer-events:none}
    .hero-card-inner{position:relative;padding:22px}
    .quote{border:1px solid rgba(255,255,255,.10);background:rgba(7,11,20,.35);border-radius:var(--radius);padding:18px;margin-bottom:14px}
    .quote .t{font-family:var(--serif);font-size:18px;margin:0 0 10px;letter-spacing:.3px}
    .quote .s{color:var(--muted);margin:0;font-size:13px;line-height:1.8}
    .grid2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .mini{border:1px solid rgba(255,255,255,.10);background:rgba(255,255,255,.03);border-radius:var(--radius);padding:14px}
    .mini strong{display:block;font-size:12px;letter-spacing:1.6px;text-transform:uppercase;font-family:var(--mono);color:var(--faint);margin-bottom:8px}
    .mini p{margin:0;color:var(--muted);font-size:13px;line-height:1.75}

    /* SECTIONS */
    section{padding:54px 0}
    .section-head{display:flex;justify-content:space-between;align-items:flex-end;gap:20px;margin-bottom:20px}
    .section-head h2{margin:0;font-family:var(--serif);font-weight:650;font-size:28px;letter-spacing:.3px}
    .section-head p{margin:0;color:var(--muted);font-size:13px;line-height:1.8;max-width:58ch}
    .cards{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .card{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:var(--radius);padding:18px;box-shadow:0 10px 30px rgba(0,0,0,.18);min-height:168px}
    .card .tag{font-family:var(--mono);color:var(--faint);font-size:11px;letter-spacing:1.8px;text-transform:uppercase;margin-bottom:10px;display:inline-flex;align-items:center;gap:8px}
    .card .tag i{width:10px;height:10px;border-radius:3px;background:linear-gradient(135deg,var(--accent2),var(--accent));opacity:.9;display:inline-block}
    .card .tag i.green{background:linear-gradient(135deg,var(--accent3),var(--accent2))}
    .card .tag i.warm{background:linear-gradient(135deg,var(--accent4),#E8A44A)}
    .card h3{margin:0 0 8px;font-size:16px;font-weight:650;letter-spacing:.2px}
    .card p{margin:0;color:var(--muted);font-size:13px;line-height:1.85}
    .split{display:grid;grid-template-columns:1.05fr .95fr;gap:14px;align-items:stretch}
    .panel{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:var(--radius2);padding:22px;box-shadow:var(--shadow)}
    .panel h3{margin:0 0 10px;font-family:var(--serif);font-size:20px;letter-spacing:.2px;font-weight:650}
    .panel p{margin:0;color:var(--muted);font-size:13px;line-height:1.95}
    .list{margin:16px 0 0;padding:0;list-style:none;display:grid;gap:10px}
    .list li{border:1px solid rgba(255,255,255,.10);background:rgba(7,11,20,.28);border-radius:16px;padding:12px 14px;display:flex;gap:12px;align-items:flex-start}
    .badge{width:28px;height:28px;border-radius:10px;border:1px solid rgba(255,255,255,.14);background:linear-gradient(135deg,rgba(74,163,255,.22),rgba(255,59,78,.18));display:flex;align-items:center;justify-content:center;font-family:var(--mono);font-size:12px;color:rgba(255,255,255,.9);flex:0 0 auto}
    .badge.green{background:linear-gradient(135deg,rgba(52,212,160,.28),rgba(74,163,255,.20))}
    .badge.warm{background:linear-gradient(135deg,rgba(232,151,106,.35),rgba(232,164,74,.25))}
    .list li div{flex:1}
    .list li strong{display:block;font-size:13px;margin-bottom:4px}
    .list li span{display:block;color:var(--muted);font-size:12px;line-height:1.75}
    .contact{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    .form{display:grid;gap:10px;margin-top:12px}
    .field{display:grid;gap:6px}
    label{font-size:12px;color:var(--faint)}
    input,textarea{width:100%;border:1px solid rgba(255,255,255,.12);background:rgba(255,255,255,.03);color:var(--text);border-radius:14px;padding:12px;font:inherit;outline:none}
    textarea{min-height:120px;resize:vertical}
    input:focus,textarea:focus{border-color:rgba(74,163,255,.35);box-shadow:0 0 0 4px rgba(74,163,255,.12)}
    .fine{color:var(--faint);font-size:12px;line-height:1.8;margin-top:12px}
    footer{border-top:1px solid var(--line);padding:26px 0 34px;color:var(--faint);font-size:12px}
    .foot{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap;align-items:center}
    .foot .motto{font-family:var(--mono);letter-spacing:1.6px;text-transform:uppercase;color:rgba(255,255,255,.62)}

    /* 全体最適セクション */
    .holistic-section{padding:64px 0;position:relative;overflow:hidden}
    .holistic-section::before{content:"";position:absolute;inset:0;background:radial-gradient(ellipse 900px 500px at 50% 50%,rgba(52,212,160,.08),transparent 70%);pointer-events:none}
    .holistic-label{display:inline-flex;align-items:center;gap:10px;padding:8px 14px;border-radius:999px;border:1px solid rgba(52,212,160,.28);background:rgba(52,212,160,.06);font-family:var(--mono);font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--accent3);margin-bottom:20px}
    .holistic-label::before{content:"";width:7px;height:7px;border-radius:50%;background:var(--accent3);box-shadow:0 0 8px rgba(52,212,160,.7);animation:pulse 2s ease-in-out infinite}
    @keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.5;transform:scale(.85)}}
    .holistic-headline{font-family:var(--serif);font-size:38px;font-weight:650;letter-spacing:.3px;line-height:1.25;margin:0 0 14px}
    .holistic-headline em{font-style:normal;background:linear-gradient(90deg,var(--accent3),var(--accent2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
    .holistic-lead{color:var(--muted);font-size:15px;line-height:1.9;max-width:62ch;margin:0 0 36px}
    .contrast-grid{display:grid;grid-template-columns:1fr auto 1fr;gap:0;align-items:stretch;margin-bottom:36px}
    .contrast-col{border:1px solid var(--line);border-radius:var(--radius2);padding:24px;background:rgba(255,255,255,.03)}
    .contrast-col.bad{border-color:rgba(255,59,78,.18);background:rgba(255,59,78,.04)}
    .contrast-col.good{border-color:rgba(52,212,160,.22);background:rgba(52,212,160,.05)}
    .contrast-divider{display:flex;align-items:center;justify-content:center;padding:0 18px;color:var(--faint);font-size:20px;font-family:var(--mono);flex-shrink:0}
    .contrast-col .clabel{font-family:var(--mono);font-size:11px;letter-spacing:1.8px;text-transform:uppercase;margin-bottom:14px}
    .contrast-col.bad .clabel{color:rgba(255,59,78,.7)}
    .contrast-col.good .clabel{color:var(--accent3)}
    .contrast-col h4{font-family:var(--serif);font-size:17px;font-weight:650;margin:0 0 10px;letter-spacing:.2px}
    .contrast-col ul{margin:0;padding:0;list-style:none;display:grid;gap:8px}
    .contrast-col ul li{font-size:13px;color:var(--muted);line-height:1.75;padding-left:16px;position:relative}
    .contrast-col ul li::before{content:"";position:absolute;left:0;top:8px;width:6px;height:6px;border-radius:50%}
    .contrast-col.bad ul li::before{background:rgba(255,59,78,.55)}
    .contrast-col.good ul li::before{background:rgba(52,212,160,.7)}
    .phase-row{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-bottom:36px}
    .phase-card{border:1px solid var(--line);background:rgba(255,255,255,.03);border-radius:var(--radius2);padding:22px;box-shadow:var(--shadow)}
    .phase-num{font-family:var(--mono);font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--accent3);margin-bottom:12px;display:flex;align-items:center;gap:8px}
    .phase-num::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,rgba(52,212,160,.3),transparent)}
    .phase-card h4{font-family:var(--serif);font-size:17px;font-weight:650;margin:0 0 8px;letter-spacing:.2px}
    .phase-card p{margin:0;color:var(--muted);font-size:13px;line-height:1.8}
    .kpi-row{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
    .kpi-block{border:1px solid rgba(52,212,160,.16);background:rgba(52,212,160,.04);border-radius:var(--radius);padding:16px;text-align:center}
    .kpi-block .num{font-family:var(--mono);font-size:28px;font-weight:700;color:var(--accent3);letter-spacing:-1px;margin-bottom:4px}
    .kpi-block .desc{font-size:12px;color:var(--muted);line-height:1.6}

    /* ===== かかりつけ参謀セクション ===== */
    .samurai-section{padding:64px 0;position:relative;overflow:hidden}
    .samurai-section::before{content:"";position:absolute;inset:0;
      background:radial-gradient(ellipse 800px 500px at 80% 30%,rgba(232,151,106,.10),transparent 65%),
        radial-gradient(ellipse 600px 400px at 20% 70%,rgba(74,163,255,.07),transparent 60%);
      pointer-events:none}
    .samurai-label{display:inline-flex;align-items:center;gap:10px;padding:8px 14px;border-radius:999px;border:1px solid rgba(232,151,106,.35);background:rgba(232,151,106,.08);font-family:var(--mono);font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--accent4);margin-bottom:20px}
    .samurai-label::before{content:"";width:7px;height:7px;border-radius:50%;background:var(--accent4);box-shadow:0 0 8px rgba(232,151,106,.7);animation:pulse 2s ease-in-out infinite}
    .samurai-headline{font-family:var(--serif);font-size:38px;font-weight:650;letter-spacing:.3px;line-height:1.25;margin:0 0 14px}
    .samurai-headline em{font-style:normal;background:linear-gradient(90deg,var(--accent4),#E8A44A);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text}
    .samurai-lead{color:var(--muted);font-size:15px;line-height:1.9;max-width:62ch;margin:0 0 36px}
    .samurai-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:36px}
    .samurai-col{display:flex;flex-direction:column;gap:14px}
    .samurai-block{border:1px solid rgba(232,151,106,.2);background:rgba(232,151,106,.05);border-radius:var(--radius2);padding:22px}
    .samurai-block .slabel{font-family:var(--mono);font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--accent4);margin-bottom:10px;display:flex;align-items:center;gap:8px}
    .samurai-block .slabel::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,rgba(232,151,106,.3),transparent)}
    .samurai-block h4{font-family:var(--serif);font-size:17px;font-weight:650;margin:0 0 8px}
    .samurai-block p{margin:0;color:var(--muted);font-size:13px;line-height:1.8}
    .ai-contrast{display:grid;grid-template-columns:1fr auto 1fr;gap:0;align-items:stretch;margin-bottom:36px}
    .ai-col{border:1px solid var(--line);border-radius:var(--radius2);padding:22px;background:rgba(255,255,255,.03)}
    .ai-col.ai{border-color:rgba(74,163,255,.2);background:rgba(74,163,255,.04)}
    .ai-col.human{border-color:rgba(232,151,106,.22);background:rgba(232,151,106,.05)}
    .ai-col .alabel{font-family:var(--mono);font-size:11px;letter-spacing:1.8px;text-transform:uppercase;margin-bottom:14px}
    .ai-col.ai .alabel{color:var(--accent2)}
    .ai-col.human .alabel{color:var(--accent4)}
    .ai-col h4{font-family:var(--serif);font-size:17px;font-weight:650;margin:0 0 10px}
    .ai-col ul{margin:0;padding:0;list-style:none;display:grid;gap:8px}
    .ai-col ul li{font-size:13px;color:var(--muted);line-height:1.75;padding-left:16px;position:relative}
    .ai-col ul li::before{content:"";position:absolute;left:0;top:8px;width:6px;height:6px;border-radius:50%}
    .ai-col.ai ul li::before{background:rgba(74,163,255,.6)}
    .ai-col.human ul li::before{background:rgba(232,151,106,.7)}
    .stage-row{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:28px}
    .stage-card{border:1px solid rgba(232,151,106,.2);background:rgba(232,151,106,.04);border-radius:var(--radius2);padding:18px;position:relative}
    .stage-num{font-family:var(--mono);font-size:11px;letter-spacing:2px;text-transform:uppercase;color:var(--accent4);margin-bottom:10px;display:flex;align-items:center;gap:6px}
    .stage-num::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,rgba(232,151,106,.3),transparent)}
    .stage-card h4{font-family:var(--serif);font-size:15px;font-weight:650;margin:0 0 6px}
    .stage-card p{margin:0;color:var(--muted);font-size:12px;line-height:1.75}
    .stage-card .stage-meta{margin-top:10px;font-family:var(--mono);font-size:10px;color:var(--accent4);opacity:.7}
    .philosophy-box{border:1px solid rgba(232,151,106,.25);border-left:4px solid var(--accent4);background:rgba(232,151,106,.06);border-radius:0 var(--radius2) var(--radius2) 0;padding:20px 24px;margin-bottom:20px}
    .philosophy-box .pquote{font-family:var(--serif);font-size:16px;color:var(--text);line-height:1.85;margin:0 0 8px}
    .philosophy-box .pattr{font-size:12px;color:var(--faint)}

    @media(max-width:980px){
      .hero-grid,.cards,.split,.contact,.contrast-grid,.phase-row,.samurai-grid,.ai-contrast,.stage-row{grid-template-columns:1fr}
      h1,.holistic-headline,.samurai-headline{font-size:28px}
      .links{display:none}
      .contrast-divider,.ai-contrast .contrast-divider{padding:12px 0;font-size:14px}
      .kpi-row{grid-template-columns:repeat(2,1fr)}
    }
  </style>
</head>
<body>
  <div class="topbar">
    <div class="wrap">
      <div class="nav">
        <a class="brand" href="#top">
          <div class="name">
            <strong>株式会社KP Company</strong>
            <span>Think Clearly. Act with Balance.</span>
          </div>
        </a>
        <nav class="links">
          <a href="#philosophy">考え方</a>
          <a href="#holistic">全体最適</a>
          <a href="#samurai">かかりつけ参謀</a>
          <a href="#services">事業</a>
          <a href="#message">代表メッセージ</a>
          <a href="#contact">お問い合わせ</a>
        </nav>
        <div class="cta">
          <a class="btn" href="#services">事業を見る</a>
          <a class="btn primary" href="#contact">相談する</a>
        </div>
      </div>
    </div>
  </div>

  <header class="hero" id="top">
    <div class="wrap">
      <div class="hero-grid">
        <div>
          <p class="kicker">KP COMPANY</p>
          <h1>全体を見渡し、<br/>静かに正しく動く。</h1>
          <p class="lead">部分の最適化を積み上げても、全体は変わらない。<br/>KP Companyは、組織・戦略・オペレーションを構造ごと捉え直し、全体最適を起点とした誠実な変革を、静かな実行力で支えます。</p>
          <div class="hero-actions">
            <a class="btn primary" href="#contact">まずは相談する</a>
            <a class="btn" href="#holistic">全体最適とは</a>
            <a class="btn warm" href="#samurai">かかりつけ参謀とは</a>
          </div>
          <div class="meta-row">
            <span class="pill"><span class="dot green"></span> 全体最適を設計思想に</span>
            <span class="pill"><span class="dot warm"></span> かかりつけ参謀で経営者を支える</span>
            <span class="pill"><span class="dot"></span> 実行まで伴走する</span>
          </div>
        </div>
        <aside class="hero-card">
          <div class="hero-card-inner">
            <div class="quote">
              <p class="t">部分最適の積み上げは、全体を救わない。</p>
              <p class="s">財務・組織・DX——それぞれが改善されても、構造が変わらなければ、課題は形を変えて戻ってくる。本質的な変革は、全体を見渡す視点から始まる。</p>
            </div>
            <div class="grid2">
              <div class="mini"><strong>Whole View</strong><p>構造全体を可視化し、介入点を絞る。</p></div>
              <div class="mini"><strong>Design</strong><p>全体最適のロードマップを設計する。</p></div>
              <div class="mini"><strong>Execute</strong><p>実行まで伴走し、成果に責任を持つ。</p></div>
              <div class="mini"><strong>Trust</strong><p>困った時に最初に思い浮かぶ存在になる。</p></div>
            </div>
          </div>
        </aside>
      </div>
    </div>
  </header>

  <section id="philosophy">
    <div class="wrap">
      <div class="section-head">
        <div>
          <h2>考え方</h2>
          <p>直接的なスローガンではなく、姿勢として徹底します。落ち着いた思考と、ぶれない意思決定。</p>
        </div>
      </div>
      <div class="cards">
        <div class="card">
          <div class="tag"><i></i> PRINCIPLE 01</div>
          <h3>先入観を置き、事実から考える</h3>
          <p>気分や空気ではなく、データと現場の声から捉え直します。複雑な課題ほど、静かに整理し、正しい問いを立てます。</p>
        </div>
        <div class="card">
          <div class="tag"><i class="green"></i> PRINCIPLE 02</div>
          <h3>部分ではなく、構造全体を診る</h3>
          <p>個別課題の解決に終始せず、組織・戦略・オペレーションを横断した全体構造を把握してから、介入優先度を決めます。</p>
        </div>
        <div class="card">
          <div class="tag"><i class="warm"></i> PRINCIPLE 03</div>
          <h3>まず貢献せよ。報酬は後からついて来る。</h3>
          <p>「まず社会に貢献せよ。報酬は後からついて来ると心得よ」——恩師・森亮一先生の言葉を、全ての行動の根底に置いています。</p>
        </div>
      </div>
    </div>
  </section>

  <section id="holistic" class="holistic-section">
    <div class="wrap">
      <div class="holistic-label">Holistic Optimization</div>
      <h2 class="holistic-headline">全体最適を、<em>設計思想</em>の中心に。</h2>
      <p class="holistic-lead">多くのコンサルティングは「部分最適の積み上げ」で終わる。財務改善、DX推進、組織改革——それぞれが孤立したプロジェクトとなり、クライアントに真の変革が残らない。私たちは、全体構造を可視化し、最も効果的な介入点に集中することで、持続的な価値を生み出します。</p>
      <div class="contrast-grid">
        <div class="contrast-col bad">
          <div class="clabel">従来のアプローチ</div>
          <h4>部分最適の積み上げ</h4>
          <ul>
            <li>各部門ごとに個別最適を追求</li>
            <li>プロジェクトが孤立し、連携がない</li>
            <li>課題を解決しても別の問題が発生</li>
            <li>「きれいな資料」で終わる提案</li>
            <li>構造的な変革に至らない</li>
          </ul>
        </div>
        <div class="contrast-divider">→</div>
        <div class="contrast-col good">
          <div class="clabel">KP Companyのアプローチ</div>
          <h4>全体最適の設計</h4>
          <ul>
            <li>組織・戦略・オペレーションを横断して診る</li>
            <li>全体構造を可視化し、介入点を絞り込む</li>
            <li>根本原因に対処し、再発を防ぐ</li>
            <li>実行まで伴走し、成果に責任を持つ</li>
            <li>持続的な変革を組織に定着させる</li>
          </ul>
        </div>
      </div>
      <div class="phase-row">
        <div class="phase-card"><div class="phase-num">Phase 01</div><h4>構造の可視化</h4><p>組織・戦略・オペレーションの全体マップを作成。表面的な課題ではなく、構造上の問題点を特定します。</p></div>
        <div class="phase-card"><div class="phase-num">Phase 02</div><h4>変革ロードマップの設計</h4><p>介入優先度を決定し、全体最適に向けた変革シナリオを設計。各施策の連動性と依存関係を明確にします。</p></div>
        <div class="phase-card"><div class="phase-num">Phase 03</div><h4>実行伴走・効果測定</h4><p>月次顧問・PMO支援で実行を支え、KPIで効果を測定します。全体最適の進捗を定点観測し、精度を高めます。</p></div>
      </div>
      <div class="kpi-row">
        <div class="kpi-block"><div class="num">40<span style="font-size:16px">%+</span></div><div class="desc">伴走型（継続）<br/>収益比率の目標</div></div>
        <div class="kpi-block"><div class="num">3<span style="font-size:16px">層</span></div><div class="desc">診断・設計・実行の<br/>一気通貫サービス</div></div>
        <div class="kpi-block"><div class="num">90<span style="font-size:16px">%+</span></div><div class="desc">案件継続率を<br/>最重要KPIとして管理</div></div>
        <div class="kpi-block"><div class="num">T<span style="font-size:16px">字型</span></div><div class="desc">全体設計力＋深い専門性を<br/>持つ人材で構成</div></div>
      </div>
    </div>
  </section>

  <!-- ===== かかりつけ参謀セクション ===== -->
  <section id="samurai" class="samurai-section">
    <div class="wrap">
      <div class="samurai-label">Kakari Samurai Program</div>
      <h2 class="samurai-headline">知識・データをもとに、<em>ヒトを動かす。</em></h2>
      <p class="samurai-lead">生成AIが急速に進化する時代。「知っていること」の価値は下がり、「知識を使ってヒトを動かせる人間」の希少価値が高まっています。経営者が困った時に最初に思い浮かぶ存在——それが「かかりつけ参謀」です。</p>

      <!-- 哲学 -->
      <div class="philosophy-box">
        <div class="pquote">「まず社会に貢献せよ。報酬は後からついて来ると心得よ。」</div>
        <div class="pattr">森亮一（元筑波大学名誉教授・故人）｜代表・川下勝也の恩師の言葉</div>
      </div>

      <!-- AIとの差別化 -->
      <div class="ai-contrast">
        <div class="ai-col ai">
          <div class="alabel">生成AIが得意なこと</div>
          <h4>静的な情報の処理</h4>
          <ul>
            <li>文字化された情報の分析</li>
            <li>法律調査・財務分析・文書作成</li>
            <li>パターン認識・予測・24時間対応</li>
            <li>過去データの高速処理</li>
          </ul>
        </div>
        <div class="contrast-divider">VS</div>
        <div class="ai-col human">
          <div class="alabel">かかりつけ参謀にしかできないこと</div>
          <h4>動的な人間関係への対応</h4>
          <ul>
            <li>言葉と表情のズレを読む</li>
            <li>沈黙の意味・発言の裏にある本音を掴む</li>
            <li>経営者の孤独に寄り添い、信頼を積み上げる</li>
            <li>人物の分岐点での行動を予見する</li>
          </ul>
        </div>
      </div>

      <!-- 2カラム：定義＋特徴 -->
      <div class="samurai-grid">
        <div class="samurai-col">
          <div class="samurai-block">
            <div class="slabel">定義</div>
            <h4>困った時に最初に思い浮かぶ存在</h4>
            <p>何が問題かわからない段階から、一緒に考えてくれる人間。専門外の話でも次の一手を示し、お金の匂いがしない人間。それが「かかりつけ参謀」です。</p>
          </div>
          <div class="samurai-block">
            <div class="slabel">差別化の核心</div>
            <h4>AIが普及するほど価値が高まる</h4>
            <p>「知っていること」の価値が下がるほど、「知識を使ってヒトを動かせる人間」の希少価値が上がります。これがかかりつけ参謀の事業としての根本的な優位性です。</p>
          </div>
        </div>
        <div class="samurai-col">
          <div class="samurai-block" style="height:100%">
            <div class="slabel">かかりつけ参謀が持つ5つの力</div>
            <ul class="list" style="margin-top:8px">
              <li><div class="badge warm">01</div><div><strong>診断スキル</strong><span>事実を正確に捉える。数字を見ることと、作られ方を見ることの違いを体得している。</span></div></li>
              <li><div class="badge warm">02</div><div><strong>予見思考</strong><span>人物特性を読み、分岐点での行動を予見する。文字化されたプロフィールだけでは不可能。</span></div></li>
              <li><div class="badge warm">03</div><div><strong>応答力思考</strong><span>「わからない」で終わらせない。知識・専門家DB・人脈の3段階を使いこなす。</span></div></li>
              <li><div class="badge warm">04</div><div><strong>倫理観</strong><span>「人として・サービスとして正しいか」全ての判断の最終軸がブレない。</span></div></li>
              <li><div class="badge warm">05</div><div><strong>関係構築力</strong><span>自分を曝け出し、長期的な信頼を積み上げる。陰徳の実践者として動く。</span></div></li>
            </ul>
          </div>
        </div>
      </div>

      <!-- プログラム構成 -->
      <div class="section-head" style="margin-bottom:16px">
        <div>
          <h2 style="font-size:22px">「かかりつけ参謀」養成プログラム</h2>
          <p>認定スーパーゼネラリストを育成する4段階のプログラム</p>
        </div>
      </div>
      <div class="stage-row">
        <div class="stage-card">
          <div class="stage-num">ENTRY</div>
          <h4>体験WS・スクリーニング</h4>
          <p>プログラムの全体像を体験し、適性を確認します。財務前提知識の確認を含みます。</p>
          <div class="stage-meta">半日〜1日 ／ 3〜5万円</div>
        </div>
        <div class="stage-card">
          <div class="stage-num">STAGE 1</div>
          <h4>知識習得（座学）</h4>
          <p>診断・思考・知識・実践の4MODULEを体系的に習得。各ルーブリックでレベル3以上が修了基準。</p>
          <div class="stage-meta">3ヶ月 ／ 要相談</div>
        </div>
        <div class="stage-card">
          <div class="stage-num">STAGE 2</div>
          <h4>現場同行・講師研修生モデル</h4>
          <p>講師の視点・言葉・判断を目と耳で直接確認。同席記録シートを毎回提出し、思考の質を高めます。</p>
          <div class="stage-meta">3〜6ヶ月 ／ 要相談（認定時全額返金予定）</div>
        </div>
        <div class="stage-card">
          <div class="stage-num">STAGE 3</div>
          <h4>単独稼働・研修医モデル</h4>
          <p>当社社員として実際のクライアントを担当。週次1on1と代表のバックアップ体制のもとで稼働します。</p>
          <div class="stage-meta">6〜12ヶ月 ／ 費用なし</div>
        </div>
      </div>

      <div style="text-align:center;margin-top:8px">
        <a class="btn warm" href="#contact">プログラムについて問い合わせる</a>
      </div>
    </div>
  </section>

  <section id="services">
    <div class="wrap">
      <div class="section-head">
        <div>
          <h2>事業</h2>
          <p>全体最適の設計思想を軸に、経営の意思決定と実行を支援します。</p>
        </div>
      </div>
      <div class="split">
        <div class="panel">
          <h3>経営支援 / 事業設計</h3>
          <p>成長戦略・収益構造・組織設計を、全体最適の視点で実務レベルまで落とし込みます。</p>
          <ul class="list">
            <li><div class="badge green">01</div><div><strong>全体構造の診断・可視化</strong><span>組織・戦略・オペレーションを横断したマッピングと課題の優先順位付け。</span></div></li>
            <li><div class="badge">02</div><div><strong>事業計画・収益モデル設計</strong><span>売上の蓋然性、KPI連動、原価/人員の実装まで。</span></div></li>
            <li><div class="badge">03</div><div><strong>DX / AI活用のグランドデザイン</strong><span>現場業務の構造化から、システム要件・導入計画まで。</span></div></li>
            <li><div class="badge">04</div><div><strong>資金調達 / 財務戦略</strong><span>投資家目線で、ストーリーと数字の整合を構築。</span></div></li>
          </ul>
        </div>
        <div class="panel">
          <h3>提供スタイル</h3>
          <p>相談だけで終わらせず、実装まで伴走します。全体最適の観点から、各フェーズを連動させて支援します。</p>
          <ul class="list">
            <li><div class="badge">A</div><div><strong>スポット相談</strong><span>論点整理・意思決定支援（単発/短期）。</span></div></li>
            <li><div class="badge green">B</div><div><strong>伴走（顧問）</strong><span>月次/隔週での実行管理と改善。継続的な全体最適の進捗管理。</span></div></li>
            <li><div class="badge warm">C</div><div><strong>かかりつけ参謀</strong><span>困った時に最初に思い浮かぶ存在として、経営者に寄り添い続ける長期伴走。</span></div></li>
          </ul>
          <p class="fine">※ 実際の提供内容は、業種・規模・課題に応じて最適化します。</p>
        </div>
      </div>
    </div>
  </section>

  <section id="message">
    <div class="wrap">
      <div class="section-head">
        <div>
          <h2>代表メッセージ</h2>
          <p>「全体を見渡し、誠実に考え、静かにやり切る」その積み重ねが、信頼をつくると信じています。</p>
        </div>
      </div>
      <div class="panel">
        <h3>知識・データをもとに、ヒトを動かす</h3>
        <p>変化が速い時代ほど、「部分最適の積み上げ」の罠にはまりやすくなります。財務が改善されても組織が機能しない。DXを導入しても戦略と連動しない。そうした分断が、企業の本質的な成長を妨げています。<br/><br/>私たちは、組織・戦略・オペレーションを構造ごと捉え直し、全体最適を設計思想の中心に据えた変革を支援します。そしてもう一つ。生成AIがどれだけ進化しても、「あなたに相談したい」と思われる人間の価値は下がりません。<br/><br/>困った時に最初に思い浮かぶ存在になる——それがKP Companyの、二つの柱です。</p>
        <p class="fine">代表取締役　川下 勝也</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="wrap">
      <div class="section-head">
        <div>
          <h2>お問い合わせ</h2>
          <p>相談内容が固まっていなくても問題ありません。状況を伺い、全体構造の整理からご一緒します。</p>
        </div>
      </div>
      <div class="contact">
        <div class="panel">
          <h3>ご相談の例</h3>
          <ul class="list">
            <li><div class="badge green">•</div><div><strong>組織・戦略・現場が噛み合っていない</strong><span>全体構造を可視化し、分断の原因を特定します。</span></div></li>
            <li><div class="badge warm">•</div><div><strong>困った時に相談できる存在がいない</strong><span>経営者の孤独に寄り添う「かかりつけ参謀」をご紹介します。</span></div></li>
            <li><div class="badge">•</div><div><strong>DX/AIの導入方針を整理したい</strong><span>全体最適の観点から、現場起点で定着する設計へ。</span></div></li>
            <li><div class="badge warm">•</div><div><strong>かかりつけ参謀プログラムに興味がある</strong><span>受講・採用いずれのご相談もお受けします。</span></div></li>
          </ul>
          <p class="fine">返信目安：原則1〜2営業日<br/>〒104-0061 東京都中央区銀座6-6-1 銀座風月堂ビル５F<br/>TEL：03-6215-8326<br/>MAIL：office@jp-kpcompany.com</p>
        </div>
        <div class="panel">
          <h3>お問い合わせ</h3>
          <div class="form">
            <div class="field"><label>お名前</label><input type="text" placeholder="例）山田 太郎" /></div>
            <div class="field"><label>メールアドレス</label><input type="email" placeholder="例）taro@example.com" /></div>
            <div class="field"><label>ご相談内容</label><textarea placeholder="現状・目的・制約など、わかる範囲でご記入ください。"></textarea></div>
            <button class="btn primary" type="https://formspree.io/f/xzedzzno">送信する</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="wrap">
      <div class="foot">
        <div>© <span id="y"></span> KP Company Inc. All rights reserved.</div>
        <div class="motto">Think Clearly. Act with Balance.</div>
      </div>
    </div>
  </footer>
  <script>document.getElementById("y").textContent=new Date().getFullYear();</script>
</body>
</html>
