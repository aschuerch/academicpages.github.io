---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

![publications](../image/noun_pub.png)



  You can find my articles on <u><a href="https://scholar.google.nl/citations?user=xh5gN60AAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
