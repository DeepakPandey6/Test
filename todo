<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Deepak Pandey — Senior 3D Artist, Environment & Asset Specialist, transitioning toward Product Management in mobile gaming.">
<title>Deepak Pandey — 3D Artist · Product · Gaming</title>

<style>
  :root {
    --bg: #f5f5f7;
    --surface: #ffffff;
    --surface-soft: #eeeeF0;
    --text: #1d1d1f;
    --muted: #6e6e73;
    --line: rgba(0,0,0,.09);
    --accent: #0071e3;
    --accent-dark: #005bb5;
    --dark: #0b0b0d;
    --radius: 28px;
    --max: 1180px;
  }

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  html {
    scroll-behavior: smooth;
  }

  body {
    font-family:
      -apple-system,
      BlinkMacSystemFont,
      "SF Pro Display",
      "SF Pro Text",
      "Segoe UI",
      Roboto,
      Helvetica,
      Arial,
      sans-serif;
    background: var(--bg);
    color: var(--text);
    line-height: 1.5;
    -webkit-font-smoothing: antialiased;
  }

  a {
    color: inherit;
    text-decoration: none;
  }

  img {
    max-width: 100%;
    display: block;
  }

  .container {
    width: min(var(--max), calc(100% - 40px));
    margin: auto;
  }

  /* ---------------- NAV ---------------- */

  nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 100;
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    background: rgba(245,245,247,.78);
    border-bottom: 1px solid rgba(0,0,0,.05);
  }

  .nav-inner {
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .brand {
    font-size: 18px;
    font-weight: 650;
    letter-spacing: -.4px;
  }

  .nav-links {
    display: flex;
    gap: 30px;
    font-size: 14px;
    color: var(--muted);
  }

  .nav-links a {
    transition: color .2s ease;
  }

  .nav-links a:hover {
    color: var(--text);
  }

  .nav-cta {
    background: var(--text);
    color: white;
    padding: 9px 17px;
    border-radius: 999px;
    font-size: 14px;
    transition: transform .2s ease, background .2s ease;
  }

  .nav-cta:hover {
    transform: translateY(-1px);
    background: #000;
  }

  /* ---------------- HERO ---------------- */

  .hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding: 150px 0 100px;
    overflow: hidden;
    position: relative;
  }

  .hero::before {
    content: "";
    position: absolute;
    width: 650px;
    height: 650px;
    right: -250px;
    top: 100px;
    background:
      radial-gradient(circle,
      rgba(0,113,227,.18),
      rgba(88,86,214,.08) 42%,
      transparent 70%);
    filter: blur(20px);
    pointer-events: none;
  }

  .hero-content {
    max-width: 920px;
    position: relative;
    z-index: 2;
  }

  .eyebrow {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    font-size: 14px;
    color: var(--accent);
    font-weight: 600;
    margin-bottom: 22px;
  }

  .eyebrow-dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #30d158;
  }

  h1 {
    font-size: clamp(54px, 8vw, 104px);
    line-height: .96;
    letter-spacing: -6px;
    font-weight: 700;
    max-width: 1000px;
  }

  .hero h1 span {
    color: #6e6e73;
  }

  .hero-subtitle {
    margin-top: 35px;
    font-size: clamp(20px, 2.4vw, 28px);
    line-height: 1.3;
    color: var(--muted);
    max-width: 760px;
    letter-spacing: -.6px;
  }

  .hero-actions {
    margin-top: 38px;
    display: flex;
    gap: 14px;
    flex-wrap: wrap;
  }

  .button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 14px 23px;
    border-radius: 999px;
    font-size: 16px;
    font-weight: 600;
    transition: all .25s ease;
  }

  .button-primary {
    background: var(--accent);
    color: white;
  }

  .button-primary:hover {
    background: var(--accent-dark);
    transform: translateY(-2px);
  }

  .button-secondary {
    background: rgba(0,0,0,.06);
  }

  .button-secondary:hover {
    background: rgba(0,0,0,.1);
  }

  /* ---------------- SECTION ---------------- */

  section {
    padding: 120px 0;
  }

  .section-label {
    color: var(--accent);
    font-size: 14px;
    font-weight: 650;
    margin-bottom: 14px;
    text-transform: uppercase;
    letter-spacing: .08em;
  }

  .section-title {
    font-size: clamp(38px, 5vw, 64px);
    line-height: 1.02;
    letter-spacing: -3px;
    max-width: 850px;
  }

  .section-description {
    color: var(--muted);
    font-size: 19px;
    max-width: 680px;
    margin-top: 22px;
  }

  /* ---------------- ABOUT ---------------- */

  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1.35fr;
    gap: 80px;
    margin-top: 65px;
    align-items: start;
  }

  .about-large {
    font-size: clamp(26px, 3vw, 38px);
    line-height: 1.2;
    letter-spacing: -1.2px;
  }

  .about-large strong {
    color: var(--accent);
  }

  .about-copy {
    color: var(--muted);
    font-size: 17px;
  }

  .about-copy p + p {
    margin-top: 20px;
  }

  /* ---------------- WORK ---------------- */

  #work {
    background: white;
  }

  .work-grid {
    margin-top: 65px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 24px;
  }

  .work-card {
    min-height: 440px;
    border-radius: var(--radius);
    padding: 38px;
    position: relative;
    overflow: hidden;
    background: #f5f5f7;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    transition: transform .35s ease;
  }

  .work-card:hover {
    transform: translateY(-6px);
  }

  .work-card.dark {
    background: #111113;
    color: white;
  }

  .work-card.blue {
    background: linear-gradient(145deg, #eaf4ff, #dbeaff);
  }

  .work-card.gray {
    background: #e8e8ed;
  }

  .work-number {
    font-size: 14px;
    color: var(--muted);
  }

  .dark .work-number {
    color: #aaa;
  }

  .work-title {
    font-size: clamp(30px, 3.2vw, 46px);
    line-height: 1.05;
    letter-spacing: -1.8px;
    max-width: 500px;
  }

  .work-description {
    margin-top: 18px;
    color: var(--muted);
    max-width: 520px;
    font-size: 16px;
  }

  .dark .work-description {
    color: #aaa;
  }

  .work-tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 25px;
  }

  .tag {
    padding: 7px 12px;
    border-radius: 999px;
    background: rgba(0,0,0,.07);
    font-size: 12px;
    font-weight: 600;
  }

  .dark .tag {
    background: rgba(255,255,255,.1);
  }

  .work-arrow {
    position: absolute;
    right: 32px;
    bottom: 28px;
    width: 44px;
    height: 44px;
    border-radius: 50%;
    background: rgba(0,0,0,.08);
    display: grid;
    place-items: center;
    font-size: 20px;
  }

  .dark .work-arrow {
    background: rgba(255,255,255,.12);
  }

  /* ---------------- TITLES ---------------- */

  .titles {
    margin-top: 60px;
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
  }

  .title-pill {
    background: white;
    border: 1px solid var(--line);
    border-radius: 999px;
    padding: 12px 17px;
    font-size: 14px;
    font-weight: 550;
  }

  /* ---------------- EXPERIENCE ---------------- */

  .experience-list {
    margin-top: 70px;
    border-top: 1px solid var(--line);
  }

  .experience {
    display: grid;
    grid-template-columns: 180px 1fr 170px;
    gap: 30px;
    padding: 34px 0;
    border-bottom: 1px solid var(--line);
    align-items: start;
  }

  .experience-date {
    color: var(--muted);
    font-size: 14px;
  }

  .experience-role {
    font-size: 23px;
    font-weight: 650;
    letter-spacing: -.6px;
  }

  .experience-company {
    margin-top: 5px;
    color: var(--accent);
    font-size: 15px;
    font-weight: 600;
  }

  .experience-description {
    margin-top: 15px;
    color: var(--muted);
    max-width: 650px;
    font-size: 15px;
  }

  .experience-type {
    text-align: right;
    color: var(--muted);
    font-size: 13px;
  }

  /* ---------------- SHIPPED TITLES ---------------- */

  .titles-section {
    background: #111113;
    color: white;
  }

  .titles-section .section-label {
    color: #64a8ff;
  }

  .titles-section .section-description {
    color: #999;
  }

  .game-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: rgba(255,255,255,.12);
    margin-top: 65px;
    border: 1px solid rgba(255,255,255,.12);
    border-radius: 24px;
    overflow: hidden;
  }

  .game {
    min-height: 190px;
    padding: 28px;
    background: #111113;
    transition: background .2s ease;
  }

  .game:hover {
    background: #1a1a1d;
  }

  .game-number {
    color: #666;
    font-size: 13px;
  }

  .game-name {
    font-size: 22px;
    margin-top: 42px;
    letter-spacing: -.5px;
  }

  .game-studio {
    color: #888;
    font-size: 13px;
    margin-top: 5px;
  }

  /* ---------------- SKILLS ---------------- */

  .skills-layout {
    margin-top: 65px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
  }

  .skill-card {
    background: white;
    border-radius: var(--radius);
    padding: 34px;
    border: 1px solid var(--line);
  }

  .skill-card h3 {
    font-size: 23px;
    letter-spacing: -.7px;
    margin-bottom: 25px;
  }

  .skill-list {
    display: flex;
    flex-wrap: wrap;
    gap: 9px;
  }

  .skill {
    padding: 9px 13px;
    border-radius: 10px;
    background: var(--surface-soft);
    font-size: 13px;
    color: #3b3b3f;
  }

  /* ---------------- PM TRANSITION ---------------- */

  .transition {
    background: linear-gradient(145deg, #e8f3ff, #f5f5f7 60%);
  }

  .transition-content {
    max-width: 850px;
  }

  .transition-text {
    font-size: clamp(28px, 4vw, 48px);
    line-height: 1.12;
    letter-spacing: -2px;
    margin-top: 35px;
  }

  .transition-text span {
    color: var(--accent);
  }

  .transition-details {
    margin-top: 30px;
    color: var(--muted);
    font-size: 17px;
    max-width: 680px;
  }

  /* ---------------- CONTACT ---------------- */

  .contact {
    background: white;
    text-align: center;
    padding: 150px 0;
  }

  .contact h2 {
    font-size: clamp(48px, 7vw, 88px);
    line-height: .98;
    letter-spacing: -5px;
  }

  .contact p {
    margin: 25px auto 35px;
    color: var(--muted);
    font-size: 19px;
    max-width: 550px;
  }

  .contact-links {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
  }

  /* ---------------- FOOTER ---------------- */

  footer {
    padding: 35px 0;
    background: white;
    border-top: 1px solid var(--line);
  }

  .footer-inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
  }

  footer p {
    color: var(--muted);
    font-size: 13px;
  }

  .footer-links {
    display: flex;
    gap: 20px;
    color: var(--muted);
    font-size: 13px;
  }

  .footer-links a:hover {
    color: var(--text);
  }

  /* ---------------- ANIMATION ---------------- */

  .reveal {
    opacity: 0;
    transform: translateY(22px);
    transition: opacity .7s ease, transform .7s ease;
  }

  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }

  /* ---------------- MOBILE ---------------- */

  @media (max-width: 850px) {

    .container {
      width: min(100% - 30px, var(--max));
    }

    .nav-links {
      display: none;
    }

    .hero {
      padding-top: 130px;
      min-height: auto;
    }

    h1 {
      letter-spacing: -3.5px;
    }

    section {
      padding: 85px 0;
    }

    .about-grid {
      grid-template-columns: 1fr;
      gap: 35px;
    }

    .work-grid {
      grid-template-columns: 1fr;
    }

    .work-card {
      min-height: 380px;
    }

    .experience {
      grid-template-columns: 1fr;
      gap: 8px;
    }

    .experience-type {
      text-align: left;
    }

    .game-grid {
      grid-template-columns: 1fr 1fr;
    }

    .skills-layout {
      grid-template-columns: 1fr;
    }

    .contact {
      padding: 100px 0;
    }

    .contact h2 {
      letter-spacing: -3px;
    }

    .footer-inner {
      flex-direction: column;
      align-items: flex-start;
    }
  }

  @media (max-width: 520px) {

    .hero-actions {
      flex-direction: column;
      align-items: stretch;
    }

    .button {
      width: 100%;
    }

    .game-grid {
      grid-template-columns: 1fr;
    }

    .work-card {
      padding: 28px;
    }
  }
