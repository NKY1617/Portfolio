# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Naveen Yadav Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background-color: #f5f6fa;
      color: #2f3640;
      line-height: 1.6;
    }

    header {
      background-color: #273c75;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #40739e;
      padding: 1rem 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
    }

    section {
      padding: 2rem 10%;
    }

    h2 {
      color: #192a56;
    }

    .card {
      background-color: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      margin-bottom: 1rem;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background-color: #dcdde1;
      font-size: 0.9rem;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }

    .contact-links a {
      margin-right: 1rem;
      color: #192a56;
    }
  </style>
</head>
<body>
  <header>
    <h1>Naveen Kumar Yadav</h1>
    <p>MSBA | Business Growth Strategist | Data & Analytics Leader</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a Business Analytics graduate student at Kent State University with 6+ years of experience in business growth, predictive modeling, and sales strategy. I’ve led cross-functional teams, trained sales units, and developed analytical models that delivered measurable results in logistics, marketing, and financial planning.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="card">
      <h3>🚛 Weather-Integrated Logistics Route Optimization</h3>
      <p><strong>Tools:</strong> Python, APIs, Scikit-learn, XGBoost</p>
      <ul>
        <li>Built real-time route, cost, and ETA prediction models integrating Google Maps and weather APIs</li>
        <li>Achieved R² = 0.98 on cost prediction and MAE = 2.6 mins on ETA</li>
        <li>Classified re-routing risks using LightGBM & XGBoost classifiers</li>
      </ul>
    </div>

    <div class="card">
      <h3>🏠 Housing Price Prediction Modeling</h3>
      <p><strong>Tools:</strong> R, Regression, EDA</p>
      <ul>
        <li>Developed regression models to predict housing prices and classification for construction quality</li>
        <li>Achieved AUC ~ 0.978 on classification model</li>
      </ul>
    </div>
  </section>

  <section id="experience">
    <h2>Experience</h2>

    <div class="card">
      <h3>📈 Business Growth Strategist – HDFC Bank Ltd (2024)</h3>
      <ul>
        <li>Analyzed sales workflows across 10 channels to boost productivity by 15%</li>
        <li>Achieved INR 100M MoM targets through data-backed process improvements</li>
      </ul>
    </div>

    <div class="card">
      <h3>📊 Senior Manager – BYJU’S Sales Strategy (2020–2023)</h3>
      <ul>
        <li>Managed 40-member team, led operations across 5 BUs</li>
        <li>Increased profitability by 15% and generated $3M in new revenue via Power BI dashboards</li>
      </ul>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills-grid">
      <div class="card"><strong>Data Tools:</strong> Power BI, Tableau, Excel</div>
      <div class="card"><strong>Languages:</strong> Python, R, SQL, MySQL</div>
      <div class="card"><strong>Analytics:</strong> Predictive Modeling, Feature Engineering, Data Mining</div>
      <div class="card"><strong>Business:</strong> Revenue Strategy, Sales Analytics, Market Research</div>
      <div class="card"><strong>Soft Skills:</strong> Leadership, Team Training, Project Management</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:naveeny1617@gmail.com">naveeny1617@gmail.com</a></p>
    <div class="contact-links">
      <a href="https://linkedin.com/in/1naveenyadav" target="_blank">LinkedIn</a>
      <a href="https://github.com/NKY1617" target="_blank">GitHub</a>
    </div>
  </section>

  <footer>
    © 2025 Naveen Kumar Yadav · Portfolio built with HTML & CSS
  </footer>
</body>
</html>
