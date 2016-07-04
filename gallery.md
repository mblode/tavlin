---
title: Photo Gallery
<<<<<<< 6d5bd165e6d22401b1f595b89f3d36b0d65d9100:gallery.html
images:
- image_path: "/assets/images/1.jpg"
  title: Image 1
=======
>>>>>>> Starting work adding foundation:gallery.md
---

<div class="gallery">
  {% for image in site.photo_gallery %}
    <li>
      <img src="{{ image.image_path }}" alt="{{ image.title }}">
    </li>
  {% endfor %}
</div>
