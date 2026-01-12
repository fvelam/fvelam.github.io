---
layout: single
title: "Education & Experience"
permalink: /experience/
author_profile: true
---

<style>
.content-experience {
  max-width: 850px;
  margin: 0 auto;
}

/* Section titles */
.content-experience h2 {
  margin: 36px 0 16px;
  font-weight: 600;
}

/* Card layout */
.card {
  display: flex;
  align-items: center;
  background: #ffffff;
  border-radius: 16px;
  padding: 18px 24px;
  margin-bottom: 18px;
  box-shadow: 0 12px 28px rgba(0,0,0,0.08);
}

/* Logo */
.card-header {
  flex-shrink: 0;
  margin-right: 22px;
}

.card-header img {
  width: 60px;
  height: auto;
}

/* Text */
.card-body {
  flex: 1;
  text-align: left;
  line-height: 1.35;
}

/* Institution (link) */
.card-text {
  margin: 1px 0;
  font-size: 0.95rem;
  color: #555;
}

/* Darker academic blue for links */
.card-text a {
  text-decoration: none;
  color: #1f4fd8;
}

.card-text a:hover {
  text-decoration: underline;
}

/* Position / Degree (main focus) */
.card-title {
  margin: 4px 0 2px;
  font-weight: 600;
  font-size: 1.05rem;
  color: #222;
}

/* Dates / secondary info */
.card-text:last-child {
  font-size: 0.9rem;
  color: #666;
}

/* Muted line (With …) */
.card-text.muted {
  font-size: 0.9rem;
  color: #777;
}

/* Mobile */
@media (max-width: 768px) {
  .card {
    flex-direction: column;
    align-items: flex-start;
  }

  .card-header {
    margin-bottom: 10px;
  }
}
</style>


<div class="content-experience">
  <!-- Education -->
  <h2>Education</h2>
  
  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/pucp-logo.png' | relative_url }}" alt="PUCP Logo">
    </div>
    <div class="card-body">
      <p class="card-text"><a href="https://www.pucp.edu.pe/carrera/finanzas/">Pontificia Universidad Católica del Perú</a></p>
      <h5 class="card-title">Student in Finance</h5>
      <p class="card-text">2022 - 2026</p>
    </div>
  </div>


  <!-- Complementary Education -->
  <h2>Complementary Education</h2>

  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/finlab_logo.png' | relative_url }}" alt="FinLab Logo">
    </div>
    <div class="card-body">
      <p class="card-text"><a href="https://linktr.ee/finlab_ccss">FinLab Pontificia – Universidad Católica del Perú</a></p>
      <h5 class="card-title">Summer School</h5>
      <p class="card-text">2026</p>
    </div>
  </div>
  
  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/qlab_logo.png' | relative_url }}" alt="QLab Logo">
    </div>
    <div class="card-body">
      <p class="card-text"><a href="https://qlab.pucp.edu.pe/">QLab Pontificia – Universidad Católica del Perú</a></p>
      <h5 class="card-title">Summer and Winter School</h5>
      <p class="card-text">2025</p>
    </div>
  </div>


  <!-- Teaching Experience -->
  <h2>Teaching Experience</h2>

  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/pucp-logo.png' | relative_url }}" alt="PUCP Logo">
    </div>
    <div class="card-body">
      <p class="card-text"><a href="https://www.pucp.edu.pe/">Pontificia Universidad Católica del Perú</a></p>
      <h5 class="card-title">Teaching Assistant – Department of Social Science</h5>
      <p class="card-text">
        Financial Microeconomics
      </p>
      <p class="card-text muted">
        With <a href="https://www.pucp.edu.pe/profesor/pavel-coronado-castellanos" target="_blank">Pavel Coronado</a> |
        <a href="https://www.pucp.edu.pe/profesor/jose-gallardo-ku" target="_blank">José Gallardo Ku</a>
      </p> 
    </div>
  </div>


    <!-- Volunteering -->
  <h2>Volunteering</h2>
  
  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/economica_logo.png' | relative_url }}" alt="Economica Logo">
    </div>
    <div class="card-body">
      <p class="card-text"><a href="https://economica.pe/">Economica</a></p>
      <h5 class="card-title">Member of Financial Area</h5>
      <p class="card-text">Mar–Aug 2025</p>
    </div>
  </div>
  
</div>
