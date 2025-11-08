# KBÜ not-hesaplama# 




**KBÜ Not Hesaplayıcı**, Karabük Üniversitesi öğrencileri için geliştirilen, not hesaplamayı kolaylaştıran modern bir web uygulamasıdır.  
Vize, yıl içi çalışma, final ve bütünleme notlarını girerek **başarı notunu**, **harf notunu** ve **geçip geçmediğini** anında hesaplar.

---

## 📘 İçindekiler
- [Özellikler](#-özellikler)
- [Ekran Görüntüleri](#-ekran-görüntüleri)
- [Hesaplama Mantığı](#-hesaplama-mantığı)
- [Kullanım](#-kullanım)
- [Dosya Yapısı](#-dosya-yapısı)
- [Canlı Demo](#-canlı-demo)
- [Teknolojiler](#-teknolojiler)
- [Katkıda Bulunma](#-katkıda-bulunma)
- [Lisans](#-lisans)
- [Geliştirici](#-geliştirici)

---

## 🚀 Özellikler

- 🧮 **Otomatik Not Hesaplama:**  
  Vize, yıl içi ve final/bütünleme notlarını gir; başarı notun anında hesaplanır.
  
- ⚙️ **KBÜ Harf Notu Sistemi:**  
  Üniversitenin resmi sistemine göre A1’den F3’e kadar harf notu belirlenir.

- 📉 **Durum Analizi:**  
  Geçti/Kaldı durumu ve açıklama otomatik olarak gösterilir.

- 🚫 **Devamsızlık & Sınava Girmeme Durumu:**  
  F1 (devamsız) ve F2 (sınava girmedi) kontrolü mevcuttur.

- 🧹 **Form Sıfırlama:**  
  “Sıfırla” butonu ile tüm alanları temizle.

- 💻 **Mobil Uyumlu & Modern Tasarım:**  
  Responsive arayüz ile tüm cihazlarda sorunsuz çalışır.

| Başarı Notu    | Harf Notu | Durum | Açıklama             |
| -------------- | --------- | ----- | -------------------- |
| 90 - 100       | A1        | Geçti | Mükemmel başarı      |
| 80 - 89        | A2        | Geçti | Çok iyi              |
| 70 - 79        | B1        | Geçti | İyi                  |
| 65 - 69        | B2        | Geçti | Orta-iyi             |
| 60 - 64        | C         | Geçti | Yeterli              |
| < 60           | F3        | Kaldı | Başarı notu yetersiz |
| Devamsız       | F1        | Kaldı | Derse devam etmedi   |
| Sınava Girmedi | F2        | Kaldı | Sınava katılmadı     |

kbu-not-hesaplayici/
│
├── index.html       # Ana sayfa (form + sonuç kartı)
├── style.css        # Görsel tasarım dosyası
├── script.js        # Hesaplama mantığı (JavaScript)
└── README.md        # Proje açıklaması (bu dosya)



