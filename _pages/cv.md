---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Candidate in Physics, Tsinghua University, 2023 – Present (Advisor: Prof. Yong Xu)
* B.Sc. in Mathematics and Physics, Tsinghua University, 2023 (GPA: 3.83/4.00, Rank: 11/55)
* Undergraduate in Chemistry, Tsinghua University, 2018 – 2020

Research Summary
======
My research focuses on deep-learning-assisted first-principles calculations, including:
* Deep-learning density functional theory (DFT) Hamiltonians (DeepH)
* Deep-learning density functional perturbation theory (DFPT)
* Neural-network DFT based on variational energy minimization
* Deep-learning hybrid DFT and magnetic materials simulations

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Code Development
======
* [DeepH-pack](https://github.com/mzjb/DeepH-pack) interface with multiple DFT codes (SIESTA, FHI-aims, ABACUS, pyscf, GPAW)
* [AI2DFT](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.133.076401) — An auto-differentiable DFT code
* Modified SIESTA for DeepH-DFPT calculations
* Post-processing tools for DeepH

Technical Skills
======
* **DFT codes:** VASP, Quantum Espresso, FHI-aims, OpenMX, ABACUS, pyscf, SIESTA
* **Phonon/EPC:** Quantum Espresso with EPW
* **Magnetic simulations:** (Non-collinear) magnets with VASP and OpenMX
* **Wannierization:** Quantum Espresso/Wannier90
* **Excited-state:** Hybrid DFT and *GW* with FHI-aims, ABACUS, pyscf
* **Programming:** Python, Julia, Fortran, C(++), MATLAB, LaTeX
