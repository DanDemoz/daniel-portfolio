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
      background: #0f172a;
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
      cursor: pointer;
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
      margin-bottom: 20px;
    }

    h2 {
      font-size: 22px;
      color: #38bdf8;
      margin-top: 20px;
      margin-bottom: 10px;
    }

    p, li {
      font-size: 16px;
      line-height: 1.6;
      color: #e2e8f0;
    }

    ul {
      padding-left: 20px;
      margin-bottom: 20px;
    }

    section.page {
      display: none;
    }

    section.page.active {
      display: block;
    }

    a {
      color: #67e8f9;
    }

    a:hover {
      text-decoration: underline;
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
    <a onclick="showPage('home')">Home</a>
    <a onclick="showPage('summary')">Summary</a>
    <a onclick="showPage('skills')">Skills</a>
    <a onclick="showPage('education')">Education</a>
    <a onclick="showPage('experience')">Experience</a>
    <a onclick="showPage('certs')">Certifications</a>
    <a onclick="showPage('contact')">Contact</a>
  </nav>

  <!-- Main Content -->
  <main>
    <div class="container">

      <!-- Home -->
      <section id="home" class="page active">
        <header>
          <div class="photo-frame">
            <img src="6.wp5975949.jpg" alt="Portrait of Daniel S. Demoz">
          </div>
          <h1>Daniel S. Demoz</h1>
          <p class="center-subtitle">AI-Powered Educator & Analytics Consultant</p>
        </header>
      </section>

      <!-- Summary -->
      <section id="summary" class="page">
        <h2>Professional Summary</h2>
        <p>Strategic data analyst and educator with 15+ years of global experience. Specialized in predictive analytics, curriculum development, and AI literacy. Passionate about empowering institutions and professionals through data-driven decision-making and emerging technology.</p>
      </section>

      <!-- Skills -->
      <section id="skills" class="page">
        <h2>Technical Skills</h2>
        <ul>
          <li><strong>Languages & Tools:</strong> SQL, MySQL, Python, SPSS, SAS, Excel, XLMiner</li>
          <li><strong>BI & Visualization:</strong> Power BI, Tableau</li>
          <li><strong>Modeling:</strong> Predictive modeling, Multivariate analysis</li>
          <li><strong>Platforms:</strong> Qualtrics, Sage 50, QuickBooks, Canvas LMS</li>
        </ul>
      </section>

      <!-- Education -->
      <section id="education" class="page">
        <h2>Education</h2>
        <ul>
          <li><strong>University of Ottawa</strong> — M.I.AI (In Progress)</li>
          <li><strong>Centennial College</strong> — Postgrad, Marketing Research & Analytics (2021)</li>
          <li><strong>Centennial College</strong> — Teaching & Learning Certificate (2023)</li>
          <li><strong>Khon Kaen University</strong> — M.A. Development Management</li>
          <li><strong>University of Asmara</strong> — B.A. Sociology & Social Work</li>
        </ul>
      </section>

      <!-- Experience -->
      <section id="experience" class="page">
        <h2>Consulting & Teaching Experience</h2>
        <p><strong>BRUKD Consulting – Founder & Lead Consultant (2017–Present)</strong></p>
        <ul>
          <li>Developed data-driven courseware used in over 3 academic institutions</li>
          <li>Delivered guest lectures on AI, analytics, and transformation in Asia & Canada</li>
          <li>Advised over 12 SMEs on analytics, automation, and digital literacy</li>
        </ul>

        <p><strong>Professor – Centennial, George Brown & Seneca Colleges</strong></p>
        <ul>
          <li>Led over 1,200 graduate students in data analysis, marketing strategy, and BI</li>
          <li>Supervised case-based learning projects using SQL, Power BI, Python, and SAS</li>
        </ul>
      </section>

      <!-- Certifications -->
      <section id="certs" class="page">
        <h2>Certifications</h2>
        <ul>
          <li>Data Science Foundations – IBM</li>
          <li>Excel for Data Analysis – Microsoft 365</li>
          <li>Requirements Elicitation – IIBA</li>
          <li>Technology for Teaching – Centennial College</li>
        </ul>
      </section>

      <!-- Contact -->
      <section id="contact" class="page">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:asbdansi9@gmail.com">asbdansi9@gmail.com</a><br>
        Location: Toronto, ON, Canada<br>
        LinkedIn: <a href="#">(Insert your LinkedIn URL here)</a></p>
      </section>

    </div>
  </main>

  <script>
    function showPage(id) {
      document.querySelectorAll('.page').forEach(section => {
        section.classList.remove('active');
      });
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
