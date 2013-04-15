---
title: libba.net BLOG
layout: page
---
# Posts:

{% for post in site.posts %}
* [{{post.title}}](..{{post.url}}) ({{post.date | date_to_string}}) <div>{{ post.excerpt | strip_html | truncate: 300 }}</div></li>
{% endfor %}
