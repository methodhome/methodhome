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

</body>
</html>
