---
layout: page
title: Code From Home
tagline: 
---
{% include JB/setup %}

{% include cfh/axis %}

{% for post in site.posts limit:10 %}
  <article>
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.content }}
  </article>
{% endfor %}

