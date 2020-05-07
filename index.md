---
layout: home
title: Portfolio
---

<!-- Thumbnail -->
<section id="thumbnails">{% for photo in site.photos %}
	<article>
		<a class="thumbnail" href="{{ photo.image }}" data-position="center top"><img src="{{ photo.thumbnail }}" alt="" /></a>
		<h2>{{ photo.title }}</h2>
		<p>{{ photo.caption }}</p>
	</article>
{% endfor %}</section>
