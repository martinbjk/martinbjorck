
<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Martin Björck — Fotografi</title>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Jost:wght@200;300;400&display=swap" rel="stylesheet" />
  <style>
    :root {
      --sand-deep:    #8b7355;
      --sand-mid:     #c4a882;
      --sand-light:   #e8d5b7;
      --sand-pale:    #f5ece0;
      --sand-white:   #faf5ed;
      --dune-shadow:  #6b5840;
      --accent:       #c4752e;
      --accent-soft:  #d4935a;
      --text-dark:    #3a2e22;
      --text-mid:     #6b5840;
      --text-soft:    #9a8472;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Jost', sans-serif;
      font-weight: 300;
      background-color: var(--sand-white);
      color: var(--text-dark);
      overflow-x: hidden;
    }

    /* ── DESERT TEXTURE BACKGROUND ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background:
        radial-gradient(ellipse 120% 80% at 20% 110%, #c4a88255 0%, transparent 55%),
        radial-gradient(ellipse 80% 60% at 80% -10%,  #e8d5b740 0%, transparent 50%),
        radial-gradient(ellipse 60% 40% at 50% 50%,  #f5ece044 0%, transparent 70%),
        linear-gradient(175deg, #faf5ed 0%, #f0e3cc 40%, #e8d5b7 70%, #d9c4a0 100%);
      z-index: -2;
      pointer-events: none;
    }

    /* Grain overlay */
    body::after {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
      background-repeat: repeat;
      background-size: 256px;
      z-index: -1;
      pointer-events: none;
      opacity: 0.6;
    }

    /* ── HEADER / HERO ── */
    header {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 4rem 2rem 6rem;
      position: relative;
    }

    .dune-divider {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      overflow: hidden;
      line-height: 0;
    }
    .dune-divider svg { display: block; width: 100%; }

    .hero-eyebrow {
      font-family: 'Jost', sans-serif;
      font-weight: 200;
      font-size: 0.75rem;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--text-soft);
      margin-bottom: 1.5rem;
      opacity: 0;
      animation: fadeUp 1s ease 0.2s forwards;
    }

    h1 {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: clamp(3.5rem, 10vw, 7.5rem);
      line-height: 0.95;
      color: var(--text-dark);
      letter-spacing: -0.01em;
      opacity: 0;
      animation: fadeUp 1s ease 0.4s forwards;
    }

    h1 em {
      font-style: italic;
      color: var(--accent);
    }

    .hero-sub {
      font-family: 'Jost', sans-serif;
      font-weight: 200;
      font-size: clamp(0.85rem, 2vw, 1rem);
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--text-soft);
      margin-top: 1.5rem;
      opacity: 0;
      animation: fadeUp 1s ease 0.6s forwards;
    }

    .hero-line {
      width: 1px;
      height: 80px;
      background: linear-gradient(to bottom, var(--sand-mid), transparent);
      margin: 3rem auto 0;
      opacity: 0;
      animation: fadeUp 1s ease 0.8s forwards;
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem 3rem;
      background: linear-gradient(to bottom, rgba(250,245,237,0.95) 0%, rgba(250,245,237,0) 100%);
      backdrop-filter: blur(4px);
    }

    .nav-logo {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 400;
      font-size: 1.1rem;
      letter-spacing: 0.05em;
      color: var(--text-dark);
      text-decoration: none;
    }

    .nav-links {
      display: flex;
      gap: 2.5rem;
      list-style: none;
    }

    .nav-links a {
      font-size: 0.72rem;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--text-mid);
      text-decoration: none;
      transition: color 0.3s;
    }

    .nav-links a:hover { color: var(--accent); }

    /* ── SECTION TITLES ── */
    .section-header {
      text-align: center;
      padding: 5rem 2rem 3rem;
    }

    .section-tag {
      font-size: 0.7rem;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--text-soft);
      display: block;
      margin-bottom: 1rem;
    }

    .section-title {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: clamp(2.5rem, 6vw, 4rem);
      color: var(--text-dark);
      line-height: 1;
    }

    .section-title em {
      font-style: italic;
      color: var(--accent);
    }

    /* ── GALLERY ── */
    #galleri {
      padding: 0 2rem 6rem;
      max-width: 1600px;
      margin: 0 auto;
    }

    .filter-bar {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      justify-content: center;
      margin-bottom: 3rem;
    }

    .filter-btn {
      font-family: 'Jost', sans-serif;
      font-size: 0.7rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      padding: 0.5rem 1.5rem;
      border: 1px solid var(--sand-mid);
      background: transparent;
      color: var(--text-mid);
      cursor: pointer;
      transition: all 0.3s;
      border-radius: 2px;
    }

    .filter-btn:hover,
    .filter-btn.active {
      background: var(--accent);
      border-color: var(--accent);
      color: white;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 1.5rem;
    }

    .gallery-item {
      position: relative;
      overflow: hidden;
      background: var(--sand-light);
      border-radius: 3px;
      cursor: pointer;
      aspect-ratio: 4/3;
      box-shadow: 0 4px 20px rgba(107,88,64,0.12);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }

    .gallery-item:nth-child(5n+1) { aspect-ratio: 3/4; }
    .gallery-item:nth-child(7n+3) { aspect-ratio: 16/10; }

    .gallery-item:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 40px rgba(107,88,64,0.2);
    }

    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.6s ease;
      filter: sepia(8%) contrast(1.03) saturate(0.95);
    }

    .gallery-item:hover img { transform: scale(1.06); }

    .gallery-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(to top, rgba(58,46,34,0.85) 0%, transparent 50%);
      opacity: 0;
      transition: opacity 0.3s;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 1.25rem;
    }

    .gallery-item:hover .gallery-overlay { opacity: 1; }

    .gallery-overlay h3 {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 400;
      font-size: 1.1rem;
      color: var(--sand-white);
      margin-bottom: 0.3rem;
    }

    .gallery-overlay span {
      font-size: 0.65rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--sand-light);
      opacity: 0.8;
    }

    .download-btn {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: var(--accent);
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      font-family: 'Jost', sans-serif;
      font-size: 0.65rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      cursor: pointer;
      border-radius: 2px;
      opacity: 0;
      transform: translateY(-4px);
      transition: opacity 0.3s, transform 0.3s;
    }

    .gallery-item:hover .download-btn {
      opacity: 1;
      transform: translateY(0);
    }

    .download-btn:hover { background: var(--dune-shadow); }

    /* ── SWISH MODAL ── */
    .modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(58,46,34,0.7);
      backdrop-filter: blur(8px);
      z-index: 200;
      display: flex;
      align-items: center;
      justify-content: center;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.3s;
    }

    .modal-backdrop.open {
      opacity: 1;
      pointer-events: all;
    }

    .modal {
      background: var(--sand-white);
      max-width: 480px;
      width: 90%;
      padding: 3rem;
      border-radius: 4px;
      text-align: center;
      position: relative;
      transform: translateY(20px);
      transition: transform 0.3s;
      box-shadow: 0 30px 80px rgba(58,46,34,0.3);
    }

    .modal-backdrop.open .modal { transform: translateY(0); }

    .modal-close {
      position: absolute;
      top: 1rem; right: 1.25rem;
      background: none;
      border: none;
      font-size: 1.5rem;
      cursor: pointer;
      color: var(--text-soft);
      line-height: 1;
    }

    .modal-close:hover { color: var(--accent); }

    .swish-logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2.5rem;
      font-weight: 600;
      color: var(--accent);
      margin-bottom: 0.5rem;
    }

    .modal h2 {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: 1.8rem;
      color: var(--text-dark);
      margin-bottom: 1rem;
    }

    .modal p {
      color: var(--text-soft);
      font-size: 0.9rem;
      line-height: 1.7;
      margin-bottom: 1.5rem;
    }

    .swish-number {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2rem;
      font-weight: 600;
      color: var(--accent);
      letter-spacing: 0.05em;
      display: block;
      margin: 1.5rem 0;
      padding: 1rem;
      border: 1px solid var(--sand-light);
      border-radius: 4px;
      background: var(--sand-pale);
    }

    .amount-suggestion {
      font-size: 0.75rem;
      color: var(--text-soft);
      letter-spacing: 0.1em;
    }

    .modal-steps {
      list-style: none;
      text-align: left;
      margin: 1.5rem 0;
    }

    .modal-steps li {
      display: flex;
      gap: 1rem;
      align-items: flex-start;
      margin-bottom: 0.8rem;
      font-size: 0.85rem;
      color: var(--text-mid);
    }

    .step-num {
      min-width: 24px;
      height: 24px;
      border-radius: 50%;
      background: var(--accent);
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.7rem;
      font-weight: 400;
    }

    .confirm-btn {
      width: 100%;
      padding: 1rem;
      background: var(--accent);
      color: white;
      border: none;
      font-family: 'Jost', sans-serif;
      font-size: 0.75rem;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      cursor: pointer;
      border-radius: 3px;
      margin-top: 1rem;
      transition: background 0.3s;
    }

    .confirm-btn:hover { background: var(--dune-shadow); }

    /* ── ABOUT ── */
    #om {
      max-width: 900px;
      margin: 0 auto;
      padding: 4rem 2rem 8rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }

    @media (max-width: 700px) {
      #om { grid-template-columns: 1fr; gap: 2rem; }
    }

    .about-portrait {
      aspect-ratio: 3/4;
      background: var(--sand-light);
      border-radius: 3px;
      overflow: hidden;
      position: relative;
    }

    .about-portrait::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(135deg, var(--sand-mid) 0%, var(--sand-deep) 100%);
      opacity: 0.3;
    }

    .portrait-placeholder {
      width: 100%;
      height: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Cormorant Garamond', serif;
      font-size: 5rem;
      color: var(--sand-mid);
      background: linear-gradient(160deg, #e8d5b7, #c4a882);
    }

    .about-text h2 {
      font-family: 'Cormorant Garamond', serif;
      font-weight: 300;
      font-size: clamp(2rem, 5vw, 3rem);
      line-height: 1.1;
      color: var(--text-dark);
      margin-bottom: 1.5rem;
    }

    .about-text h2 em {
      font-style: italic;
      color: var(--accent);
    }

    .about-text p {
      font-size: 0.9rem;
      line-height: 1.9;
      color: var(--text-soft);
      margin-bottom: 1.2rem;
    }

    .about-divider {
      width: 40px;
      height: 1px;
      background: var(--accent);
      margin: 2rem 0;
    }

    /* ── FOOTER ── */
    footer {
      background: var(--sand-deep);
      color: var(--sand-light);
      text-align: center;
      padding: 3rem 2rem;
    }

    footer .footer-name {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.5rem;
      font-weight: 300;
      margin-bottom: 0.5rem;
      color: var(--sand-white);
    }

    footer p {
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      color: var(--sand-mid);
    }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .fade-in.visible {
      opacity: 1;
      transform: none;
    }

    /* ── LOAD MORE ── */
    .load-more-wrap {
      text-align: center;
      margin-top: 3rem;
    }

    .load-more {
      font-family: 'Jost', sans-serif;
      font-size: 0.72rem;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      padding: 1rem 3rem;
      border: 1px solid var(--sand-mid);
      background: transparent;
      color: var(--text-mid);
      cursor: pointer;
      border-radius: 2px;
      transition: all 0.3s;
    }

    .load-more:hover {
      background: var(--accent);
      border-color: var(--accent);
      color: white;
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 600px) {
      nav { padding: 1rem 1.5rem; }
      .nav-links { gap: 1.5rem; }
      .gallery-grid { grid-template-columns: 1fr 1fr; gap: 0.75rem; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a class="nav-logo" href="#">MB</a>
    <ul class="nav-links">
      <li><a href="#galleri">Galleri</a></li>
      <li><a href="#om">Om</a></li>
      <li><a href="#kontakt">Kontakt</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <header>
    <p class="hero-eyebrow">Fotografi & Konst — Sverige</p>
    <h1>Martin<br><em>Björck</em></h1>
    <p class="hero-sub">Bilder som berättar</p>
    <div class="hero-line"></div>

    <div class="dune-divider">
      <svg viewBox="0 0 1440 80" fill="none" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
        <path d="M0 80 C360 0 720 60 1080 20 C1260 0 1380 40 1440 30 L1440 80 Z" fill="#faf5ed"/>
      </svg>
    </div>
  </header>

  <!-- GALLERY SECTION -->
  <section>
    <div class="section-header fade-in">
      <span class="section-tag">Samling</span>
      <h2 class="section-title">Mina <em>bästa</em> bilder</h2>
    </div>

    <div id="galleri">
      <div class="filter-bar fade-in">
        <button class="filter-btn active" data-filter="alla">Alla</button>
        <button class="filter-btn" data-filter="natur">Natur</button>
        <button class="filter-btn" data-filter="stad">Stad</button>
        <button class="filter-btn" data-filter="portratt">Porträtt</button>
        <button class="filter-btn" data-filter="resor">Resor</button>
        <button class="filter-btn" data-filter="abstrakt">Abstrakt</button>
      </div>

      <div class="gallery-grid" id="galleryGrid">
        <!-- Populated by JS -->
      </div>

      <div class="load-more-wrap fade-in">
        <button class="load-more" id="loadMore">Visa fler bilder</button>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="om">
    <div class="about-portrait fade-in">
      <div class="portrait-placeholder">M</div>
    </div>
    <div class="about-text">
      <h2>Om <em>mig</em></h2>
      <div class="about-divider"></div>
      <p>
        Jag är Martin Björck, fotograf baserad i Sverige. Jag fångar ögonblick som annars
        passerar obemärkt — ljusets spel, stämningars tystnad, landskapets själ.
      </p>
      <p>
        Varje bild i det här galleriet representerar ett minne, en känsla eller
        en berättelse. Väljer du att äga en av dem, tar du också med dig en bit
        av den världen hem.
      </p>
      <p>
        Betalning sker enkelt via Swish direkt till mig. Kontakta mig sedan med
        vilken bild du köpt, så skickar jag en högupplöst fil.
      </p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer id="kontakt">
    <p class="footer-name">Martin Björck</p>
    <p>Sverige &nbsp;·&nbsp; Fotografi &nbsp;·&nbsp; Swish-betalning</p>
  </footer>

  <!-- SWISH MODAL -->
  <div class="modal-backdrop" id="swishModal">
    <div class="modal">
      <button class="modal-close" id="closeModal">×</button>
      <div class="swish-logo">◎ Swish</div>
      <h2>Ladda ner bild</h2>
      <p id="modalImageTitle">Köp denna bild via Swish och få en högupplöst fil direkt till dig.</p>

      <span class="swish-number" id="swishNumber">123 456 78 90</span>
      <p class="amount-suggestion">Föreslaget belopp: <strong>150–500 kr</strong></p>

      <ul class="modal-steps">
        <li>
          <span class="step-num">1</span>
          <span>Öppna Swish-appen och skicka valfritt belopp till numret ovan.</span>
        </li>
        <li>
          <span class="step-num">2</span>
          <span>Skriv bildens titel som meddelande i Swish.</span>
        </li>
        <li>
          <span class="step-num">3</span>
          <span>Kontakta mig med din Swish-bekräftelse, så skickar jag bildfilen inom 24h.</span>
        </li>
      </ul>

      <button class="confirm-btn" id="closeModal2">Jag förstår — stäng</button>
    </div>
  </div>

  <script>
    // ── Gallery Data ──────────────────────────────────────────────
    const categories = ['natur', 'stad', 'portratt', 'resor', 'abstrakt'];

    const titles = [
      'Morgondimma', 'Solnedgång', 'Stilla vatten', 'Vindkast', 'Gryningens guld',
      'Skymningens blå', 'Stoftmoln', 'Tystnad', 'Spegel', 'Horisont',
      'Dröm', 'Vind och eld', 'Kall natt', 'Vårregn', 'Isblomma',
      'Stenrev', 'Djupdykning', 'Sandkornet', 'Ljusbrist', 'Halvmörker',
      'Skyline', 'Gränder', 'Broarna', 'Nattliv', 'Fasader',
      'Spökgata', 'Regndroppar', 'Neonljus', 'Tunnel', 'Toppen',
      'Ansikten', 'Blick', 'Händer', 'Skratt', 'Eftertanke',
      'Vila', 'Rörelse', 'Kraft', 'Mjukhet', 'Kontrast',
      'Fjord', 'Alp', 'Öken', 'Djungel', 'Strandkant',
      'Vildmark', 'Nomad', 'Ruiner', 'Marknad', 'Tempel',
      'Passage', 'Fält', 'Bergstopp', 'Båtar', 'Hamn',
      'Dimma', 'Frost', 'Hav', 'Klippa', 'Strand',
      'Form', 'Linje', 'Mönster', 'Geometri', 'Röd punkt',
      'Skugga', 'Ljuskägla', 'Upplösning', 'Textur', 'Perspektiv',
      'Spegling', 'Brus', 'Rörelseoskärpa', 'Negativ', 'Siluett',
      'Ögonblick', 'Avsked', 'Möte', 'Kärlek', 'Ensamhet',
      'Gemenskap', 'Framtid', 'Minne', 'Tid', 'Evighet',
      'Det försvunna', 'Återfunnet', 'Glömt', 'Skapat', 'Levt',
      'Norra ljus', 'Midnattssol', 'Björkskog', 'Älv', 'Hemkomst'
    ];

    const palettes = [
      ['#c4a882','#d9c4a0'],['#8b7355','#c4a882'],['#e8d5b7','#c4a882'],
      ['#d9c4a0','#8b7355'],['#6b5840','#c4a882'],['#a0876a','#e8d5b7'],
      ['#b8976e','#d9c4a0'],['#7a6248','#c4a882'],['#c4a882','#8b7355'],
      ['#e0ceaf','#a0876a']
    ];

    const images = titles.map((title, i) => ({
      id: i + 1,
      title,
      category: categories[i % categories.length],
      palette: palettes[i % palettes.length],
    }));

    // ── Render Gallery ────────────────────────────────────────────
    const grid = document.getElementById('galleryGrid');
    let shown = 0;
    const batchSize = 20;

    function createItem(img) {
      const div = document.createElement('div');
      div.className = 'gallery-item fade-in';
      div.dataset.category = img.category;

      // Placeholder SVG as image
      const svg = `<svg xmlns='http://www.w3.org/2000/svg' width='800' height='600'>
        <defs>
          <linearGradient id='g${img.id}' x1='0%' y1='0%' x2='100%' y2='100%'>
            <stop offset='0%' stop-color='${img.palette[0]}'/>
            <stop offset='100%' stop-color='${img.palette[1]}'/>
          </linearGradient>
          <filter id='noise${img.id}'><feTurbulence type='fractalNoise' baseFrequency='0.65' numOctaves='3' stitchTiles='stitch'/><feColorMatrix type='saturate' values='0'/><feBlend in='SourceGraphic' mode='multiply' result='blend'/></filter>
        </defs>
        <rect width='100%' height='100%' fill='url(#g${img.id})'/>
        <rect width='100%' height='100%' filter='url(#noise${img.id})' opacity='0.15'/>
        <text x='50%' y='52%' dominant-baseline='middle' text-anchor='middle' 
          font-family='Georgia,serif' font-size='22' fill='rgba(255,255,255,0.35)' letter-spacing='3'>
          ${img.title.toUpperCase()}
        </text>
      </svg>`;

      const blob = new Blob([svg], {type: 'image/svg+xml'});
      const url  = URL.createObjectURL(blob);

      div.innerHTML = `
        <img src="${url}" alt="${img.title}" loading="lazy" />
        <div class="gallery-overlay">
          <h3>${img.title}</h3>
          <span>${img.category.charAt(0).toUpperCase() + img.category.slice(1)}</span>
        </div>
        <button class="download-btn" data-title="${img.title}">Köp & Ladda ner</button>
      `;

      div.querySelector('.download-btn').addEventListener('click', e => {
        e.stopPropagation();
        openSwish(img.title);
      });

      div.addEventListener('click', () => openSwish(img.title));
      return div;
    }

    function renderBatch() {
      const end = Math.min(shown + batchSize, images.length);
      const filtered = activeFilter === 'alla'
        ? images : images.filter(i => i.category === activeFilter);

      const slice = filtered.slice(shown, shown + batchSize);
      slice.forEach((img, idx) => {
        const el = createItem(img);
        el.style.transitionDelay = `${idx * 50}ms`;
        grid.appendChild(el);
      });
      shown += slice.length;
      if (shown >= filtered.length) {
        document.getElementById('loadMore').style.display = 'none';
      }
      observeFadeIns();
    }

    // ── Filter ────────────────────────────────────────────────────
    let activeFilter = 'alla';
    document.querySelectorAll('.filter-btn').forEach(btn => {
      btn.addEventListener('click', () => {
        document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        activeFilter = btn.dataset.filter;
        grid.innerHTML = '';
        shown = 0;
        document.getElementById('loadMore').style.display = '';
        renderBatch();
      });
    });

    document.getElementById('loadMore').addEventListener('click', renderBatch);

    // ── Swish Modal ───────────────────────────────────────────────
    const SWISH_NUMBER = '123 456 78 90'; // ← Byt till ditt Swish-nummer

    function openSwish(title) {
      document.getElementById('modalImageTitle').textContent =
        `Köp "${title}" via Swish och få en högupplöst fil direkt till dig.`;
      document.getElementById('swishNumber').textContent = SWISH_NUMBER;
      document.getElementById('swishModal').classList.add('open');
    }

    function closeSwish() {
      document.getElementById('swishModal').classList.remove('open');
    }

    document.getElementById('closeModal').addEventListener('click', closeSwish);
    document.getElementById('closeModal2').addEventListener('click', closeSwish);
    document.getElementById('swishModal').addEventListener('click', e => {
      if (e.target === document.getElementById('swishModal')) closeSwish();
    });

    // ── Intersection Observer ─────────────────────────────────────
    function observeFadeIns() {
      const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.classList.add('visible');
            observer.unobserve(entry.target);
          }
        });
      }, { threshold: 0.1 });

      document.querySelectorAll('.fade-in:not(.visible)').forEach(el => observer.observe(el));
    }

    // ── Init ──────────────────────────────────────────────────────
    renderBatch();
    observeFadeIns();
  </script>
</body>
</html>
