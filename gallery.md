---
title: Photo Gallery
---

<div class="row">
  <div class="gallery">
    {% for image in site.data.gallery %}
      <div class="columns">
        <img class="thumbnail" src="../{{ image.image_path }}" alt="{{ image.title }}">
      </div>
    {% endfor %}
  </div>
</div>

