---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---

Burada LinkedIn makalelerimi, sektördeki gelişmeleri ve kişisel görüşlerimi paylaşıyorum.

---

<h3 class="archive__subtitle">Son Yazılar</h3>

<div class="entries-list">
  {% for post in site.posts %}
    <div class="list__item">
      <article class="archive__item">
        
        {% if post.header.teaser %}
          <div class="archive__item-teaser">
            <img src="{{ post.header.teaser | relative_url }}" alt="">
          </div>
        {% endif %}
        
        <h2 class="archive__item-title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </h2>
        
        <div class="archive__item-excerpt">
          {{ post.excerpt | markdownify | strip_html | truncatewords: 25 }}
        </div>
        
        <p class="card-auto-date-blog">📅 {{ post.date | date: "%d.%m.%Y" }}</p>

      </article>
    </div>
  {% endfor %}
</div>
