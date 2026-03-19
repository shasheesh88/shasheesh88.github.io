---
layout: single
title: "Career"
permalink: /career/
author_profile: false
---
<script>
if(sessionStorage.getItem("auth") !== "yes"){
   window.location.href = "/password.html";
}
</script>
<style>
.career-section-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 48px;
  align-items: start;
  margin: 24px 0 40px;
}

.col-label {
  font-family: var(--mono);
  font-size: 0.65rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--ink-light);
  margin-bottom: 14px;
  display: block;
}

.project-entry {
  border-left: 2px solid var(--border);
  padding-left: 18px;
  margin-bottom: 32px;
  transition: border-left-color 0.2s;
}
.project-entry:hover { border-left-color: var(--rust); }

.project-title {
  font-family: var(--display);
  font-style: italic;
  font-size: 1.15rem;
  font-weight: 400;
  color: var(--ink);
  margin: 0 0 4px 0;
}

.project-meta {
  font-family: var(--mono);
  font-size: 0.68rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--rust);
  margin-bottom: 12px;
  display: block;
}

.project-entry ul {
  list-style: none !important;
  padding: 0 !important;
  margin: 0 0 10px !important;
}
.project-entry ul li {
  padding: 5px 0 !important;
  border-bottom: 1px solid var(--paper-alt) !important;
  font-size: 0.92rem !important;
  margin: 0 !important;
}
.project-entry ul li:last-child { border-bottom: none !important; }

.insight-label {
  font-family: var(--mono);
  font-size: 0.65rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: #a8a29e;
  margin-top: 10px;
  display: block;
}

.placeholder {
  font-family: var(--mono);
  font-size: 0.7rem;
  color: #c8c1b8;
  font-style: italic;
}

.ruled-list {
  list-style: none !important;
  padding: 0 !important;
  margin: 0 !important;
}
.ruled-list li {
  padding: 6px 0 !important;
  border-bottom: 1px solid var(--paper-alt) !important;
  font-size: 0.95rem !important;
  margin: 0 !important;
}
.ruled-list li:last-child { border-bottom: none !important; }

.closing-note {
  font-style: italic;
  color: var(--ink-light);
  font-size: 0.93rem;
  border-top: 1px solid var(--border);
  padding-top: 24px;
}

/* ── CAREER INTRO ── */
.career-intro {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 40px;
  align-items: start;
  margin-bottom: 32px;
}

/* ── CONTACT + PROFILE IMAGES ── */
.career-contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
  min-width: 220px;
}

.career-contact h3 {
  display: none;
}

.career-contact p {
  align-self: flex-start;
  margin: 0;
  font-size: 0.78rem;
  color: var(--ink-light);
  line-height: 1.8;
}

.profile-images {
  display: flex;
  flex-direction: row;
  gap: 10px;
  width: 100%;
  margin-bottom: 4px;
}

.profile-images img {
  width: 100px;
  height: 100px;
  border-radius: 8px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  object-fit: cover;
  object-position: center top;
  display: block;
}

/* ── RESEARCH IMAGES ── */
.research-images {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
  margin: 16px 0 10px;
}

.research-img-card {
  border: 1px solid var(--border);
  border-radius: 8px;
  overflow: hidden;
  background: var(--paper-alt);
}

.research-img-card img {
  width: 100%;
  display: block;
  object-fit: contain;
  max-height: 200px;
  background: #fff;
  padding: 8px;
}

.research-img-caption {
  font-family: var(--mono);
  font-size: 0.65rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: var(--ink-light);
  padding: 8px 10px;
  border-top: 1px solid var(--border);
  text-align: center;
}

@media (max-width: 900px) {
  .career-section-grid { grid-template-columns: 1fr; }
  .career-intro        { grid-template-columns: 1fr; }
  .research-images     { grid-template-columns: 1fr; }
  .profile-images img  { width: 90px; height: 90px; }
}
</style>

<div class="career-intro">
  <div class="career-summary">

## Professional Direction

With a background in maths and analytics, and an interest in solving problems with data, I use data science, AI/ML, and cloud platforms to design and build scalable and ethical intelligent systems that create sustainable and meaningful impact.

