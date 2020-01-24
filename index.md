---
layout: home
permalink: /
title: "Latest Posts"
logo: "asdf"
description: "fesf"
image: blog-cover.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
