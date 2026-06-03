---
layout: single
title: "Research Outlook"
permalink: /research-outlook/
author_profile: true
---

<style>
  .outlook-shell {
    --outlook-card: rgba(255, 255, 255, 0.03);
    --outlook-stroke: rgba(255, 255, 255, 0.1);
    --outlook-glow: rgba(255, 255, 255, 0.04);
    --outlook-text: #e8e8e8;
    --outlook-accent: #ffffff;
    margin: 0.5rem 0 1.2rem;
  }

  .outlook-hero {
    position: relative;
    padding: 1.2rem 1.1rem;
    border: 1px solid var(--outlook-stroke);
    border-radius: 14px;
    background: linear-gradient(130deg, var(--outlook-card), rgba(255, 255, 255, 0.01));
    box-shadow: 0 10px 35px var(--outlook-glow);
    overflow: hidden;
    animation: fadeLift 0.8s ease both;
  }

  .outlook-hero::after {
    content: "";
    position: absolute;
    inset: -25% -10% auto auto;
    width: 220px;
    height: 220px;
    border-radius: 999px;
    background: radial-gradient(circle, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0));
    animation: pulseGlow 3.2s ease-in-out infinite;
    pointer-events: none;
  }

  .outlook-kicker {
    display: inline-block;
    font-size: 0.76rem;
    text-transform: uppercase;
    letter-spacing: 0.14em;
    color: var(--outlook-accent);
    margin-bottom: 0.5rem;
  }

  .outlook-lead {
    color: var(--outlook-text);
    margin: 0;
    max-width: 65ch;
  }

  .outlook-actions {
    display: flex;
    gap: 0.7rem;
    flex-wrap: wrap;
    margin-top: 0.95rem;
  }

  .outlook-btn {
    display: inline-block;
    border: 1px solid var(--outlook-accent);
    color: var(--outlook-accent);
    background: transparent;
    border-radius: 999px;
    padding: 0.45rem 0.8rem;
    font-weight: 600;
    text-decoration: none;
    transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
  }

  .outlook-btn:hover {
    transform: translateY(-1px);
    box-shadow: 0 6px 20px rgba(255, 255, 255, 0.08);
    background: rgba(255, 255, 255, 0.07);
    text-decoration: none;
  }

  .outlook-panel {
    margin-top: 1rem;
    border: 1px solid var(--outlook-stroke);
    border-radius: 14px;
    overflow: hidden;
    background: rgba(255, 255, 255, 0.02);
    animation: fadeLift 0.95s ease both;
    animation-delay: 0.12s;
  }

  .outlook-panel-head {
    padding: 0.6rem 0.85rem;
    border-bottom: 1px solid var(--outlook-stroke);
    color: var(--outlook-text);
    font-size: 0.92rem;
    opacity: 0.95;
  }

  .outlook-grid {
    margin-top: 1rem;
    display: grid;
    grid-template-columns: 1fr;
    gap: 0.9rem;
  }

  .outlook-card {
    border: 1px solid var(--outlook-stroke);
    border-radius: 12px;
    background: rgba(255, 255, 255, 0.02);
    padding: 0.95rem 0.95rem;
    box-shadow: 0 6px 24px rgba(0, 0, 0, 0.3);
    animation: fadeLift 0.8s ease both;
  }

  .outlook-grid .outlook-card:nth-child(1) { animation-delay: 0.12s; }
  .outlook-grid .outlook-card:nth-child(2) { animation-delay: 0.2s; }
  .outlook-grid .outlook-card:nth-child(3) { animation-delay: 0.28s; }
  .outlook-grid .outlook-card:nth-child(4) { animation-delay: 0.36s; }
  .outlook-grid .outlook-card:nth-child(5) { animation-delay: 0.44s; }

  .outlook-card h3 {
    margin-top: 0;
    margin-bottom: 0.55rem;
    color: var(--outlook-accent);
    letter-spacing: 0.01em;
  }

  .outlook-card p {
    margin: 0 0 0.72rem;
    color: var(--outlook-text);
    line-height: 1.68;
  }

  .outlook-card p:last-child {
    margin-bottom: 0;
  }

  .outlook-embed {
    width: 100%;
    height: min(78vh, 860px);
    border: 0;
    display: block;
  }

  @keyframes fadeLift {
    from {
      opacity: 0;
      transform: translateY(8px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes pulseGlow {
    0%, 100% {
      transform: scale(0.94);
      opacity: 0.65;
    }
    50% {
      transform: scale(1.06);
      opacity: 1;
    }
  }

  @media (max-width: 700px) {
    .outlook-hero {
      padding: 1rem 0.9rem;
    }

    .outlook-embed {
      height: min(68vh, 620px);
    }
  }
</style>

<div class="outlook-shell">
  <section class="outlook-hero">
    <span class="outlook-kicker">Research Outlook</span>
    <p class="outlook-lead">
      This page captures my research agenda on large language model evaluation, responsible AI, and human-centered scientific methodology.
    </p>
    <div class="outlook-actions">
      <a class="outlook-btn" href="/files/RDResearchStatement.pdf" target="_blank" rel="noopener noreferrer">Open PDF</a>
      <a class="outlook-btn" href="/files/RDResearchStatement.pdf" download>Download Statement</a>
    </div>
  </section>

  <section class="outlook-grid">
    <article class="outlook-card">
      <h3>Personal Background</h3>
      <p>
        PhD researcher in Computer Science at the University of Copenhagen (CoAStaL NLP group). Background in linguistics, cognitive science, and applied NLP. Research agenda centres on the scientific and epistemic foundations of LLM evaluation.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Research Statement</h3>
      <p>
        My work asks: what does it mean for a language model to perform well, and are current evaluation practices adequate for answering that? I treat evaluation as both a technical and epistemic problem: one that requires defining which capacities matter, operationalising them rigorously, and communicating results in ways that hold up across research, industry, and governance contexts.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Cognitive Evaluation Strand</h3>
      <p>
        Investigates whether and how LLMs approximate human language processing and conceptual representation. Rather than accepting surface behavioural similarity, I examine where the cognitive analogy holds, where it breaks down, and what those limits reveal about the nature of machine intelligence. Current focus: compositionality and semantic representation.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Methodological Evaluation Strand</h3>
      <p>
        <strong>Generality evaluation.</strong> Current benchmarks optimise for narrow task performance, yielding capability claims that do not generalise. I work on evaluation designs that better characterise the scope and limits of model capabilities, shifting the question from "does the model pass this benchmark" to "what does passing reveal about underlying competence."
      </p>
      <p>
        <strong>Efficient evaluation via psychometrics.</strong> Comprehensive evaluation is expensive; most practitioners cannot afford it at scale. I apply psychometric methods (item response theory, adaptive testing) to build evaluation instruments that yield reliable capability estimates with substantially fewer test items, without sacrificing measurement validity.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Governance and Communication Strand</h3>
      <p>
        As AI systems enter high-stakes deployment contexts, how evaluation is reported becomes as consequential as how it is designed. I work on standardised reporting frameworks (see: EvalCards) that make evaluation results auditable and interpretable across researcher, developer, and policymaker audiences, supporting informed governance rather than internal model comparison.
      </p>
    </article>
  </section>

  <section class="outlook-panel">
    <div class="outlook-panel-head">Full statement PDF</div>
    <iframe
      class="outlook-embed"
      src="/files/RDResearchStatement.pdf#view=FitH"
      title="Research Statement PDF"
      loading="lazy"
    ></iframe>
  </section>
</div>
