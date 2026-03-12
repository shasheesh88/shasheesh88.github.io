---
layout: single
title: "Career"
permalink: /career/
author_profile: false
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,500;1,400&family=DM+Mono:wght@300;400&family=Crimson+Pro:ital,wght@0,300;0,400;1,300&display=swap');

/* Project h3 titles — override the mono style from main.scss for this page */
.page__content h3 {
  font-family: 'Crimson Pro', Georgia, serif !important;
  font-size: 1.2rem !important;
  font-style: italic !important;
  font-weight: 400 !important;
  letter-spacing: 0.01em !important;
  text-transform: none !important;
  color: #1c1917 !important;
  margin-top: 2rem !important;
  margin-bottom: 0.3rem !important;
}

/* "myTVS — 2025" bold company/date line under each h3 */
.page__content h3 + p {
  font-family: 'DM Mono', monospace !important;
  font-size: 0.7rem !important;
  letter-spacing: 0.15em !important;
  text-transform: uppercase !important;
  color: #9a3412 !important;
  font-style: normal !important;
  font-weight: 400 !important;
  margin-bottom: 12px !important;
  display: block !important;
  justify-content: unset !important;
}

/* "Insight gained:" label */
.page__content p strong,
.page__inner-wrap p strong {
  font-family: 'DM Mono', monospace;
  font-size: 0.68rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: #78716c;
  font-weight: 400;
}

/* Bullet lists in projects */
.page__content ul li {
  padding: 4px 0;
  border-bottom: 1px solid #ede8df;
  list-style: none;
  padding-left: 0;
  font-size: 0.95rem;
  color: #1c1917;
}

.page__content ul li:last-child {
  border-bottom: none;
}

.page__content ul {
  padding-left: 0;
}

/* Achievements list — keep as normal bullets */
.achievements-list {
  list-style: disc;
  padding-left: 20px;
}

.achievements-list li {
  border-bottom: none !important;
  list-style: disc !important;
  padding-left: 0 !important;
}

/* Personal note placeholder text */
.placeholder-note {
  font-family: 'DM Mono', monospace;
  font-size: 0.72rem;
  color: #a8a29e;
  letter-spacing: 0.06em;
  font-style: italic;
}

/* Closing reflection */
.closing-note {
  font-style: italic;
  color: #78716c;
  font-size: 0.93rem;
  border-top: 1px solid #d6cfc4;
  padding-top: 24px;
  margin-top: 8px;
}
</style>

<div class="career-intro">

  <div class="career-summary">
    <h2>Professional Direction</h2>
    <p>
      With a background in maths and analytics, and an interest in solving problems with data, I use data science, AI/ML, and cloud platforms to design and build scalable and ethical intelligent systems that create sustainable and meaningful impact.
    </p>
  </div>

  <div class="career-contact">
    <h3>Contact</h3>
    <p>
      eshwaranchittaluri123@gmail.com<br>
      shasheesh88@yahoo.com
    </p>
  </div>

</div>

<hr>

## Personal Note  *(optional — edit later)*

I am drawn to problems that require both structured reasoning and creative thinking.  
What motivates me most is building systems that not only work technically, but also make real-world processes clearer, faster, and more meaningful.

<p class="placeholder-note">[Write 2–4 sentences here later about why you chose this field.]</p>

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


### Generative AI-Based Telematics Insights Agent
**myTVS (TVS & Sons) — 2025–Present**

- Built an agent using Google's Agent Development Kit (Vertex AI ADK) enabling users to interact with telematics databases using natural language instead of SQL.
- Deployed on Colab Enterprise runtime (Nvidia Tesla L4 GPU, 15GB RAM, 120GB SSD, n1-standard-4).
- Integrated MySQL cloud database with validation layers (parameterization + fallback) for efficient and graceful query handling.

**Insight gained:**  
<span class="placeholder-note">[Add later — what this project taught you technically or mentally.]</span>

---

### Car Inspection Analysis & Rating Code Mapping
**myTVS — 2024**

- Developed a human-centric system mapping free-text technician responses from 14 inspection components to predefined rating codes.
- Cleaned input data and dynamically created new rating codes when patterns appeared.
- Integrated Gemini models on GCP to interpret response nuance and extended system to 62 major inspection components, reducing reliance on generic "Other" entries.

**Insight gained:**  
<span class="placeholder-note">[Add reflection later.]</span>

---

### Vehicle Inspection Analysis & Custom Message Generation
**myTVS — 2025**

- Designed a system analyzing vehicle inspection OLTP data.
- Generated personalized owner reports.
- Automated message generation using fine-tuned Gemini-2.5-Flash on Vertex AI.

**Insight gained:**  
<span class="placeholder-note">[Add reflection later.]</span>

---

### Used Car Price Prediction System
**myTVS — 2025**

- Built a CatBoost model for price estimation.
- Implemented preprocessing and fuzzy variant normalization using RapidFuzz.
- Deployed a Flask REST API via Docker on Google Cloud Run.
- Added feedback loop for model refinement.

**Insight gained:**  
<span class="placeholder-note">[Add reflection later.]</span>

---

### Computational Research — Battery Interfaces
**2021–2022**

Studied effects of Ni concentration on formation mechanisms and structure of cathode-electrolyte interfaces in LiNixCoyMn1−x−yO2 materials.

Applied Monte Carlo simulations and density functional calculations for mechanism analysis.

**Insight gained:**  
<span class="placeholder-note">[What research taught you about thinking or problem solving.]</span>

---

### Credit Approval Ensemble Model
**Apr 2023 – Jun 2023**

- Built ML models for credit prediction.
- Designed ensemble combining Naive Bayes, SVM, and KNN.
- Tuned XGBoost classifier and optimized ANN.
- Used scikit-learn, NumPy, and Pandas for preprocessing and modeling.

**Insight gained:**  
<span class="placeholder-note">[Add reflection later.]</span>

---

## Achievements

<ul class="achievements-list">
  <li>Qualified JEE-Advanced</li>
  <li>Certificate of Extracurricular Excellence in Badminton from Dean of Students' Welfare</li>
</ul>

---

## Current Focus  *(optional but powerful section)*

Right now I am focused on:

- strengthening real-world AI system deployment skills  
- improving model interpretability and reliability  
- learning scalable architecture design  
- deepening mathematical intuition behind ML systems  

---

## Long-Term Direction  *(edit anytime)*

I aim to work on systems that combine strong math foundations, responsible AI practices, and practical deployment — systems that are not only intelligent, but useful, trustworthy, and scalable.

---

## Closing Reflection

<p class="closing-note">This page is not a static résumé.<br>It is a record of how my skills, thinking, and direction evolve over time.</p>
