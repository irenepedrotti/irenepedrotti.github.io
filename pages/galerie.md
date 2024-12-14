---
layout: page
title: Galerie
permalink: /galerie/
navbar_order: 4
---

<aside>
<div class="gallery">
{% for image in site.gallery_images %}
<div class=gallery_item>
  <a href="{{image}}"><img class="gallery_img" src="{{image}}"></a>
</div>
{% endfor %}
</div>
<aside>
