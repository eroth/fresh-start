---
permalink: /resources/
title: "Resources"
excerpt: "Minimal Mistakes is a flexible two-column Jekyll theme."
layout: archive
---

<p><i>Articles written by professional life coaches to get you started down the right path...</i></p>
{% for post in site.resources %}
  {% include archive-single.html %}
{% endfor %}
