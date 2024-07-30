---
layout: experiences
title: "Experiences"
---


{% for details in site.data.settings.experiences %}

<div class="row g-5 mb-5">
  <div class="col-md-6">
    <h4>{{ details.name }}</h4>
    <p><em>{{ details.position }}</em></p>
    <p> </p>
    <p>{{ details.bullet_11 }}</p>
    <p>{{ details.bullet_12 }}</p>
    <p> </p>
    <p><a href="https://www.logitechg.com/en-us/products/gaming-mice.html">Link</a></p>
  </div>
  <div class="col-md-6">
    <img src="{{ site.github.url }}/{{ details.image }}" alt="Contact" width="100%">
  </div>
</div>

<div class="row g-5 mb-5">
  <div class="col-md-6">
    <h4>{{ details.name2 }}</h4>
    <p><em>{{ details.position2 }}</em></p>
    <p> </p>
    <p>{{ details.bullet_21 }}</p>
    <p>{{ details.bullet_22 }}</p>
    <p>{{ details.bullet_23 }}</p>
    <p> </p>
    <p><a href="https://tritonrobotics.ucsd.edu/">Link</a></p>
  </div>
  <div class="col-md-6">
    <img src="{{ site.github.url }}/{{ details.image2 }}" alt="Contact" width="100%">
  </div>
</div>

<div class="row g-5 mb-5">
  <div class="col-md-6">
    <h4>{{ details.name3 }}</h4>
    <p><em>{{ details.position3 }}</em></p>
    <p> </p>
    <p>{{ details.bullet_31 }}</p>
    <p>{{ details.bullet_32 }}</p>
    <p> </p>
    <p><a href="https://v5rc-kb.recf.org/hc/en-us/articles/9660827298839-Competition-History-2020-2021-Change-Up">Link</a></p>
  </div>
  <div class="col-md-6">
    <img src="{{ site.github.url }}/{{ details.image3 }}" alt="Contact" width="100%">
  </div>
</div>



{% endfor %}