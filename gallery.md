---
title: Photo Gallery
class: gallery
---

<div class="row">
    {% for image in site.data.gallery %}
      <div class="columns small-12 medium-3">
      <a href="../{{ image.image_path }}" target="_blank">
        <figure>
          <img src="../{{ image.image_path }}" alt="{{ image.title }}">
        </figure>
      </a>
    </div>
    {% endfor %}
</div>

<div class="medium-gutter"></div>

