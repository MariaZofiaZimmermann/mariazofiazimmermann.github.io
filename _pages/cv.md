---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-grid {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 10px;
  max-width: 760px;
  margin: 20px 0 30px;
}

.cv-tile {
  min-width: 0;
  min-height: 95px;
  padding: 12px 7px;
  background: #d0d0d0;
  border: 1px solid #bfbfbf;
  border-radius: 8px;
  color: #444444 !important;
  text-decoration: none !important;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 9px;
  text-align: center;
  transition: background .2s, transform .2s;
}

.cv-tile:hover {
  background: #c2c2c2;
  color: #333333 !important;
  transform: translateY(-2px);
}

.cv-tile:focus-visible {
  outline: 2px solid #777777;
  outline-offset: 3px;
}

.cv-icon {
  color: #888888;
  font-size: 22px;
  line-height: 1;
}

.cv-label {
  color: #444444;
  font-size: 13px;
  font-weight: 400 !important;
  line-height: 1.35;
}

@media (max-width: 600px) {
  .cv-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}
</style>

<div class="cv-grid">

  <a class="cv-tile"
     href="/files/CV_Maria_Zimmermann.pdf"
     target="_blank"
     rel="noopener noreferrer">
    <span class="cv-icon">&#9633;</span>
    <span class="cv-label">Download my CV (PDF)</span>
  </a>

</div>
