---
title: Home
header_image: 
header_title: Home
header_desc: 
layout: default
---

<div class="home">
  {% for post in site.posts %}
  <a class="post--link" href="{{ post.url | prepend: site.baseurl }}">
    <div class="post--list">
      <time class="post--meta">{{ post.date | date: "%b %-d, %Y" }}</time>
      <h2 class="post--title">
        {{ post.title }}
      </h2>
      <p>{{ post.content | strip_html | truncatewords: 30 }}</p>
      <span class="post--meta">
        Read more...
      </span>
    </div>
  </a>
  {% endfor %}
</div>
