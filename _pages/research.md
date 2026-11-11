---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

My research focuses on developing intelligent learning and optimization methods for complex problems, combining mathematical foundations with practical applications. My interests span geometric machine learning, meta-learning, deep learning, and intelligent decision-making systems.

<style>
.research-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1.1rem;
  margin: 1.4rem 0 2rem;
}

.research-card {
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;
  overflow: hidden;
  background: var(--global-card-bg-color);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.research-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 5px 16px rgba(0, 0, 0, 0.08);
}

.research-card img {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  object-fit: cover;
  background: var(--global-bg-color);
  border-bottom: 1px solid var(--global-divider-color);
}

.research-card-body {
  padding: 1rem;
}

.research-card h3 {
  font-size: 1.08rem;
  margin: .1rem 0 .55rem;
}

.research-card p {
  margin: 0;
  font-size: .95rem;
}

@media (max-width: 900px) {
  .research-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 575px) {
  .research-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="research-grid">

  <!-- 1. Riemannian Meta-Learning -->
  <article class="research-card">
    <img src="{{ '/assets/img/research/riemannian-meta-learning.png' | relative_url }}"
         alt="Meta-learning algorithms operating on a Riemannian manifold"
         loading="lazy">
    <div class="research-card-body">
      <h3>Riemannian Meta-Learning</h3>
      <p>
        Developing meta-learning algorithms for non-Euclidean spaces, with
        particular emphasis on few-shot learning, geometric adaptation,
        and optimization on Riemannian manifolds. My research explores
        geometry-aware meta-learning, orthogonality constraints, and
        bilevel optimization to improve learning and generalization across
        related tasks.
      </p>
    </div>
  </article>

  <!-- 2. Dynamic Vehicle Routing -->
  <article class="research-card">
    <img src="{{ '/assets/img/research/dynamic-vehicle-routing.png' | relative_url }}"
         alt="Distribution centers, vehicles, customers, and dynamically updated delivery routes"
         loading="lazy">
    <div class="research-card-body">
      <h3>Dynamic Vehicle Routing Problem</h3>
      <p>
        Developing intelligent solutions for dynamic vehicle routing and
        transportation optimization. This research investigates deep
        reinforcement learning, multi-agent systems, and adaptive
        decision-making for fleet management, distribution networks,
        and routing under changing operational conditions.
      </p>
    </div>
  </article>

  <!-- 3. Machine Unlearning -->
  <article class="research-card">
    <img src="{{ '/assets/img/research/machine-unlearning.png' | relative_url }}"
         alt="Selective removal of information from a trained neural network"
         loading="lazy">
    <div class="research-card-body">
      <h3>Machine Unlearning</h3>
      <p>
        Investigating methods that enable machine-learning models to
        selectively forget specific information while retaining useful
        knowledge and predictive performance. Particular interests include
        backpropagation-free unlearning, local learning algorithms,
        Forward-Forward networks, and privacy-aware machine learning.
      </p>
    </div>
  </article>

  <!-- 4. Riemannian Geometry and Manifold Learning -->
  <article class="research-card">
    <img src="{{ '/assets/img/research/riemannian-geometry-manifold-learning.png' | relative_url }}"
         alt="Riemannian manifold illustrating geodesics, tangent spaces, and geometric projections"
         loading="lazy">
    <div class="research-card-body">
      <h3>Riemannian Geometry and Manifold Learning</h3>
      <p>
        Studying the geometric foundations of machine learning, with an
        emphasis on representing, analyzing, and processing data on
        nonlinear spaces. Research interests include Riemannian manifolds,
        Grassmann and Stiefel manifolds, symmetric positive-definite
        matrices, geometric optimization, and manifold-based learning.
      </p>
    </div>
  </article>

  <!-- 5. Deep Learning and Multimodal Learning -->
  <article class="research-card">
    <img src="{{ '/assets/img/research/deep-learning-multimodal-learning.png' | relative_url }}"
         alt="Image, text, audio, and other modalities combined through multimodal neural networks"
         loading="lazy">
    <div class="research-card-body">
      <h3>Deep Learning and Multimodal Learning</h3>
      <p>
        Exploring deep learning architectures and representation-learning
        methods for complex and heterogeneous data. Research interests
        include multimodal representation learning, cross-modal information
        fusion, attention mechanisms, and learning from diverse sources
        such as images, text, and temporal signals.
      </p>
    </div>
  </article>

</div>
