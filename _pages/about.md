---
layout: about
title: About
permalink: /
subtitle: MSc Computer Science · <a href='https://www.wits.ac.za/'>University of the Witwatersrand</a>

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   more_info: >
#     <p>mzaidmns@gmail.com</p>
#     <p>Johannesburg, South Africa</p>
    
#   #<p>MSc Computer Science</p>
#    # <p>123 your address street</p>
#     # <p>Your City, State 12345</p>

# selected_papers: false # includes a list of papers marked as "selected={true}"
# social: true # includes social icons at the bottom of the page

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <div class="pc-info">
    <p class="pc-loc"><i class="fa-solid fa-location-dot"></i> Johannesburg, South Africa</p>
    <div class="pc-social">
    <a class="pc-mail" href="mailto:mzaidmns@gmail.com" title="Email"><i class="fa-solid fa-envelope"></i></a>
    <a class="pc-li" href="https://www.linkedin.com/in/mohammad-zaid-moonsamy-7214a7284/" target="_blank" title="LinkedIn"><i class="fa-brands fa-linkedin-in"></i></a>
    <a class="pc-gh" href="https://github.com/MZSFighters" target="_blank" title="GitHub"><i class="fa-brands fa-github"></i></a>
    <a class="pc-gs" href="https://scholar.google.com/citations?user=2Cyte0QAAAAJ" target="_blank" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
    <a class="pc-orcid" href="https://orcid.org/0009-0006-5321-8179" target="_blank" title="ORCID"><i class="ai ai-orcid"></i></a>
    </div>
    </div>


selected_papers: false
social: false

# announcements:
#   enabled: true # includes a list of news items
#   scrollable: true # adds a vertical scroll bar if there are more than 3 news items
#   limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

<!-- Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->

<!-- I am a masters student in computer science at the University of the Witwatersrand, working at the intersection of Artificial Intelligence and Healthcare. My research interests include training, optimizing and applying AI agents to solve problems in the biomedical healthcare domain. I am currently in the process of writing my MSc Thesis and thus looking forward to finish it. -->
I am an MSc Computer Science student at the University of the Witwatersrand, working at the intersection of artificial intelligence and healthcare. My research focuses on training, optimising and applying AI agents to problems in healthcare and the biomedical domain, from AI-assisted scientific discovery to offline clinical decision support. I am currently completing my MSc thesis.

<style>
.home-h { display: flex; justify-content: space-between; align-items: baseline; margin: 3rem 0 1.2rem; border-bottom: 1px solid var(--global-divider-color); padding-bottom: 0.4rem; }
.home-h h2 { margin: 0; font-size: 1.6rem; }
.home-h a { font-size: 0.9rem; }
.jstrip { display: flex; gap: 1rem; overflow-x: auto; padding: 0.5rem 0 1rem; }
.jstep { flex: 0 0 210px; position: relative; padding-top: 1.6rem; }
.jstep::before { content: ""; position: absolute; top: 0.45rem; left: 0; right: -1rem; height: 2px; background: var(--global-divider-color); }
.jstep:last-child::before { right: 50%; }
.jstep::after { content: ""; position: absolute; top: 0; left: 0; width: 16px; height: 16px; border-radius: 50%; background: var(--global-theme-color); }
.jstep img { width: 72px; height: 72px; object-fit: contain; background: #fff; border-radius: 14px; padding: 8px; margin-bottom: 0.6rem; box-shadow: 0 0 0 2px var(--global-theme-color), 0 4px 14px rgba(0,0,0,0.45); }
.jdate { font-size: 0.8rem; color: var(--global-theme-color); font-weight: 600; margin: 0; }
.jtitle { font-size: 0.92rem; margin: 0.15rem 0 0; line-height: 1.4; }
.news-list { display: flex; flex-direction: column; gap: 0.8rem; }
.news-item { display: flex; gap: 1rem; align-items: center; padding: 0.7rem; border-radius: 12px; border: 1px solid var(--global-divider-color); }
.news-thumb { width: 110px; height: 80px; object-fit: cover; border-radius: 10px; flex-shrink: 0; background: #fff; box-shadow: 0 0 0 1px var(--global-divider-color), 0 4px 12px rgba(0,0,0,0.4); }
.news-thumb.logo { object-fit: contain; padding: 8px; }
.news-date { font-size: 0.8rem; color: var(--global-text-color-light); margin: 0; }
.news-text p { margin: 0; display: inline; }
.pc-info, .pc-info p { text-align: center; font-family: inherit !important; margin-top: 0.8rem; }
.pc-loc { font-size: 0.95rem; margin: 0 0 0.8rem !important; color: var(--global-text-color-light); }
.pc-loc i { color: var(--global-theme-color); margin-right: 0.3rem; }
.pc-social { display: flex; justify-content: center; flex-wrap: wrap; gap: 0.6rem; }
.pc-social a { width: 40px; height: 40px; border-radius: 50%; display: inline-flex; align-items: center; justify-content: center;
  font-size: 1.1rem; text-decoration: none; color: var(--global-text-color) !important;
  border: 1px solid var(--global-divider-color); transition: all 0.2s; }
.pc-social a:hover { color: #fff !important; transform: translateY(-2px); }
.pc-mail:hover { background: #ea4335; border-color: #ea4335; }
.pc-li:hover { background: #0a66c2; border-color: #0a66c2; }
.pc-gh:hover { background: #24292f; border-color: #24292f; }
.pc-gs:hover { background: #4285f4; border-color: #4285f4; }
.pc-orcid:hover { background: #a6ce39; border-color: #a6ce39; }
</style>

<div class="home-h"><h2>Journey</h2><a href="{{ '/journey/' | relative_url }}">Full journey →</a></div>
<div class="jstrip">
<div class="jstep"><img src="{{ '/assets/img/logos/wits.jpeg' | relative_url }}" alt=""><p class="jdate">Jan 2025</p><p class="jtitle">Started MSc Computer Science, University of the Witwatersrand, Johannesburg, South Africa</p></div>
<div class="jstep"><img src="{{ '/assets/img/logos/epfl.png' | relative_url }}" alt=""><p class="jdate">June 2025</p><p class="jtitle">Summer@EPFL research intern, Lausanne, Switzerland</p></div>
<div class="jstep"><img src="{{ '/assets/img/logos/saicsit2026.png' | relative_url }}" alt=""><p class="jdate">Jul 2026</p><p class="jtitle">Best Paper Award, SAICSIT 2026 (first author), Cape Town, South Africa</p></div>
<div class="jstep"><img src="{{ '/assets/img/logos/frontiers.png' | relative_url }}" alt=""><p class="jdate">Aug 2026</p><p class="jtitle">Co-authored paper in Frontiers in Cellular and Infection Microbiology</p></div>
<div class="jstep"><img src="{{ '/assets/img/logos/wits.jpeg' | relative_url }}" alt=""><p class="jdate">Oct 2026</p><p class="jtitle">3rd place, Best Research Presentation, Wits Faculty of Science</p></div>
<!-- <div class="jstep"><img src="{{ '/assets/img/logos/wits.png' | relative_url }}" alt=""><p class="jdate">Nov 2026</p><p class="jtitle">Applying to PhD programmes</p></div> -->
</div>

<!-- <div class="home-h"><h2>News</h2></div>
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
</div> -->

<div class="home-h"><h2>Recent Publications</h2><a href="{{ '/publications/' | relative_url }}">All publications →</a></div>
<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>