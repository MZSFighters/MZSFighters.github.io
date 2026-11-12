---
layout: page
title: Dutch-Afrikaans NER
description: Cross-lingual transfer from Dutch to Afrikaans for named entity recognition with BERT
img: assets/img/NER.png
importance: 5
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
<a href="https://github.com/MZSFighters/Dutch-Afrikaans-NER" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
<a href="{{ '/assets/pdf/NER.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> Report</a>
</div>
<div class="pj-meta" style="margin-top: 0;">
<p class="pj-date">Aug 2024 – Sep 2024</p>
</div>
</div>

### Abstract
Despite recent advances in Natural Language Processing, there remains a significant gap in language models for African languages, including Afrikaans. This paper presents BERTaal, a novel approach to Named Entity Recognition (NER) in Afrikaans using transfer learning from Dutch. Leveraging the linguistic similarities between Dutch and Afrikaans, we fine-tune the Dutch pre-trained model BERTje through a twostage process: first with masked language modeling on an Afrikaans Wikipedia corpus, followed by task-specific fine-tuning on an Afrikaans NER dataset. Our results demonstrate that BERTaal achieves 94% accuracy and a weighted F1-score of 0.94, outperforming a baseline model fine-tuned solely on the NER task. Through detailed attention map analysis, we uncover and address key patterns in the model’s behavior, including the impact of dataset structure on attention mechanisms. This work not only presents a practical solution for Afrikaans NER but also provides insights into effective transfer learning strategies for low-resource languages with linguistic similarities to better-resourced languages.

{% include figure.liquid path="assets/img/NER.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">Attention heatmap - BERT</div>

### My contribution
In this group project, I led the technical implementation and wrote much of the codebase, including the initial fine-tuning of a Dutch BERT model with masked language modelling. I also carried out extensive preprocessing of both the Afrikaans Wikipedia corpus and the Afrikaans named entity recognition dataset, and co-wrote the final report with the group.