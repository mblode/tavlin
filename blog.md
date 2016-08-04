---
title: Tavlin Blog
class: blog
---

<div class="row">
  <div class="columns small-12">
    {% for blog in site.blog %}
      <div class="blog--list">
        <div class="blog--data">

          <a href="{{ blog.url }}"><h2 class="blog--title">{{ blog.title }}</h2>
          <date>{{ blog.date | date: '%B %d, %Y' }}</date>
          <p class="blog--content">{{ blog.content | strip_html | truncatewords: 50 }}</p>
          <span class="read-more">Read more...</span></a>
        </div>
      </div>
    {% endfor %}
  </div>
</div>