</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
  <div class="container nav-inner">
    <a href="#top" class="brand">Deepak Pandey</a>

    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#work">Work</a>
      <a href="#experience">Experience</a>
      <a href="#skills">Skills</a>
    </div>

    <a href="#contact" class="nav-cta">Let's talk</a>
  </div>
</nav>


<!-- HERO -->

<main id="top">

<section class="hero">
  <div class="container">
    <div class="hero-content reveal">

      <div class="eyebrow">
        <span class="eyebrow-dot"></span>
        Available for opportunities
      </div>

      <h1>
        I build worlds.<br>
        <span>And the systems behind them.</span>
      </h1>

      <p class="hero-subtitle">
        Senior 3D Artist with 10+ years in gaming and VR,
        specializing in environments, real-time production,
        optimization and cross-functional problem solving.
      </p>

      <div class="hero-actions">
        <a class="button button-primary"
           href="https://www.artstation.com/deepak"
           target="_blank">
          View my work
        </a>

        <a class="button button-secondary"
           href="#contact">
          Get in touch
        </a>
      </div>

    </div>
  </div>
</section>


<!-- ABOUT -->

<section id="about">
  <div class="container">

    <div class="section-label reveal">About</div>

    <h2 class="section-title reveal">
      Art is where I started.<br>
      Problem solving is where I’m going.
    </h2>

    <div class="about-grid">

      <div class="about-large reveal">
        I combine <strong>visual craft</strong>,
        technical thinking and production ownership
        to build experiences that work in the real world.
      </div>

      <div class="about-copy reveal">

        <p>
          I have spent more than a decade working across
          game art, real-time 3D and VR, creating assets and
          environments for both AAA and mobile experiences.
        </p>

        <p>
          At MY Whoosh, my work extends beyond creating assets.
          I work across art, design and engineering to balance
          visual quality, performance, production constraints
          and player experience.
        </p>

        <p>
          I am now expanding that experience into Product
          Management, with a particular interest in mobile
          gaming and products where user experience,
          experimentation and business impact intersect.
        </p>

      </div>

    </div>
  </div>
