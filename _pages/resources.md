---
permalink: /resources/
title: "Resources"
excerpt: "Articles written by professional life coaches to help readers of the Last Call Project."
layout: archive
---

<p><i>Articles written by professional life coaches to get you started down the right path...</i></p>
{% for post in site.resources %}
  {% include archive-single.html %}
{% endfor %}
