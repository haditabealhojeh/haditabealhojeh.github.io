---
layout: page
title: Research
permalink: /research/
description: Research interests of Dr. Hadi Tabealhojeh in AI, meta-learning, Riemannian geometry, and manifold optimization.
nav: true
nav_order: 2
---

My research explores learning and optimization methods for problems where data or model parameters have geometric structure. A recurring goal is to develop algorithms that are mathematically principled while remaining practical for modern machine-learning tasks.

<style>
.research-grid { display:grid; grid-template-columns:repeat(3,minmax(0,1fr)); gap:1.1rem; margin:1.4rem 0 2rem; }
.research-card { border:1px solid var(--global-divider-color); border-radius:8px; overflow:hidden; background:var(--global-card-bg-color); }
.research-card img { display:block; width:100%; aspect-ratio: 16 / 9; object-fit:cover; background:var(--global-bg-color); border-bottom:1px solid var(--global-divider-color); }
.research-card-body { padding:1rem; }
.research-card h3 { font-size:1.08rem; margin:.1rem 0 .55rem; }
.research-card p { margin:0; font-size:.95rem; }
@media (max-width: 900px) { .research-grid { grid-template-columns:repeat(2,minmax(0,1fr)); } }
@media (max-width: 575px) { .research-grid { grid-template-columns:1fr; } }
</style>

<div class="research-grid">
  <article class="research-card">
    <img src="{{ '/assets/img/research/meta-learning.jpg' | relative_url }}" alt="Illustration of few-shot examples passing through a meta-learning and adaptation pipeline" loading="lazy">
    <div class="research-card-body">
      <h3>Meta-learning and Few-shot Learning</h3>
      <p>Learning to adapt to new tasks from only a few examples, with an emphasis on optimization-based meta-learning and structured representations.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="{{ '/assets/img/research/riemannian-geometry.jpg' | relative_url }}" alt="Curved Riemannian manifold with a path between two points" loading="lazy">
    <div class="research-card-body">
      <h3>Riemannian Geometry and Manifold Learning</h3>
      <p>Learning from data on curved spaces, including subspaces, rotations, and symmetric positive-definite matrices.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="{{ '/assets/img/research/multimodal-learning.jpg' | relative_url }}" alt="Image, text, and audio representations being fused for downstream tasks" loading="lazy">
    <div class="research-card-body">
      <h3>Deep Learning and Multimodal Learning</h3>
      <p>Representation learning and methods for combining information across modalities and learning settings.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="{{ '/assets/img/research/environmental-ai.jpg' | relative_url }}" alt="Environmental map and time-series curves used for forecasting" loading="lazy">
    <div class="research-card-body">
      <h3>Time Series and Environmental AI</h3>
      <p>Applying machine learning to temporal data and environmental forecasting, including air-quality prediction.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="{{ '/assets/img/research/ai-robotics.jpg' | relative_url }}" alt="Robotics perception, planning, and control workflow" loading="lazy">
    <div class="research-card-body">
      <h3>Artificial Intelligence and Robotics</h3>
      <p>Connecting learning methods with intelligent systems, perception, planning, and adaptive decision-making.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="{{ '/assets/img/research/optimization.jpg' | relative_url }}" alt="Optimization trajectory over a loss landscape and curved manifold" loading="lazy">
    <div class="research-card-body">
      <h3>Optimization and Learning Theory</h3>
      <p>Studying optimization algorithms, generalization, and geometry-aware methods for machine learning.</p>
    </div>
  </article>
</div>

Each figure is an independent image file, so you can replace the illustrations without editing the page layout. Image filenames and dimensions are documented in `IMAGE-ASSETS-README.md`.
