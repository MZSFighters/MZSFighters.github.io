<!-- ---
layout: about
title: about
permalink: /
subtitle: MSc Computer Science · <a href='https://www.wits.ac.za/'>University of the Witwatersrand</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>mzaidmns@gmail.com</p>
    <p>Johannesburg, South Africa</p>
    
  #<p>MSc Computer Science</p>
   # <p>123 your address street</p>
    # <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->

<!-- I am a masters student in computer science at the University of the Witwatersrand, working at the intersection of Artificial Intelligence and Healthcare. My research interests include training, optimizing and applying AI agents to solve problems in the biomedical healthcare domain. I am currently in the process of writing my MSc Thesis and thus looking forward to finish it. -->
 -->



---
layout: about
title: about
permalink: /
subtitle: MSc Computer Science · <a href='https://www.wits.ac.za/'>University of the Witwatersrand</a>

selected_papers: true # selected publications appear below the news
social: false # socials are shown in the profile card instead

announcements:
  enabled: false # the news list below replaces the default one

latest_posts:
  enabled: false
---

<style>
/* ---------- HERO ---------- */
.hero { display: grid; grid-template-columns: 1fr 300px; gap: 2.5rem; align-items: start; margin-top: 0.5rem; }
@media (max-width: 820px) { .hero { grid-template-columns: 1fr; } .hero-card { order: -1; max-width: 340px; margin: 0 auto; } }
.hero-bio p { font-size: 1.05rem; line-height: 1.75; }
.hero-card { border: 1px solid var(--global-divider-color); border-radius: 16px; padding: 1rem; background: var(--global-card-bg-color); text-align: center; }
.hero-card img.photo { width: 100%; aspect-ratio: 4 / 5; object-fit: cover; border-radius: 12px; }
.hero-loc { margin: 0.9rem 0 0.6rem; font-size: 0.95rem; color: var(--global-text-color-light); }
.hero-loc i { color: var(--global-theme-color); margin-right: 0.35rem; }
.hero-social { display: flex; justify-content: center; gap: 0.5rem; flex-wrap: wrap; }
.hero-social a { width: 40px; height: 40px; display: inline-flex; align-items: center; justify-content: center; border-radius: 50%;
  border: 1px solid var(--global-divider-color); color: var(--global-text-color); font-size: 1.1rem; transition: all 0.2s; }
