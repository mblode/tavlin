---
title: Home
header_image: 
layout: default
---

{% include hero.html %}

<div class="row">
  <div class="small-12 columns medium-10 large-8 medium-offset-1 large-offset-2">
    <div class="medium-gutter"></div>
    {% for post in site.posts %}
      {% if post.index == true %}
        <h2>{{ post.title }}</h2>
        {{ post.content }}
      {% endif %}
    {% endfor %}

    <div class="medium-gutter"></div>
  </div>
</div>

<div class="gallery--bg">
  <div class="row">
    <div class="columns small-12 text-center">
      <div class="large-gutter"></div>
      <div class="large-gutter"></div>
    </div>
  </div>
</div>

<div class="row">
  <div class="medium-gutter"></div>
  <div class="columns small-12 medium-4">
    <h3>Restaurant</h3>
    <p>Plan ahead and save time waiting with a reservation at Tavlin. We accept reservations and would be happy to assist you. Simply book online. Walk in diners are also accepted.</p>
  </div>

  <div class="columns small-12 medium-4">
    <h3>Take-Away</h3>
    <p>an ahead and save time waiting with a reservation at Red Door Yum Cha. We accept reservations and would be happy to assist you.</p>
  </div>

  <div class="columns small-12 medium-4">
    <h3>Catering</h3>
    <p>We also offer catering for all occasions. Please phone us to discuss your event and we will tailor a menu to your needs. We offer pick up catering only and do not do on site events or functions.</p>
  </div>
  <div class="medium-gutter"></div>
</div>

<div class="row">
  <div class="columns small-6">
    <img src="uploads/corn-salad.jpg">
  </div>
  <div class="columns small-6">
    <img src="uploads/cauliflower.jpg">
  </div>
</div>

{% include sm-contact.html %}