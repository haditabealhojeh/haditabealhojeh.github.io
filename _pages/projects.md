---
layout: page
title: Projects
permalink: /projects/
description: Research and applied AI projects by Dr. Hadi Tabealhojeh.
nav: true
nav_order: 5
---

Selected research and applied-AI projects spanning geometric machine learning, forecasting, and semantic data.

<style>
.project-grid { display:grid; grid-template-columns:repeat(2,minmax(0,1fr)); gap:1.2rem; margin:1.4rem 0 2rem; }
.project-card { border:1px solid var(--global-divider-color); border-radius:8px; overflow:hidden; background:var(--global-card-bg-color); }
.project-card img { display:block; width:100%; aspect-ratio:16 / 9; object-fit:cover; background:var(--global-bg-color); border-bottom:1px solid var(--global-divider-color); }
.project-card-body { padding:1.05rem; }
.project-card h3 { font-size:1.12rem; margin:.1rem 0 .55rem; }
.project-card p { margin:0 0 .85rem; }
.project-tags { display:flex; flex-wrap:wrap; gap:.4rem; }
.project-tag { display:inline-block; border-radius:999px; padding:.2rem .6rem; background:var(--global-code-bg-color); font-size:.78rem; }
@media (max-width: 650px) { .project-grid { grid-template-columns:1fr; } }
</style>

<div class="project-grid">
  <article class="project-card">
    <img src="{{ '/assets/img/projects/air-pollution-forecasting.jpg' | relative_url }}" alt="Air pollution forecasting concept with an urban skyline, spatial map, and time-series chart" loading="lazy">
    <div class="project-card-body">
      <h3>Air Pollution Forecasting</h3>
      <p>Temporal representation learning and forecasting for environmental data, including a published case study of air-pollution levels in Nasiriyah City.</p>
      <div class="project-tags"><span class="project-tag">Deep Learning</span><span class="project-tag">Time Series</span><span class="project-tag">Environmental AI</span></div>
    </div>
  </article>
  <article class="project-card">
    <img src="{{ '/assets/img/projects/rmaml.jpg' | relative_url }}" alt="Conceptual comparison of Euclidean MAML and Riemannian meta-learning on curved manifolds" loading="lazy">
    <div class="project-card-body">
      <h3>RMAML: Riemannian Meta-learning</h3>
      <p>Research on few-shot learning with orthogonality constraints and optimization on Riemannian manifolds.</p>
      <div class="project-tags"><span class="project-tag">Meta-learning</span><span class="project-tag">Riemannian Geometry</span><span class="project-tag">Optimization</span></div>
    </div>
  </article>
  <article class="project-card">
    <img src="{{ '/assets/img/projects/temporal-knowledge-graph.jpg' | relative_url }}" alt="Knowledge graph feeding a temporal representation model and forecasting chart" loading="lazy">
    <div class="project-card-body">
      <h3>Knowledge-guided Temporal Forecasting</h3>
      <p>Exploring how structured domain knowledge and temporal representations can support forecasting tasks.</p>
      <div class="project-tags"><span class="project-tag">Knowledge Graphs</span><span class="project-tag">Temporal Learning</span><span class="project-tag">AI</span></div>
    </div>
  </article>
  <article class="project-card">
    <img src="{{ '/assets/img/projects/persianfarm.jpg' | relative_url }}" alt="Ontology matching illustration linking document-like data sources to a semantic graph" loading="lazy">
    <div class="project-card-body">
      <h3>PersianFarm Dataset</h3>
      <p>A dataset for Persian ontology matching, supporting research in semantic web technologies and knowledge representation.</p>
      <div class="project-tags"><span class="project-tag">Semantic Web</span><span class="project-tag">Ontology Matching</span><span class="project-tag">NLP</span></div>
    </div>
  </article>
</div>

Add only projects you can publicly describe. For industry work, keep client names, data, and outcomes confidential unless you have permission to disclose them. Image filenames and dimensions are documented in `IMAGE-ASSETS-README.md`.
