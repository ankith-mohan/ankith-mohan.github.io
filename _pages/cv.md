---
layout: page
title: cv
permalink: /cv/
nav: true
nav_order: 3
---

<div class="cv-desktop">
  <iframe
    src="/assets/pdf/CV_Mohan_Ankith.pdf"
    width="100%"
    height="100%"
    style="border: none;">
  </iframe>
</div>

<div class="cv-mobile">
  <p>
    <a
      href="/assets/pdf/CV_Mohan_Ankith.pdf"
      target="_blank"
      rel="noopener noreferrer"
      class="btn btn-primary"
    >
      Open CV
    </a>
  </p>
</div>

<style>
  .cv-desktop {
    width: min(95vw, 1400px);
    height: 90vh;
    margin-left: 50%;
    transform: translateX(-50%);
  }

  .cv-mobile {
    display: none;
  }

  @media (max-width: 768px) {
    .cv-desktop {
      display: none;
    }

    .cv-mobile {
      display: block;
      margin-top: 2rem;
    }
  }
</style>
