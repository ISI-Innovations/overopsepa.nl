---
layout: page
title: OverOpSEPA.nl
tagline: Nieuws over SEPA
---
{% include JB/setup %}

## Artikelen

Hieronder vind u een lijst van artikelen geschreven door de experts van OverOpSEPA.nl

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> - {{post.author}}</li>
  {% endfor %}
</ul>
