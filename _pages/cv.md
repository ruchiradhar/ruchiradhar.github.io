---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
  .cv-actions {
    display: flex;
    gap: 0.6rem;
    flex-wrap: wrap;
    margin: 0.4rem 0 1rem;
  }

  .cv-btn {
    display: inline-block;
    border: 1px solid rgba(0, 0, 0, 0.25);
    border-radius: 999px;
    padding: 0.42rem 0.9rem;
    font-size: 0.82rem;
    font-weight: 600;
    text-decoration: none !important;
    transition: border-color 0.18s ease, background 0.18s ease;
  }

  .cv-btn:hover,
  .cv-btn:focus {
    border-color: rgba(0, 0, 0, 0.6);
    background: rgba(0, 0, 0, 0.04);
  }

  .cv-frame {
    border: 1px solid rgba(0, 0, 0, 0.12);
    border-radius: 10px;
    overflow: hidden;
  }

  .cv-embed {
    width: 100%;
    height: min(88vh, 1050px);
    border: 0;
    display: block;
  }

  .cv-fallback {
    margin: 0;
    padding: 1.4rem 1.1rem;
    font-size: 0.88rem;
    text-align: center;
  }

  .cv-note {
    font-size: 0.78rem;
    opacity: 0.65;
    margin-top: 0.6rem;
  }

  @media (max-width: 700px) {
    .cv-embed {
      height: min(70vh, 640px);
    }
  }
</style>

<div class="cv-actions">
  <a class="cv-btn" href="/files/RuchiraResume.pdf" target="_blank" rel="noopener noreferrer">Open PDF</a>
  <a class="cv-btn" href="/files/RuchiraResume.pdf" download>Download CV</a>
</div>

<div class="cv-frame">
  <object
    class="cv-embed"
    data="/files/RuchiraResume.pdf#view=FitH"
    type="application/pdf"
    title="Ruchira Dhar CV"
  >
    <p class="cv-fallback">
      Your browser can't display the CV inline.
      <a href="/files/RuchiraResume.pdf" target="_blank" rel="noopener noreferrer">Open it in a new tab</a>
      or <a href="/files/RuchiraResume.pdf" download>download the PDF</a>.
    </p>
  </object>
</div>

<p class="cv-note">Some mobile browsers won't show an embedded PDF. If the viewer above is blank, use the Open PDF link.</p>
