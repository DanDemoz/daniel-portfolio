<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Daniel S. Demoz – Data Analyst & Consultant</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: #0f172a; /* Dark blue-gray */
      color: #e2e8f0;
      display: flex;
      min-height: 100vh;
    }

    nav.sidebar {
      width: 240px;
      background: #1e293b;
      color: #fff;
      padding-top: 30px;
      position: fixed;
      height: 100vh;
      overflow-y: auto;
    }

    nav.sidebar h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 18px;
      color: #38bdf8;
    }

    nav.sidebar a {
      display: block;
      color: #a5f3fc;
      padding: 14px 20px;
      text-decoration: none;
      border-bottom: 1px solid #334155;
      transition: background 0.3s;
    }

    nav.sidebar a:hover {
      background-color: #0ea5e9;
      color: #fff;
    }

    main {
      margin-left: 240px;
      padding: 40px;
      width: calc(100% - 240px);
    }

    .container {
      background: #1e293b;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(56, 189, 248, 0.2);
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    .photo-frame {
      max-width: 220px;
      height: 220px;
      margin: 0 auto 20px auto;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(56, 189, 248, 0.4);
    }

    .photo-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    h1 {
      font-size: 28px;
      color: #7dd3fc;
      margin-bottom: 5px;
    }

    .center-subtitle {
      font-size: 16px;
      color: #94a3b8;
    }

    @media (max-width: 768px) {
      nav.sidebar {
        position: static;
        width: 100%;
        height: auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
      }

      main {
        margin-left: 0;
        width: 100%;
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Sidebar -->
  <nav class="sidebar" aria-label="Main Navigation">
    <h2>Menu</h2>
    <a href="summary.html">Summary</a>
    <a href="skills.html">Skills</a>
    <a href="education.html">Education</a>
    <a href="experience.html">Experience</a>
    <a href="certifications.html">Certifications</a>
    <a href="contact.html">Contact</a>
  </nav>

  <!-- Main -->
  <main>
    <div class="container">
      <header>
        <div class="photo-frame">
          <img src="6.wp5975949.jpg" alt="Portrait of Daniel S. Demoz">
        </div>
        <h1>Daniel S. Demoz</h1>
        <p class="center-subtitle">AI-Powered Educator & Analytics Consultant</p>
      </header>
    </div>
  </main>
</body>
</html>