</section>


<!-- SELECTED WORK -->

<section id="work">

  <div class="container">

    <div class="section-label reveal">Selected work</div>

    <h2 class="section-title reveal">
      From individual assets<br>
      to entire environments.
    </h2>

    <p class="section-description reveal">
      My work sits at the intersection of art, technology
      and production — from creating game-ready assets
      to building scalable workflows for teams.
    </p>


    <div class="work-grid">

      <article class="work-card dark reveal">

        <div>
          <div class="work-number">01 / MY WHOOSH</div>

          <h3 class="work-title">
            Real-time environments for mobile & PC
          </h3>

          <p class="work-description">
            Building optimized environments and assets for
            a live cycling platform while balancing visual
            quality with memory, texture and performance
            constraints.
          </p>

          <div class="work-tags">
            <span class="tag">Environment</span>
            <span class="tag">Optimization</span>
            <span class="tag">Unity</span>
            <span class="tag">Mobile</span>
          </div>
        </div>

        <div class="work-arrow">↗</div>

      </article>


      <article class="work-card blue reveal">

        <div>
          <div class="work-number">02 / PRODUCTION</div>

          <h3 class="work-title">
            Building scalable art pipelines
          </h3>

          <p class="work-description">
            Creating workflows, documentation and production
            systems that improve consistency, onboarding and
            delivery across teams.
          </p>

          <div class="work-tags">
            <span class="tag">Pipeline</span>
            <span class="tag">AI Workflow</span>
            <span class="tag">Jira</span>
            <span class="tag">Leadership</span>
          </div>
        </div>

        <div class="work-arrow">↗</div>

      </article>


      <article class="work-card gray reveal">

        <div>
          <div class="work-number">03 / AAA GAMES</div>

          <h3 class="work-title">
            Assets that shipped on major titles
          </h3>

          <p class="work-description">
            Production experience across globally recognized
            game franchises including Spider-Man, Prey,
            The Walking Dead, GTA Mobile and Immortals
            Fenyx Rising.
          </p>

          <div class="work-tags">
            <span class="tag">AAA</span>
            <span class="tag">Game Art</span>
            <span class="tag">PBR</span>
            <span class="tag">Environment</span>
          </div>
        </div>

        <div class="work-arrow">↗</div>

      </article>


      <article class="work-card reveal">

        <div>
          <div class="work-number">04 / PRODUCT THINKING</div>

          <h3 class="work-title">
            From making features to understanding users
          </h3>

          <p class="work-description">
            Applying player feedback, technical data and
            cross-functional collaboration to identify
            problems and improve the overall product
            experience.
          </p>

          <div class="work-tags">
            <span class="tag">Product</span>
            <span class="tag">User Experience</span>
            <span class="tag">Research</span>
            <span class="tag">Mobile Games</span>
          </div>
        </div>

        <div class="work-arrow">↗</div>

      </article>

    </div>


    <div class="titles reveal">

      <span class="title-pill">Spider-Man — Sony</span>
      <span class="title-pill">Prey — Arkane Studios</span>
      <span class="title-pill">The Walking Dead — Starbreeze</span>
      <span class="title-pill">World of Tanks — Wargaming</span>
      <span class="title-pill">GTA Mobile — Rockstar Games</span>
      <span class="title-pill">Immortals Fenyx Rising — Ubisoft</span>

    </div>

  </div>
