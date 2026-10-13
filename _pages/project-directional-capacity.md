---
layout: single
title: "Directional Capacity of Shared Representations"
permalink: /projects/directional-capacity/
author_profile: true
---

<link rel="stylesheet" href="/assets/css/research.css">
<div class="research-detail">
<a class="rp-back" href="/projects/">← Projects</a>
<p class="rp-kicker">Learning theory · Statistical identifiability</p>

<p class="rp-lead">Collecting more data does not help if the selected sources never reveal the direction a shared model needs to learn.</p>

<h2>Information capacity before model fitting</h2>
<p>Shared-representation pipelines often train their common components using a restricted selection of tasks, clients, or donor units. I study which directions the selection can supply, separating <strong>directional capacity</strong> from <strong>estimation precision</strong>.</p>
<p>The resulting rank-based audit can detect an information gap before an expensive shared model is fitted. In a protein-data stress test, an observation-count rule suggested that 32 sources were sufficient; empirical identification appeared near 128. Across 4,000 controlled Gaussian designs, the capacity criterion matched the realized rank.</p>

<h2>Research direction</h2>
<p>This perspective connects shared representation learning and data-source selection to a broader question in adaptive learning: <strong>what can the available evidence identify?</strong> It provides one mathematical foundation for my doctoral work on model updates after structural change.</p>


<figure class="rp-figure">
<img src="/images/research/directional-capacity-figure.png" alt="Shared-model performance over controlled regimes" loading="lazy">
<figcaption>Selected controlled comparisons from the representation-learning research.</figcaption>
</figure>

<p class="rp-pub"><strong>Manuscript:</strong> <em>Which Units May Update a Shared Representation? Directional Capacity versus Task Diversity</em>. With Prof. Yassine Yaakoubi.</p>

</div>
