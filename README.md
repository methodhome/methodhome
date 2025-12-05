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
</body>
</html>
