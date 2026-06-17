---
title: Home
---

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Chris Norman</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #0d1117;
      color: #e6edf3;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .subtitle {
      color: #8b949e;
      margin-bottom: 30px;
    }

    .card {
      background: #161b22;
      padding: 20px;
      margin: 15px 0;
      border-radius: 10px;
      text-decoration: none;
      color: white;
      display: block;
    }

    .card:hover {
      background: #21262d;
    }

    .nav {
      margin-bottom: 30px;
    }

    .nav a {
      margin-right: 15px;
      color: #58a6ff;
      text-decoration: none;
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>Chris Norman</h1>
    <div class="subtitle">Cybersecurity • Engineering • Film Reviews</div>

    <div class="nav">
      <a href="/">Home</a>
      <a href="/Cybersecurity">Cybersecurity</a>
      <a href="/Engineering">Engineering</a>
      <a href="/Film-Reviews">Film Reviews</a>
    </div>

    <a class="card" href="/Cybersecurity">
      <h2>Cybersecurity</h2>
      <p>Pentesting notes, tools, and writeups.</p>
    </a>

    <a class="card" href="/Engineering">
      <h2>Engineering</h2>
      <p>ESP32 projects, electronics, builds.</p>
    </a>

    <a class="card" href="/Film-Reviews">
      <h2>Film Reviews</h2>
      <p>Movies, analysis, and personal reviews.</p>
    </a>

  </div>
</body>
</html>
