---
title: Blog
---

<div class="row">
  <div class="columns small-12 medium-10">
    {% for blog in site.blog %}
      <div id="{{ blog.hash }}">
        <h3><a href="{{ blog.url }}">{{ blog.title }}</a></h3>
        {{ blog.excerpt }}
      </div>
    {% endfor %}
  </div>
</div>
