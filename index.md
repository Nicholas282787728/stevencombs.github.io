---
layout: page
---
{% include JB/setup %}

###Combsing through the minutia…

<p class="posts">
  {% for post in site.posts %}
    <p><b>{{ post.date | date_to_string }} &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></b></p>
    <p>{% if post.content contains '<!--more-->' %}{{ post.content | split:'<!--more-->' | first }}{% else %}{{ post.content }}{% endif %}</p>
  {% endfor %}
</p>