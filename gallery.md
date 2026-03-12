
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
    <p><em>Inspiration through humility, knowledge, and dedication to learning.</em></p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/lincoln.jpeg' | relative_url }}" alt="Abraham Lincoln">
    <p><em>Leadership rooted in integrity, resilience, and moral courage.</em></p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/ammamma.jpeg' | relative_url }}" alt="Ammamma">
    <p><em>A reminder that strength, sacrifice, and wisdom often begin at home.</em></p>
  </div>
  <div class="gallery-item">
    <img src="{{ '/images/mindful.jpeg' | relative_url }}" alt="Mindfulness Reminder">
    <p><em>Stay present. Focus on what can be controlled. Think clearly.</em></p>
  </div>
</div>
