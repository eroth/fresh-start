---
permalink: /archive/
title: "Archive"
excerpt: "Archived posts for the Last Call Project."
layout: archive
---
<p><i>Past stories from those who have contributed...</i></p>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
