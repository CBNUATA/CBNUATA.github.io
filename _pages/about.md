cat > _pages/about.md << 'EOF'
---
layout: about
title: Home
permalink: /
subtitle: Senior Researcher, Medical Device Evaluation Center · Korea Testing & Research Institute (KTR)

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Korea Testing &amp; Research Institute (KTR)</p>
    <p>Medical Device Evaluation Center</p>
    <p>Gwacheon, Republic of Korea</p>

selected_papers: false
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
  h1:first-of-type,
  h1:first-of-type + p {
    display: none;
  }
</style>

<div style="margin-bottom: 2rem;">
  <h2 style="font-size: clamp(1.05rem, 3.4vw, 1.5rem); font-weight: bold; margin-bottom: 0.75rem; white-space: nowrap;">Welcome to the Alternative Toxicology &amp; Analytics (ATA) Lab</h2>
  <p>I am a Senior Researcher at the Medical Device Evaluation Center, Korea Testing &amp; Research Institute (KTR), where I work on chemical characterization and extractables &amp; leachables (E&amp;L) testing of medical devices in accordance with ISO 10993-18.</p>
</div>
<<<<<<< HEAD
<<<<<<< HEAD

=======
<!--
  Photo grid — replace these placeholder paths with your own photos
  once uploaded to assets/img/gallery/
-->
<div style="display: flex; gap: 1rem; margin-bottom: 2rem; flex-wrap: wrap;">
  <img src="{{ '/assets/img/gallery/photo1.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; max-width: 480px; height: 224px; object-fit: cover; flex: 2 1 300px;" alt="Photo 1">
  <div style="display: flex; flex-direction: column; gap: 1rem; flex: 1 1 140px;">
    <img src="{{ '/assets/img/gallery/photo2.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; height: 104px; object-fit: cover;" alt="Photo 2">
    <img src="{{ '/assets/img/gallery/photo3.jpg' | relative_url }}" style="border-radius: 0.5rem; width: 100%; height: 104px; object-fit: cover;" alt="Photo 3">
  </div>
</div>
>>>>>>> be2a24bf5183f514c2c30915c7d1740c7a278134
=======

>>>>>>> 6485bf6bd8d6a52db06b8ed373820b30bfc3d47a
---

I hold a Dr. rer. nat. in Pharmacy (Pharmazie) from Universität des Saarlandes, Germany, completed under the supervision of Prof. Dr. Markus R. Meyer and Prof. Dr. Alexandra K. Kiemer, with doctoral research conducted at the Environmental Safety Group, KIST-Europe (Saarbrücken). My doctoral thesis developed an Adverse Outcome Pathway (AOP) for 5α-reductase inhibition and its environmental implications for endocrine disruption. I received my M.Sc. and B.Sc. in Industrial Crop Science and Technology (with a double major in Biochemistry) from Chungbuk National University, Korea.

My research has spanned **endocrine disruptor toxicity assessment** — building AOPs across in vitro models (H295R, 293FT, SF9, zebrafish embryos, *Daphnia magna*), non-targeted metabolomics/lipidomics via QTOF HR-MS, CYP450 metabolism, and hormone receptor reporter assays — as well as **environmental and tobacco-smoke toxicology** and, currently, **chemical characterization for medical device biocompatibility**. I'm interested in bridging these areas into an integrated chemical safety-assessment framework that connects analytical chemistry with mechanistic toxicology.
EOF
git add -A
git commit -m "Resolve merge conflict again, finalize Home page"
git push origin main
