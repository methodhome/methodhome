<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>METHOD HOME | Premium Supply for Russia</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    /* COLOR PALETTE (Luxury Gold / Black / White) */
    :root {
      --gold: #d4af37;
      --gold-light: #e9d798;
      --black: #0d0d0d;
      --dark: #131313;
      --white: #ffffff;
      --gray: #bfbfbf;
      --max-width: 1200px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: system-ui, sans-serif;
      background: var(--black);
      color: var(--white);
      line-height: 1.6;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    header {
      width: 100%;
      background: var(--dark);
      padding: 1rem 0;
      border-bottom: 1px solid rgba(255,255,255,0.1);
      position: sticky;
      top: 0;
      z-index: 50;
    }

    .nav-container {
      max-width: var(--max-width);
      margin: auto;
      padding: 0 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.4rem;
      font-weight: 700;
      letter-spacing: 0.05em;
      color: var(--white);
    }

    .logo span {
      color: var(--gold);
    }

    nav {
      display: flex;
      gap: 1.5rem;
      font-size: 0.95rem;
    }

    nav a:hover {
      color: var(--gold);
    }

    .lang {
      display: flex;
      gap: 0.7rem;
      font-size: 0.85rem;
    }

    .lang a {
      padding: 0.2rem 0.6rem;
      border: 1px solid transparent;
      border-radius: 999px;
    }

    .lang a.active {
      border-color: var(--gold);
      color: var(--gold);
    }

    main {
      max-width: var(--max-width);
      margin: auto;
      padding: 2rem 1.5rem;
    }

  </style>
</head>

<body>

<header>
  <div class="nav-container">
    <div class="logo">METHOD <span>HOME</span></div>

    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#industries">Industries</a>
      <a href="#about">About</a>
      <a href="#quality">Quality</a>
      <a href="#contact">Contact</a>
    </nav>

    <div class="lang">
      <a class="active">EN</a>
      <a>RU</a>
    </div>
  </div>
</header>

<main>
  <!-- محتوا بعداً اضافه می‌شود -->
  <h2 style="color: var(--gold); margin-top: 2rem;">Base Template Loaded Successfully</h2>
  <p>If you see this message, the site structure works and we can continue.</p>
</main>
<section id="home" class="hero">
  <style>
    .hero {
      padding: 4rem 0;
      display: grid;
      grid-template-columns: 1.1fr 1fr;
      gap: 3rem;
      align-items: center;
      border-bottom: 1px solid rgba(255, 191, 0, 0.25);
    }

    .hero h1 {
      font-size: 2.4rem;
      font-weight: 700;
      line-height: 1.3;
      color: var(--gold);
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.05rem;
      color: var(--gray);
      margin-bottom: 1.5rem;
      max-width: 500px;
    }

    .hero-btns {
      display: flex;
      gap: 1rem;
      margin-bottom: 2rem;
    }

    .btn-gold {
      padding: 0.75rem 1.4rem;
      border-radius: 999px;
      background: var(--gold);
      color: var(--black);
      font-weight: 600;
    }

    .btn-outline {
      padding: 0.75rem 1.4rem;
      border-radius: 999px;
      border: 1px solid var(--gold);
      color: var(--gold);
      font-weight: 600;
    }

    .hero-box {
      background: var(--dark);
      border: 1px solid rgba(255, 215, 0, 0.3);
      padding: 1.5rem;
      border-radius: 1rem;
      box-shadow: 0 0 20px rgba(255, 215, 0, 0.08);
    }

    .hero-box h3 {
      color: var(--gold);
      margin-bottom: 1rem;
    }

    .hero-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .tag {
      padding: 0.35rem 0.8rem;
      background: rgba(212,175,55,0.12);
      border: 1px solid rgba(212,175,55,0.3);
      border-radius: 999px;
      font-size: 0.85rem;
      color: var(--gold);
    }

    @media(max-width: 850px) {
      .hero {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div>
    <h1>Premium supply of detergents, food products and nuts for the Russian B2B market</h1>

    <p>
      METHOD HOME delivers detergents, hygiene products, food items and premium nuts to distributors, manufacturers and wholesale markets across Russia and neighboring regions.
    </p>

    <div class="hero-btns">
      <a href="#products" class="btn-gold">View Products</a>
      <a href="#contact" class="btn-outline">Contact Sales</a>
    </div>

    <div class="hero-tags">
      <span class="tag">Detergents & Hygiene</span>
      <span class="tag">Food Products</span>
      <span class="tag">Nuts & Dried Fruits</span>
      <span class="tag">B2B Supply</span>
    </div>
  </div>

  <div class="hero-box">
    <h3>Key product groups</h3>
    <div class="hero-tags">
      <span class="tag">Detergents</span>
      <span class="tag">Hygiene</span>
      <span class="tag">Food Items</span>
      <span class="tag">Nuts</span>
    </div>

    <h3 style="margin-top:1.5rem;">Main Focus</h3>
    <div class="hero-tags">
      <span class="tag">Private Label</span>
      <span class="tag">Bulk Supply</span>
      <span class="tag">Russia Market</span>
    </div>
  </div>
</section>
<section id="products" class="section-products">
  <style>
    .section-products {
      padding: 3rem 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    }

    .section-products-header {
      margin-bottom: 2rem;
    }

    .section-products-header h2 {
      font-size: 1.8rem;
      color: var(--gold);
      margin-bottom: 0.5rem;
    }

    .section-products-header p {
      color: var(--gray);
      max-width: 550px;
      font-size: 0.98rem;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 1.5rem;
    }

    .product-card {
      background: #181818;
      border-radius: 0.9rem;
      padding: 1.4rem;
      border: 1px solid rgba(255, 255, 255, 0.06);
      box-shadow: 0 0 18px rgba(0, 0, 0, 0.4);
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      min-height: 200px;
    }

    .product-pill {
      font-size: 0.78rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--gold-light);
    }

    .product-title {
      font-size: 1.05rem;
      font-weight: 600;
      color: var(--white);
    }

    .product-text {
      font-size: 0.9rem;
      color: var(--gray);
      flex: 1;
    }

    .product-meta {
      font-size: 0.85rem;
      color: var(--gold-light);
      margin-top: 0.3rem;
    }

    .product-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.3rem;
    }

    .product-list li {
      font-size: 0.86rem;
      color: var(--gray);
      margin-bottom: 0.15rem;
      position: relative;
      padding-left: 0.9rem;
    }

    .product-list li::before {
      content: "•";
      position: absolute;
      left: 0;
      top: 0;
      color: var(--gold);
    }

    @media (max-width: 950px) {
      .products-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }
    }

    @media (max-width: 650px) {
      .products-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="section-products-header">
    <h2>Our main product groups</h2>
    <p>
      METHOD HOME focuses on three core product groups designed for B2B partners in Russia:
      detergents & hygiene, food products and premium nuts & dried fruits.
    </p>
  </div>

  <div class="products-grid">
    <!-- Group 01 -->
    <div class="product-card">
      <div class="product-pill">Group 01</div>
      <div class="product-title">Detergents & Hygiene</div>
      <p class="product-text">
        Household and industrial detergents and hygiene products suitable for distribution
        and private-label production.
      </p>
      <ul class="product-list">
        <li>Laundry liquids and powders</li>
        <li>Dishwashing liquids</li>
        <li>Surface and floor cleaners</li>
        <li>Hand wash and sanitizers</li>
      </ul>
      <div class="product-meta">Target: distributors · manufacturers</div>
    </div>

    <!-- Group 02 -->
    <div class="product-card">
      <div class="product-pill">Group 02</div>
      <div class="product-title">Food Products</div>
      <p class="product-text">
        Essential food items sourced under controlled quality for wholesale, cash & carry
        and retail partners.
      </p>
      <ul class="product-list">
        <li>Edible oils</li>
        <li>Rice and grains</li>
        <li>Canned and packaged foods</li>
        <li>Basic ingredients for retail shelves</li>
      </ul>
      <div class="product-meta">Target: wholesalers · cash & carry</div>
    </div>

    <!-- Group 03 -->
    <div class="product-card">
      <div class="product-pill">Group 03</div>
      <div class="product-title">Nuts & Dried Fruits</div>
      <p class="product-text">
        Premium nuts and dried fruits for snacks, bakery, confectionery and food-industry applications.
      </p>
      <ul class="product-list">
        <li>Pistachios, hazelnuts, sunflower seeds</li>
        <li>Raisins, dates, mixed dried fruits</li>
        <li>Bulk and retail-ready options</li>
        <li>Suitable for export-oriented partners</li>
      </ul>
      <div class="product-meta">Target: distributors · food industry</div>
    </div>
  </div>
</section>
<section id="industries" class="section-industries">
  <style>
    .section-industries {
      padding: 3rem 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    }

    .section-industries-header h2 {
      font-size: 1.8rem;
      color: var(--gold);
      margin-bottom: 0.5rem;
    }

    .section-industries-header p {
      color: var(--gray);
      max-width: 600px;
      font-size: 0.96rem;
      margin-bottom: 2rem;
    }

    .industries-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 1.5rem;
    }

    .industry-card {
      background: #181818;
      border-radius: 0.9rem;
      padding: 1.4rem;
      border: 1px solid rgba(255, 255, 255, 0.06);
      box-shadow: 0 0 18px rgba(0, 0, 0, 0.4);
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      min-height: 180px;
    }

    .industry-title {
      font-size: 1.02rem;
      font-weight: 600;
      color: var(--white);
    }

    .industry-text {
      font-size: 0.9rem;
      color: var(--gray);
      flex: 1;
    }

    .industry-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.4rem;
    }

    .industry-list li {
      font-size: 0.86rem;
      color: var(--gray);
      margin-bottom: 0.15rem;
      padding-left: 0.9rem;
      position: relative;
    }

    .industry-list li::before {
      content: "•";
      position: absolute;
      left: 0;
      top: 0;
      color: var(--gold);
    }

    @media (max-width: 950px) {
      .industries-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }
    }

    @media (max-width: 650px) {
      .industries-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="section-industries-header">
    <h2>Industries we serve</h2>
    <p>
      METHOD HOME supports professional buyers in the Russian and regional markets, including distributors,
      manufacturers and wholesale operators.
    </p>
  </div>

  <div class="industries-grid">
    <!-- Card 1 -->
    <div class="industry-card">
      <div class="industry-title">Distributors & wholesalers</div>
      <p class="industry-text">
        Stable assortments, competitive pricing and documentation support for distribution across Russia
        and neighboring regions.
      </p>
      <ul class="industry-list">
        <li>Balanced product ranges</li>
        <li>Flexible minimum order quantities (MOQ)</li>
        <li>Support with labels and certificates</li>
      </ul>
    </div>

    <!-- Card 2 -->
    <div class="industry-card">
      <div class="industry-title">Manufacturers & private label</div>
      <p class="industry-text">
        Bulk supplies and private-label options for detergents, hygiene products, food items and nuts.
      </p>
      <ul class="industry-list">
        <li>Contract filling and production</li>
        <li>Custom packaging and branding</li>
        <li>Specification and quality control</li>
      </ul>
    </div>

    <!-- Card 3 -->
    <div class="industry-card">
      <div class="industry-title">Wholesale & cash & carry</div>
      <p class="industry-text">
        Ready-to-sell products and formats designed for wholesale markets, cash & carry and regional chains.
      </p>
      <ul class="industry-list">
        <li>High-rotation SKUs</li>
        <li>Attractive margins for partners</li>
        <li>Consistent supply from Turkey to Russia</li>
      </ul>
    </div>
  </div>
</section>


<section id="about" class="section-about">
  <style>
    .section-about {
      padding: 3rem 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    }

    .about-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 2rem;
    }

    .section-about h2 {
      font-size: 1.8rem;
      color: var(--gold);
      margin-bottom: 0.5rem;
    }

    .section-about p {
      color: var(--gray);
      font-size: 0.95rem;
      margin-bottom: 0.8rem;
    }

    .about-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.5rem;
    }

    .about-badge {
      font-size: 0.8rem;
      padding: 0.3rem 0.7rem;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      color: var(--gold-light);
    }

    .about-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.5rem;
    }

    .about-list li {
      font-size: 0.9rem;
      color: var(--gray);
      margin-bottom: 0.25rem;
      padding-left: 0.9rem;
      position: relative;
    }

    .about-list li::before {
      content: "•";
      position: absolute;
      left: 0;
      top: 0;
      color: var(--gold);
    }

    @media (max-width: 850px) {
      .about-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="about-grid">
    <div>
      <h2>METHOD HOME in brief</h2>
      <p>
        METHOD HOME is a sourcing and distribution partner focused on detergents, hygiene products,
        food items and nuts. Our goal is to connect reliable producers with professional buyers in Russia
        and surrounding markets.
      </p>
      <p>
        Operating between Turkey, Russia and CIS, we provide a single contact point for product selection,
        documentation and logistics, so our partners can focus on sales and growth.
      </p>

      <div class="about-badges">
        <span class="about-badge">B2B only</span>
        <span class="about-badge">Detergents & hygiene</span>
        <span class="about-badge">Food & nuts</span>
        <span class="about-badge">Russia & CIS focus</span>
      </div>
    </div>

    <div>
      <h3 style="font-size: 1rem; color: var(--gold); margin-bottom: 0.4rem;">Our principles</h3>
      <ul class="about-list">
        <li><strong>Reliability:</strong> stable supply and clear communication.</li>
        <li><strong>Transparency:</strong> honest information on prices, specifications and timelines.</li>
        <li><strong>Flexibility:</strong> product and packaging options tailored to each partner.</li>
      </ul>

      <h3 style="font-size: 1rem; color: var(--gold); margin: 1.2rem 0 0.4rem;">Main regions</h3>
      <ul class="about-list">
        <li>Russia as the primary market</li>
        <li>CIS and neighboring regions</li>
        <li>Close cooperation with Turkish producers</li>
      </ul>
    </div>
  </div>
</section>
<section id="industries" class="section-industries">
  <style>
    .section-industries {
      padding: 3rem 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    }

    .section-industries-header h2 {
      font-size: 1.8rem;
      color: var(--gold);
      margin-bottom: 0.5rem;
    }

    .section-industries-header p {
      color: var(--gray);
      max-width: 600px;
      font-size: 0.96rem;
      margin-bottom: 2rem;
    }

    .industries-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 1.5rem;
    }

    .industry-card {
      background: #181818;
      border-radius: 0.9rem;
      padding: 1.4rem;
      border: 1px solid rgba(255, 255, 255, 0.06);
      box-shadow: 0 0 18px rgba(0, 0, 0, 0.4);
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
      min-height: 180px;
    }

    .industry-title {
      font-size: 1.02rem;
      font-weight: 600;
      color: var(--white);
    }

    .industry-text {
      font-size: 0.9rem;
      color: var(--gray);
      flex: 1;
    }

    .industry-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.4rem;
    }

    .industry-list li {
      font-size: 0.86rem;
      color: var(--gray);
      margin-bottom: 0.15rem;
      padding-left: 0.9rem;
      position: relative;
    }

    .industry-list li::before {
      content: "•";
      position: absolute;
      left: 0;
      top: 0;
      color: var(--gold);
    }

    @media (max-width: 950px) {
      .industries-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }
    }

    @media (max-width: 650px) {
      .industries-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="section-industries-header">
    <h2>Industries we serve</h2>
    <p>
      METHOD HOME supports professional buyers in the Russian and regional markets, including distributors,
      manufacturers and wholesale operators.
    </p>
  </div>

  <div class="industries-grid">
    <!-- Card 1 -->
    <div class="industry-card">
      <div class="industry-title">Distributors & wholesalers</div>
      <p class="industry-text">
        Stable assortments, competitive pricing and documentation support for distribution across Russia
        and neighboring regions.
      </p>
      <ul class="industry-list">
        <li>Balanced product ranges</li>
        <li>Flexible minimum order quantities (MOQ)</li>
        <li>Support with labels and certificates</li>
      </ul>
    </div>

    <!-- Card 2 -->
    <div class="industry-card">
      <div class="industry-title">Manufacturers & private label</div>
      <p class="industry-text">
        Bulk supplies and private-label options for detergents, hygiene products, food items and nuts.
      </p>
      <ul class="industry-list">
        <li>Contract filling and production</li>
        <li>Custom packaging and branding</li>
        <li>Specification and quality control</li>
      </ul>
    </div>

    <!-- Card 3 -->
    <div class="industry-card">
      <div class="industry-title">Wholesale & cash & carry</div>
      <p class="industry-text">
        Ready-to-sell products and formats designed for wholesale markets, cash & carry and regional chains.
      </p>
      <ul class="industry-list">
        <li>High-rotation SKUs</li>
        <li>Attractive margins for partners</li>
        <li>Consistent supply from Turkey to Russia</li>
      </ul>
    </div>
  </div>
</section>


<section id="about" class="section-about">
  <style>
    .section-about {
      padding: 3rem 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    }

    .about-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 2rem;
    }

    .section-about h2 {
      font-size: 1.8rem;
      color: var(--gold);
      margin-bottom: 0.5rem;
    }

    .section-about p {
      color: var(--gray);
      font-size: 0.95rem;
      margin-bottom: 0.8rem;
    }

    .about-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.5rem;
    }

    .about-badge {
      font-size: 0.8rem;
      padding: 0.3rem 0.7rem;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      color: var(--gold-light);
    }

    .about-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.5rem;
    }

    .about-list li {
      font-size: 0.9rem;
      color: var(--gray);
      margin-bottom: 0.25rem;
      padding-left: 0.9rem;
      position: relative;
    }

    .about-list li::before {
      content: "•";
      position: absolute;
      left: 0;
      top: 0;
      color: var(--gold);
    }

    @media (max-width: 850px) {
      .about-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="about-grid">
    <div>
      <h2>METHOD HOME in brief</h2>
      <p>
        METHOD HOME is a sourcing and distribution partner focused on detergents, hygiene products,
        food items and nuts. Our goal is to connect reliable producers with professional buyers in Russia
        and surrounding markets.
      </p>
      <p>
        Operating between Turkey, Russia and CIS, we provide a single contact point for product selection,
        documentation and logistics, so our partners can focus on sales and growth.
      </p>

      <div class="about-badges">
        <span class="about-badge">B2B only</span>
        <span class="about-badge">Detergents & hygiene</span>
        <span class="about-badge">Food & nuts</span>
        <span class="about-badge">Russia & CIS focus</span>
      </div>
    </div>

    <div>
      <h3 style="font-size: 1rem; color: var(--gold); margin-bottom: 0.4rem;">Our principles</h3>
      <ul class="about-list">
        <li><strong>Reliability:</strong> stable supply and clear communication.</li>
        <li><strong>Transparency:</strong> honest information on prices, specifications and timelines.</li>
        <li><strong>Flexibility:</strong> product and packaging options tailored to each partner.</li>
      </ul>

      <h3 style="font-size: 1rem; color: var(--gold); margin: 1.2rem 0 0.4rem;">Main regions</h3>
      <ul class="about-list">
        <li>Russia as the primary market</li>
        <li>CIS and neighboring regions</li>
        <li>Close cooperation with Turkish producers</li>
      </ul>
    </div>
  </div>
</section>
</body>
</html>
