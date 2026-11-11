---
layout: page
title: other
permalink: /other/
description: Teaching, workshops and volunteer work.
nav: true
nav_order: 6
---

<style>
.ow-section { margin: 2.5rem 0 1rem; font-weight: 600; border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.3rem; }
.ow-card { display: flex; gap: 1rem; padding: 1.1rem 1.2rem; margin-bottom: 1rem; border-radius: 10px;
  border: 1px solid var(--global-divider-color); background: var(--global-card-bg-color); }
.ow-logo { width: 52px; height: 52px; object-fit: contain; flex-shrink: 0; background: #fff; border-radius: 10px; padding: 5px; }
.ow-body { flex: 1; }
.ow-title { font-weight: 600; margin: 0; }
.ow-meta { font-size: 0.85rem; color: var(--global-text-color-light); margin: 0.15rem 0 0.5rem; }
.ow-desc { margin: 0; }
.ow-photo { width: 100%; max-width: 380px; border-radius: 8px; margin-top: 0.7rem; }
.ow-links a { font-size: 0.85rem; margin-right: 0.8rem; }
</style>

<h3 class="ow-section">Teaching &amp; Lectures</h3>

<div class="ow-card">
  <img class="ow-logo" src="{{ '/assets/img/logos/university.png' | relative_url }}" alt="">
  <div class="ow-body">
    <p class="ow-title">Guest Lecture: [Lecture Title]</p>
    <p class="ow-meta">[Course name / audience] · [University] · [Month 2026]</p>
    <p class="ow-desc">[One or two sentences: what you taught, to whom, how many students.]</p>
    <div class="ow-links"><a href="{{ '/assets/pdf/lecture-slides.pdf' | relative_url }}">Slides</a></div>
  </div>
</div>

<h3 class="ow-section">Workshops</h3>

<div class="ow-card">
  <img class="ow-logo" src="{{ '/assets/img/logos/organisation.png' | relative_url }}" alt="">
  <div class="ow-body">
    <p class="ow-title">[Workshop Title]</p>
    <p class="ow-meta">[Role: Facilitator / Speaker / Participant] · [Organiser] · [Month Year]</p>
    <p class="ow-desc">[What the workshop covered and what you did.]</p>
  </div>
</div>

<h3 class="ow-section">Volunteering</h3>

<div class="ow-card">
  <img class="ow-logo" src="{{ '/assets/img/logos/organisation.png' | relative_url }}" alt="">
  <div class="ow-body">
    <p class="ow-title">[Role], [Organisation]</p>
    <p class="ow-meta">[Start – End]</p>
    <p class="ow-desc">[What you did and the impact, e.g. "Mentored 30 high-school learners in Python".]</p>
    <img class="ow-photo" src="{{ '/assets/img/events/volunteer-1.jpg' | relative_url }}" alt="">
  </div>
</div>