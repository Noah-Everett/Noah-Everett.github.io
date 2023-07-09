<!-- ---
permalink: /
title: "Hello!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I made this because I was bored -->

---
layout: default
title: "Gallery"
permalink: /gallery/
---

# Gallery: Some of my favorite pictures

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
