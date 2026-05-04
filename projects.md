---
layout: single
title: "Uygulama Çalışmalarım"
permalink: /projects/
author_profile: true
---
<style>
  /* Kartları Esnek Hale Getirerek Butonları Aynı Hizaya Çekme */
  .grid__wrapper {
    display: flex !important;
    flex-wrap: wrap !important;
    align-items: stretch !important;
  }
  .grid__item {
    display: flex !important;
    flex-direction: column !important;
  }
  .archive__item {
    display: flex !important;
    flex-direction: column !important;
    height: 100% !important;
    margin-bottom: 0 !important;
  }
  
  /* Metin Hizalaması, Boyut Küçültme ve Kurumsal Düzen */
  .archive__item-title {
    font-size: 0.95rem !important; /* %20 küçültüldü */
    margin-top: 15px !important;
    text-align: left !important;
  }
  
  .archive__item-excerpt {
    font-size: 0.75rem !important; /* %20 küçültüldü */
    line-height: 1.6 !important;
    text-align: justify !important; /* Dikkati dağıtmayan kurumsal hizalama */
    flex-grow: 1 !important; /* Açıklama kısa olsa bile butonu aşağı iter */
    margin-bottom: 20px !important;
  }

  /* Tüm Butonların Hizasını, Rengini ve Şeklini Eşitleme */
  .archive__item .btn {
    margin-top: auto !important; /* Her zaman en alt hizada sabit kalır */
    font-size: 0.65rem !important;
    padding: 8px 15px !important;
    background-color: #2c3e50 !important; /* Özgeçmiş sayfasındaki kurumsal lacivert */
    border: none !important;
    color: #fff !important;
    border-radius: 4px !important; 
    text-align: center !important;
    display: inline-block !important;
    transition: background 0.3s;
  }
  
  .archive__item .btn:hover {
    background-color: #34495e !important;
  }
</style>

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
      <div class="btn-wrapper"><a href="/portfolyo/vibetrack.html" target="_blank" class="btn btn--info btn--small">Detaylar</a></div>
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
