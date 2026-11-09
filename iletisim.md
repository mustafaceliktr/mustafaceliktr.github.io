---
layout: single
title: "İletişim"
permalink: /iletisim/
author_profile: false
share: false
classes: contact-modern
excerpt: "İş birliği, proje, sektör değerlendirmesi veya profesyonel iletişim için Mustafa Çelik ile bağlantı kurun."
---

<div class="contact-page">
  <p class="contact-page__intro">İş birliği, projeler ve profesyonel konular için benimle iletişime geçebilirsiniz.</p>
  <div class="contact-page__accent" aria-hidden="true"></div>

  <div class="contact-page__columns">
  <form class="contact-form" action="https://formspree.io/f/xlgkzjva" method="POST">
    <input type="hidden" name="_subject" value="Web sitesi iletişim formu">

    <div class="contact-form__field">
      <label for="contact-name">Ad Soyad</label>
      <input id="contact-name" type="text" name="Ad Soyad" autocomplete="name" required>
    </div>

    <div class="contact-form__field">
      <label for="contact-email">E-posta</label>
      <input id="contact-email" type="email" name="E-posta" autocomplete="email" required>
    </div>

    <div class="contact-form__field">
      <label for="contact-subject">Konu</label>
      <input id="contact-subject" type="text" name="Konu" required>
    </div>

    <div class="contact-form__field">
      <label for="contact-message">Mesaj</label>
      <textarea id="contact-message" name="Mesaj" rows="5" required></textarea>
    </div>

    <button class="contact-form__button" type="submit">Gönder</button>
  </form>

  <section class="contact-links" aria-labelledby="contact-links-title">
    <h2 id="contact-links-title">Diğer İletişim Kanalları</h2>
    <div class="contact-links__list">
      <a href="https://linkedin.com/in/mustafaceliktr" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      <a href="https://wa.me/mcelik84" target="_blank" rel="noopener noreferrer">WhatsApp</a>
    </div>
  </section>
  </div>
</div>

<script>
(function () {
  const params = new URLSearchParams(window.location.search);
  const konu = params.get('konu');
  if (!konu) return;

  const subjectField = document.getElementById('contact-subject');
  const formspreeSubject = document.querySelector('input[name="_subject"]');

  if (subjectField) subjectField.value = konu;
  if (formspreeSubject) formspreeSubject.value = konu;
})();
</script>
