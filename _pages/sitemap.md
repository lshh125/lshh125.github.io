---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

Explore my research, talks, blog posts, and professional background.

<ul>
{% for link in site.data.navigation.main %}
  <li><a href="{{ link.url | relative_url }}">{{ link.title }}</a></li>
{% endfor %}
</ul>

## Talk recordings

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

## Blog posts

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
