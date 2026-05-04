---
layout: single
title: ""
permalink: /cv/
author_profile: true
---

<style>
  /* Sayfa genelindeki başlık ve çizgi gizleme ayarları */
  .page__title {
    display: none !important;
  }
  .page__header {
    border-bottom: none !important;
    margin-bottom: 0 !important;
    padding-bottom: 0 !important;
  }

  /* Butonlar ve Konumlandırma */
  .cv-download-container {
    position: absolute;
    top: -20px !important; 
    right: 0;
    display: flex;
    flex-direction: row; 
    gap: 10px;
    z-index: 10;
  }
  .cv-btn {
    display: inline-block;
    padding: 8px 15px; 
    background-color: #2c3e50;
    color: #fff !important;
    text-decoration: none !important;
    border-radius: 4px;
    font-size: 0.60rem !important; /* Buton metni */
    font-weight: 600;
    text-align: center;
    transition: background 0.3s;
    white-space: nowrap;
  }

  /* İçerik Boşluğu */
  .cv-content {
    margin-top: 50px !important;
    position: relative;
  }

  /* Ana Bölüm Başlıkları (İş Deneyimleri, Eğitim Bilgileri, Özgeçmiş Özeti h2 vb.) */
  .cv-section-title, .ozet-alani h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
    margin-top: 25px;
    margin-bottom: 15px;
    font-size: 0.95rem !important; /* Özetteki başlık boyutu */
  }
  
  /* Genel Paragraflar ve Listeler (Tüm açıklama metinleri) */
  p, ul li, .ozet-alani p, .job-description {
    font-size: 0.70rem !important; /* Özetteki paragraf boyutu */
    line-height: 1.5 !important;
  }
  
  /* İş Pozisyonu Adı (Ufak bir vurgu farkı için) */
  .job-title {
    font-size: 0.80rem !important; 
    font-weight: 600;
    color: #2980b9;
    margin-bottom: 0 !important;
  }
  
  /* Şirket Adı ve Tarih (Biraz daha silik ve küçük) */
  .company-date {
    font-size: 0.65rem !important;
    color: #7f8c8d;
    font-style: italic;
    margin-top: 2px;
    margin-bottom: 10px;
  }

  /* Form (Anket) Alanı Fontları */
  .form-alani h3 {
    font-size: 0.85rem !important;
  }
  .form-alani label, .form-alani input {
    font-size: 0.70rem !important;
  }
</style>
<div class="cv-content">
  <div class="cv-download-container">
    <a href="#form-alani" class="cv-btn" onclick="setLanguage('tr')"><i class="fas fa-file-pdf"></i> Türkçe CV İndir</a>
    <a href="#form-alani" class="cv-btn" onclick="setLanguage('en')"><i class="fas fa-file-pdf"></i> Download English CV</a>
  </div>

 <div class="ozet-alani">
    <h2>Özgeçmiş Özeti</h2>
    <p>Satış Profesyoneli olarak, satış ve müşteri yönetimi alanında 15 yıllık geniş bir deneyime sahibim. 2008 yılından bu yana, küçük, orta ve büyük ölçekli müşterilerle etkili satış stratejileri geliştirerek, müşteri ihtiyaçlarını anlama ve çözüm odaklı yaklaşımlar sunma konularında başarılı sonuçlar elde ettim.</p>
  </div>

  <h2 class="cv-section-title">İş Deneyimleri</h2>

  <div class="job-item">
    <p class="job-title">Satış Yöneticisi</p>
    <p class="company-date">Zebra Electronics | Eylül 2024 - Ocak 2026</p>
    <p class="job-description">DC/AC şarj üniteleri satışı ve CPO yazılım çözümleri süreçlerini yönettim. Toplamda 2 milyon USD değerinde sözleşme yönetimi gerçekleştirdim.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Bizim Toptan Satış Mağazaları | Nisan 2022 - Mayıs 2024</p>
    <p class="job-description">300+ çalışana sahip kurumsal firmaların tedarik operasyonlarını planlayarak maliyet optimizasyonu sağladım.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Mepsan Petrol Cihazları A.Ş. | Ağustos 2016 - Nisan 2022</p>
    <p class="job-description">Üretilen akaryakıt ekipmanları ve akaryakıt dağıtım şirketleri ile iş birliği içinde geliştirilen projeler çerçevesinde kurumsal satışları gerçekleştirdim. Petrol Ofisi, Alpet, Lukoil, Soil gibi büyük akaryakıt dağıtım şirketleri ve kamu kurumları ile projeler geliştirip başarıyla uygulamaya geçirdim.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Nixonled - Yağmur Group & Techled Aydınlatma | Aralık 2011 - Temmuz 2016</p>
    <p class="job-description">Endüstriyel LED aydınlatma armatürlerinin pazarlama ve satış süreçlerini yönettim. Hayat Kimya, Aksa Akrilik, Arçelik, TÜPRAŞ gibi büyük kurumsal firmaları müşteri portföyüne kazandırdım. İstanbul Büyükşehir Belediyesi dahil birçok kamu projesine liderlik ettim.</p>
  </div>

  <h2 class="cv-section-title">Eğitim Bilgileri</h2>
  <ul>
    <li><strong>Marmara Üniversitesi</strong> - Teknoloji Fakültesi, Elektrik Öğretmenliği (Eylül 2023 - Devam ediyor)</li>
    <li><strong>Conley Üniversitesi</strong> - İşletme Yönetimi, Lisans (2020 - 2022)</li>
  </ul>

</div>

<div class="form-alani">
  <h3>Özgeçmişi İndirmek İçin Bilgilerinizi Paylaşın</h3>
  <p>Kişisel verilerin güvenliği ve iletişim takibi için lütfen aşağıdaki formu doldurunuz. İndirme bağlantısı form gönderildikten sonra doğrudan açılacaktır.</p>

  <form action="https://api.sheetmonkey.io/form/vkzVxiCPicRA18yL4ezYdc" method="POST" style="max-width: 400px;">
    
    <label>Adınız Soyadınız:</label>
    <input type="text" name="Ad Soyad" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <label>E-posta Adresiniz:</label>
    <input type="email" name="E-posta" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <label>Telefon Numaranız:</label>
    <input type="tel" name="Telefon" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <input type="submit" value="Bilgileri Gönder ve CV İndir" class="cv-btn" style="width: 100%; cursor: pointer; padding: 12px; margin-top: 10px;">
    
    <input type="hidden" id="pdf-linki" name="x-sheetmonkey-redirect" value="https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_tr.pdf">
  </form>
</div>

<script>
  function setLanguage(lang) {
    var linkInput = document.getElementById('pdf-linki');
    if (lang === 'tr') {
      linkInput.value = "https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_tr.pdf";
    } else if (lang === 'en') {
      // Eğer İngilizce PDF'inin adı farklıysa, aşağıdaki kısmı kendi İngilizce dosya adınla değiştirmelisin
      linkInput.value = "https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_en.pdf"; 
    }
  }
</script>
