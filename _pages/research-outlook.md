---
layout: single
title: "Research Outlook"
permalink: /research-outlook/
author_profile: true
---

<style>
  .outlook-shell {
    --outlook-card: rgba(198, 165, 74, 0.08);
    --outlook-stroke: rgba(198, 165, 74, 0.35);
    --outlook-glow: rgba(198, 165, 74, 0.2);
    --outlook-text: #e0c36f;
    --outlook-accent: #c6a54a;
    margin: 0.5rem 0 1.2rem;
  }

  .outlook-hero {
    position: relative;
    padding: 1.2rem 1.1rem;
    border: 1px solid var(--outlook-stroke);
    border-radius: 14px;
    background: linear-gradient(130deg, var(--outlook-card), rgba(198, 165, 74, 0.02));
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
    background: radial-gradient(circle, rgba(224, 195, 111, 0.25), rgba(224, 195, 111, 0));
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
    box-shadow: 0 6px 20px rgba(224, 195, 111, 0.28);
    background: rgba(224, 195, 111, 0.12);
    text-decoration: none;
  }

  .outlook-panel {
    margin-top: 1rem;
    border: 1px solid var(--outlook-stroke);
    border-radius: 14px;
    overflow: hidden;
    background: rgba(198, 165, 74, 0.03);
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
    background: rgba(198, 165, 74, 0.035);
    padding: 0.95rem 0.95rem;
    box-shadow: 0 6px 24px rgba(198, 165, 74, 0.08);
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
        I am a PhD researcher in Computer Science at the University of Copenhagen working on large language model evaluation and responsible AI. My academic background in linguistics and cognitive science, combined with industry experience in applied NLP and generative AI, has shaped a research agenda centered on understanding, evaluating, and responsibly communicating the capabilities of language technologies.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Research Statement</h3>
      <p>
        My research is motivated by a longstanding interest in human cognition and language. My training in linguistics and cognitive science led me to questions about how humans represent meaning, process language, and interpret the world through communication. Over time, this interest expanded into machine cognition: if language models are increasingly used as proxies for humans, what kinds of capabilities do we actually want them to possess, and how should we evaluate those capabilities in a scientifically meaningful and socially responsible way?
      </p>
      <p>
        My work focuses primarily on evaluation. I am interested in the foundational question of what it means for an AI system to perform well, and whether current evaluation practices, tools, and methodological assumptions are adequate for answering that question. This involves not only measuring model performance, but also examining the conceptual choices behind evaluation practices. I see evaluation as both a technical and epistemic problem: it requires us to define which capacities matter, determine how they can be measured, and communicate results in ways that are interpretable and useful across research, industry, and governance settings.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Cognitive Evaluation Strand</h3>
      <p>
        A first strand of my research concerns the evaluation of cognitive aspects of language processing. I am interested in whether and in what ways machines exhibit properties that resemble human language understanding, reasoning, or representation. Rather than taking human-like behavior at face value, I aim to investigate it carefully: which aspects of cognition are meaningfully comparable, where the analogies break down, and what such comparisons reveal about both human and machine intelligence.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Methodological Evaluation Strand</h3>
      <p>
        A second strand of my work addresses methodological questions in AI evaluation. I am interested in how evaluation datasets are designed, how tasks operationalize complex constructs, and how conclusions about model ability are drawn from benchmark results. My goal is to contribute to more rigorous and transparent evaluation frameworks that move beyond narrow performance metrics and instead capture the broader validity, limitations, and intended use of an assessment. In this regard, I see evaluation as an essential scientific infrastructure for AI: without careful methodology, our claims about intelligence, reasoning, or usefulness remain underspecified.
      </p>
    </article>

    <article class="outlook-card">
      <h3>Governance and Communication Strand</h3>
      <p>
        A third strand of my research engages with the regulatory and communicative dimensions of evaluation. As AI systems are deployed to wider publics and increasingly shape decisions across domains, it becomes important not only to evaluate systems well, but also to standardize how evaluation is reported and communicated. I am particularly interested in frameworks that make evaluation results more transparent, comparable, and accountable for different stakeholders, including researchers, developers, policymakers, and end users. My work on standardized reporting emerges from this concern that evaluation should support informed governance and responsible adoption, not merely internal model comparison.
      </p>
      <p>
        Across these directions, my broader aim is to build evaluation methods that are technically rigorous, conceptually grounded, and socially responsive. I want to contribute to a research culture in which AI systems are not only optimized for performance, but also examined in terms of what their capabilities mean, how they are measured, and how those measurements are communicated. By combining insights from linguistics, cognitive science, and computer science, I hope to advance a more human-centered and transparent science of AI evaluation.
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
