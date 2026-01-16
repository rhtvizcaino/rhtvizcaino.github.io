---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Download

- **1-page academic resume (PDF):** [Download]({{ base_path }}/files/RHTV_Postdoc_Resume_1p.pdf)

*Full academic CV available upon request.*

---

## Snapshot (EN)

PhD candidate in Applied Geosciences at IPICYT (Mexico), specializing in igneous petrology and volcanic geochemistry of young ocean-island systems. Dissertation: eruptive and magmatic evolution of the 1952–53 Bárcena monogenetic cone (Isla San Benedicto, Revillagigedo Archipelago) integrating stratigraphy, whole-rock geochemistry (XRF, ICP-MS), mineral chemistry (EPMA), SEM textures, and radiogenic isotopes (TIMS; Sr–Nd–Pb). **Expected defense: late June 2026.**

**Core methods:** EPMA • TIMS (Sr–Nd–Pb) • SEM • XRD • XRF • ICP-MS • thin sections & polished mounts • mineral separation • Python (PCA, clustering)

---

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Talks & Posters

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

## Teaching & Mentoring

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