.hero-social a:hover { background: var(--global-theme-color); border-color: var(--global-theme-color); color: #fff; text-decoration: none; }

/* ---------- EDUCATION ---------- */
.edu { display: flex; flex-direction: column; gap: 0.7rem; margin-top: 1.5rem; }
.edu-item { display: flex; align-items: center; gap: 0.9rem; padding: 0.7rem 0.9rem; border-radius: 12px; border: 1px solid var(--global-divider-color); }
.edu-item img { width: 48px; height: 48px; object-fit: contain; background: #fff; border-radius: 10px; padding: 4px; flex-shrink: 0; }
.edu-deg { font-weight: 600; margin: 0; }
.edu-meta { margin: 0; font-size: 0.88rem; color: var(--global-text-color-light); }
.edu-now { font-size: 0.7rem; padding: 0.05rem 0.5rem; border-radius: 999px; background: var(--global-theme-color); color: #fff; margin-left: 0.4rem; vertical-align: middle; }

/* ---------- SECTION HEADINGS ---------- */
.home-h { display: flex; justify-content: space-between; align-items: baseline; margin: 3rem 0 1.2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.4rem; }
.home-h h2 { margin: 0; font-size: 1.6rem; }
.home-h a { font-size: 0.9rem; }

/* ---------- JOURNEY STRIP ---------- */
.jstrip { display: flex; gap: 1rem; overflow-x: auto; padding: 0.5rem 0 1rem; scroll-snap-type: x mandatory; position: relative; }
.jstep { flex: 0 0 190px; scroll-snap-align: start; position: relative; padding-top: 1.6rem; }
.jstep::before { content: ""; position: absolute; top: 0.45rem; left: 0; right: -1rem; height: 2px; background: var(--global-divider-color); }
.jstep:last-child::before { right: 50%; }
.jstep::after { content: ""; position: absolute; top: 0; left: 0; width: 16px; height: 16px; border-radius: 50%;
  background: var(--global-theme-color); box-shadow: 0 0 0 4px var(--global-bg-color); }
.jstep img { width: 44px; height: 44px; object-fit: contain; background: #fff; border-radius: 10px; padding: 4px; margin-bottom: 0.5rem; }
.jdate { font-size: 0.8rem; color: var(--global-theme-color); font-weight: 600; margin: 0; }
.jtitle { font-size: 0.92rem; margin: 0.15rem 0 0; line-height: 1.4; }

/* ---------- NEWS WITH THUMBNAILS ---------- */
.news-list { display: flex; flex-direction: column; gap: 0.8rem; }
.news-item { display: flex; gap: 1rem; align-items: center; padding: 0.7rem; border-radius: 12px; border: 1px solid var(--global-divider-color); }
.news-thumb { width: 84px; height: 64px; object-fit: cover; border-radius: 8px; flex-shrink: 0; background: #fff; }
.news-thumb.logo { object-fit: contain; padding: 6px; }
.news-date { font-size: 0.8rem; color: var(--global-text-color-light); margin: 0; }
.news-text { margin: 0; }
.news-text p { margin: 0; display: inline; }
</style>

<div class="hero">
<div class="hero-bio">
<p>I am an MSc Computer Science student at the University of the Witwatersrand, working at the intersection of <strong>artificial intelligence and healthcare</strong>. My research focuses on training, optimising and applying <strong>AI agents and language models</strong> to problems in the biomedical domain. Most recently, I have worked on using small open-weight language models to screen and appraise scientific literature in microbial oncogenesis.</p>
<p>I am currently completing my MSc thesis and am <strong>applying to PhD programmes</strong> starting in 2027.</p>
<div class="edu">
<div class="edu-item">
<img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="Wits logo">
<div><p class="edu-deg">MSc Computer Science <span class="edu-now">Current</span></p><p class="edu-meta">University of the Witwatersrand · 20XX – present</p></div>
</div>
<div class="edu-item">
<img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="University logo">
<div><p class="edu-deg">[Previous degree, e.g. BSc (Hons) Computer Science]</p><p class="edu-meta">[University] · 20XX – 20XX</p></div>
</div>
</div>
</div>
<div class="hero-card">
<img class="photo" src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Mohammad Zaid Moonsamy">
<p class="hero-loc"><i class="fa-solid fa-location-dot"></i>Johannesburg, South Africa</p>
<div class="hero-social">
<a href="mailto:YOUR_EMAIL@example.com" title="Email"><i class="fa-solid fa-envelope"></i></a>
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN" title="LinkedIn" target="_blank"><i class="fa-brands fa-linkedin-in"></i></a>
<a href="https://github.com/YOUR_GITHUB" title="GitHub" target="_blank"><i class="fa-brands fa-github"></i></a>
<a href="https://scholar.google.com/citations?user=YOUR_ID" title="Google Scholar" target="_blank"><i class="ai ai-google-scholar"></i></a>
<a href="https://orcid.org/YOUR_ORCID" title="ORCID" target="_blank"><i class="ai ai-orcid"></i></a>
<a href="{{ '/cv/' | relative_url }}" title="CV"><i class="fa-solid fa-file-lines"></i></a>
</div>
</div>
</div>

<div class="home-h"><h2>journey</h2><a href="{{ '/journey/' | relative_url }}">Full journey →</a></div>
<div class="jstrip">
<div class="jstep">
<img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
<p class="jdate">20XX</p><p class="jtitle">Started MSc Computer Science at Wits</p>
</div>
<div class="jstep">
<img src="{{ '/assets/img/logos/saicsit.png' | relative_url }}" alt="">
<p class="jdate">Jul 2026</p><p class="jtitle">First-author paper at SAICSIT 2026, Cape Town</p>
</div>
<div class="jstep">
<img src="{{ '/assets/img/logos/frontiers.png' | relative_url }}" alt="">
<p class="jdate">2026</p><p class="jtitle">Co-authored paper in Frontiers in Cellular and Infection Microbiology</p>
</div>
<div class="jstep">
<img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
<p class="jdate">Oct 2026</p><p class="jtitle">3rd place, Best Research Presentation, Wits Faculty of Science</p>
</div>
<div class="jstep">
<img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt="">
<p class="jdate">Nov 2026</p><p class="jtitle">Applying to PhD programmes</p>
</div>
</div>

<div class="home-h"><h2>news</h2></div>
<div class="news-list">
{%- assign news_items = site.news | sort: "date" | reverse -%}
{%- for item in news_items limit: 5 -%}
<div class="news-item">
{%- if item.thumbnail -%}<img class="news-thumb{% if item.thumbnail_is_logo %} logo{% endif %}" src="{{ item.thumbnail | relative_url }}" alt="">{%- endif -%}
<div>
<p class="news-date">{{ item.date | date: "%b %-d, %Y" }}</p>
{%- if item.inline -%}
<div class="news-text">{{ item.content }}</div>
{%- else -%}
<p class="news-text"><a href="{{ item.url | relative_url }}">{{ item.title }}</a></p>
{%- endif -%}
</div>
</div>
{%- endfor -%}
</div>