</section>


<!-- EXPERIENCE -->

<section id="experience">

  <div class="container">

    <div class="section-label reveal">Experience</div>

    <h2 class="section-title reveal">
      A career built around<br>
      shipping real products.
    </h2>

    <div class="experience-list">

      <div class="experience reveal">
        <div class="experience-date">
          May 2024 — Present
        </div>

        <div>
          <div class="experience-role">
            Senior 3D Asset & Environment Artist
          </div>

          <div class="experience-company">
            MY Whoosh
          </div>

          <div class="experience-description">
            Established scalable workflows, optimized assets
            for mobile performance, documented production
            standards and collaborated across art and technical
            teams.
          </div>
        </div>

        <div class="experience-type">
          Mobile / PC<br>
          Real-time
        </div>
      </div>


      <div class="experience reveal">
        <div class="experience-date">
          Sep 2022 — May 2024
        </div>

        <div>
          <div class="experience-role">
            3D Asset & Environment Artist
          </div>

          <div class="experience-company">
            MY Whoosh
          </div>

          <div class="experience-description">
            Created optimized 3D models, textures and materials,
            integrated assets into Unity and worked closely with
            art, design and development teams.
          </div>
        </div>

        <div class="experience-type">
          Unity<br>
          Mobile Games
        </div>
      </div>


      <div class="experience reveal">
        <div class="experience-date">
          Dec 2020 — Aug 2022
        </div>

        <div>
          <div class="experience-role">
            3D Artist
          </div>

          <div class="experience-company">
            RealWorld One
          </div>

          <div class="experience-description">
            Produced optimized 3D content for real-time
            applications while collaborating with cross-functional
            teams to meet production timelines.
          </div>
        </div>

        <div class="experience-type">
          Real-time<br>
          VR / 3D
        </div>
      </div>


      <div class="experience reveal">
        <div class="experience-date">
          Jan 2020 — Nov 2020
        </div>

        <div>
          <div class="experience-role">
            Mid Texturing Artist
          </div>

          <div class="experience-company">
            Xentrix Studio
          </div>

          <div class="experience-description">
            Delivered production-ready game assets while
            maintaining visual and technical consistency
            across the pipeline.
          </div>
        </div>

        <div class="experience-type">
          Game Art
        </div>
      </div>


      <div class="experience reveal">
        <div class="experience-date">
          Oct 2018 — Dec 2019
        </div>

        <div>
          <div class="experience-role">
            CG Game Artist
          </div>

          <div class="experience-company">
            Technicolor
          </div>

          <div class="experience-description">
            Supported production of game-ready content for
            AAA projects while working with senior artists
            and production teams.
          </div>
        </div>

        <div class="experience-type">
          AAA<br>
          Game Art
        </div>
      </div>


      <div class="experience reveal">
        <div class="experience-date">
          Aug 2015 — Sep 2018
        </div>

        <div>
          <div class="experience-role">
            Junior Game Artist
          </div>

          <div class="experience-company">
            Dhruva Interactive
          </div>

          <div class="experience-description">
            Built the foundation of my game-art career,
            developing production skills and contributing
            to shipped game projects.
          </div>
        </div>

        <div class="experience-type">
          Game Development
        </div>
      </div>

    </div>
  </div>
