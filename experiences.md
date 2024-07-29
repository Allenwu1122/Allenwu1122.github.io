---
layout: experiences
title: "Experiences"
---


{% for details in site.data.settings.experiences %}

<div class="row g-5 mb-5">
  <div class="col-md-6">
    <h5>{{ details.name }}</h5>
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
    <h5>{{ details.name2 }}</h5>
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


{% endfor %}