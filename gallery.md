---
title: Photo Gallery
---

<div class="row">
  <div class="gallery">

    {% for image in site.data.gallery %}
      <div class="column small-12 medium-4">
        <img class="thumbnail" src="../{{ image.image_path }}" alt="{{ image.title }}">
      </div>
    {% endfor %}
  </div>
</div>

