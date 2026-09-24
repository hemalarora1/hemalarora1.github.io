---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items

latest_posts:
  enabled: false
---

<style>
  html { scroll-behavior: smooth; }
  .post-title, .section h2 { font-weight: 700; }
  .section { clear: both; }
  .section h2 { scroll-margin-top: 7rem; margin-bottom: 2rem; }
  .section hr { margin: 3rem 0 2rem; }
  .links { font-family: monospace; margin-top: 2rem; }
  .callout { border-left: 3px solid var(--global-theme-color); padding-left: 1rem; margin: 1.5rem 0; color: var(--global-text-color-light); }

  .entry-card { display: flex; gap: 2rem; margin-bottom: 3rem; }
  .entry-thumb { flex: 0 0 34%; }
  .entry-thumb img, .entry-thumb-placeholder { width: 100%; aspect-ratio: 16 / 9; object-fit: cover; border-radius: 8px; border: 1px solid var(--global-divider-color); }
  .entry-thumb-placeholder { background: color-mix(in srgb, var(--global-theme-color) 10%, transparent); }
  .entry-body { flex: 1; min-width: 0; }
  .entry-title { font-size: 1.3rem; font-weight: 700; line-height: 1.3; margin: 0 0 0.4rem; color: var(--global-text-color); }
  .entry-subtitle { font-weight: 500; margin-bottom: 0.3rem; }
  .entry-authors { color: var(--global-text-color-light); margin-bottom: 0.6rem; }
  .entry-authors strong { color: var(--global-text-color); font-weight: 800; }
  .entry-meta { display: flex; flex-wrap: wrap; align-items: center; gap: 0.75rem; margin-bottom: 0.75rem; font-size: 0.9rem; color: var(--global-text-color-light); }
  .entry-venue { font-family: monospace; font-weight: 600; padding: 0.1rem 0.6rem; border-radius: 4px; border: 1px solid var(--global-theme-color); color: var(--global-theme-color); }
  .entry-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 0.75rem; }
  .entry-tags span { font-size: 0.78rem; font-weight: 500; padding: 0.15rem 0.65rem; border-radius: 999px; background: color-mix(in srgb, var(--global-theme-color) 14%, transparent); color: var(--global-theme-color); }
  .entry-links { font-family: monospace; margin-bottom: 0.6rem; }
  .entry-links a { margin-right: 1.25rem; }
  .entry-links a::after { content: " ↗"; font-size: 0.8em; }
  .entry-desc { color: var(--global-text-color); opacity: 0.78; line-height: 1.65; margin: 0; }
  @media (max-width: 640px) {
    .entry-card { flex-direction: column; gap: 1rem; }
  }
</style>

Hi! I'm Hemal, a senior at Stanford studying Electrical Engineering. I'm an undergraduate researcher at the [Interactive Perception and Robot Learning Lab](https://iprl.stanford.edu/), advised by Prof. Jeannette Bohg.

I'm interested in robotics, simulation, and learning for perception and control. I enjoy working on problems at the intersection of research and engineering: developing new methods, building end-to-end systems, and testing them on real hardware.

<p class="callout">Looking for Summer 2027 research/engineering opportunities in Robotics and Physical AI.</p>

<p class="links">
  <a href="https://www.linkedin.com/in/hemalarora/">LinkedIn</a>&emsp;
  <a href="mailto:hemal1@stanford.edu">Email</a>&emsp;
  <a href="/assets/pdf/hemal_arora_resume.pdf">CV</a>&emsp;
  <a href="https://scholar.google.com/citations?user=JMMxOTwAAAAJ">Google Scholar</a>&emsp;
  <a href="https://github.com/hemalarora1">GitHub</a>
</p>

<div class="section">
<hr>
<h2 id="work">Selected Work</h2>
{% for entry in site.data.work %}{% include entry_card.liquid entry=entry %}{% endfor %}
</div>

<div class="section">
<hr>
<h2 id="research">Research</h2>
{% for entry in site.data.research %}{% include entry_card.liquid entry=entry %}{% endfor %}
</div>
