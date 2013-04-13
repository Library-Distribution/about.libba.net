---
title: libba.net BLOG
layout: page
---
# libba.net BLOG

## Posts:

{% for post in site.posts %}
* [{{post.title}}](..{{post.url}}) ({{post.date | date_to_string}}) <div>{{ post.excerpt | strip_html | truncate: 300 }}</div></li>
{% endfor %}
