---
layout: page
title: SLMs for Cost-Efficient Literature Screening
description: Small open-weight language models for biomedical literature screening · Publication 
img: assets/img/slm.png
importance: 2
---

*Part of my MSc project: [AI Co-Scientist for Microbe–Cancer Discovery](/projects/1_project/).*

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
<a href="https://github.com/MZSFighters/MCP" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
<a href="https://arxiv.org/abs/2512.06502" target="_blank"><i class="ai ai-arxiv"></i> Preprint</a>
<!-- <a href="{{ '/assets/pdf/NER.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> </a> -->
</div>
<div class="pj-meta" style="margin-top: 0;">
<!-- <p class="pj-date">Aug 2024 – Sep 2024</p> -->
</div>
</div>

### Abstract
Artificial Intelligence (AI) co-scientists must be able to sift through vast research literature cost-efficiently while applying nuanced scientific reasoning. We evaluate selected Small Language Models (SLMs, ≤ 8B parameters), namely Qwen2.5 and Llama 3, for complex-criteria classification of medical research based on titles and abstracts. As a case study, we curate a dataset with expert labels on the potential of MMTV-like virus to cause breast cancer. We assess model performance on both zero-shot and in-context learning (ICL) strategies against frontier proprietary Large Language Models (LLMs). Gemini 2.5 Pro performed best against all other models on the three-class classification task. However, on the binary classification task, the SLMs achieved performance indistinguishable from Gemini 2.5 Pro. In contrast, GPT-5 (high/low-effort reasoning) performed the worst due to its conservatism. ICL provided statistically significant improvements in F1 (at 97% confidence) for Llama 3, increasing by 13 percentage points on average over zero-shot while Qwen2.5 did not benefit significantly from ICL, already showing strong zero-shot performance. Lexical-ablation experiments show that SLM decisions are often grounded in valid scientific cues but can be influenced by spurious textual artifacts, underscoring the need for interpretability in high-stakes pipelines. Our results reveal both promise and limitations of modern SLMs for scientific triage; pairing SLMs with simple but principled prompting strategies can approach the performance of the strongest LLMs for targeted literature filtering in co-scientist pipelines.

{% include figure.liquid path="assets/img/slm.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">Heatmap of model-technique classifications</div>

### My contribution
I am first author on this work (to appear in Springer CCIS; joint first author on the arXiv preprint). I ran experiments across a range of small language models, tested prompt optimisation techniques, and led the main analysis of the results, including interpreting the performance heatmaps and the precision–sensitivity trade-off when comparing small open-weight models against larger proprietary ones for classifying biomedical literature. The paper received the Best Paper Award (Computer Science Track) at SAICSIT 2026.