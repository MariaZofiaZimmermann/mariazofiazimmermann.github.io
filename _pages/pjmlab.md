---
layout: single
permalink: /pjmlab/
author_profile: true
---

<style>
.pjmlab-page {
  margin-top: 25px;
}

/* Nagłówek */

.pjmlab-page h2 {
  font-size: 23px;
  font-weight: 650;
  letter-spacing: -0.4px;
  margin: 0 0 22px;
  border: none;
}

/* Siatka kafelków */

.pjmlab-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 15px;
  margin: 20px 0 40px;
}

/* Kafelki */

.pjmlab-tile {
  min-width: 0;
  min-height: 145px;
  padding: 20px;
  border: 1px solid #e4e9ef;
  border-radius: 14px;
  background: #f8fbff;
  color: #40464d !important;
  text-decoration: none !important;

  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  gap: 10px;

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease,
    border-color 0.2s ease;
}

/* Kolory kategorii */

.pjmlab-tile--pl {
  background: #f8fbff;
  border-color: #e3edf9;
}

.pjmlab-tile--pjm {
  background: #faf9ff;
  border-color: #ebe6f7;
}

/* Hover */

a.pjmlab-tile:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 22px rgba(30, 40, 60, 0.07);
  border-color: #b9c7da;
  text-decoration: none !important;
}

a.pjmlab-tile:focus-visible {
  outline: 2px solid #718db5;
  outline-offset: 3px;
}

/* Oryginalna ikonka */

.pjmlab-icon {
  font-size: 22px;
  line-height: 1;
  color: #8994a1;
}

/* Kategoria */

.pjmlab-category {
  font-size: 11px;
  font-weight: 500;
  color: #84909d;
  line-height: 1.3;
}

/* Nazwa testu */

.pjmlab-label {
  font-size: 16px;
  font-weight: 600;
  line-height: 1.4;
  color: #40464d;
}

/* Niedostępne testy */

.pjmlab-soon {
  opacity: 0.65;
  cursor: default;
}

.pjmlab-soon small {
  font-size: 11px;
  color: #8a929c;
}

/* Sekcja fMRI */

.pjmlab-fmri {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 22px;
  margin: 15px 0 40px;
  background: #f8fafc;
  border: 1px solid #e4e9ed;
  border-radius: 14px;
}

.pjmlab-fmri-icon {
  flex-shrink: 0;
  width: 48px;
  height: 48px;
  background: #e8edf5;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #647c9d;
}

.pjmlab-brain-icon {
  width: 26px;
  height: 26px;
}

.pjmlab-fmri-content {
  flex: 1;
  min-width: 0;
}

.pjmlab-fmri-title {
  font-size: 15px;
  font-weight: 600;
  margin-bottom: 5px;
}

.pjmlab-fmri-description {
  font-size: 12px;
  color: #77818d;
  line-height: 1.6;
}

.pjmlab-fmri-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 11px 15px;
  background: #455d7b;
  color: white !important;
  text-decoration: none !important;
  border-radius: 9px;
  font-size: 12px;
  font-weight: 600;
  white-space: nowrap;
}

.pjmlab-fmri-button:hover {
  background: #334964;
  color: white !important;
}

.pjmlab-fmri-button:focus-visible {
  outline: 2px solid #455d7b;
  outline-offset: 3px;
}

/* Telefony */

@media (max-width: 600px) {
  .pjmlab-grid {
    grid-template-columns: 1fr;
    gap: 12px;
  }

  .pjmlab-tile {
    min-height: 125px;
    padding: 18px;
  }

  .pjmlab-fmri {
    flex-wrap: wrap;
  }

  .pjmlab-fmri-button {
    width: 100%;
  }
}
</style>

<div class="pjmlab-page">

<h2>Testy behawioralne online</h2>

<div class="pjmlab-grid">

  <!-- ORTOGRAFIA -->

  <a class="pjmlab-tile pjmlab-tile--pl"
     href="https://marysiaz.github.io/orto/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">Język polski:</span>
    <span class="pjmlab-label">Ortografia</span>
  </a>

  <!-- FONETYKA -->

  <a class="pjmlab-tile pjmlab-tile--pl"
     href="https://marysiaz.github.io/decoding_test/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">Język polski:</span>
    <span class="pjmlab-label">Fonetyka</span>
  </a>

  <!-- LEXTALE -->

  <div class="pjmlab-tile pjmlab-tile--pl pjmlab-soon">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">Język polski:</span>
    <span class="pjmlab-label">LexTALE</span>
    <small>Wkrótce</small>
  </div>

  <!-- GRAMATYKA -->

  <div class="pjmlab-tile pjmlab-tile--pl pjmlab-soon">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">Język polski:</span>
    <span class="pjmlab-label">Gramatyka</span>
    <small>Wkrótce</small>
  </div>

  <!-- FLUENCJA FONOLOGICZNA -->

  <a class="pjmlab-tile pjmlab-tile--pjm"
     href="https://maria-zimmermann.com/PJMlab_fluency_phon/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">PJM:</span>
    <span class="pjmlab-label">Fluencja fonologiczna</span>
  </a>

  <!-- FLUENCJA SEMANTYCZNA -->

  <a class="pjmlab-tile pjmlab-tile--pjm"
     href="https://maria-zimmermann.com/PJMlab_fluency_sem/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">PJM:</span>
    <span class="pjmlab-label">Fluencja semantyczna</span>
  </a>

  <!-- PJM-PCT -->

  <a class="pjmlab-tile pjmlab-tile--pjm"
     href="https://pjmlab.com/pjm-pct/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">PJM:</span>
    <span class="pjmlab-label">PJM-PCT</span>
  </a>

  <!-- VISUAL VERNACULAR -->

  <a class="pjmlab-tile pjmlab-tile--pjm"
     href="https://maria-zimmermann.com/PJMlab_tests_visual_vernacular/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-category">PJM:</span>
    <span class="pjmlab-label">Visual Vernacular</span>
  </a>

</div>

