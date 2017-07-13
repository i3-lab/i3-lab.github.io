---
layout: archive
title: "People"
permalink: /people/
author_profile: false
---


<div class="grid__wrapper">
  {% for post in site.faculties %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>



<div class="grid__wrapper">
  {% for post in site.fellows %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
