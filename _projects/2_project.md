---
layout: page
title: Mam-AI
description: Offline edge-device LLM assistant supporting midwives in Zanzibar. Summer@EPFL project
img: assets/img/mam-ai.png
importance: 3
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
<a href="https://github.com/MZSFighters/Mam-AI" target="_blank"><i class="fa-brands fa-github"></i> Code</a>
<a href="https://www.kaggle.com/competitions/google-gemma-3n-hackathon/writeups/light-mam-ai" target="_blank"><i class="fa-brands fa-kaggle"></i> Kaggle Google Gemma Challenge</a>
<!-- <a href="https://arxiv.org/abs/..." target="_blank"><i class="ai ai-arxiv"></i> Preprint</a> -->
<a href="{{ '/assets/pdf/Mam-AI-Report.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf"></i> Technical Report</a>
</div>
<div class="pj-meta">
<div class="pj-logos">
<img src="{{ '/assets/img/logos/light.png' | relative_url }}" alt="LiGHT Lab">
<img src="{{ '/assets/img/logos/epfl.png' | relative_url }}" alt="EPFL">
</div>
<p class="pj-date">Jun 2025 – Aug 2025</p>
</div>
</div>

### Abstract

Zanzibar experiences unacceptably high rates of maternal and newborn mortality, primarily due to lack of information at the point of care. MAM-AI is an offline-first, privacy-preserving, clinical smart-search app designed to support nurses and midwives in Zanzibar for neonatal care. The key challenge of these nurses is information scarcity - doctors and supervisors are often far away and unavailable. MAM-AI addresses this by putting easy summaries of gold-standard clinical guidelines right in the hands of the nurses in need at the point of care. Nurses type their queries into the search bar, the app searches through the guidelines, and they receive a summary of the relevant clinical information. MAM-AI aims to reduce preventable maternal and neonatal deaths by democratizing access to expert medical information at the point of care.

<a class="pj-video" href="https://www.youtube.com/watch?v=VIDEO_ID" target="_blank">
<img src="https://www.youtube.com/watch?v=ks5fF-1xY4M&t=2s" alt="Mam-AI demo video">
<span class="pj-play"><i class="fa-solid fa-play"></i></span>
</a>
<div class="caption">Mam-AI app in action (If video does not work, please check it out on the Google gemma 3n kaggle challenge link above)</div>

### My contribution
[One to three sentences with concrete verbs: built, designed, evaluated, deployed.]