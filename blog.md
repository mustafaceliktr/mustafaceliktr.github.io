---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---

<div class="blog-index">
  <section class="blog-intro">
    <p>Burada LinkedIn makalelerimi, sektördeki gelişmeleri ve kişisel görüşlerimi paylaşıyorum.</p>
    <span class="blog-intro__accent" aria-hidden="true"></span>
  </section>

  {% assign featured_post = site.posts.first %}
  {% assign remaining_posts = site.posts | slice: 1, site.posts.size %}

  {% if featured_post %}
    <section class="blog-featured" aria-label="Öne çıkan yazı">
      {% if featured_post.header.teaser %}
        <a class="blog-featured__media" href="{{ featured_post.url | relative_url }}" aria-label="{{ featured_post.title | escape }}">
          <img src="{{ featured_post.header.teaser | relative_url }}" alt="">
        </a>
      {% endif %}

      <div class="blog-featured__content">
        {% if featured_post.categories %}
          <div class="blog-pills" aria-label="Kategoriler">
            {% for category in featured_post.categories %}
              <span class="blog-pill">{{ category }}</span>
            {% endfor %}
          </div>
        {% endif %}

        <h2 class="blog-featured__title">
          <a href="{{ featured_post.url | relative_url }}">{{ featured_post.title }}</a>
        </h2>

        <p class="blog-featured__excerpt">
          {{ featured_post.excerpt | markdownify | strip_html | truncatewords: 34 }}
        </p>

        <div class="blog-meta">
          <time datetime="{{ featured_post.date | date_to_xmlschema }}">{{ featured_post.date | date: "%d.%m.%Y" }}</time>
          <a class="blog-read-link" href="{{ featured_post.url | relative_url }}">Yazıyı Oku →</a>
        </div>
      </div>
    </section>
  {% else %}
    <p class="blog-empty">Henüz blog yazısı bulunmuyor.</p>
  {% endif %}

  {% if remaining_posts.size > 0 %}
    <section class="blog-list-section" aria-labelledby="blog-recent-title">
      <h2 id="blog-recent-title" class="blog-section-title">Son Yazılar</h2>

      <div class="blog-list">
        {% for post in remaining_posts %}
          <article class="blog-card">
            {% if post.header.teaser %}
              <a class="blog-card__media" href="{{ post.url | relative_url }}" aria-label="{{ post.title | escape }}">
                <img src="{{ post.header.teaser | relative_url }}" alt="">
              </a>
            {% endif %}

            <div class="blog-card__content">
              {% if post.categories %}
                <div class="blog-pills" aria-label="Kategoriler">
                  {% for category in post.categories %}
                    <span class="blog-pill">{{ category }}</span>
                  {% endfor %}
                </div>
              {% endif %}

              <h3 class="blog-card__title">
                <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
              </h3>

              <p class="blog-card__excerpt">
                {{ post.excerpt | markdownify | strip_html | truncatewords: 24 }}
              </p>

              <div class="blog-meta">
                <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%d.%m.%Y" }}</time>
                <a class="blog-read-link" href="{{ post.url | relative_url }}">Oku →</a>
              </div>
            </div>
          </article>
        {% endfor %}
      </div>
    </section>
  {% endif %}
</div>
