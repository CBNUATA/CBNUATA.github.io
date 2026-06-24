---
layout: page
permalink: /
title: Home
---

<h1 style="font-size: clamp(1.3rem, 4.2vw, 2rem); font-weight: bold; margin-bottom: 0.75rem;">Welcome to the Alternative Toxicology &amp; Analytics (ATA) Lab</h1>

<p>I am a Senior Researcher at the Medical Device Evaluation Center, Korea Testing &amp; Research Institute (KTR), where I work on chemical characterization and extractables &amp; leachables (E&amp;L) testing of medical devices in accordance with ISO 10993-18.</p>

<!--
  Photo grid — replace these placeholder paths with your own photos
  once uploaded to assets/img/gallery/
-->
<div style="display: flex; gap: 1rem; margin: 1.5rem 0; flex-wrap: wrap;">
  <img src="{{ '/assets/img/gallery/photo1.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; max-width: 480px; height: 224px; object-fit: cover; flex: 2 1 300px;" alt="Photo 1">
  <div style="display: flex; flex-direction: column; gap: 1rem; flex: 1 1 140px;">
    <img src="{{ '/assets/img/gallery/photo2.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; height: 104px; object-fit: cover;" alt="Photo 2">
    <img src="{{ '/assets/img/gallery/photo3.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; height: 104px; object-fit: cover;" alt="Photo 3">
  </div>
</div>

## News

<div style="display: flex; flex-direction: column; gap: 0.75rem; margin-bottom: 2rem;">
{% assign sorted_news = site.news | sort: 'date' | reverse %}
{% for item in sorted_news limit: 5 %}
  <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
    <strong style="min-width: 110px; flex-shrink: 0;">{{ item.date | date: "%b %d, %Y" }}</strong>
    <span>{{ item.content }}</span>
  </div>
{% endfor %}
</div>

<div style="text-align: center; margin-top: 2rem;">
  <a href="mailto:h.cho@ktr.or.kr" style="margin: 0 0.6rem;">Email</a> ·
  <a href="https://www.linkedin.com/in/hyunki-cho-60b393354" target="_blank" style="margin: 0 0.6rem;">LinkedIn</a> ·
  <a href="https://scholar.google.com/citations?user=QkfTLzUAAAAJ&hl=en" target="_blank" style="margin: 0 0.6rem;">Google Scholar</a> ·
  <a href="https://www.researchgate.net/profile/Hyunki-Cho-2" target="_blank" style="margin: 0 0.6rem;">ResearchGate</a>
</div>
<p style="text-align: center; font-size: 0.9rem; opacity: 0.8; margin-top: 0.5rem;">Senior Researcher, Chemical Characterization Team, KTR Medical Device Evaluation Center</p>
