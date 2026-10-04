# Paperswallah
Practice makes you perfect. 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>MP Board Class 10th Mathematics | Premium Master Course 2026–27</title>
  <meta name="description" content="MP Board Class 10th Mathematics Premium Master Course 2026–27. NCERT, examples, PYQs, practice sets, tests and revision.">
  <meta name="theme-color" content="#ff6b00">

  <style>
    :root {
      --primary: #ff6b00;
      --primary-dark: #e85d00;
      --bg: #f6f7fb;
      --card: #ffffff;
      --text: #171717;
      --muted: #6b7280;
      --border: #e5e7eb;
      --green: #16a34a;
      --dark: #111827;
      --radius: 18px;
      --shadow: 0 8px 30px rgba(0,0,0,.07);
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
      font-family: Inter, system-ui, -apple-system, BlinkMacSystemFont,
                   "Segoe UI", Roboto, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    button {
      font: inherit;
    }

    /* NAVBAR */

    .navbar {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(255,255,255,.94);
      backdrop-filter: blur(14px);
      border-bottom: 1px solid var(--border);
    }

    .nav-inner {
      max-width: 1180px;
      margin: auto;
      padding: 14px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .logo {
      font-size: 21px;
      font-weight: 800;
      letter-spacing: -.5px;
    }

    .logo span {
      color: var(--primary);
    }

    .nav-links {
      display: flex;
      gap: 22px;
      align-items: center;
      font-size: 14px;
      font-weight: 600;
    }

    .nav-links a:hover {
      color: var(--primary);
    }

    .nav-btn {
      background: var(--primary);
      color: white;
      padding: 9px 16px;
      border-radius: 10px;
    }

    /* HERO */

    .hero {
      background:
        radial-gradient(circle at 85% 20%, rgba(255,107,0,.15), transparent 30%),
        linear-gradient(135deg,#fff,#fff7f0);
      padding: 72px 20px 65px;
      border-bottom: 1px solid var(--border);
    }

    .hero-inner {
      max-width: 1180px;
      margin: auto;
      display: grid;
      grid-template-columns: 1.35fr .65fr;
      gap: 50px;
      align-items: center;
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      background: #fff0e6;
      color: var(--primary-dark);
      border: 1px solid #ffd5ba;
      padding: 7px 12px;
      border-radius: 999px;
      font-size: 13px;
      font-weight: 700;
      margin-bottom: 18px;
    }

    .hero h1 {
      font-size: clamp(38px, 6vw, 65px);
      line-height: 1.03;
      letter-spacing: -2.5px;
      margin-bottom: 18px;
    }

    .hero h1 span {
      color: var(--primary);
    }

    .hero p {
      color: var(--muted);
      max-width: 680px;
      font-size: 17px;
      margin-bottom: 26px;
    }

    .hero-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 13px 20px;
      border-radius: 12px;
      font-weight: 750;
      border: 1px solid transparent;
      cursor: pointer;
      transition: .2s;
    }

    .btn-primary {
      background: var(--primary);
      color: white;
      box-shadow: 0 8px 20px rgba(255,107,0,.2);
    }

    .btn-primary:hover {
      background: var(--primary-dark);
      transform: translateY(-1px);
    }

    .btn-secondary {
      background: white;
      border-color: var(--border);
    }

    .btn-secondary:hover {
      border-color: var(--primary);
      color: var(--primary);
    }

    .hero-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 24px;
      padding: 26px;
      box-shadow: var(--shadow);
    }

    .score {
      font-size: 52px;
      font-weight: 900;
      color: var(--primary);
      line-height: 1;
      margin-bottom: 8px;
    }

    .hero-card p {
      font-size: 14px;
      margin: 0 0 20px;
    }

    .mini-list {
      list-style: none;
    }

    .mini-list li {
      padding: 9px 0;
      border-bottom: 1px solid var(--border);
      font-size: 14px;
    }

    .mini-list li:last-child {
      border-bottom: 0;
    }

    /* COMMON */

    .section {
      max-width: 1180px;
      margin: auto;
      padding: 65px 20px;
    }

    .section-heading {
      margin-bottom: 28px;
    }

    .section-heading .eyebrow {
      color: var(--primary);
      text-transform: uppercase;
      font-size: 12px;
      font-weight: 800;
      letter-spacing: 1.3px;
    }

    .section-heading h2 {
      font-size: clamp(28px,4vw,40px);
      line-height: 1.15;
      margin: 5px 0 8px;
      letter-spacing: -.8px;
    }

    .section-heading p {
      color: var(--muted);
      max-width: 700px;
    }

    /* FEATURES */

    .feature-grid {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 15px;
    }

    .feature {
      background: white;
      border: 1px solid var(--border);
      padding: 20px;
      border-radius: var(--radius);
      box-shadow: 0 4px 18px rgba(0,0,0,.035);
    }

    .feature-icon {
      width: 40px;
      height: 40px;
      display: grid;
      place-items: center;
      background: #fff1e7;
      border-radius: 11px;
      margin-bottom: 12px;
      font-size: 19px;
    }

    .feature h3 {
      font-size: 16px;
      margin-bottom: 4px;
    }

    .feature p {
      font-size: 13px;
      color: var(--muted);
    }

    /* CHAPTER TABLE */

    .table-wrap {
      background: white;
      border: 1px solid var(--border);
      border-radius: 18px;
      overflow: hidden;
      box-shadow: var(--shadow);
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th {
      background: #111827;
      color: white;
      text-align: left;
      padding: 15px 18px;
      font-size: 13px;
    }

    td {
      padding: 14px 18px;
      border-bottom: 1px solid var(--border);
      font-size: 14px;
    }

    tr:last-child td {
      border-bottom: 0;
    }

    tbody tr {
      cursor: pointer;
      transition: .15s;
    }

    tbody tr:hover {
      background: #fff8f3;
    }

    .chapter-no {
      color: var(--primary);
      font-weight: 800;
    }

    /* DASHBOARD */

    .dashboard {
      display: grid;
      grid-template-columns: repeat(5,1fr);
      gap: 12px;
    }

    .dash-item {
      background: white;
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 18px 14px;
      text-align: center;
      font-size: 13px;
      font-weight: 700;
    }

    .dash-item span {
      display: block;
      font-size: 20px;
      margin-bottom: 7px;
    }

    /* CHAPTER CARDS */

    .chapter-grid {
      display: grid;
      grid-template-columns: repeat(2,1fr);
      gap: 18px;
    }

    .chapter-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 18px;
      overflow: hidden;
      transition: .2s;
    }

    .chapter-card:hover {
      transform: translateY(-3px);
      box-shadow: var(--shadow);
      border-color: #ffd1b0;
    }

    .chapter-top {
      padding: 20px;
      border-bottom: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      gap: 15px;
    }

    .chapter-number {
      color: var(--primary);
      font-size: 12px;
      font-weight: 900;
      text-transform: uppercase;
    }

    .chapter-card h3 {
      margin-top: 3px;
      font-size: 18px;
      line-height: 1.3;
    }

    .chapter-card h3 small {
      display: block;
      color: var(--muted);
      font-size: 13px;
      font-weight: 500;
      margin-top: 3px;
    }

    .chapter-body {
      padding: 18px 20px;
    }

    .chapter-points {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 9px;
      list-style: none;
      margin-bottom: 17px;
    }

    .chapter-points li {
      font-size: 13px;
      color: #374151;
    }

    .chapter-points li::before {
      content: "✓";
      color: var(--green);
      font-weight: 900;
      margin-right: 6px;
    }

    .chapter-actions {
      display: flex;
      gap: 8px;
    }

    .small-btn {
      flex: 1;
      padding: 9px;
      text-align: center;
      border-radius: 9px;
      font-size: 12px;
      font-weight: 800;
      border: 1px solid var(--border);
      cursor: pointer;
      background: white;
    }

    .small-btn.primary {
      background: var(--primary);
      border-color: var(--primary);
      color: white;
    }

    /* ROADMAP */

    .roadmap {
      display: grid;
      grid-template-columns: repeat(3,1fr);
      gap: 15px;
    }

    .roadmap-card {
      background: white;
      border: 1px solid var(--border);
      padding: 22px;
      border-radius: 16px;
    }

    .roadmap-card .num {
      font-size: 12px;
      font-weight: 900;
      color: var(--primary);
    }

    .roadmap-card h3 {
      margin: 4px 0;
      font-size: 17px;
    }

    .roadmap-card p {
      color: var(--muted);
      font-size: 13px;
    }

    /* BONUS */

    .bonus {
      background: #111827;
      color: white;
      border-radius: 24px;
      padding: 35px;
    }

    .bonus .section-heading p {
      color: #cbd5e1;
    }

    .bonus-grid {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 12px;
    }

    .bonus-item {
      background: rgba(255,255,255,.07);
      border: 1px solid rgba(255,255,255,.1);
      padding: 18px;
      border-radius: 14px;
    }

    .bonus-item h3 {
      font-size: 15px;
      margin-bottom: 4px;
    }

    .bonus-item p {
      color: #cbd5e1;
      font-size: 12px;
    }

    /* FAQ */

    .faq {
      max-width: 800px;
    }

    details {
      background: white;
      border: 1px solid var(--border);
      border-radius: 13px;
      margin-bottom: 10px;
      padding: 17px 18px;
    }

    summary {
      cursor: pointer;
      font-weight: 750;
    }

    details p {
      color: var(--muted);
      font-size: 14px;
      padding-top: 10px;
    }

    /* CTA */

    .cta {
      text-align: center;
      background: linear-gradient(135deg,#fff0e5,#ffffff);
      border: 1px solid #ffd5ba;
      border-radius: 24px;
      padding: 45px 20px;
    }

    .cta h2 {
      font-size: clamp(28px,4vw,42px);
      margin-bottom: 10px;
    }

    .cta p {
      color: var(--muted);
      max-width: 650px;
      margin: 0 auto 20px;
    }

    /* FOOTER */

    footer {
      background: #111827;
      color: white;
      margin-top: 60px;
    }

    .footer-inner {
      max-width: 1180px;
      margin: auto;
      padding: 35px 20px;
      display: flex;
      justify-content: space-between;
      gap: 20px;
    }

    footer p {
      color: #9ca3af;
      font-size: 13px;
    }

    /* MODAL */

    .modal {
      position: fixed;
      inset: 0;
      z-index: 2000;
      background: rgba(0,0,0,.55);
      display: none;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .modal.active {
      display: flex;
    }

    .modal-box {
      background: white;
      width: min(680px,100%);
      max-height: 90vh;
      overflow-y: auto;
      border-radius: 20px;
      padding: 28px;
      position: relative;
    }

    .close {
      position: absolute;
      right: 17px;
      top: 14px;
      border: 0;
      background: #f3f4f6;
      width: 34px;
      height: 34px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 18px;
    }

    .modal-box h2 {
      padding-right: 40px;
      margin-bottom: 5px;
    }

    .modal-subtitle {
      color: var(--muted);
      margin-bottom: 20px;
    }

    .modal-section {
      padding: 15px 0;
      border-top: 1px solid var(--border);
    }

    .modal-section h3 {
      font-size: 15px;
      margin-bottom: 7px;
    }

    .modal-section ul {
      padding-left: 20px;
      color: #4b5563;
      font-size: 14px;
    }

    /* RESPONSIVE */

    @media(max-width:900px) {
      .hero-inner {
        grid-template-columns: 1fr;
      }

      .feature-grid {
        grid-template-columns: repeat(2,1fr);
      }

      .dashboard {
        grid-template-columns: repeat(3,1fr);
      }

      .bonus-grid {
        grid-template-columns: repeat(2,1fr);
      }

      .roadmap {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media(max-width:650px) {
      .nav-links {
        display: none;
      }

      .hero {
        padding-top: 50px;
      }

      .hero h1 {
        letter-spacing: -1.5px;
      }

      .feature-grid,
      .chapter-grid,
      .roadmap {
        grid-template-columns: 1fr;
      }

      .dashboard {
        grid-template-columns: 1fr 1fr;
      }

      .bonus-grid {
        grid-template-columns: 1fr;
      }

      .table-wrap {
        overflow-x: auto;
      }

      table {
        min-width: 650px;
      }

      .footer-inner {
        flex-direction: column;
      }

      .chapter-points {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar">
  <div class="nav-inner">
    <a href="#home" class="logo">Papers<span>Wallah</span></a>

    <div class="nav-links">
      <a href="#chapters">Chapters</a>
      <a href="#dashboard">Dashboard</a>
      <a href="#features">Features</a>
      <a href="#tests">Tests</a>
      <a href="#faq">FAQ</a>
      <a href="#start" class="nav-btn">Start Course</a>
    </div>
  </div>
</nav>


<!-- HERO -->
<header class="hero" id="home">
  <div class="hero-inner">

    <div>
      <div class="badge">✦ PREMIUM MASTER COURSE • 2026–27</div>

      <h1>
        Class 10th<br>
        <span>Mathematics</span>
      </h1>

      <p>
        Complete MP Board Mathematics preparation with
        concepts, NCERT solutions, solved examples, PYQs,
        important questions, practice sets and mock tests.
      </p>

      <div class="hero-buttons">
        <a href="#chapters" class="btn btn-primary">Explore Chapters →</a>
        <a href="#dashboard" class="btn btn-secondary">View Course Plan</a>
      </div>
    </div>

    <div class="hero-card">
      <div class="score">14</div>
      <strong>Complete Chapters</strong>
      <p>Hindi + English | MP Board 2026–27</p>

      <ul class="mini-list">
        <li>✓ NCERT + Solved Examples</li>
        <li>✓ Chapter-wise PYQs</li>
        <li>✓ Important Questions</li>
        <li>✓ Practice Sets</li>
        <li>✓ Mock Tests + Revision</li>
      </ul>
    </div>

  </div>
</header>


<!-- FEATURES -->
<section class="section" id="features">

  <div class="section-heading">
    <div class="eyebrow">What's Included</div>
    <h2>Everything You Need to Master Maths</h2>
    <p>
      A structured preparation system designed for
      understanding, practice and board-level performance.
    </p>
  </div>

  <div class="feature-grid">

    <div class="feature">
      <div class="feature-icon">📖</div>
      <h3>Concept Classes</h3>
      <p>Basic to board-level explanations in easy language.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">✍️</div>
      <h3>NCERT Solutions</h3>
      <p>Step-by-step NCERT examples and exercise solutions.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">🎯</div>
      <h3>MP Board PYQs</h3>
      <p>Previous-year questions arranged chapter-wise.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">🔥</div>
      <h3>Important Questions</h3>
      <p>Exam-focused questions for targeted revision.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">📝</div>
      <h3>Practice Sets</h3>
      <p>Extra questions to strengthen every concept.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">⏱️</div>
      <h3>Chapter Tests</h3>
      <p>Test your preparation after every chapter.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">📌</div>
      <h3>Formula Sheets</h3>
      <p>Quick formula and theorem revision.</p>
    </div>

    <div class="feature">
      <div class="feature-icon">⚡</div>
      <h3>Quick Revision</h3>
      <p>Last-minute chapter-wise revision material.</p>
    </div>

  </div>
</section>


<!-- CHAPTER TABLE -->
<section class="section" id="chapters">

  <div class="section-heading">
    <div class="eyebrow">Syllabus</div>
    <h2>Chapter List</h2>
    <p>MP Board Class 10th Mathematics — 2026–27</p>
  </div>

  <div class="table-wrap">

    <table>
      <thead>
        <tr>
          <th>Ch.</th>
          <th>English Name</th>
          <th>हिंदी नाम</th>
        </tr>
      </thead>

      <tbody>

        <tr onclick="openChapter(1)">
          <td class="chapter-no">01</td>
          <td><strong>Real Numbers</strong></td>
          <td>वास्तविक संख्याएँ</td>
        </tr>

        <tr onclick="openChapter(2)">
          <td class="chapter-no">02</td>
          <td><strong>Polynomials</strong></td>
          <td>बहुपद</td>
        </tr>

        <tr onclick="openChapter(3)">
          <td class="chapter-no">03</td>
          <td><strong>Pair of Linear Equations in Two Variables</strong></td>
          <td>दो चर वाले रैखिक समीकरण युग्म</td>
        </tr>

        <tr onclick="openChapter(4)">
          <td class="chapter-no">04</td>
          <td><strong>Quadratic Equations</strong></td>
          <td>द्विघात समीकरण</td>
        </tr>

        <tr onclick="openChapter(5)">
          <td class="chapter-no">05</td>
          <td><strong>Arithmetic Progressions</strong></td>
          <td>समांतर श्रेढ़ियाँ</td>
        </tr>

        <tr onclick="openChapter(6)">
          <td class="chapter-no">06</td>
          <td><strong>Triangles</strong></td>
          <td>त्रिभुज</td>
        </tr>

        <tr onclick="openChapter(7)">
          <td class="chapter-no">07</td>
          <td><strong>Coordinate Geometry</strong></td>
          <td>निर्देशांक ज्यामिति</td>
        </tr>

        <tr onclick="openChapter(8)">
          <td class="chapter-no">08</td>
          <td><strong>Introduction to Trigonometry</strong></td>
          <td>त्रिकोणमिति का परिचय</td>
        </tr>

        <tr onclick="openChapter(9)">
          <td class="chapter-no">09</td>
          <td><strong>Some Applications of Trigonometry</strong></td>
          <td>त्रिकोणमिति के कुछ अनुप्रयोग</td>
        </tr>

        <tr onclick="openChapter(10)">
          <td class="chapter-no">10</td>
          <td><strong>Circles</strong></td>
          <td>वृत्त</td>
        </tr>

        <tr onclick="openChapter(11)">
          <td class="chapter-no">11</td>
          <td><strong>Areas Related to Circles</strong></td>
          <td>वृत्तों से संबंधित क्षेत्रफल</td>
        </tr>

        <tr onclick="openChapter(12)">
          <td class="chapter-no">12</td>
          <td><strong>Surface Areas and Volumes</strong></td>
          <td>पृष्ठीय क्षेत्रफल और आयतन</td>
        </tr>

        <tr onclick="openChapter(13)">
          <td class="chapter-no">13</td>
          <td><strong>Statistics</strong></td>
          <td>सांख्यिकी</td>
        </tr>

        <tr onclick="openChapter(14)">
          <td class="chapter-no">14</td>
          <td><strong>Probability</strong></td>
          <td>प्रायिकता</td>
        </tr>

      </tbody>
    </table>

  </div>
</section>


<!-- CHAPTER DASHBOARD -->
<section class="section" id="dashboard">

  <div class="section-heading">
    <div class="eyebrow">Chapter Dashboard</div>
    <h2>Your Learning Roadmap</h2>
    <p>Follow the same premium learning system for every chapter.</p>
  </div>

  <div class="dashboard">

    <div class="d
