---
title: Our Menus
---

<div class="row">

  <div class="columns small-12 show-for-small-only">
    <ul class="menu">
      {% for post in site.posts %}
        {% if post.index != true %}
          <li>
            <a href="#{{ post.hash }}" class="a--menu">{{ post.title }}</a>
          </li>
        {% endif %}
      {% endfor %}
    </ul>
    <hr class="hr--small">
  </div>

  <div class="columns small-12 medium-10">
    {% for post in site.posts %}
      {% if post.index != true %}
      <div id="{{ post.hash }}">
        <h2>{{ post.title }}</h2>
        {{ post.content }}
      </div>
      {% endif %}
    {% endfor %}
  </div>

  <div class="columns medium-2 right show-for-medium" data-sticky-container>
    <div class="sticky" data-sticky data-top-anchor="lunch:top" data-btm-anchor="desserts:bottom">
      <h4>Menus</h4>
        <ul class="menu vertical">
          {% for post in site.posts %}
            {% if post.index != true %}
              <li>
                <a href="#{{ post.hash }}" class="a--menu">{{ post.title }}</a>
              </li>
            {% endif %}
          {% endfor %}
        </ul>
    </div>
  </div>
</div>