I am drawn to problems that require both structured reasoning and creative thinking. What motivates me most is building systems that not only work technically, but also make real-world processes clearer, faster, and more meaningful.

  </div>
  <div class="career-contact">

<div class="profile-images">
  <img src="{{ '/images/shashi_passport_size.png' | relative_url }}" alt="Shashi — Passport Photo">
  <img src="{{ '/images/shashi_screenshot_2.png' | relative_url }}" alt="Shashi">
</div>

<p>
  eshwaranchittaluri123@gmail.com<br>
  shasheesh88@yahoo.com<br>
  +91 91829 38074
</p>

  </div>
</div>

---

## Education

<div class="education-grid">
  <div class="education-item">
    <strong>National Institute of Technology Karnataka (NITK), Surathkal</strong><br>
    MBA — Analytics & AI<br>
    Specialization: ML & AI Systems<br>
    Grade: ≈ 8.5<br>
    2022–2024
  </div>
  <div class="education-item">
    <strong>Indian Institute of Science Education and Research (IISER), Trivandrum</strong><br>
    BS–MS — Computational Materials Science<br>
    Focus: Molecular Modeling & Quantum Simulations<br>
    Overall Grade: ≈ 7.0<br>
    Masters Grade: 8.10<br>
    2017–2022
  </div>
</div>

---

## Skills

<div class="skills-grid">
  <div>
    <strong>Data Science Tools</strong><br>
    Pandas, NumPy, SciPy, TensorFlow, PyTorch, XGBoost, Keras, Scikit-Learn, Transformers, SpaCy, Hugging Face, Apache Airflow, MLflow, Scrapy, Requests, Missingno, PuLP, DateTime, Regex, Vertex AI ADK
  </div>
  <div>
    <strong>Machine Learning</strong><br>
    Machine Learning, Deep Learning, Supervised Learning, Optimization, Unsupervised Learning, NLP, Computer Vision, Generative AI, LLMs, Agent Frameworks, MLOps, Hyperparameter Tuning, RAG, RLHF
  </div>
  <div>
    <strong>Languages & Tools</strong><br>
    Python, SQL, Bash, gcloud CLI, MySQL, Windows, WSL
  </div>
  <div>
    <strong>Databases & Cloud</strong><br>
    PostgreSQL, MySQL, Data Warehousing, BigQuery, Cloud Run, Artifact Registry, Cloud Storage, Logging & Monitoring, Serverless Deployment, IAM Security, ETL/ELT Workflows, Data Interpretation, Cloud-agnostic architecture (GCP → AWS/Azure transferable)
  </div>
  <div>
    <strong>Visualization</strong><br>
    Tableau, Matplotlib, Seaborn
  </div>
  <div>
    <strong>Other Skills</strong><br>
    Alteryx Designer, HPC Clusters, MS Office Suite, Statistical Analysis, Problem Solving, Analytical Thinking, Data Storytelling
  </div>
  <div>
    <strong>Soft Skills</strong><br>
    Communication, Insight Synthesis, Collaboration, Presentation Skills
  </div>
</div>

---

## Work Experience & Projects

