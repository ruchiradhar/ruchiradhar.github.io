---
layout: single
title: "Personal Projects"
permalink: /personal-projects/
author_profile: true
---

A home for projects I build while exploring ideas, tools, and systems.

<style>
  .project-section-title {
    margin: 1.8rem 0 0.3rem;
    font-size: 1.1rem;
    font-weight: 600;
    letter-spacing: 0.02em;
  }

  .project-section-note {
    margin: 0 0 1rem;
    font-size: 0.85rem;
    opacity: 0.68;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(255px, 1fr));
    gap: 0.9rem;
    margin-bottom: 0.6rem;
  }

  a.project-card {
    display: flex;
    align-items: flex-start;
    gap: 0.85rem;
    padding: 0.85rem;
    border: 1px solid rgba(0, 0, 0, 0.12);
    border-radius: 10px;
    background: #ffffff;
    text-decoration: none !important;
    transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  }

  a.project-card:hover,
  a.project-card:focus {
    transform: translateY(-2px);
    border-color: rgba(0, 0, 0, 0.3);
    box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
    text-decoration: none !important;
  }

  .project-thumb {
    flex: 0 0 auto;
    width: 68px;
    height: 51px;
    border: 1px solid rgba(0, 0, 0, 0.08);
    border-radius: 7px;
  }

  .project-body {
    min-width: 0;
  }

  .project-name {
    font-size: 0.92rem;
    font-weight: 600;
    line-height: 1.3;
    margin-bottom: 0.22rem;
  }

  .project-desc {
    font-size: 0.8rem;
    line-height: 1.55;
    opacity: 0.72;
    margin-bottom: 0.3rem;
  }

  .project-repo {
    display: inline-block;
    font-size: 0.74rem;
    letter-spacing: 0.02em;
    opacity: 0.6;
    word-break: break-word;
  }

  a.project-card:hover .project-repo {
    opacity: 0.9;
  }

  @media (max-width: 480px) {
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<h3 class="project-section-title">Mini Projects</h3>
<p class="project-section-note">Small end-to-end builds, prototypes, and practical implementations.</p>

<div class="project-grid">
  <a class="project-card" href="https://github.com/ruchiradhar/cyberpins" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/cyberpins.svg" alt="CyberPins thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">CyberPins</div>
      <div class="project-desc">A global map of source-linked cybersecurity news, with 7-day, 30-day, and 3-month country coverage built on GDELT data.</div>
      <span class="project-repo">cyberpins &#8599;</span>
    </div>
  </a>

  <a class="project-card" href="https://github.com/ruchiradhar/llm_reasoning_project" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/slm-reasoning.svg" alt="SLM Reasoning thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">SLM Reasoning</div>
      <div class="project-desc">An absolute beginner-friendly repo on how to call LLMs and evaluate them on reasoning tasks.</div>
      <span class="project-repo">llm_reasoning_project &#8599;</span>
    </div>
  </a>

  <a class="project-card" href="https://github.com/ruchiradhar/semantic_autograder" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/semantic-autograder.svg" alt="Automated Essay Grader thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">Automated Essay Grader</div>
      <div class="project-desc">A student grading prediction model with a full machine learning pipeline.</div>
      <span class="project-repo">semantic_autograder &#8599;</span>
    </div>
  </a>

  <a class="project-card" href="https://github.com/ruchiradhar/mnist_classifier" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/mnist-classifier.svg" alt="Fashion MNIST classifier thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">Image Classifier on Fashion MNIST</div>
      <div class="project-desc">An image classifier trained and evaluated on the Fashion MNIST dataset.</div>
      <span class="project-repo">mnist_classifier &#8599;</span>
    </div>
  </a>
</div>

<h3 class="project-section-title">Learning Repos</h3>
<p class="project-section-note">Projects focused on learning-by-building, experimentation, and skill development.</p>

<div class="project-grid">
  <a class="project-card" href="https://github.com/ruchiradhar/learninglab_ai" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/learninglab-ai.svg" alt="Learning AI thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">Learning AI</div>
      <div class="project-desc">A learning-focused repository for AI concepts.</div>
      <span class="project-repo">learninglab_ai &#8599;</span>
    </div>
  </a>

  <a class="project-card" href="https://github.com/ruchiradhar/learninglab_stats" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/learninglab-stats.svg" alt="Learning Statistics thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">Learning Statistics</div>
      <div class="project-desc">A learning-focused repository for statistics concepts.</div>
      <span class="project-repo">learninglab_stats &#8599;</span>
    </div>
  </a>

  <a class="project-card" href="https://github.com/ruchiradhar/learninglab_dsa" target="_blank" rel="noopener noreferrer">
    <img class="project-thumb" src="/images/projects/learninglab-dsa.svg" alt="Learning C++ and DSA thumbnail" loading="lazy">
    <div class="project-body">
      <div class="project-name">Learning C++</div>
      <div class="project-desc">A learning-focused repository for C++ and data structures and algorithms concepts.</div>
      <span class="project-repo">learninglab_dsa &#8599;</span>
    </div>
  </a>
</div>
