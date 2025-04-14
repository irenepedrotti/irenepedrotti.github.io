---
layout: page
title: Galerie
permalink: /galerie/
navbar_order: 4
description: Bildergalerie mit Fotos aus dem Ballettunterricht.
---

<aside>
<div class="gallery">
{% for image in site.gallery_images %}
<div class=gallery__item>
  <a href="{{image}}"><img class="gallery__img" src="{{image}}"></a>
</div>
{% endfor %}
</div>
<aside>
