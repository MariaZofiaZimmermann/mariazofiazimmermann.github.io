---
layout: single
permalink: /pjmlab/
author_profile: true
---

<style>
/* Nagłówki */
.pjmlab-section-title {
  font-size: 17px;
  font-weight: 400 !important;
  margin: 25px 0 12px;
}

/* Siatka */
.pjmlab-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 10px;
  max-width: 760px;
  margin: 12px 0 28px;
}

/* Kafelki */
.pjmlab-tile {
  min-width: 0;
  min-height: 95px;
  padding: 12px 7px;
  background: transparent !important;
  border: 1px solid currentColor;
  border-radius: 8px;
  color: inherit !important;
  text-decoration: none !important;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 9px;
  text-align: center;
  transition: opacity .2s, transform .2s;
}

/* Linki – bez narzuconych kolorów */
a.pjmlab-tile,
a.pjmlab-tile:visited,
a.pjmlab-tile:hover,
a.pjmlab-tile:active {
  background: transparent !important;
  color: inherit !important;
  text-decoration: none !important;
}

/* Hover */
a.pjmlab-tile:hover {
  opacity: 0.7;
  transform: translateY(-2px);
}

/* Fokus klawiatury */
a.pjmlab-tile:focus-visible {
  outline: 2px solid currentColor;
  outline-offset: 3px;
}

/* Ikony */
.pjmlab-icon {
  color: inherit !important;
  font-size: 22px;
  line-height: 1;
}

/* Napisy */
.pjmlab-label {
  color: inherit !important;
  font-size: 13px;
  font-weight: 400 !important;
  line-height: 1.35;
}

/* Wkrótce */
.pjmlab-soon {
  cursor: default;
}

.pjmlab-soon small {
  font-size: 10px;
  color: inherit !important;
  opacity: 0.7;
}

/* Wyśrodkowany kafelek fMRI */
.pjmlab-fmri-grid {
  display: flex;
  justify-content: center;
  margin: 18px 0 35px;
}

.pjmlab-fmri-grid .pjmlab-tile {
  width: 185px;
  max-width: 100%;
}

/* Ikonka mózgu */
.pjmlab-brain-icon {
  width: 25px;
  height: 25px;
  color: inherit !important;
}

/* Kontakt */
.pjmlab-contact {
  margin-top: 35px;
  font-size: 15px;
  line-height: 1.6;
}

.pjmlab-contact a {
  color: inherit;
  text-decoration: underline;
  text-underline-offset: 3px;
}

.pjmlab-contact a:hover {
  opacity: 0.7;
}

/* Dziedziczenie koloru tekstu z motywu strony */
.page__content .pjmlab-grid,
.page__content .pjmlab-fmri-grid {
  color: inherit;
}

/* Wymuszenie spójności kolorów */
.page__content .pjmlab-tile,
.page__content .pjmlab-tile:visited,
.page__content .pjmlab-tile:hover,
.page__content .pjmlab-tile .pjmlab-label,
.page__content .pjmlab-tile .pjmlab-icon,
.page__content .pjmlab-tile .pjmlab-brain-icon,
.page__content .pjmlab-tile small {
  color: inherit !important;
}

/* Delikatniejsze obramowania */
.page__content .pjmlab-tile {
  border-color: currentColor;
}

/* Telefony */
@media (max-width: 600px) {
  .pjmlab-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>

<p class="pjmlab-section-title">
  Chcesz wziąć udział w naszym badaniu z użyciem obrazowania mózgu (fMRI)?
</p>

<div class="pjmlab-fmri-grid">

  <a class="pjmlab-tile"
     href="https://forms.gle/WgZLTMXtYACskeBaA"
     target="_blank"
     rel="noopener noreferrer">

    <svg class="pjmlab-brain-icon"
         xmlns="http://www.w3.org/2000/svg"
         viewBox="0 0 24 24"
         fill="none"
         stroke="currentColor"
         stroke-width="1.5"
         stroke-linecap="round"
         stroke-linejoin="round"
         aria-hidden="true">
      <path d="M12 18V5a3 3 0 0 0-5.8-1.1A4 4 0 0 0 3 10a4 4 0 0 0 1 7.5A3.5 3.5 0 0 0 12 18Z"/>
      <path d="M12 18V5a3 3 0 0 1 5.8-1.1A4 4 0 0 1 21 10a4 4 0 0 1-1 7.5A3.5 3.5 0 0 1 12 18Z"/>
      <path d="M7 8c1.5 0 2.5 1 2.5 2.5"/>
      <path d="M17 8c-1.5 0-2.5 1-2.5 2.5"/>
      <path d="M6 15c1.5-1 3-.5 3.5 1"/>
      <path d="M18 15c-1.5-1-3-.5-3.5 1"/>
    </svg>

    <span class="pjmlab-label">
      Wypełnij ankietę zgłoszeniową
    </span>

  </a>

</div>

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

<p class="pjmlab-section-title">
  Polski język migowy (PJM)
</p>

<div class="pjmlab-grid">

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_fluency_phon/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Fluencja fonologiczna</span>
  </a>

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_fluency_sem/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Fluencja semantyczna</span>
  </a>

  <a class="pjmlab-tile" href="https://pjmlab.com/pjm-pct/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">PJM-PCT</span>
  </a>

  <a class="pjmlab-tile" href="https://maria-zimmermann.com/PJMlab_tests_visual_vernacular/">
    <span class="pjmlab-icon">&#9633;</span>
    <span class="pjmlab-label">Visual Vernacular</span>
  </a>

</div>


