---
layout: single
title: "Projelerim"
permalink: /projects/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: "/banner.jpg"
---

<style>
  /* Grid kapsayıcısının esnek olması ve çocukların aynı boyda uzaması için */
  .grid__wrapper {
    display: flex !important;
    flex-wrap: wrap !important;
    align-items: stretch !important;
  }

  /* Kartların esnek yapısı */
  .grid__item {
    display: flex !important;
    flex-direction: column !important;
  }
  
  .archive__item {
    display: flex !important;
    flex-direction: column !important;
    height: 100% !important;
    flex-grow: 1 !important;
  }
  
  /* Görsellerin ezilmeden kusursuz kırpılması */
  .archive__item-teaser img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    display: block;
    margin-bottom: 15px;
  }
  
  /* Kurumsal ve Sola Hizalı Başlık Tipografisi */
  .archive__item-title {
    margin-top: 0 !important;
    margin-bottom: 8px !important;
    text-align: left !important;
    font-size: 1.15rem !important;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    font-weight: 600 !important;
    line-height: 1.3 !important;
  }
  
  /* Kurumsal ve Sola Hizalı Açıklama Tipografisi */
  .archive__item-excerpt {
    text-align: left !important;
    font-size: 0.9rem !important;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    line-height: 1.5 !important;
    color: #4a4a4a !important;
    margin-bottom: 20px !important;
    flex-grow: 1 !important; /* Açıklama kısmını esneterek butonu en alta iter */
  }
  
  /* Buton hizalaması ve sabitleme */
  .btn-wrapper {
    margin-top: auto !important; /* Butonu her zaman kartın en altına yapıştırır */
    display: flex;
    justify-content: flex-start;
  }
</style>

Yazılım geliştirme sürecimde hayata geçirdiğim çalışmaların özeti aşağıdadır. Projeleri incelemek isterseniz tanıtım sayfalarına gitmek için ilgili proje detaylar butonunu tıklayabilirsiniz.

<div class="grid__wrapper">

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/herseyim.png" alt=""></div>
      <h3 class="archive__item-title">HerŞeyim</h3>
      <div class="archive__item-excerpt">Görev, not ve toplantı yönetimini tek merkezde toplayan yaşam asistanı.</div>
      <div class="btn-wrapper"><a href="/portfolyo/herseyim.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/inerken.png" alt=""></div>
      <h3 class="archive__item-title">İnerken</h3>
      <div class="archive__item-excerpt">Linkle veya manuel eklenen ürün için birden fazla e-ticaret platformunda akıllı fiyat takibi ve bildirim uygulaması.</div>
      <div class="btn-wrapper"><a href="/portfolyo/inerken.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/skttakip.png" alt=""></div>
      <h3 class="archive__item-title">freshly</h3>
      <div class="archive__item-excerpt">Gıda, ilaç ve kozmetik ürünlerin SKT'lerini takip eden son kullanma tarihi asistanı.</div>
      <div class="btn-wrapper"><a href="/portfolyo/freshly.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/vibe.png" alt=""></div>
      <h3 class="archive__item-title">VibeTrack</h3>
      <div class="archive__item-excerpt">Ruh haline göre AI üretimi müzikler dinleyebileceğin odaklanma odaları ve Pomodoro sayacı.</div>
      <div class="btn-wrapper"><a href="/portfolyo/vibe.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/dataker.png" alt=""></div>
      <h3 class="archive__item-title">E.V.C.P. DaTAker</h3>
      <div class="archive__item-excerpt">Elektrikli araç şarj istasyonları verilerini api ile alıp, Excel raporlarına dönüştüren araç.</div>
      <div class="btn-wrapper"><a href="/portfolyo/evcpdataker.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/ekosistem.png" alt=""></div>
      <h3 class="archive__item-title">E.A. Şarj Ekosistemi Analizi</h3>
      <div class="archive__item-excerpt">Elektrikli araç şarj istasyonlarının çoklu dönem gelişimini gösterir analiz ve raporlama yazılımı.</div>
      <div class="btn-wrapper"><a href="/portfolyo/sarjekosistemianaliz.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/gelisim.png" alt=""></div>
      <h3 class="archive__item-title">E.A. Şarj Noktaları Gelişim Raporu</h3>
      <div class="archive__item-excerpt">Elektrikli araç şarj noktalarının EPDK verilerinin yüklenerek iki dönemli temel gelişim analizi çıktısı olan uygulama.</div>
      <div class="btn-wrapper"><a href="/portfolyo/gelisimraporu.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

  <div class="grid__item span-3">
    <article class="archive__item">
      <div class="archive__item-teaser"><img src="/assets/images/projectos.png" alt=""></div>
      <h3 class="archive__item-title">ProjectOS</h3>
      <div class="archive__item-excerpt">Çoklu proje yönetimi ve AI context süreçlerini otomatize eden araç.</div>
      <div class="btn-wrapper"><a href="/portfolyo/projectos.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
    </article>
  </div>

</div>
