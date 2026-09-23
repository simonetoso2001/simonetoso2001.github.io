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
<div style="display:flex; align-items:flex-start; gap:12px; margin-bottom:24px;">
  <img src="{{ '/images/bocconi.png' | relative_url }}"
       alt=""
       style="width:60px !important; height:60px !important;
              max-width:60px !important; object-fit:contain;
              flex:0 0 60px; margin:0;">

  <div style="flex:1; min-width:0;">
    <strong>Bocconi University</strong><br>
    PhD in Computer Science<br>
    <small> 2026 – Today </small><br>
  </div>
</div>

<div style="display:flex; align-items:flex-start; gap:12px; margin-bottom:24px;">
  <img src="{{ '/images/padova.png' | relative_url }}"
       alt=""
       style="width:60px !important; height:60px !important;
              max-width:60px !important; object-fit:contain;
              flex:0 0 60px; margin:0;">

  <div style="flex:1; min-width:0;">
    <strong>Università degli Studi di Padova</strong><br>
    MSc in Physics of Data<br>
    <small> 2022 – 2024 </small><br>
    <strong>Grade:</strong> 110/110 with honours<br>
    <strong>Thesis:</strong> Leveraging generative models for the optimization of 3D implicit representations
    <ul>
      <li>Research thesis based on the work done during my internship at SONY</li>
    </ul>
  </div>
</div>

<div style="display:flex; align-items:flex-start; gap:12px; margin-bottom:24px;">
  <img src="{{ '/images/padova.png' | relative_url }}"
       alt=""
       style="width:60px !important; height:60px !important;
              max-width:60px !important; object-fit:contain;
              flex:0 0 60px; margin:0;">

  <div style="flex:1; min-width:0;">
    <strong>Università degli Studi di Padova</strong><br>
    BSc in Physics<br>
    <small> 2019 – 2022 </small><br>
    <strong>Grade:</strong> 110/110 with honours<br>
    <strong>Thesis:</strong> General statistical laws in complex component systems
  </div>
</div>

Work experience
======
<div style="display:flex; align-items:flex-start; gap:12px; margin-bottom:24px;">
  <img src="{{ '/images/fbk.png' | relative_url }}"
       alt=""
       style="width:60px !important; height:60px !important;
              max-width:60px !important; object-fit:contain;
              flex:0 0 60px; margin:0;">

  <div style="flex:1; min-width:0;">
    <strong>Fondazione Bruno Kessler</strong><br>
    Technologist<br>
    <small> Trento, Italy, 2024 – 2026 </small>
    <br>Worked on developing ML solutions for industrial clients<br>
  </div>
</div>

<div style="display:flex; align-items:flex-start; gap:12px; margin-bottom:24px;">
  <img src="{{ '/images/sony.png' | relative_url }}"
       alt=""
       style="width:60px !important; height:60px !important;
              max-width:60px !important; object-fit:contain;
              flex:0 0 60px; margin:0;">

  <div style="flex:1; min-width:0;">
    <strong>SONY Stuttgart Laboratory 1</strong><br>
    Research intern<br>
    <small> Stuttgart, Germany, Mar 2024 - Sep 2026 </small>
    <br>Developed a sparse-view 3D reconstruction pipeline by leveraging multi-view diffusion models<br>
  </div>
</div>
  
Skills
======
* Experienced in Python. Extensive use of PyTorch to design and train deep neural networks. 
* Working experience with `bash`, `slurm`, `git`, `docker`, `uv`, `conda`

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
