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

<style>
/* ── PHOTO GRID ── */
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 24px;
  padding: 20px 0;
}

.gallery-item {
  background: #1a1a2e;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 15px rgba(0,0,0,0.3);
  transition: transform 0.2s ease;
}

.gallery-item:hover {
  transform: translateY(-4px);
}

.gallery-item img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}

.gallery-item p {
  padding: 12px 14px;
  margin: 0;
  font-size: 0.88rem;
  color: #ccc;
  line-height: 1.5;
}

/* ── VIDEO SECTION ── */
.video-section {
  margin-top: 48px;
}

.video-section h2 {
  font-size: 1.6rem;
  margin-bottom: 24px;
  color: #eee;
  border-left: 4px solid #e07b39;
  padding-left: 12px;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
  gap: 28px;
}

.video-card {
  background: #12121f;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0,0,0,0.4);
}

.video-card video {
  width: 100%;
  display: block;
  background: #000;
  max-height: 220px;
  object-fit: cover;
}

.video-info {
  padding: 12px 14px 6px;
}

.video-info h3 {
  margin: 0 0 4px;
  font-size: 1rem;
  color: #f0f0f0;
}

.video-info p {
  margin: 0 0 10px;
  font-size: 0.82rem;
  color: #aaa;
  line-height: 1.4;
}

