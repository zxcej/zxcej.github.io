---
layout: single
title: "MAGnet — Anatomy-Guided MRI-to-CT Synthesis"
permalink: /projects/magnet/
author_profile: true
---

<link rel="stylesheet" href="/assets/css/research.css">
<div class="research-detail">
<a class="rp-back" href="/projects/">← Projects</a>
<p class="rp-kicker">Medical image analysis · SPIE Medical Imaging 2026</p>

<p class="rp-lead">Synthetic CT images can support MRI-based radiotherapy workflows. MAGnet builds anatomical structure directly into the synthesis model, with separate pathways for bone and soft tissue.</p>

<h2>Mask-guided synthesis</h2>
<p>For my master's thesis, I developed a generative framework that uses automatically generated segmentation masks to guide CT synthesis from MRI. The architecture allocates model capacity to anatomy that matters for medical use, including bone structures needed for radiotherapy planning.</p>
<p>I designed the method, conducted the experiments, and wrote the paper. The evaluation includes clinical imaging data acquired on multiple scanners during my visiting research at Ludwig Maximilian University of Munich.</p>


<figure class="rp-figure">
<img src="/images/research/magnet-qualitative.webp" alt="Comparison of MAGnet with multiple MRI-to-CT methods and their errors" loading="lazy">
<figcaption>Qualitative comparison from the MAGnet imaging study: MRI input, reference CT, synthesized CT from baseline models and corresponding error maps.</figcaption>
</figure>

<p class="rp-pub"><strong>Publication:</strong> Zhu, X. C., Portafaix, A., Cheers, G. M., Mayer-Wagner, S., and Fevens, T. (2026). <em>MAGnet: synthesis of CT images from MRI data with guided segmentation masks.</em> Proceedings of SPIE 13925, 1392522. <a href="https://doi.org/10.1117/12.3086114">Read published paper ↗</a></p>

</div>
