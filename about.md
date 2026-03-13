---
layout: single
title: "About Me"
permalink: /about/
author_profile: false
---
<script>
if(sessionStorage.getItem("auth") !== "yes"){
   window.location.href = "/password.html";
}
</script>
<style>
/* Layout only — typography comes from main.scss */

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 48px;
  align-items: start;
  margin-bottom: 40px;
}

.section-label {
  font-family: var(--display);
  font-style: italic;
  font-size: 1.45rem;
  font-weight: 400;
  color: var(--ink);
  border-bottom: 1px solid var(--border);
  padding-bottom: 6px;
  margin: 0 0 20px 0;
}

.interests-block {
  background: var(--paper-alt) !important;
  border: 1px solid var(--border) !important;
  padding: 28px !important;
}
.interests-block ul {
  list-style: none !important;
  padding: 0 !important;
  margin: 0 !important;
}
.interests-block ul li {
  padding: 7px 0 !important;
  border-bottom: 1px solid var(--border) !important;
  font-style: italic !important;
  margin: 0 !important;
}
.interests-block ul li:last-child {
  border-bottom: none !important;
}

.about-image img {
  width: 100%;
  display: block;
  filter: sepia(12%) contrast(0.95);
}

.vision-block {
  border-left: 2px solid var(--rust);
  background: var(--rust-faint);
  padding: 14px 22px;
  margin: 16px 0;
  font-style: italic;
  color: var(--ink-mid);
  font-size: 1rem;
}
.vision-block p {
  margin: 0 0 10px 0 !important;
}
.vision-block p:last-child {
  margin-bottom: 0 !important;
}

.about-divider {
  border: none;
  border-top: 1px solid var(--border);
  margin: 36px 0;
}

@media (max-width: 800px) {
  .about-grid { grid-template-columns: 1fr; }
}
</style>

<hr class="about-divider" style="margin-top:0;">

<div class="about-grid">
  <div>
    <p class="section-label">Introduction</p>
    <p>Hello. I am Shasheesh.</p>
    <p>I was born and brought up in Telangana. My father is a teacher, and my mother, who was earlier a teacher, later became a full-time homemaker. I have one elder brother.</p>
    <p>I always wanted to be the best in the things I am interested in, whether it is data science, badminton, or cricket. I always want to be unique and exceptional and stand away from the crowd.</p>
    <p>I am deeply connected with my family, especially my father Venkanna and my grandmother Bharataamma. They have had a strong impact on my personality and who I am today. They are very important to me.</p>
    <p>I like fishing a lot. I like being in nature and staying close to it. I enjoy being surrounded by animals like buffaloes, cows, dogs, and others.</p>
  </div>
  <div>
    <p class="section-label">Interests</p>
    <div class="interests-block">
      <ul>
        <li>Fishing</li>
        <li>Technology</li>
        <li>Spending time in nature and around animals</li>
        <li>Badminton</li>
        <li>Sarcastic conversations with friends</li>
      </ul>
    </div>
    <div class="about-image" style="margin-top:20px;">
      <img src="/images/A_calm_countryside_river_at_sunset__A_person_sits_peacefully_on_the_grassy_bank__fishing_with_a_simp.png" alt="Fishing at sunset" />
    </div>
  </div>
</div>

<hr class="about-divider">

<div class="about-grid">
  <div>
    <p class="section-label">Long-Term Vision</p>
    <div class="vision-block">
      <p>Having my own space where I can fish and spend days surrounded by flora and fauna.</p>
      <p>Living a peaceful and calm life.</p>
      <p>Spending quality time with my family.</p>
    </div>
  </div>
  <div>
    <!-- intentionally open — add a photo or quote here later -->
  </div>
</div>