/* ── BADGES ── */
.badge {
  display: inline-block;
  font-size: 0.7rem;
  padding: 2px 8px;
  border-radius: 20px;
  margin-bottom: 6px;
  font-weight: 600;
  color: #fff;
}
.badge-my-video   { background: #2e4ccc; }
.badge-animation  { background: #7c3aed; }
.badge-documentary { background: #0f7a55; }
.badge-film       { background: #b45309; }

/* ── VIDEO CONTROLS ── */
.video-controls {
  display: flex;
  gap: 8px;
  padding: 0 14px 14px;
}

.btn-play-pause {
  padding: 7px 20px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.82rem;
  font-weight: 600;
  background: #2ecc71;
  color: #fff;
  min-width: 90px;
  transition: background 0.2s, transform 0.1s;
}

.btn-play-pause.playing {
  background: #f39c12;
}

.btn-play-pause:hover  { filter: brightness(1.1); }
.btn-play-pause:active { transform: scale(0.96);  }

.btn-stop {
  padding: 7px 16px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.82rem;
  font-weight: 600;
  background: #e74c3c;
  color: #fff;
  transition: background 0.2s, transform 0.1s;
}

.btn-stop:hover  { background: #c0392b; }
.btn-stop:active { transform: scale(0.96); }

.btn-stop:disabled {
  background: #555;
  cursor: not-allowed;
  opacity: 0.5;
}

/* ── COPYRIGHT ── */
.copyright-notice {
  margin: 0 14px 14px;
  font-size: 0.72rem;
  color: #666;
  border-top: 1px solid #2a2a3e;
  padding-top: 8px;
  line-height: 1.5;
}

.copyright-notice .label {
  color: #e07b39;
  font-weight: 700;
}
</style>

<!-- ════════════════════════════════
     PHOTO GALLERY
     ════════════════════════════════ -->
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
    <div class="gallery-item">
    <img src="{{ '/images/shashi_independence_day.jpg' | relative_url }}" alt="Independence Day">
    <p>Standing proud on Independence Day — a moment of patriotism, unity, and remembrance of those who gave us freedom.</p>
  </div>

  <div class="gallery-item">
    <img src="{{ '/images/volleyball_team_2022.jpg' | relative_url }}" alt="Volleyball Team 2022">
    <p>On the court with the crew — friendships built through sweat, teamwork, and the love of the game. 🏐</p>
  </div>

</div>

<!-- ════════════════════════════════
     VIDEO GALLERY
     ════════════════════════════════ -->
<div class="video-section">
  <h2>📽️ Videos</h2>
  <div class="video-grid">

    <!-- 1. Childhood Animation -->
    <div class="video-card">
      <video id="vid-childhood" preload="metadata">
        <source src="{{ '/images/childhood.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <div class="video-info">
        <span class="badge badge-animation">🎨 Animation</span>
        <h3>🌾 Childhood — An Andhra Story</h3>
        <p>A nostalgic animated journey through the little joys of growing up in Andhra Pradesh —
           summer mangoes, clay games, school bells, and the warmth of a simpler time.</p>
      </div>
      <div class="video-controls">
        <button class="btn-play-pause" id="btn-childhood"
                onclick="togglePlay('vid-childhood','btn-childhood')">▶ Play</button>
        <button class="btn-stop" id="stop-childhood"
                onclick="stopVid('vid-childhood','btn-childhood')" disabled>⏹ Stop</button>
      </div>
      <div class="copyright-notice">
        <span class="label">© Copyright:</span> Original animated content. All rights reserved.
        Unauthorised reproduction or distribution is prohibited.
      </div>
    </div>

    <!-- 2. Honey Documentary -->
    <div class="video-card">
      <video id="vid-honey" preload="metadata">
        <source src="{{ '/images/honey.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <div class="video-info">
        <span class="badge badge-documentary">🎥 Documentary</span>
        <h3>🍯 Honey — Nature's Gold</h3>
        <p>Watch bees craft one of nature's most incredible creations — a glimpse into
           the fascinating world of honey-making.</p>
      </div>
      <div class="video-controls">
        <button class="btn-play-pause" id="btn-honey"
                onclick="togglePlay('vid-honey','btn-honey')">▶ Play</button>
        <button class="btn-stop" id="stop-honey"
                onclick="stopVid('vid-honey','btn-honey')" disabled>⏹ Stop</button>
      </div>
      <div class="copyright-notice">
        <span class="label">⚠ Copyright Notice:</span> Documentary excerpt. All rights belong to
        the respective production house and distributors. Shared for personal,
        non-commercial viewing only.
      </div>
    </div>

    <!-- 3. Otters Documentary -->
    <div class="video-card">
      <video id="vid-otters" preload="metadata">
        <source src="{{ '/images/otters.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <div class="video-info">
        <span class="badge badge-documentary">🎥 Documentary</span>
        <h3>🦦 Otters — Life by the Water</h3>
        <p>Otters at play and at peace — a delightful look at one of nature's most
           charming creatures living their best lives.</p>
      </div>
      <div class="video-controls">
        <button class="btn-play-pause" id="btn-otters"
                onclick="togglePlay('vid-otters','btn-otters')">▶ Play</button>
        <button class="btn-stop" id="stop-otters"
                onclick="stopVid('vid-otters','btn-otters')" disabled>⏹ Stop</button>
      </div>
      <div class="copyright-notice">
        <span class="label">⚠ Copyright Notice:</span> Documentary excerpt. All rights belong to
        the respective production house and distributors. Shared for personal,
        non-commercial viewing only.
      </div>
    </div>

    <!-- 4. Shashi Badminton — Civil -->
    <div class="video-card">
      <video id="vid-shashi-civi" preload="metadata">
        <source src="{{ '/images/shashi_civi.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <div class="video-info">
        <span class="badge badge-my-video">🏸 My Video</span>
        <h3>Shashi on Court — Civil</h3>
        <p>Smashes, drops, and rallies — a personal badminton session captured on camera.</p>
      </div>
      <div class="video-controls">
        <button class="btn-play-pause" id="btn-shashi-civi"
                onclick="togglePlay('vid-shashi-civi','btn-shashi-civi')">▶ Play</button>
        <button class="btn-stop" id="stop-shashi-civi"
                onclick="stopVid('vid-shashi-civi','btn-shashi-civi')" disabled>⏹ Stop</button>
      </div>
      <div class="copyright-notice">
        <span class="label">© Copyright:</span> Original content created and owned by Shashi.
        All rights reserved. Unauthorised reproduction or distribution is prohibited.
      </div>
    </div>

    <!-- 5. Shashi Badminton — Bat -->
    <div class="video-card">
      <video id="vid-shashi-bat" preload="metadata">
        <source src="{{ '/images/shashi_bat.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <div class="video-info">
        <span class="badge badge-my-video">🏸 My Video</span>
        <h3>Shashi on Court — Bat Cam</h3>
        <p>Another angle, more action — Shashi brings the energy to every rally
           on the badminton court.</p>
      </div>
      <div class="video-controls">
        <button class="btn-play-pause" id="btn-shashi-bat"
                onclick="togglePlay('vid-shashi-bat','btn-shashi-bat')">▶ Play</button>
        <button class="btn-stop" id="stop-shashi-bat"
                onclick="stopVid('vid-shashi-bat','btn-shashi-bat')" disabled>⏹ Stop</button>
      </div>
      <div class="copyright-notice">
        <span class="label">© Copyright:</span> Original content created and owned by Shashi.
        All rights reserved. Unauthorised reproduction or distribution is prohibited.
      </div>
    </div>

  </div>
</div>

<script>
function togglePlay(vidId, btnId) {
  const v       = document.getElementById(vidId);
  const btn     = document.getElementById(btnId);
  const stopBtn = document.getElementById(btnId.replace('btn-', 'stop-'));

  if (v.paused) {
    // Pause every other video first
    document.querySelectorAll('video').forEach(other => {
      if (other.id !== vidId && !other.paused) {
        other.pause();
        const otherBtnId  = 'btn-'  + other.id.replace('vid-', '');
        const otherStopId = 'stop-' + other.id.replace('vid-', '');
        const otherBtn    = document.getElementById(otherBtnId);
        const otherStop   = document.getElementById(otherStopId);
        if (otherBtn)  { otherBtn.textContent = '▶ Play'; otherBtn.classList.remove('playing'); }
        if (otherStop) { otherStop.disabled = true; }
      }
    });

    v.play();
    btn.textContent = '⏸ Pause';
    btn.classList.add('playing');
    if (stopBtn) stopBtn.disabled = false;

  } else {
    v.pause();
    btn.textContent = '▶ Play';
    btn.classList.remove('playing');
  }
}

function stopVid(vidId, btnId) {
  const v       = document.getElementById(vidId);
  const btn     = document.getElementById(btnId);
  const stopBtn = document.getElementById(btnId.replace('btn-', 'stop-'));

  v.pause();
  v.currentTime = 0;
  btn.textContent = '▶ Play';
  btn.classList.remove('playing');
  if (stopBtn) stopBtn.disabled = true;
}

// Auto-reset buttons when a video ends naturally
document.addEventListener('DOMContentLoaded', () => {
  document.querySelectorAll('video').forEach(v => {
    v.addEventListener('ended', () => {
      const btnId   = 'btn-'  + v.id.replace('vid-', '');
      const stopId  = 'stop-' + v.id.replace('vid-', '');
      const btn     = document.getElementById(btnId);
      const stopBtn = document.getElementById(stopId);
      if (btn)     { btn.textContent = '▶ Play'; btn.classList.remove('playing'); }
      if (stopBtn) stopBtn.disabled = true;
    });
  });
});
</script>
