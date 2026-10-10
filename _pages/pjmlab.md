---
layout: single
permalink: /pjmlab/
author_profile: true
---

<style>
.pjmlab-section-title {
  font-size: 17px;
  font-weight: 400 !important;
  margin: 25px 0 12px;
}

.pjmlab-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 10px;
  max-width: 760px;
  margin: 12px 0 28px;
}

.pjmlab-tile {
  min-width: 0;
  min-height: 95px;
  padding: 12px 7px;
  background: #e5e5e5;
  border: 1px solid #d5d5d5;
  border-radius: 8px;
  color: #555555 !important;
  text-decoration: none !important;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 9px;
  text-align: center;
  transition: background .2s, transform .2s;
}

a.pjmlab-tile:hover {
  background: #d6d6d6;
  color: #333333 !important;
  transform: translateY(-2px);
}

a.pjmlab-tile:focus-visible {
  outline: 2px solid #777777;
  outline-offset: 3px;
}

.pjmlab-icon {
  color: #999999;
  font-size: 22px;
  line-height: 1;
}

.pjmlab-label {
  color: #555555;
  font-size: 13px;
  font-weight: 400 !important;
  line-height: 1.35;
}

.pjmlab-soon {
  opacity: .65;
  cursor: default;
}

.pjmlab-soon small {
  font-size: 10px;
  color: #777777;
}

.pjmlab-contact {
  margin-top: 35px;
  font-size: 15px;
  line-height: 1.6;
}

@media (max-width: 600px) {
  .pjmlab-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>

<h2>Testy behawioralne online</h2>

<p class="pjmlab-section-title">Język polski</p>

<div class="pjmlab-grid">

  <a class="pjmlab-tile" href="https://marysiaz.github.io/orto/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Ortografia</span>
  </a>

  <a class="pjmlab-tile" href="https://marysiaz.github.io/decoding_test/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Fonetyka</span>
  </a>

  <div class="pjmlab-tile pjmlab-soon">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">LexTALE</span>
    <small>Wkrótce</small>
  </div>

  <div class="pjmlab-tile pjmlab-soon">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Gramatyka</span>
    <small>Wkrótce</small>
  </div>

</div>

<p class="pjmlab-section-title">Polski język migowy (PJM)</p>

<div class="pjmlab-grid">

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_fluency_phon/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Fluencja fonologiczna</span>
  </a>

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_fluency_sem/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Fluencja semantyczna</span>
  </a>

  <a class="pjmlab-tile"
     href="#"
     onclick="var p = prompt('PJM-PCT: Wprowadź hasło dostępu'); if (p === 'pct2026') { window.location.href = 'https://pjmlab.com/pjm-pct/'; } else if (p !== null) { alert('Nieprawidłowe hasło'); } return false;">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">PJM-PCT</span>
  </a>

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_tests_visual_vernacular/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Visual Vernacular</span>
  </a>

</div>

<p class="pjmlab-contact">
  Chcesz użyć tych testów we własnych badaniach?
  Skontaktuj się z nami.
</p>


