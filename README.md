# 🎓 KBÜ Not Hesaplayıcı

![Proje Kapak Görseli]<img width="1919" height="910" alt="Ekran görüntüsü 2025-11-08 212231" src="https://github.com/user-attachments/assets/b40b1b1a-2b4d-4da0-a624-d6b3ce72be23" />


**KBÜ Not Hesaplayıcı**, Karabük Üniversitesi öğrencileri için hazırlanmış,  
vize, yıl içi, final ve bütünleme notlarını kullanarak **başarı notu**, **harf notu**  
ve **geçme durumunu** otomatik hesaplayan modern bir web uygulamasıdır.

---

## 🌐 Canlı Demo

🔗 **Uygulamayı hemen dene:**  
👉 [https://r-a743.github.io/not-hesaplama/](https://r-a743.github.io/not-hesaplama/)

---

## 📘 İçindekiler
- [Özellikler](#-özellikler)
- [Ekran Görüntüsü](#-ekran-görüntüsü)
- [Hesaplama Mantığı](#-hesaplama-mantığı)
- [Dosya Yapısı](#-dosya-yapısı)
- [Teknolojiler](#-teknolojiler)
- [Geliştirici](#-geliştirici)

---

## 🚀 Özellikler

✅ **Otomatik Not Hesaplama:**  
Girilen vize, yıl içi, final veya bütünleme notlarına göre anında hesaplama yapar.

✅ **KBÜ Harf Notu Sistemine Uygunluk:**  
A1–F3 arasında doğru harf notunu verir.

✅ **Durum ve Açıklama Gösterimi:**  
Geçti / Kaldı bilgisini ve nedenini (F1, F2, F3 vb.) açıklar.

✅ **Devamsızlık (F1) ve Sınava Girmeme (F2) Desteği:**  
Sınava girmeyen veya derse devam etmeyen öğrenciler için özel durumlar.

✅ **Responsive Tasarım:**  
Mobil, tablet ve bilgisayar ekranlarında mükemmel görünüm.

✅ **Basit, Hızlı, Arayüz Odaklı Kullanım:**  
Tek tıkla sonuç al, anında sıfırla ve tekrar hesapla.

---

## 🖼️ Ekran Görüntüsü

> ![Örnek Ekran Görüntüsü]
<img width="1919" height="910" alt="Ekran görüntüsü 2025-11-08 212231" src="https://github.com/user-attachments/assets/143dc32d-51be-4572-baff-e6aaf6fea31e" />


---

## 🧮 Hesaplama Mantığı

Başarı notu şu formül ile hesaplanır:


| Başarı Notu    | Harf Notu | Durum | Açıklama                        |
| -------------- | --------- | ----- | ------------------------------- |
| 90 - 100       | A1        | Geçti | Mükemmel başarı                 |
| 80 - 89        | A2        | Geçti | Çok iyi                         |
| 70 - 79        | B1        | Geçti | İyi                             |
| 65 - 69        | B2        | Geçti | Orta                            |
| 60 - 64        | C         | Geçti | Yeterli                         |
| < 60           | F3        | Kaldı | Başarı notu 60'ın altında       |
| Devamsız       | F1        | Kaldı | Devamsızlık nedeniyle başarısız |
| Sınava girmedi | F2        | Kaldı | Sınava katılmadı                |



- [Dosya Yapısı](#-dosya-yapısı)

not-hesaplama/
│
├── index.html       # Ana HTML sayfası (form ve sonuç alanı)
├── style.css        # Arayüz ve responsive tasarım dosyası
├── script.js        # Hesaplama mantığı (JavaScript)
└── README.md        # Proje açıklaması




🧰 Teknolojiler (#-teknolojiler)
Teknoloji	Açıklama
🧱 HTML5	Sayfa yapısı
🎨 CSS3	Arayüz ve responsive tasarım
⚙️ JavaScript (Vanilla)	Not hesaplama algoritması
☁️ GitHub Pages	Canlı demo ve hosting hizmeti




🧑‍💻Geliştirici
Geliştirici: R-a743
Proje Adı: KBÜ Not Hesaplayıcı
Canlı Demo: https://r-a743.github.io/not-hesaplama/
GitHub: https://github.com/R-a743/not-hesaplama

















# KBÜ Not Hesaplayıcı

KBÜ Not Hesaplayıcı, öğrencilerin vize, yıl içi, final ve bütünleme notlarını girerek başarı notunu, harf notunu ve durumlarını hızlıca öğrenmelerini sağlayan bir web uygulamasıdır.

Canlı demo: [https://r-a743.github.io/not-hesaplama/](https://r-a743.github.io/not-hesaplama/)

---

<details>
<summary>📷 Ekran Görüntüsü</summary>

![Ekran Görüntüsü](screenshot.png)  

*Not: `screenshot.png` dosyasını proje dizinine ekleyerek çalıştırabilirsiniz.*
</details>

<details>
<summary>✨ Özellikler</summary>

- Vize / ara sınav, yıl içi, final ve bütünleme notlarını girme.  
- Devamsızlık (F1) ve sınava girmeme (F2) durumlarını otomatik hesaplama.  
- Başarı notunu ve harf notunu anlık olarak hesaplama.  
- Kullanıcı dostu, mobil uyumlu arayüz.  
- Sıfırlama butonu ile formu temizleme.  
- Sonuçlar renkli ve okunabilir bir kartta gösterilir.  
</details>

<details>
<summary>👨‍💻 Geliştirici</summary>

- Adı: [R-A743](https://github.com/r-a743)  
- GitHub: [https://github.com/r-a743](https://github.com/r-a743)  
</details>

<details>
<summary>🧮 Hesaplama Mantığı</summary>

1. **Devamsızlık veya sınava girme durumu** kontrol edilir:  
   - Devamsız: F1 ile kaldı.  
   - Sınava girmedi: F2 ile kaldı.  

2. **Yıl içi notu**:  
   - Eğer yıl içi notu girilmemişse, vize notu kullanılır.  

3. **Sınav notu**:  
   - Bütünleme notu girilmişse final yerine geçer.  
   - Final veya bütünleme notu yoksa hesaplama yapılmaz.  

4. **Başarı notu**:  
- 50’nin altındaki sınav notu → F3  
- Başarı notu 60’ın altında → F3  
- 60-64 → C  
- 65-69 → B2  
- 70-79 → B1  
- 80-89 → A2  
- 90+ → A1  
</details>

<details>
<summary>📂 Dosya Yapısı</summary>

</details>

<details>
<summary>🛠️ Teknolojiler</summary>

- HTML5  
- CSS3  
- JavaScript (Vanilla JS)  
- Git & GitHub Pages (canlı demo için)  
</details>












