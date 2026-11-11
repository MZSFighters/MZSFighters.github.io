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
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Oct 2026 <span class="tl-tag">Award</span></div>
    <p class="tl-title">3rd Place, Best Research Presentation</p>
    <p class="tl-desc">Wits Faculty of Science Research Showcase 2026. Presented my MSc research on [topic].</p>
    </div>
    <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase">
  </div>

  <div class="tl-item">
    <div class="tl-date">Jul 2026 <span class="tl-tag">Award</span></div>
    <p class="tl-title">Best Paper Award at SAICSIT 2026</p>
    <p class="tl-desc">Awarded for best paper in the computer science track</p>
  </div>

  <div class="tl-item">
    <div class="tl-date">Jul 2026 <span class="tl-tag">Presentation</span></div>
    <p class="tl-title">Presented my MSc work at SAICSIT (South African Institute of Computer Science and Information Technologies) 2026</p>
    <p class="tl-desc">Titled: "Democratizing Discovery: Cost-Efficient Scientific Literature Screening with Open-Weight SLMs"</p>
  </div>

  <div class="tl-item">
    <div class="tl-date">2025 <span class="tl-tag">Award</span></div>
    <p class="tl-title">[Award / Scholarship name]</p>
    <p class="tl-desc">Awarded for [reason].</p>
  </div>

  <div class="tl-item">
    <div class="tl-date">Jan 2025 <span class="tl-tag">Education</span></div>
    <p class="tl-title">Started MSc Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Supervised by Prof Bruce Bassett and Prof Richard Klein, working on Small Language Models (SLMs), contradiction detection and large-scale deployment for Microbe-Cancer pair discovery.</p>
  </div>
  
  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jan 2024 - Nov 2024<span class="tl-tag">Education</span></div>
    <p class="tl-title">BSc (Hons) Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Courses: Artificial Intelligence, Machine Learning, Natural Language Processing, Computer Vision, Probabilistic Graphical Models, Applications of Algorithms and Robotics.</p>
    <p class="tl-desc">Research Project: Semi-automated grading of free-text computer science answers</p>
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
    <!-- <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt=""> -->
    <!-- <div class="tl-body"> -->
    <div class="tl-date">Jan 2022<span class="tl-tag">Award</span></div>
    <p class="tl-title">University Council Merit Scholarship</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>  

  <div class="tl-item">
    <!-- <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt=""> -->
    <!-- <div class="tl-body"> -->
    <div class="tl-date">2021<span class="tl-tag">Award</span></div>
    <p class="tl-title">Dean's List</p>
    <p class="tl-desc">Awarded to top 5% students</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>  

  <div class="tl-item">
    <!-- <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt=""> -->
    <!-- <div class="tl-body"> -->
    <div class="tl-date">2021<span class="tl-tag">Award</span></div>
    <p class="tl-title">Finalist in Wits Mathematics Competition 2021</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>  

  <div class="tl-item">
    <!-- <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt=""> -->
    <!-- <div class="tl-body"> -->
    <div class="tl-date">2021<span class="tl-tag">Award</span></div>
    <p class="tl-title">University Entrance Scholarship</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase">
  </div>   -->

  <div class="tl-item">
    <img class="tl-logo" src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
    <div class="tl-body">
    <div class="tl-date">Jan 2021 - Nov 2023<span class="tl-tag">Education</span></div>
    <p class="tl-title">BSc Computer Science, University of the Witwatersrand</p>
    <p class="tl-desc">Majors: Computer Science and Computer Applications</p>
    </div>
    <!-- <img class="tl-thumb" src="{{ '/assets/img/events/showcase-2026.jpg' | relative_url }}" alt="Presenting at the Wits research showcase"> -->
  </div>  

</div>