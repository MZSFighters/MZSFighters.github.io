---
layout: page
title: Semi-Automated Grading 
description: Clustering student answers to grade free-text responses with less manual marking · BSc Hons project
img: assets/img/auto-grading.png
importance: 4
---

<style>
.pj-head { display: flex; justify-content: space-between; align-items: flex-start; gap: 1rem; flex-wrap: wrap; margin: 0.2rem 0 2rem; }
.pj-links { display: flex; flex-wrap: wrap; gap: 0.5rem; }
.pj-links a { display: inline-flex; align-items: center; gap: 0.4rem; padding: 0.35rem 0.9rem; border-radius: 999px; font-size: 0.9rem;
  border: 1px solid var(--global-theme-color); color: var(--global-theme-color) !important; text-decoration: none; transition: all 0.2s; }
.pj-links a:hover { background: var(--global-theme-color); color: #fff !important; }
.pj-meta { text-align: right; margin-top: -6rem; }
.pj-logos { display: flex; gap: 0.6rem; justify-content: flex-end; }
.pj-logos img { height: 56px; width: auto; max-width: 120px; object-fit: contain; background: #fff; border-radius: 10px; padding: 6px; }
.pj-date { font-size: 0.85rem; color: var(--global-text-color-light); margin: 0.4rem 0 0; }
@media (max-width: 600px) { .pj-meta { text-align: left; margin-top: 0; } .pj-logos { justify-content: flex-start; } }
.pj-video { position: relative; display: block; max-width: 720px; margin: 1.5rem auto 0.5rem; border-radius: 12px; overflow: hidden; }
.pj-video img { width: 100%; display: block; aspect-ratio: 16 / 9; object-fit: cover; transition: transform 0.3s; }
.pj-video:hover img { transform: scale(1.03); }
.pj-video .pj-play { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 72px; height: 72px; border-radius: 50%;
  background: rgba(255, 0, 0, 0.9); display: flex; align-items: center; justify-content: center; color: #fff; font-size: 1.8rem; padding-left: 5px; }
</style>

<div class="pj-head">
<div class="pj-links">
<a href="https://github.com/MZSFighters/auto-grading-of-computer-science-answers" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
<a href="{{ '/assets/pdf/auto-grading.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> Report</a>
</div>
<div class="pj-meta" style="margin-top: 0;">
<p class="pj-date">Jul 2024 – Nov 2024</p>
</div>
</div>

### Abstract
Manual grading of free-text responses in Data Structures and Algorithms (DSA) courses presents a significant challenge for educators, requiring substantial time and resources. This paper introduces a semi-automated grading system that combines Large Language Models (LLMs) with clustering techniques to reduce grading workload while maintaining assessment quality. Our key contribution is a novel Greedy Monte Carlo (GMC) sampling strategy that intelligently selects which submissions to mark manually, while providing confidence metrics for automated grading decisions. We evaluate our system using a dataset of anonymized student responses from a university-level DSA course. Our experiments reveal that BERT embeddings consistently outperform GPT-2 for representing student responses, and k-means clustering provides more reliable cluster distributions compared to hierarchical clustering approaches. The GMC sampling strategy demonstrates superior performance over random sampling, achieving Pearson correlation scores of up to 0.7 with human-assigned grades while requiring significantly fewer manual markings. Importantly, the system provides educators with confidence measures for automated grades, enabling informed decisions about when additional manual grading is necessary. These results suggest that our approach can substantially reduce grading effort while maintaining assessment reliability, offering a practical solution for scaling assessment in computer science education.

{% include figure.liquid path="assets/img/k-means.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">k-means clustering</div>

### My contribution
I am the sole author of this work, completed under the supervision of Prof. Richard Klein.