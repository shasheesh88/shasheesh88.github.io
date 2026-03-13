---
layout: single
title: "Gallery"
permalink: /gallery/
author_profile: false
---
<script>
if(sessionStorage.getItem("auth") !== "yes"){
   window.location.href = "/password.html";
}
</script>

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="{{ '/images/kalam_sir.jpeg' | relative_url }}" alt="A.P.J. Abdul Kalam">
    <p>Inspiration through humility, knowledge, and dedication to learning.</p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/lincoln.jpeg' | relative_url }}" alt="Abraham Lincoln">
    <p>Leadership rooted in integrity, resilience, and moral courage.</p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/ammamma.jpeg' | relative_url }}" alt="Ammamma">
    <p>A reminder that strength, sacrifice, and wisdom often begin at home.</p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/mindful.jpeg' | relative_url }}" alt="Mindfulness Reminder">
    <p>Stay present. Focus on what can be controlled. Think clearly.</p>
  </div>
</div>
