---
layout: default
title: Beaverdam Field
---
# Beaverdam Field

This site's purpose is to collect information about what's happening with the Beaverdam Field (408 Beaverdam Road) located across from Revol Church.

Revol church was given the land a couple years ago by the previous church, and is now working on selling it to developers. 

Many people weren't aware of this, so I decided to make a website that'd have some basic information about it.

Please let me know if there's anything to add, or anything that should be corrected!

<p><em>Note: This website is not affiliated with the <a href="https://beaverdamvalleyna.org/">Beaverdam Valley Neighborhood Association</a></em></p>

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

## Contact 📧

If you have any information that'd be helpful to get onto this site, or if you want to correct anything on here, please <a href="mailto:info@beaverdamfield.com">let me know</a>!
