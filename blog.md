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
      <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork" style="position: relative !important; padding-bottom: 45px !important; min-height: 250px !important;">
        
        {% if post.header.teaser %}
          <div class="archive__item-teaser">
            <img src="{{ post.header.teaser | relative_url }}" alt="" style="border-radius: 6px; margin-bottom: 15px;">
          </div>
        {% endif %}
        
        <h2 class="archive__item-title no_toc" itemprop="headline" style="margin-top: 0;">
          <a href="{{ post.url | relative_url }}" rel="permalink">{{ post.title }}</a>
        </h2>
        
        <div class="archive__item-excerpt" itemprop="description" style="flex-grow: 1;">
          {{ post.excerpt | markdownify | strip_html | truncatewords: 30 }}
        </div>
        
        <p style="position: absolute !important; bottom: 15px !important; right: 20px !important; font-size: 0.65rem !important; color: #888 !important; margin: 0 !important; font-weight: bold !important; z-index: 10;">
          📅 {{ post.date | date: "%d.%m.%Y" }}
        </p>

      </article>
    </div>
  {% endfor %}
</div>
