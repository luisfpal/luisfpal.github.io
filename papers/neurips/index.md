---
layout: default
title: NeurIPS 2026
---

<p class="path"><a href="{{ '/' | relative_url }}">~/</a><a href="{{ '/papers/' | relative_url }}">papers/</a>neurips/</p>

<p class="claim">Visual instruction tuning writes visual features into the middle of a language model, where the model already abstracts text. The early layers stay on their own modality. Tuning only that middle band, on LLaVA-7B and OneVision-4B, matches full fine-tuning on the vision benchmarks and takes less training time.</p>

<figure class="paper-figure">
  <img src="{{ '/assets/img/abstraction.png' | relative_url }}" alt="Figure 1 from the paper. An image and a caption of the same scene are compared across the layers of the language model.">
  <figcaption>
    An image and a caption of the same scene. They meet in the intermediate layers.<br>
    Figure from Palacios, Basile, Doimo, and Cazzaniga, arXiv:2606.03871, CC BY 4.0.
  </figcaption>
</figure>

<h2 class="paper-title">Visual Instruction Tuning Aligns Modalities through Abstraction</h2>

<p class="byline">Luis Palacios*, Lorenzo Basile*, Diego Doimo, Alberto Cazzaniga.</p>

<p class="venue">Accepted as a poster, NeurIPS 2026. <a href="https://arxiv.org/abs/2606.03871">Preprint</a>. <a href="{{ '/theses/dsai.pdf' | relative_url }}">📄 Thesis</a>.</p>

<p class="note">* Equal contribution.</p>

<p class="role">The paper began as my master's thesis at the Laboratory of Data Engineering, Area Science Park. Lorenzo Basile, Diego Doimo, and Alberto Cazzaniga designed the core experiments. I developed the codebase and ran the experiments with Lorenzo Basile and Diego Doimo.</p>
