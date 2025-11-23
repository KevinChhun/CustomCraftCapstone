<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CustomCraft — CS Capstone 2025</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="page">
    <header class="hero-card">
      <div class="hero-inner">
        <div class="meta"><span class="status-dot"></span> CS Capstone • Fall 2025</div>
        <h1 class="title">CustomCraft</h1>
        <p class="lead">
          A mobile platform connecting customers and independent artists to commission custom handmade items — from secure payments and project tracking to streamlined communication and artist portfolios.
        </p>

        <div class="pills">
          <span class="pill">Project Type: Mobile App & HCI</span>
          <span class="pill">Platform: Android (Kotlin, Jetpack Compose)</span>
          <span class="pill">Backend: Firebase (Auth, Firestore, Storage)</span>
        </div>
      </div>
    </header>

    <nav class="tabbar" aria-label="Sections">
      <a href="#intro" class="tab">Introduction</a>
      <a href="#background" class="tab">Background & Motivation</a>
      <a href="#approach" class="tab">Methodology / Approach</a>
      <a href="#results" class="tab">Results & Findings</a>
      <a href="#future" class="tab">Discussion & Future Work</a>
      <a href="#feedback" class="tab">Feedback</a>
      <a href="#ack" class="tab">Acknowledgments</a>
    </nav>

    <main class="container">
      <section id="intro" class="card section">
        <h2>1. Project Title & Introduction</h2>
        <p><strong>CustomCraft</strong> is a mobile-first commissioning platform for handmade goods. It organizes commission requests, supports secure payments, lets artists publish portfolios, and provides a step-by-step workflow for custom orders.</p>
        <p>We implemented a full end-to-end prototype (mobile client + cloud backend) to demonstrate usability and technical feasibility.</p>
      </section>

      <section id="background" class="card section">
        <h2>2. Background & Motivation</h2>
        <p>Many artisanal commissions are coordinated over DMs and comments, which makes tracking, payments, and references fragile. CustomCraft aims to reduce friction and provide a professional, persistent workflow for both clients and artists.</p>
      </section>

      <section id="approach" class="card section">
        <h2>3. Methodology / Approach</h2>
        <p>User interviews → low-fi prototypes → iterative UI built in Jetpack Compose → backend using Firebase (Firestore for data, Storage for images, Cloud Functions for server-side logic).</p>
      </section>

      <section id="results" class="card section">
        <h2>4. Results & Findings</h2>
        <p>The prototype supports: artist profiles, commission requests with references, deadline tracking, in-app messaging, image uploads, and mock payment flow.</p>
      </section>

      <section id="future" class="card section">
        <h2>5. Discussion & Future Work</h2>
        <p>Planned: integrated payments, discovery algorithms, ratings, analytics dashboard, and multi-language support.</p>
      </section>

      <section id="feedback" class="card section">
        <h2>6. Feedback</h2>
        <p>Open for instructor and peer feedback — notes from usability tests will be added here.</p>
      </section>

      <section id="ack" class="card section">
        <h2>7. Acknowledgments</h2>
        <p>Thanks to mentors, participants, and classmates who helped with user research and testing.</p>
      </section>

      <footer class="footer">
        <small>CustomCraft • CS Capstone 2025</small>
      </footer>
    </main>
  </div>
</body>
</html>
