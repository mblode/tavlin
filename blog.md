---
title: Blog
---

<div class="columns small-12 medium-10">
  {% for blog in site.blogs %}
    {% if blog.index != true %}
    <div id="{{ blog.hash }}">
      <h2>{{ blog.title }}</h2>
      {{ blog.content }}
    </div>
    {% endif %}
  {% endfor %}
</div>