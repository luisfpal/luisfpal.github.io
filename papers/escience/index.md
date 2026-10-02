---
layout: default
title: IEEE eScience 2026
---

<p class="path"><a href="{{ '/' | relative_url }}">~/</a><a href="{{ '/papers/' | relative_url }}">papers/</a>escience/</p>

<h2 class="paper-title">Building Service Layers Above Research Cyberinfrastructure</h2>

<p class="byline">Luis Fernando Palacios Flores, Federica Bazzocchi, Tommaso Rodani.</p>

<p class="venue">Submitted to IEEE eScience 2026. Not accepted. The review wanted throughput experiments the paper did not have.</p>

<p>Two separate services on the same research facility. One is a generator: machine-learning services that share a structure are deployed the same way. The working example classifies scanning-electron-microscope images. The other is a web app for storage and governance. The plan was to join them later. I left before that.</p>

<p>Both were deployed and worked. They were not tuned for throughput. The storage app is still on the public site.</p>

<p class="entry-links">
  <a href="{{ '/papers/escience/paper.pdf' | relative_url }}">📄 pdf</a>
  <a href="https://github.com/luisfpal/s3bucket-manager-app">storage code</a>
  <a href="https://buckets-explorer.areasciencepark.it/">storage site</a>
  <a href="https://github.com/luisfpal/sem-image-classifier-api">generator code</a>
</p>
