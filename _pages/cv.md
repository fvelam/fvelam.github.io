---
layout: pages
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
  margin: 40px 0 20px;
  font-weight: 600;
}

/* Card layout */
.card {
  display: flex;
  align-items: center;
  background: #ffffff;
  border-radius: 16px;
  padding: 20px 25px;
  margin-bottom: 20px;
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
}

.card-title {
  margin: 6px 0;
  font-weight: 600;
}

.card-text {
  margin: 2px 0;
  color: #555;
}

.card-text a {
  text-decoration: none;
  color: #1a73e8;
}

/* Mobile */
@media (max-width: 768px) {
  .card {
    flex-direction: column;
    align-items: flex-start;
  }

  .card-header {
    margin-bottom: 12px;
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
      <p class="card-text">FinLab – Pontificia Universidad Católica del Perú</p>
      <h5 class="card-title">Summer School</h5>
      <p class="card-text">2026</p>
    </div>
  </div>
  
  <div class="card">
    <div class="card-header">
      <img draggable="false" src="{{ '/assets/img/institutions/qlab_logo.png' | relative_url }}" alt="QLab Logo">
    </div>
    <div class="card-body">
      <p class="card-text">QLab – Pontificia Universidad Católica del Perú</p>
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
