---
title: Tavlin Blog
class: blog
---

<div class="row">
  <div class="columns small-12 medium-10">
    {% for blog in site.blog %}
      <div class="blog--list">
        <div class="blog--data">
          <a href="{{ blog.url }}"><h1 class="blog--title">{{ blog.title }}</h1></a>
          <a href="{{ blog.url }}"><date>{{ blog.date | date: '%B %d, %Y' }}</date></a>
          <p class="blog--content">{{ blog.content | strip_html | truncatewords: 50 }}</p>
          <a href="{{ blog.url }}"><span class="read-more">Read more...</span></a>
        </div>
      </div>
    {% endfor %}
  </div>
</div>
