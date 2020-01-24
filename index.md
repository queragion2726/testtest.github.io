---
layout: home
permalink: /
title: "Latest Posts"
image:
  feature: blog-cover(1).jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
