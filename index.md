---
layout: default
title: Beaverdam Field
---
# Beaverdam Field

This site's purpose is to collect information about what's happening with the Beaverdam Field (408 Beaverdam Road) located across from Revol Church.

Revol church was given the land a couple years ago by the previous church, and is now working on selling it to developers. 

Many people weren't aware of this, so I decided to make a website that'd have some basic information about it.

Please let me know if there's anything to add, or anything that should be corrected!

email: blah

## Latest Posts

{% if site.posts and site.posts.size > 0 %}
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
			({{ post.date | date: "%B %-d, %Y" }})
		</li>
	{% endfor %}
</ul>
{% endif %}