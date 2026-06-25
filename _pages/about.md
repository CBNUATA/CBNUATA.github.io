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

---

I hold a Dr. rer. nat. in Pharmacy (Pharmazie) from Universität des Saarlandes, Germany, completed under the supervision of Prof. Dr. Markus R. Meyer and Prof. Dr. Alexandra K. Kiemer, with doctoral research conducted at the Environmental Safety Group, KIST-Europe (Saarbrücken). My doctoral thesis developed an Adverse Outcome Pathway (AOP) for 5α-reductase inhibition and its environmental implications for endocrine disruption. I received my M.Sc. and B.Sc. in Industrial Crop Science and Technology (with a double major in Biochemistry) from Chungbuk National University, Korea.

My research has spanned **endocrine disruptor toxicity assessment** — building AOPs across in vitro models (H295R, 293FT, SF9, zebrafish embryos, *Daphnia magna*), non-targeted metabolomics/lipidomics via QTOF HR-MS, CYP450 metabolism, and hormone receptor reporter assays — as well as **environmental and tobacco-smoke toxicology** and, currently, **chemical characterization for medical device biocompatibility**. I'm interested in bridging these areas into an integrated chemical safety-assessment framework that connects analytical chemistry with mechanistic toxicology.
EOF
git add -A
git commit -m "Resolve merge conflict again, finalize Home page"
git push origin main
