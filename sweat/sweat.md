---
layout: page
title: Putting sweat into words as I progress through my fitness journey.
cover: /assets/images/sweat.jpg
---

<div class="message">
  This page is still in its teething stage. Meanwhile, feast yourself on this lovely athletic creature.
</div>

![Tiger](/assets/images/tiger.jpg)

-----

<div id="post-list">
	{% for post in paginator.posts %}
		<div>
			<span class="post-date">{{ post.date | date_to_long_string }}</span>
			<h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
			<p class="post-description">{{ post.excerpt }}</p>
		</div>
		<br>
	{% endfor %}
</div>

See you soon!