</section>


<!-- SHIPPED TITLES -->

<section class="titles-section">

  <div class="container">

    <div class="section-label reveal">
      Shipped titles
    </div>

    <h2 class="section-title reveal">
      Work that made<br>
      it into the game.
    </h2>

    <p class="section-description reveal">
      Experience across AAA, mobile and real-time
      interactive projects.
    </p>


    <div class="game-grid">

      <div class="game reveal">
        <div class="game-number">01</div>
        <div class="game-name">Spider-Man</div>
        <div class="game-studio">Sony</div>
      </div>

      <div class="game reveal">
        <div class="game-number">02</div>
        <div class="game-name">Prey</div>
        <div class="game-studio">Arkane Studios</div>
      </div>

      <div class="game reveal">
        <div class="game-number">03</div>
        <div class="game-name">The Walking Dead</div>
        <div class="game-studio">Starbreeze Studios</div>
      </div>

      <div class="game reveal">
        <div class="game-number">04</div>
        <div class="game-name">World of Tanks</div>
        <div class="game-studio">Wargaming</div>
      </div>

      <div class="game reveal">
        <div class="game-number">05</div>
        <div class="game-name">GTA Mobile</div>
        <div class="game-studio">Rockstar Games</div>
      </div>

      <div class="game reveal">
        <div class="game-number">06</div>
        <div class="game-name">Immortals Fenyx Rising</div>
        <div class="game-studio">Ubisoft</div>
      </div>

    </div>

  </div>
