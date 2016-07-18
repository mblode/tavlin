---
title: Blog
---

<div class="columns small-12 medium-10">
  {% for blohs in site.blogs %}
    {% if blohs.index != true %}
    <div id="{{ blog.hash }}">
      <h2>{{ blog.title }}</h2>
      {{ blog.content }}
    </div>
    {% endif %}
  {% endfor %}
</div>