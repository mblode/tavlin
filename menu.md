---
title: Menu
---

<div class="row">
  <div class="columns small-12 show-for-small-only">
    <ul class="menu">
      {% for post in site.posts %}
        <li>
          <a href="#{{ post.hash }}" class="a--menu">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
    <hr class="hr--small">
  </div>

  <div class="columns small-12 medium-9 large-10">
    {% for post in site.posts %}
      <div id="{{ post.hash }}">
        <h1>{{ post.title }}</h1>
        {{ post.content }}
      </div>
    {% endfor %}
  </div>

  <div class="columns medium-3 large-2 right show-for-medium" data-sticky-container>
    <div class="sticky" data-sticky data-top-anchor="lunch:top" data-btm-anchor="desserts:bottom">
      <h4>Menus</h4>
        <ul class="menu vertical">
          {% for post in site.posts %}
            <li>
              <a href="#{{ post.hash }}" class="a--menu">{{ post.title }}</a>
            </li>
          {% endfor %}
        </ul>
    </div>
  </div>
</div>


