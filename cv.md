---
layout: single
title: "Özgeçmiş"
permalink: /cv/
author_profile: true
---

<style>
  /* Sayfa başlığını ve çizgiyi gizleme */
  .page__title { display: none !important; }
  .page__header { border-bottom: none !important; margin-bottom: 0 !important; padding-bottom: 0 !important; }

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
    font-size: 0.60rem !important;
    font-weight: 600;
    text-align: center;
    transition: background 0.3s;
    white-space: nowrap;
    cursor: pointer;
  }
  .cv-btn:hover { background-color: #34495e; }

  /* İçerik Boşluğu */
  .cv-content { margin-top: 50px !important; position: relative; }

  /* Bölüm Başlıkları ve Metin Boyutları */
  .cv-section-title, .ozet-alani h2 {
    color: #2c3e50;
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
    margin-top: 25px;
    margin-bottom: 15px;
    font-size: 0.95rem !important;
  }
  
  p, ul li, .ozet-alani p, .job-description {
    font-size: 0.70rem !important;
    line-height: 1.5 !important;
  }
  
  .job-title { font-size: 0.80rem !important; font-weight: 600; color: #2980b9; margin-bottom: 0 !important; }
  .company-date { font-size: 0.65rem !important; color: #7f8c8d; font-style: italic; margin-top: 2px; margin-bottom: 10px; }

  /* Form Alanı Fontları */
  .form-alani { margin-top: 50px; }
  .form-alani h3 { font-size: 0.85rem !important; }
  .form-alani label, .form-alani input { font-size: 0.70rem !important; }
</style>

<div class="cv-content">
  <div class="cv-download-container">
    <a class="cv-btn" onclick="prepareDownload('tr')"><i class="fas fa-file-pdf"></i> Türkçe CV İndir</a>
    <a class="cv-btn" onclick="prepareDownload('en')"><i class="fas fa-file-pdf"></i> Download English CV</a>
  </div>

  <div class="ozet-alani">
    <h2>Özgeçmiş Özeti</h2>
    <p>Satış Profesyoneli olarak, satış ve müşteri yönetimi alanında 15 yıllık geniş bir deneyime sahibim. 2008 yılından bu yana, küçük, orta ve büyük ölçekli müşterilerle etkili satış stratejileri geliştirerek, müşteri ihtiyaçlarını anlama ve çözüm odaklı yaklaşımlar sunma konularında başarılı sonuçlar elde ettim. İş süreçlerini optimize etme becerim sayesinde, müşteri memnuniyetini artırarak şirket hedeflerine ulaşılmasına katkı sağladım.</p>
  </div>

  <h2 class="cv-section-title">İş Deneyimleri</h2>

  <div class="job-item">
    <p class="job-title">Satış Yöneticisi</p>
    <p class="company-date">Zebra Electronics | Eylül 2024 - Ocak 2026</p>
    <p class="job-description">Şirketin ürettiği DC/AC elektrikli araç şarj ünitelerinin lisanslı CPO ve B2B müşterilerine satışını gerçekleştirdim. CPO yazılımı ve çağrı merkezi hizmetlerinin satışını yaparak müşteri ihtiyaçlarını analiz ettim, teknik ve ticari çözümler sundum. Toplamda 2 milyon USD değerinde sözleşmeler imzaladım.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Bizim Toptan Satış Mağazaları | Nisan 2022 - Mayıs 2024</p>
    <p class="job-description">Aylık ortalama %30 düzenli ciro artışı sağladım. 300+ çalışana sahip kurumsal firmaların, akaryakıt istasyonlarının ve restoran zincirlerinin gıda/gıda dışı ürün tedarik operasyonlarını planlayarak verimlilik sağladım.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Mepsan Petrol Cihazları A.Ş. | Ağustos 2016 - Nisan 2022</p>
    <p class="job-description">Üretilen akaryakıt ekipmanları ve akaryakıt dağıtım şirketleri ile iş birliği içinde projeler geliştirdim. Petrol Ofisi, Alpet, Lukoil gibi büyük akaryakıt dağıtım şirketleri ile projeler başarıyla uygulamaya geçirildi.</p>
  </div>

  <div class="job-item">
    <p class="job-title">Kurumsal Satış Yöneticisi</p>
    <p class="company-date">Nixonled - Yağmur Group & Techled Aydınlatma | Aralık 2011 - Temmuz 2016</p>
    <p class="job-description">Endüstriyel LED aydınlatma armatürlerinin pazarlama ve satış süreçlerini yönettim. Hayat Kimya, Aksa Akrilik, Arçelik, TÜPRAŞ gibi firmaları portföye kazandırdım.</p>
  </div>

  <h2 class="cv-section-title">Eğitim Bilgileri</h2>
  <ul>
    <li><strong>Marmara Üniversitesi</strong> - Teknoloji Fakültesi, Elektrik Öğretmenliği (Eylül 2023 - Devam ediyor)</li>
    <li><strong>Conley Üniversitesi</strong> - İşletme Yönetimi, Lisans (Eylül 2020 - Haziran 2022)</li>
  </ul>

  <h2 class="cv-section-title">Teknik ve Profesyonel Yetenekler</h2>
  <ul>
    <li><strong>Satış & İş Geliştirme:</strong> Kurumsal Pazarlama, Çözüm Satışı, Müşteri İlişkileri, Süreç Yönetimi.</li>
    <li><strong>Teknoloji & Yazılım:</strong> Yapay Zeka (Vibe Coding), Python (Raporlama), SAP HANA, Oracle, ERP, Autocad.</li>
  </ul>

  <h2 class="cv-section-title">Hobi ve İlgi Alanları</h2>
  <p>Yapay zeka asistanları üzerinden Vibe Coding ile çeşitli masaüstü ve mobil uygulamalar geliştirmek. Detaylar için Projeler sayfasına bakabilirsiniz.</p>
</div>

<br><br>

<div id="form-alani" class="form-alani">
  <hr>
  <h3>Özgeçmişi İndirmek İçin Bilgilerinizi Paylaşın</h3>
  <p>Kişisel verilerin güvenliği için lütfen formu doldurunuz. İndirme bağlantısı gönderim sonrası açılacaktır.</p>

  <form action="https://api.sheetmonkey.io/form/mojrerve" method="POST" style="max-width: 400px;">
    <label>Adınız Soyadınız:</label>
    <input type="text" name="Ad Soyad" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <label>E-posta Adresiniz:</label>
    <input type="email" name="E-posta" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <label>Telefon Numaranız:</label>
    <input type="tel" name="Telefon" required style="width: 100%; margin-bottom: 10px; padding: 8px; border: 1px solid #ccc; border-radius: 4px;">
    
    <input type="submit" value="Bilgileri Gönder ve CV İndir" class="cv-btn" style="width: 100%; cursor: pointer; padding: 12px; margin-top: 10px; font-size: 0.70rem !important;">
    
    <input type="hidden" id="pdf-linki" name="x-sheetmonkey-redirect" value="https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_tr.pdf">
  </form>
</div>

<script>
  function prepareDownload(lang) {
    var linkInput = document.getElementById('pdf-linki');
    var formArea = document.getElementById('form-alani');
    if (lang === 'tr') {
      linkInput.value = "https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_tr.pdf";
    } else {
      linkInput.value = "https://mustafaceliktr.github.io/assets/docs/mustafa_celik_cv_en.pdf";
    }
    formArea.scrollIntoView({ behavior: 'smooth' });
  }
</script>