<div class="career-section-grid">
  <div>

    <div class="project-entry">
      <p class="project-title">Generative AI-Based Telematics Insights Agent</p>
      <span class="project-meta">myTVS (TVS & Sons) — 2025–Present</span>
      <ul>
        <li>Built an agent using Google's Agent Development Kit (Vertex AI ADK) enabling users to interact with telematics databases using natural language instead of SQL.</li>
        <li>Deployed on Colab Enterprise runtime (Nvidia Tesla L4 GPU, 15GB RAM, 120GB SSD, n1-standard-4).</li>
        <li>Integrated MySQL cloud database with validation layers (parameterization + fallback) for efficient and graceful query handling.</li>
      </ul>
      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[Add later — what this project taught you technically or mentally.]</p>
    </div>

    <div class="project-entry">
      <p class="project-title">Car Inspection Analysis & Rating Code Mapping</p>
      <span class="project-meta">myTVS — 2024</span>
      <ul>
        <li>Developed a human-centric system mapping free-text technician responses from 14 inspection components to predefined rating codes.</li>
        <li>Cleaned input data and dynamically created new rating codes when patterns appeared.</li>
        <li>Integrated Gemini models on GCP to interpret response nuance and extended system to 62 major inspection components, reducing reliance on generic "Other" entries.</li>
      </ul>
      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[Add reflection later.]</p>
    </div>

    <div class="project-entry">
      <p class="project-title">Vehicle Inspection Analysis & Custom Message Generation</p>
      <span class="project-meta">myTVS — 2025</span>
      <ul>
        <li>Designed a system analyzing vehicle inspection OLTP data.</li>
        <li>Generated personalized owner reports.</li>
        <li>Automated message generation using fine-tuned Gemini-2.5-Flash on Vertex AI.</li>
      </ul>
      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[Add reflection later.]</p>
    </div>

  </div>
  <div>

    <div class="project-entry">
      <p class="project-title">Used Car Price Prediction System</p>
      <span class="project-meta">myTVS — 2025</span>
      <ul>
        <li>Built a CatBoost model for price estimation.</li>
        <li>Implemented preprocessing and fuzzy variant normalization using RapidFuzz.</li>
        <li>Deployed a Flask REST API via Docker on Google Cloud Run.</li>
        <li>Added feedback loop for model refinement.</li>
      </ul>
      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[Add reflection later.]</p>
    </div>

    <div class="project-entry">
      <p class="project-title">Computational Research — Battery Interfaces</p>
      <span class="project-meta">2021–2022</span>
      <p>Studied effects of Ni concentration on formation mechanisms and structure of cathode-electrolyte interfaces in LiNixCoyMn1−x−yO2 materials.</p>
      <p>Applied Monte Carlo simulations and density functional calculations for mechanism analysis.</p>

      <div class="research-images">
        <div class="research-img-card">
          <img src="{{ '/images/quantum_mechanis.png' | relative_url }}" alt="Schrödinger Wave Equation">
          <div class="research-img-caption">Schrödinger Wave Equation — Quantum Mechanical Basis</div>
        </div>
        <div class="research-img-card">
          <img src="{{ '/images/metropolis.png' | relative_url }}" alt="Metropolis Algorithm — Monte Carlo">
          <div class="research-img-caption">Metropolis Criterion — MC Accept / Reject</div>
        </div>
      </div>

      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[What research taught you about thinking or problem solving.]</p>
    </div>

    <div class="project-entry">
      <p class="project-title">Credit Approval Ensemble Model</p>
      <span class="project-meta">Apr 2023 – Jun 2023</span>
      <ul>
        <li>Built ML models for credit prediction.</li>
        <li>Designed ensemble combining Naive Bayes, SVM, and KNN.</li>
        <li>Tuned XGBoost classifier and optimized ANN.</li>
        <li>Used scikit-learn, NumPy, and Pandas for preprocessing and modeling.</li>
      </ul>
      <span class="insight-label">Insight gained</span>
      <p class="placeholder">[Add reflection later.]</p>
    </div>

  </div>
</div>

---

<div class="career-section-grid">
  <div>
    <span class="col-label">Achievements</span>
    <ul class="ruled-list">
      <li>Qualified JEE-Advanced</li>
      <li>Certificate of Extracurricular Excellence in Badminton from Dean of Students' Welfare</li>
    </ul>
  </div>
  <div>
    <span class="col-label">Current Focus</span>
    <p style="font-size:0.9rem; color:var(--ink-light); font-style:italic; margin-bottom:10px;">Right now I am focused on:</p>
    <ul class="ruled-list">
      <li>Strengthening real-world AI system deployment skills</li>
      <li>Improving model interpretability and reliability</li>
      <li>Learning scalable architecture design</li>
      <li>Deepening mathematical intuition behind ML systems</li>
    </ul>
  </div>
</div>

---

<p style="font-size:0.97rem; color:var(--ink); max-width:60ch;">I aim to work on systems that combine strong math foundations, responsible AI practices, and practical deployment — systems that are not only intelligent, but useful, trustworthy, and scalable.</p>

<p class="closing-note">This page is not a static résumé. It is a record of how my skills, thinking, and direction evolve over time.</p>
