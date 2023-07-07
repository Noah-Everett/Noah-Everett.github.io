---
layout: gallary
title: "Gallary: Some of my favorite picture"
permalink: /gallary/
author_profile: true
redirect_from:
  - /galary
---

<div style="display: flex; flex-wrap: wrap;">
  {% for image in site.static_files %}
    {% if image.path contains 'images/gallery' %}
      <div style="flex: 33.33%; padding: 5px;">
        <a href="{{ image.path }}" target="_blank">
          <img src="{{ image.path }}" alt="{{ image.name }}" style="width: 100%;">
        </a>
      </div>
    {% endif %}
  {% endfor %}
</div>