</section>


<!-- SKILLS -->

<section id="skills">

  <div class="container">

    <div class="section-label reveal">
      Capabilities
    </div>

    <h2 class="section-title reveal">
      Creative, technical<br>
      and increasingly product-minded.
    </h2>


    <div class="skills-layout">

      <div class="skill-card reveal">

        <h3>3D & Game Art</h3>

        <div class="skill-list">
          <span class="skill">Environment Art</span>
          <span class="skill">3D Asset Creation</span>
          <span class="skill">PBR Texturing</span>
          <span class="skill">High → Low Poly</span>
          <span class="skill">UV Optimization</span>
          <span class="skill">Baking</span>
          <span class="skill">LOD Creation</span>
          <span class="skill">Collision Setup</span>
          <span class="skill">Materials</span>
          <span class="skill">Real-time Optimization</span>
        </div>

      </div>


      <div class="skill-card reveal">

        <h3>Production & Product</h3>

        <div class="skill-list">
          <span class="skill">Requirements Gathering</span>
          <span class="skill">Cross-functional Collaboration</span>
          <span class="skill">Pipeline Ownership</span>
          <span class="skill">Production Planning</span>
          <span class="skill">Agile / Jira</span>
          <span class="skill">User Feedback</span>
          <span class="skill">Performance Data</span>
          <span class="skill">Process Improvement</span>
          <span class="skill">AI Workflow Optimization</span>
        </div>

      </div>


      <div class="skill-card reveal">

        <h3>Tools</h3>

        <div class="skill-list">
          <span class="skill">Unity</span>
          <span class="skill">Maya</span>
          <span class="skill">ZBrush</span>
          <span class="skill">Blender</span>
          <span class="skill">Substance Painter</span>
          <span class="skill">Photoshop</span>
          <span class="skill">Marmoset Toolbag</span>
          <span class="skill">Perforce</span>
          <span class="skill">Jira</span>
          <span class="skill">SQL</span>
          <span class="skill">Azure</span>
        </div>

      </div>


      <div class="skill-card reveal">

        <h3>Education</h3>

        <div style="font-size:20px;font-weight:600;">
          B.A. in Animation & Film Making
        </div>

        <div style="margin-top:8px;color:#6e6e73;">
          2013
        </div>

        <div style="margin-top:35px;font-size:15px;color:#6e6e73;">
          Product Management Certification
          <br>
          In progress · Expected 2026
        </div>

      </div>

    </div>

  </div>
