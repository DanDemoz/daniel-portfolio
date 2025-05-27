<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Daniel S. Demoz – Data Science Educator & Analytics Consultant</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
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
    }
    nav.sidebar a:hover,
    nav.sidebar a.active-link {
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
    section {
      margin-bottom: 40px;
    }
    a {
      color: #67e8f9;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 14px;
      color: #64748b;
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
    <a href="#home-summary">Home</a>
    <a href="#skills">Skills</a>
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#certs">Certifications</a>
    <a href="#projects">Projects</a>
    <a href="#publications">Publications</a>
    <a href="#talks">Talks</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
    <a href="Daniel-Demoz-Resume.pdf" download style="margin: 10px 20px; color:#0ea5e9;">Download Resume (PDF)</a>
  </nav>

  <!-- Main Content -->
  <main>
    <div class="container">
      <section id="home-summary">
        <header>
          <div class="photo-frame">
            <img src="profile-picture.jpg" alt="Portrait of Daniel S. Demoz">
          </div>
          <h1>Daniel S. Demoz</h1>
          <p class="center-subtitle">College Professor | Data & Analytics Consultant | AI-Enhanced Educator</p>
        </header>
        <h2>Professional Summary</h2>
        <p>I am a College Professor, Researcher, and Consultant with over 15 years of experience working across academia, consulting, and public service. I specialize in business intelligence, analytics-driven curriculum development, AI-powered insights, and performance optimization. My teaching portfolio spans leading institutions such as George Brown College, Centennial College, and Seneca College. I bring industry-aligned instruction in SQL, Power BI, Tableau, SAS, Python, and Qualtrics. Through BRUKD Consulting, I support institutions and SMEs with analytics integration, research strategy, and curriculum digitization, delivering training across Canada, Indonesia, and Thailand.</p>
      </section>

      <section id="skills">
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

      <section id="education">
        <h2>Education</h2>
        <ul>
          <li>Master of Interdisciplinary AI – University of Ottawa (In Progress)</li>
          <li>Certificate in Teaching in Higher Education – Centennial College</li>
          <li>Postgraduate Certificate in Marketing Research & Analytics – Centennial College</li>
          <li>MA in Development Management – Khon Kaen University</li>
          <li>BA in Sociology & Social Work – University of Asmara</li>
        </ul>
      </section>

      <section id="experience">
        <h2>Experience</h2>
        <p>Experience content here...</p>
      </section>

      <section id="certs">
        <h2>Certifications</h2>
        <ul>
          <li>Data Science Foundations – IBM</li>
          <li>Excel for Data Analysis – Microsoft</li>
          <li>Requirements Elicitation and Analysis – IIBA</li>
          <li>Technology for Teaching – Centennial College</li>
        </ul>
      </section>

      <section id="projects">
        <h2>Projects</h2>
        <p>Highlight 3–5 major consulting or academic projects with tools used and outcomes achieved.</p>
      </section>

      <section id="publications">
        <h2>Publications</h2>
        <ul>
          <li>“Factors Affecting the Attitudes of Members Towards Participation in Fisheries Cooperatives, Dahlak Islands”</li>
          <li>“Attitudes of Members Toward Performance of Fisheries Cooperative in Dahlak Sub-Zone”</li>
        </ul>
      </section>

      <section id="talks">
        <h2>Guest Lectures & Talks</h2>
        <p>Summary of speaking engagements, academic presentations, and invited lectures.</p>
      </section>

      <section id="testimonials">
        <h2>Testimonials</h2>
        <blockquote>“Daniel’s insights into data strategy transformed how our department approaches reporting.” — Academic Dean</blockquote>
      </section>

      <section id="gallery">
        <h2>Portfolio Gallery</h2>
        <p>Visual samples of BI dashboards, teaching tools, or data visualizations.</p>
      </section>

      <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:asdansi9@yahoo.com">asdansi9@yahoo.com</a><br>
           LinkedIn: <a href="https://www.linkedin.com/in/daniel-s-demoz">linkedin.com/in/daniel-s-demoz</a></p>
      </section>

      <footer>
        &copy; 2025 Daniel S. Demoz. All rights reserved. | Last updated: May 2025
      </footer>
    </div>
  </main>
</body>
</html>
