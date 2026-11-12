---
layout: page
title: Microbe-Cancer Pair Discovery
description: An AI co-scientist to detect potential novel microbe-cancer pairs
img: assets/img/mcp.jpg
importance: 1
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
.pj-pubs { list-style: none; padding-left: 0; margin: 0.5rem 0 0; }
.pj-pubs li { padding: 0.8rem 1rem; margin-bottom: 0.7rem; border-radius: 10px; border: 1px solid var(--global-divider-color); }
.pj-pubs .pj-status { display: inline-block; font-size: 0.72rem; padding: 0.1rem 0.55rem; border-radius: 999px; margin-right: 0.4rem;
  border: 1px solid var(--global-theme-color); color: var(--global-theme-color); vertical-align: middle; }
.pj-pubs .pj-venue { font-size: 0.88rem; color: var(--global-text-color-light); }
</style>

<div class="pj-head">
<div class="pj-links">
<a href="https://www.wits.ac.za/idori/projects/microbe-cancer-pairs/" target="_blank"><i class="fa-solid fa-globe"></i> Project Website</a>
<a href="https://arxiv.org/abs/2512.06502" target="_blank"><i class="ai ai-arxiv"></i> Preprint (SAICSIT 2026)</a>
<a href="https://www.frontiersin.org/journals/cellular-and-infection-microbiology/articles/10.3389/fcimb.2026.1876326/full" target="_blank"><i class="fa-solid fa-file-lines"></i> Paper (Frontiers)</a>
</div>
<div class="pj-meta">
<div class="pj-logos">
<img src="{{ '/assets/img/logos/idori.jpeg' | relative_url }}" alt="Wits IDORI">
<img src="{{ '/assets/img/logos/mind.png' | relative_url }}" alt="Wits MIND">
</div>
<p class="pj-date">Jan 2025 – present</p>
</div>
</div>

### Abstract

This project, a joint initiative of Wits IDORI and Wits MIND, applies AI to rank and prioritise research on novel microbial causes of cancer. The discovery of human papillomavirus (HPV) as the main cause of cervical cancer transformed public health oncology, making cervical cancer the first cancer that could potentially be eliminated through infection prevention and treatment.

Today, microbes are estimated to contribute to 1 in 5 cancers worldwide, prompting growing efforts to identify other microbe–cancer pairs (MCPs) with similar potential for prevention. The result is a vast, rapidly expanding body of biomedical literature, far too large for any team to review comprehensively.

We are developing a transparent, validated AI pipeline that automates this process: literature search and retrieval, dataset refinement, and the extraction and synthesis of key findings. By evaluating the strength of evidence for each MCP and combining it with cancer incidence and disease burden, the pipeline generates interpretable plausibility and impact scores, so MCPs can be ranked to guide research priorities and resource allocation. The pipeline is designed to generalise to other causal questions, making large-scale literature assessment more accessible, transparent and reproducible.

{% include figure.liquid path="assets/img/mcps.png" class="img-fluid rounded z-depth-1" zoomable=true %}
<div class="caption">Overview of the AI co-scientist pipeline.</div>

### My contribution

This project forms the basis of my MSc thesis within the Wits IDORI MCP team. I developed the literature screening and classification stage of the pipeline, showing that small open-weight language models can screen biomedical literature with nuanced reasoning at a fraction of the cost of large proprietary models. [Add one more sentence on your role in the wider pipeline, e.g. evidence extraction, contradiction detection, or evaluation.]

So far, the project has produced two publications:

<ul class="pj-pubs">
<li><span class="pj-status">First author · To appear</span><strong>Democratizing Discovery: Cost-Efficient Scientific Literature Screening with Open-Weight SLMs</strong><br>
<span class="pj-venue">SAICSIT 2026, Springer CCIS · <a href="https://arxiv.org/abs/2512.06502" target="_blank">arXiv preprint</a></span></li>
<li><span class="pj-status">Co-author · Published</span><strong>Artificial intelligence can match domain experts in evidence extraction and critical appraisal of microbial oncogenesis research publications</strong><br>
<span class="pj-venue">Frontiers in Cellular and Infection Microbiology, 2026 · <a href="https://www.frontiersin.org/journals/cellular-and-infection-microbiology/articles/10.3389/fcimb.2026.1876326/full" target="_blank">Read paper</a></span></li>
</ul>

See all my papers on the [publications page](/publications/).