</section>


<!-- PRODUCT TRANSITION -->

<section class="transition">

  <div class="container">

    <div class="transition-content">

      <div class="section-label reveal">
        What's next
      </div>

      <div class="transition-text reveal">
        I'm moving from building the
        <span>experience</span> to helping
        decide what experience should
        be built next.
      </div>

      <p class="transition-details reveal">
        My next goal is to bring my game-development
        background, production experience and user-focused
        problem solving into Product Management — with
        mobile gaming as my primary focus.
      </p>

      <div class="hero-actions reveal">
        <a class="button button-primary"
           href="mailto:92deepakadi@gmail.com">
          Start a conversation
        </a>
      </div>

    </div>

  </div>
</section>


<!-- CONTACT -->

<section id="contact" class="contact">

  <div class="container">

    <div class="section-label reveal">
      Contact
    </div>

    <h2 class="reveal">
      Let's build<br>
      something useful.
    </h2>

    <p class="reveal">
      Open to conversations around game art,
      environment production, leadership and
      Product Management opportunities.
    </p>

    <div class="contact-links reveal">

      <a class="button button-primary"
         href="mailto:92deepakadi@gmail.com">
        Email me
      </a>

      <a class="button button-secondary"
         href="https://www.artstation.com/deepak"
         target="_blank">
        ArtStation
      </a>

      <a class="button button-secondary"
         href="https://www.linkedin.com/in/deepak-pandey-2766b6b2/"
         target="_blank">
        LinkedIn
      </a>

    </div>

  </div>

</section>

</main>


<!-- FOOTER -->

<footer>

  <div class="container footer-inner">

    <p>
      © <span id="year"></span> Deepak Pandey
    </p>

    <div class="footer-links">
      <a href="mailto:92deepakadi@gmail.com">Email</a>
      <a href="https://www.artstation.com/deepak" target="_blank">ArtStation</a>
      <a href="https://www.linkedin.com/in/deepak-pandey-2766b6b2/" target="_blank">LinkedIn</a>
    </div>

  </div>

</footer>


<script>

  /* Current year */
  document.getElementById("year").textContent =
    new Date().getFullYear();


  /* Scroll reveal */

  const revealElements =
    document.querySelectorAll(".reveal");

  const observer =
    new IntersectionObserver(
      entries => {

        entries.forEach(entry => {

          if (entry.isIntersecting) {
            entry.target.classList.add("visible");
            observer.unobserve(entry.target);
          }

        });

      },
      {
        threshold: 0.12
      }
    );


  revealElements.forEach(element => {
    observer.observe(element);
  });

</script>

</body>
</html>
