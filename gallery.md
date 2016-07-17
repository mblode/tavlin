---
title: Photo Gallery
---

<div class="row">
  <div class="gallery">
    {% for image in site.data.gallery %}
    <a>
      <figure>
        <img src="../{{ image.image_path }}" alt="{{ image.title }}">
      </figure>
    </a>
    {% endfor %}
  </div>
  <div class="medium-gutter"></div>
</div>

