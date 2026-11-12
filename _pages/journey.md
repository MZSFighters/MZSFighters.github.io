---
layout: page
title: Journey
permalink: /journey/
nav: true
nav_order: 2
---

<style>
.timeline { position: relative; margin: 2rem 0; padding-left: 2rem; border-left: 2px solid var(--global-divider-color); }
.tl-item { position: relative; margin-bottom: 2.5rem; display: flex; gap: 1.2rem; align-items: flex-start; }
.tl-item::before { content: ""; position: absolute; left: calc(-2rem - 8px); top: 1.4rem; width: 14px; height: 14px;
  border-radius: 50%; background: var(--global-theme-color); box-shadow: 0 0 0 4px var(--global-bg-color); }
.tl-logo { width: 64px; height: 64px; object-fit: contain; flex-shrink: 0; background: #fff; border-radius: 12px; padding: 6px;
  box-shadow: 0 0 0 2px var(--global-theme-color), 0 4px 12px rgba(0,0,0,0.4); }
.tl-body { flex: 1; min-width: 0; }
.tl-date { font-size: 0.85rem; color: var(--global-text-color-light); }
.tl-tag { display: inline-block; font-size: 0.7rem; padding: 0.1rem 0.5rem; margin-left: 0.4rem; border-radius: 999px;
  border: 1px solid var(--global-theme-color); color: var(--global-theme-color); }
.tl-title { font-weight: 600; margin: 0.2rem 0; }
.tl-desc { margin: 0 0 0.3rem; }
.tl-more { font-size: 0.9rem; }
.tl-thumb { width: 200px; height: 130px; object-fit: cover; flex-shrink: 0; border-radius: 10px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.45); transition: transform 0.2s; }
.tl-thumb:hover { transform: scale(1.03); }
@media (max-width: 700px) {
  .tl-item { flex-wrap: wrap; }
  .tl-thumb { width: 100%; height: 180px; order: 3; }
}
</style>

<div class="timeline">


  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.jpeg' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Oct 2026 <span class="tl-tag">Award</span></div>
    <p class="tl-title">3rd Place, Best Research Presentation</p>
    <p class="tl-desc">Wits Faculty of Science Research Showcase 2026</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>


  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/frontiers.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Aug 2026<span class="tl-tag">Publication</span></div>
    <p class="tl-title">Co-authored paper in Frontiers in Cellular and Infection Microbiology</p>
    <p class="tl-desc"><a href="https://www.frontiersin.org/journals/cellular-and-infection-microbiology/articles/10.3389/fcimb.2026.1876326/full" target="_blank"><em>Artificial intelligence can match domain experts in evidence extraction and critical appraisal of microbial oncogenesis research publications</em></a></p>
    </div>
  </div>

  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/saicsit2026.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jul 2026 <span class="tl-tag">Conference</span> <span class="tl-tag">Award</span></div>
<p class="tl-title">🏆 Best Paper Award (Computer Science Track), SAICSIT 2026</p>
<p class="tl-desc">First-author paper, presented in Cape Town: <a href="https://arxiv.org/abs/2512.06502" target="_blank"><em>Democratizing Discovery: Cost-Efficient Scientific Literature Screening with Open-Weight SLMs</em></a></p>
    <!-- <div class="tl-date">Jul 2026 <span class="tl-tag">Conference</span></div>
    <p class="tl-title">Presented first-author research paper at SAICSIT (South African Institute of Computer Scientists and Information Technologists) 2026</p>
    <p class="tl-desc">Paper Titled: "Democratizing Discovery: Cost-Efficient Scientific Literature Screening with Open-Weight SLMs"</p>
    <ul class="tl-awards">
    <li>🏅 Best Paper in Computer Science Track Award</li>
    </ul> -->
    </div>
  </div>


  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/epfl.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jun 2025 - Aug 2025 <span class="tl-tag">Internship</span></div>
    <p class="tl-title">Summer@EPFL research intern</p>
    <p class="tl-desc">Research internship in the LiGHT Lab, supervised by Dr Trevor Brokowski. Built LLM and RAG components for Mam-AI, an offline, on-device app that gives midwives in Zanzibar instant access to clinical guidelines.</p>
    <a class="tl-more" href="{{ '/projects/2_project/' | relative_url }}">See project →</a>
    </div>
  </div>

  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jan 2025 - present <span class="tl-tag">Education</span></div>
    <p class="tl-title">Started MSc Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Supervised by Prof Bruce Bassett and Prof Richard Klein, working on Small Language Models (SLMs), contradiction detection and large-scale deployment for Microbe-Cancer pair discovery.</p>
    <!-- </div> -->
    <ul class="tl-awards">
    <li>🏅 MSc Fellowship 2025-2026</li>
    <li>🏅 Postgraduate Merit Award, 2025, 2026</li>
    </ul>
    </div>
  </div>
  
  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.jpeg' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jan 2024 - Nov 2024<span class="tl-tag">Education</span></div>
    <p class="tl-title">BSc (Hons) Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Graduated with Distinction (Cum Laude)</p>
    <p class="tl-desc">Courses: Artificial Intelligence, Machine Learning, Natural Language Processing, Computer Vision, Probabilistic Graphical Models, Applications of Algorithms and Robotics.</p>
    <p class="tl-desc">Research Project: Semi-automated grading of free-text computer science answers (Supervised by Prof Richard Klein)</p>
    <ul class="tl-awards">
    <li>🏅 Postgraduate Merit Award, 2024</li>
    <li>🏅 Dean's List, 2024</li>
    </ul>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div> 

  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/golden_key.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">2022<span class="tl-tag">Award</span></div>
    <p class="tl-title">Golden Key Honour Society Member</p>
    <p class="tl-desc">Awarded to students who rank in the top 15% of their academic class based on their overall university performance</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div> 


  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.jpeg' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jan 2021 - Nov 2023<span class="tl-tag">Education</span></div>
    <p class="tl-title">BSc Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Graduated with A (aggregate)</p>
    <ul class="tl-awards">
    <li>🏅 University Entrance Scholarship, 2021</li>
    <li>🏅 Finalist in Wits Mathematics Competition, 2021</li>
    <li>🏅 Dean's List, 2021</li>
    <li>🏅 University Council Merit Scholarship, 2022</li>
    <li>🏅 Postgraduate Merit Award, 2023</li>
    </ul>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>  

</div>