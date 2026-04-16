---
layout: archive
title: "Blog & Görüşler"
permalink: /blog/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/banner.jpg"
---

Burada LinkedIn makalelerimi, sektördeki gelişmeleri ve kişisel görüşlerimi paylaşıyorum.

---

<h3 class="archive__subtitle">Son Yazılar</h3>

<div class="entries-list">
  {% for post in site.posts %}
    {% include archive-single.html %}
  {% endfor %}
</div>
