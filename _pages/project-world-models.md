---
layout: single
title: "Local Adaptation under Structural Shift"
permalink: /projects/world-models/
author_profile: true
---

<link rel="stylesheet" href="/assets/css/research.css">
<div class="research-detail">
<a class="rp-back" href="/projects/">← Projects</a>
<p class="rp-kicker">Ph.D. research · Model-based planning · Causal learning</p>

<p class="rp-lead">When the environment changes, a learned world model should update its predictions about the changed mechanism while preserving those that are still correct.</p>

<h2>Mechanism-indexed local updates</h2>
<p>World models support planning by predicting what follows from an agent's actions. Many deployment changes are local: a surface changes friction, an airport adopts a new procedure, or a logistics problem gains a constraint. My dissertation studies the information needed to identify that change and the scope of the model update that best supports decisions.</p>

<h2>Initial evidence</h2>
<p>In a controlled navigation task with 16 region-specific mechanisms, 64 balanced post-shift probes localized an unknown change in <strong>90.8%</strong> of trials, compared with <strong>42.6%</strong> for task-driven sampling. The preferred update also depended on the data budget: an anchored broad update led at 16 transitions, while local revision had lower prediction error at 64.</p>
<p>The next steps develop identifiability diagnostics, an evidence-gated update rule, and evaluations that measure both preservation of unchanged mechanisms and planning quality.</p>


<figure class="rp-figure" style="max-width:350px">
<img src="/images/research/world-models-thumb.webp" alt="Example navigation environment" loading="lazy">
<figcaption>Navigation environment used in the mechanism-adaptation research.</figcaption>
</figure>

<p class="rp-pub"><strong>Dissertation:</strong> <em>Identifiable Mechanism-Factored World Models for Local Adaptation under Structural Shift</em>. Supervisor: Prof. Yassine Yaakoubi, Concordia University.</p>

</div>
