<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Daniel S. Demoz – Data Science Educator & Analytics Consultant</title>
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

      <section id="home" class="page active">
        <header>
          <div class="photo-frame">
            <img src="6.wp5975949.jpg" alt="Portrait of Daniel S. Demoz">
          </div>
          <h1>Daniel S. Demoz</h1>
          <p class="center-subtitle">College Professor | Data & Analytics Consultant | AI-Enhanced Educator</p>
        </header>
      </section>

      <section id="summary" class="page">
        <h2>Professional Summary</h2>
        <p>I am a College Professor, Researcher, and Consultant with over 15 years of experience working across academia, consulting, and public service. I specialize in business intelligence, analytics-driven curriculum development, AI-powered insights, and performance optimization. My teaching portfolio spans leading institutions such as George Brown College, Centennial College, and Seneca College. I bring industry-aligned instruction in SQL, Power BI, Tableau, SAS, Python, and Qualtrics. Through BRUKD Consulting, I support institutions and SMEs with analytics integration, research strategy, and curriculum digitization, delivering training across Canada, Indonesia, and Thailand.</p>
      </section>

      <section id="skills" class="page">
        <h2>Key Skills</h2>
        <ul>
          <li>Data Strategy, Governance & Quality</li>
          <li>Advanced Analytics & Machine Learning</li>
          <li>BI Tools: Power BI, Tableau, Excel Dashboards</li>
          <li>Database Mining: SQL, MySQL, Access</li>
          <li>Statistical Software: SPSS, SAS, Python</li>
          <li>Curriculum Development & LMS (Canvas)</li>
        </ul>
      </section>

      <section id="education" class="page">
        <h2>Education</h2>
        <ul>
          <li>Master of Interdisciplinary AI – University of Ottawa (In Progress)</li>
          <li>Certificate in Teaching in Higher Education – Centennial College (2023)</li>
          <li>Postgraduate Certificate in Marketing Research & Analytics – Centennial College (2021)</li>
          <li>MA in Development Management – Khon Kaen University (2018)</li>
          <li>BA in Sociology & Social Work – University of Asmara (2006)</li>
        </ul>
      </section>

      <section id="experience" class="page">
        <h2>Experience</h2>
        <ul>
          <li><strong>George Brown College</strong> – Professor: Data systems, MySQL, Power BI, and Excel curriculum design.</li>
          <li><strong>Centennial College</strong> – Professor: Teaching postgraduate courses in marketing metrics, database mining, and applied research.</li>
          <li><strong>Seneca College</strong> – Professor: Business and data analytics instruction (since 2023).</li>
          <li><strong>Computek College</strong> – Instructor: Courses in business software, finance, HR, and advanced MS365 tools.</li>
          <li><strong>BRUKD Consulting</strong> – Consultant: Designed 9 digital textbooks, led curriculum planning, delivered guest lectures, and managed research consultation in Southeast Asia.</li>
          <li><strong>Massawa College of Marine Science & Technology</strong> – Lecturer & Researcher: Directed fisheries research and editorial leadership.</li>
          <li><strong>Ministry of Energy & Mines, Eritrea</strong> – SIA Coordinator: Led assessments and national guideline drafting for mining impacts.</li>
          <li><strong>HAMSET Project</strong> – M&E Manager: Oversaw multisector evaluations in education, health, and agriculture.</li>
        </ul>
      </section>

      <section id="certs" class="page">
        <h2>Certifications</h2>
        <ul>
          <li>IBM – Data Science Foundations</li>
          <li>Microsoft – Managing and Analyzing Data in Excel (365)</li>
          <li>IIBA – Requirements Elicitation & Analysis</li>
          <li>Centennial – Technology for Teaching</li>
        </ul>
      </section>

      <section id="contact" class="page">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:asdansi9@yahoo.com">asdansi9@yahoo.com</a><br>
        Location: Toronto, ON, Canada<br>
        LinkedIn: <a href="https://www.linkedin.com/in/daniel-s-demoz">linkedin.com/in/daniel-s-demoz</a></p>
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
