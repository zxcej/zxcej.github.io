---
layout: single
title: "Effect Heredity in Combinatorial Experiments"
permalink: /projects/heredity/
author_profile: true
---

<link rel="stylesheet" href="/assets/css/research.css">
<div class="research-detail">
<a class="rp-back" href="/projects/">← Projects</a>
<p class="rp-kicker">Research · Structure-aware estimation · Experimental design</p>

<p class="rp-lead">A high-order interaction is often linked to lower-order effects. My research examines how <strong>effect heredity</strong> changes what can be estimated from a limited set of experiments, and how to use that structure to decide which experiment to run next.</p>

<h2>Learning interactions from sparse observations</h2>
<p>The project develops estimators and identification results for combinatorial interventions, with empirical studies on drug combinations and protein sequence–function landscapes.</p>
<p>In a fully measured 13-site fluorescent-protein landscape containing 8,192 genotypes, our method reached <strong>0.770 held-out R² from just 64 observed genotypes</strong>, compared with 0.603 for a standard sparse-regression baseline. The lower-budget pattern also appeared in a second assay of the same library.</p>

<figure class="rp-figure">
<img src="/images/research/heredity-sample-recovery.png" alt="Scientific plot from the research: held-out recovery error as the number of observations increases" loading="lazy">
<figcaption>A controlled sample-budget comparison from the research code; lower recovery error is better.</figcaption>
</figure>

<h2>Experimental design for protein landscapes</h2>
<p>At a fixed budget of 2,048 measurements on GB1, an interaction-informed acquisition policy increased held-out R² from <strong>0.324 with uniform sampling to 0.429</strong>. The project uses learned interaction structure to target measurements that will improve recovery, connecting statistical modeling to laboratory design.</p>
<p>Another case concerns a mutation whose average effect is nearly zero, yet whose effect swings substantially in specific genetic backgrounds. It illustrates why small marginal effects do not rule out important interactions.</p>

<p class="rp-pub"><strong>Current work.</strong> A journal manuscript is in preparation. I lead the project, currently with Yassine Yaakoubi and Diaa Azzam.</p>

</div>
