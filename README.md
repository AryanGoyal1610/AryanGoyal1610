<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>Aryan Goyal — Portfolio</title>
  <meta name="description" content="Aryan Goyal | B.Tech CSE @ VIT Vellore — AI/ML, Data Analytics, projects, certifications, achievements."/>
  <meta name="theme-color" content="#0ea5e9"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#0b0e14;--panel:#0f172a;--line:#1e2a3f;--text:#e7edf4;--muted:#a8b3c7;--brand:#22d3ee;--brand2:#0ea5e9;}
    *{box-sizing:border-box} html,body{margin:0;background:linear-gradient(180deg,var(--bg),#0c1220);color:var(--text);font-family:Inter,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif}
    a{color:var(--brand);text-decoration:none} a:hover{text-decoration:underline}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    header{position:sticky;top:0;background:rgba(11,14,20,.6);backdrop-filter:blur(16px);border-bottom:1px solid var(--line);z-index:10}
    nav{display:flex;align-items:center;justify-content:space-between;gap:14px}
    .navlinks a{margin-left:10px;padding:8px 12px;border-radius:12px;border:1px solid var(--line)}
    .brand{display:flex;align-items:center;gap:12px}
    .avatar{width:44px;height:44px;border-radius:12px;display:grid;place-items:center;background:linear-gradient(135deg,var(--brand),var(--brand2));font-weight:800;color:#0b0e14}
    h1{font-size:38px;margin:6px 0 10px;letter-spacing:-.02em} h2{font-size:24px;margin:0 0 10px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,0));border:1px solid var(--line);border-radius:20px;padding:20px}
    .grid{display:grid;grid-template-columns:1.2fr .8fr;gap:24px} @media(max-width:900px){.grid{grid-template-columns:1fr}}
    .pill{display:inline-flex;align-items:center;gap:8px;padding:6px 10px;border-radius:999px;background:#0e192f;border:1px solid var(--line);margin:6px 6px 0 0;font-size:13px;color:#bbd1ee}
    .list{display:flex;flex-wrap:wrap;gap:10px}
    .section{margin:20px 0 34px}
    .item{padding:14px 0;border-bottom:1px dashed #1c2740} .item:last-child{border-bottom:none}
    .badge{display:inline-flex;align-items:center;gap:6px;padding:6px 10px;border:1px solid var(--line);background:#0b1628;border-radius:999px;font-size:12px;color:#cfe6ff}
    .btn{display:inline-flex;align-items:center;gap:10px;border:1px solid var(--line);background:#0d1626;padding:10px 14px;border-radius:12px;color:var(--text)}
    .btn:hover{transform:translateY(-1px);transition:150ms;box-shadow:0 8px 22px rgba(14,165,233,.18)}
    .stats{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:10px}
    .stat{background:#0b1628;border:1px solid var(--line);border-radius:16px;padding:14px;text-align:center}
    .stat b{font-size:22px;display:block}
    .tag{display:inline-block;padding:6px 10px;border-radius:999px;background:#0e192f;border:1px solid var(--line);color:#bbd1ee;margin:6px 8px 0 0}
    footer{color:#8ea5c4}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand">
          <div class="avatar" aria-hidden="true">AG</div>
          <div>
            <div style="font-weight:800;letter-spacing:-.02em">Aryan Goyal</div>
            <div style="font-size:13px;color:#9fb3cf">B.Tech CSE @ VIT Vellore • AI/ML & Data Analytics</div>
          </div>
        </div>
        <div class="navlinks">
          <a href="#projects">Projects</a>
          <a href="#experience">Experience</a>
          <a href="#education">Education</a>
          <a href="#skills">Skills</a>
          <a href="#certs">Certifications</a>
          <a href="#achievements">Achievements</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="grid">
      <div class="card">
        <div class="pill">📍 India • Open to SDE / Data / ML roles</div>
        <h1>Hi, I’m Aryan — I build ML-powered products that ship.</h1>
        <p>Focused on deep learning, data analytics, and performant user experiences. Previously a Summer Intern at EY, where I improved internal APIs and built helpful documentation for the team.</p>
        <div class="stats" aria-label="Quick stats">
          <div class="stat"><b>9.1</b><span>CGPA</span></div>
          <div class="stat"><b>20k+</b><span>faces trained</span></div>
          <div class="stat"><b>50k+</b><span>med. images</span></div>
          <div class="stat"><b>Top 12%</b><span>Amazon HackOn</span></div>
        </div>
        <div class="list" style="margin-top:14px">
          <a class="btn" href="mailto:aryangoyal1610@gmail.com">✉️ Email</a>
          <a class="btn" href="https://www.linkedin.com/in/aryan-goyal-580021275/" target="_blank" rel="noreferrer">🔗 LinkedIn</a>
          <a class="btn" href="https://leetcode.com/u/0ScJPGF6Ht/" target="_blank" rel="noreferrer">🧩 LeetCode</a>
          <a class="btn" href="Final_Aryan_Resume.pdf" download>⬇️ Download Resume</a>
        </div>
        <div class="list" style="margin-top:12px">
          <span class="tag">Java</span><span class="tag">Python</span><span class="tag">SQL</span>
          <span class="tag">TensorFlow</span><span class="tag">NumPy</span><span class="tag">Pandas</span>
          <span class="tag">Seaborn</span><span class="tag">Matplotlib</span><span class="tag">Flutter</span><span class="tag">Firebase</span>
        </div>
      </div>
      <div class="card">
        <h2>LeetCode Snapshot</h2>
        <p style="margin-top:6px">Live stats from my profile.</p>
        <a href="https://leetcode.com/u/0ScJPGF6Ht/" target="_blank" rel="noreferrer" style="display:block">
          <img src="https://leetcard.jacoblin.cool/0ScJPGF6Ht?ext=heatmap" alt="LeetCode profile card for Aryan" style="width:100%;border-radius:12px;border:1px solid #1e2a3f"/>
        </a>
      </div>
    </section>

    <section id="projects" class="section">
      <h2>Projects</h2>
      <div class="item">
        <h3>Facial Emotion Detection AI <span class="badge">TensorFlow • Colab • NumPy • Pandas • Seaborn • Matplotlib</span></h3>
        <p>Trained on 20,000+ labeled expressions and 2,000+ keypoint-annotated samples; combined facial keypoint detection with an emotion classifier to improve accuracy; accelerated iteration on Colab GPUs with rich visualizations.</p>
      </div>
      <div class="item">
        <h3>Alzheimer’s Disease Prediction Model <span class="badge">Python • TensorFlow • scikit-learn • Pandas</span></h3>
        <p>Built a deep learning pipeline achieving <strong>99.5% accuracy</strong> for early Alzheimer’s detection; processed 50k+ medical images and records; benchmarked across public datasets with a 95% success rate; presented research at ICTIS 2025.</p>
      </div>
      <div class="item">
        <h3>Bus Tracking Application <span class="badge">Flutter • Android Studio • Firebase</span></h3>
        <p>Real-time vehicle tracking & ETA with Google Maps API and Firebase for auth + synchronization. Tuned UI performance for smooth loads.</p>
      </div>
    </section>

    <section id="experience" class="section">
      <h2>Experience</h2>
      <div class="item">
        <h3>Ernst & Young — Summer Intern, Gurugram</h3>
        <p>Contributed to the Trusted Verification project to strengthen recruitment security; refactored 15+ API identifiers improving clarity; created a searchable catalog of 20+ APIs (functions, access protocols, use-cases) to speed onboarding.</p>
        <div class="list"><span class="pill">🗓️ May 2024 – July 2024</span></div>
      </div>
    </section>

    <section id="education" class="section">
      <h2>Education</h2>
      <div class="item">
        <h3>VIT Vellore — B.Tech in Computer Science</h3>
        <p>CGPA: 9.1 • Sep 2022 – May 2026</p>
      </div>
      <div class="item">
        <h3>Saint Joseph Public School — CBSE (Class XII)</h3>
        <p>Percentage: 91%</p>
      </div>
    </section>

    <section id="skills" class="section">
      <h2>Skills & Interests</h2>
      <div class="list">
        <span class="tag">Java</span><span class="tag">Python</span><span class="tag">SQL</span>
        <span class="tag">TensorFlow</span><span class="tag">NumPy</span><span class="tag">Pandas</span>
        <span class="tag">Seaborn</span><span class="tag">Matplotlib</span>
      </div>
      <h3 style="margin-top:16px">Interests</h3>
      <div class="list"><span class="tag">Data Analytics</span><span class="tag">Machine Learning</span></div>
      <h3 style="margin-top:16px">Soft Skills</h3>
      <div class="list">
        <span class="tag">Teamwork</span><span class="tag">Leadership</span><span class="tag">Deadline Adherence</span>
        <span class="tag">Quantitative Analysis</span><span class="tag">Communication</span><span class="tag">Project Coordination</span>
      </div>
    </section>

    <section id="certs" class="section">
      <h2>Certifications</h2>
      <div class="list" style="gap:8px">
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1wb_3t-e4_BCrCADg_jD1ukJYf57r_rRU/view?usp=sharing">Oracle Certified Foundation Associate — 1Z0-006</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1wve5zZYynBSYX8G69_7YWJsbgMI2s98W/view?usp=sharing">Oracle MySQL Implementation Certified Associate — 1Z0-922</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1ig7KjthIJIJmQnpKknWz1i91NhxbCmvG/view?usp=sharing">Microsoft Azure Fundamentals — AZ-900</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1Ee1Ev2DgCt0J2Op3pyLzz9tTxpMeDjsA/view?usp=sharing">Microsoft Azure Data Fundamentals — DP-900</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1GCCZ4CXaX4KQwysSAspWROnFS6xAQvYx/view?usp=sharing">Cisco — Introduction to Data Science</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/10XUhMDsydTotApz-3jPPfNvRgv3O0YsI/view?usp=sharing">Deloitte — Data Analytics Job Simulation</a>
        <a class="btn" target="_blank" rel="noreferrer" href="https://drive.google.com/file/d/1kqp-hPb2a1QXPY60ttGW_gzAs5PpydyC/view?usp=sharing">ICTIS 2025 — Presentation Certificate</a>
      </div>
    </section>

    <section id="achievements" class="section">
      <h2>Achievements</h2>
      <ul style="margin:0;padding-left:18px;color:#a8b3c7">
        <li>Top 12% (1860/14,971 teams) — Amazon HackOn Season 5; among 53k+ participants.</li>
        <li>Secured ₹1Cr+ sponsorship for Riviera, VIT University; collaborated with brands like Pepsi.</li>
        <li>Closed ₹25L+ sponsorships for Gravitas, VIT University with Autodesk and Altium as co-sponsors.</li>
      </ul>
    </section>

    <footer style="margin:40px 0 10px">
      <hr style="border:0;border-top:1px solid #18243a;margin:24px 0"/>
      <div style="display:flex;flex-wrap:wrap;gap:14px;align-items:center;color:#8ea5c4">
        <span>Made with ♥ by Aryan</span><span>•</span>
        <a href="mailto:aryangoyal1610@gmail.com">aryangoyal1610@gmail.com</a><span>•</span>
        <a href="https://www.linkedin.com/in/aryan-goyal-580021275/" target="_blank" rel="noreferrer">LinkedIn</a><span>•</span>
        <a href="https://leetcode.com/u/0ScJPGF6Ht/" target="_blank" rel="noreferrer">LeetCode</a>
      </div>
    </footer>
  </main>

  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Person",
    "name":"Aryan Goyal",
    "email":"mailto:aryangoyal1610@gmail.com",
    "alumniOf":{"@type":"CollegeOrUniversity","name":"VIT Vellore"},
    "sameAs":[
      "https://www.linkedin.com/in/aryan-goyal-580021275/",
      "https://leetcode.com/u/0ScJPGF6Ht/"
    ],
    "knowsAbout":["Machine Learning","Data Analytics","Deep Learning","Computer Vision","Java","Python","SQL"],
    "hasCredential":["Oracle 1Z0-006","Oracle 1Z0-922","Microsoft AZ-900","Microsoft DP-900","Cisco Intro to Data Science","Deloitte Data Analytics"],
    "url":"https://aryangoyal1610.github.io"
  }
  </script>
</body>
</html>
