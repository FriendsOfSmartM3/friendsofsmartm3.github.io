---
layout: page
title: Friends of Smart-M3
tagline: students loving RDF triples
---
{% include JB/setup %}

<p>Welcome to <strong>Friends of Smart-M3</strong> if you published a student group project just send us a pull request :)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
