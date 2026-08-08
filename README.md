# Merhaba, Ben Yasin Anber 👋

<div align="center">
  <h3>Bilgisayar Mühendisi | Otomasyon | Gömülü Sistemler | Veri & Yapay Zeka</h3>
  <p><i>TED Üniversitesi Bilgisayar Mühendisliği · Uygulamalı Veri Analizi (ADA) Yan Dalı</i></p>
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yasinanber)
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YasinAnber)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yasin.anber@tedu.edu.tr)
</div>

---

## 👨‍💻 Hakkımda

Yazılımı fiziksel dünyayla buluşturan sistemler geliştirmekten; sensör verilerini işlemekten, donanım-yazılım bileşenlerini entegre etmekten ve gerçek dünya problemlerine otonom çözümler üretmekten keyif alıyorum. Bilgisayar mühendisliği eğitimim boyunca **yazılım geliştirme, veri analizi, gömülü sistemler ve endüstriyel otomasyon** alanlarında derinleştim.

*   **Endüstriyel Otomasyon:** Andritz Hydro'da gerçekleştirdiğim stajda PLC tabanlı HIPASE altyapıları üzerine çalışarak otomasyon süreçlerini uygulamalı olarak deneyimledim.
*   **Kurumsal Yazılım:** Limak Teknoloji'deki stajımda, kurumsal mimarilerde **React.js (Frontend)** ve **.NET (Backend)** katmanlarının entegrasyonu üzerine pratik tecrübe kazandım.
*   **Siber-Fiziksel Sistemler:** Donanım, sensörler ve yazılımın birleştiği en büyük başarım; TUSAŞ LIFT UP kapsamında 350+ proje arasından ilk 10'a giren ve TÜBİTAK 2209-B desteği alan **CODENGE** projesidir.

Kariyerimde; otomasyon, gömülü sistemler ve yapay zekanın kesişiminde çalışarak yenilikçi ve deterministik çözümler geliştirmeyi hedefliyorum.

---

## 🛠️ Teknik Yetkinlikler

| Alan | Teknolojiler & Araçlar |
| :--- | :--- |
| **💻 Yazılım Geliştirme** | C/C++, Java, Python, JavaScript, React.js, .NET, HTML/CSS, SQL, Git/GitHub |
| **📊 Veri Analizi & Yapay Zeka** | NumPy, Pandas, Scikit-learn, PyTorch (Veri ön işleme, model eğitimi) |
| **🔌 Gömülü Sistemler & Donanım** | Arduino, STM32, ARM LPC2148, Load Cell & HX711, Devre Tasarımı |
| **⚙️ Endüstriyel Otomasyon** | PLC Kontrol Sistemleri, HIPASE, Donanım-Yazılım Entegrasyonu |
| **🧰 Sistem & Ağ Araçları** | MATLAB, Linux/Ubuntu, Wireshark, Nmap, VMware, Vercel |

**🌍 Yabancı Diller:** 🇬🇧 İngilizce (C1) | 🇩🇪 Almanca (A1.1)

---

## ✈️ Öne Çıkan Proje: CODENGE 
**Hava Araçları İçin Ağırlık Merkezi Tespiti ve Otonom Dengeleme Sistemi**

> 🔬 *TÜBİTAK 2209-B Destekli* | 🥇 *TUSAŞ LIFT UP Top 10* | 🏆 *Genç Beyinler Yeni Fikirler Top 5* | 🎓 *EMO BPS Proje Sergisi*

Hava araçlarının kalkış öncesi ağırlık merkezini (CG) gerçek zamanlı olarak tespit etmek ve hedef konuma taşımak amacıyla geliştirilmiş donanım-yazılım entegrasyonlu otonom dengeleme platformudur. Sistem; Load Cell ve HX711 tabanlı sensörlerden alınan ağırlık verilerini işleyerek X-Y düzlemindeki ağırlık merkezini hesaplar ve hareketli mekanik karşı ağırlık sistemiyle dengeleme işlemini gerçekleştirir. Arayüz ve yazılım süreçleri takım arkadaşım Yazılım Mühendisi **Sude İpekci** tarafından yönetilmiştir.

🔗 **[Canlı Sistem & Web Sitesini İncele](https://codenge.vercel.app)** | 🌐 **[GitHub Repository](https://github.com/YasinAnber/codenge_Project)**

### 🔧 Karşılaşılan Zorluklar ve Çözümler
*   **Sensör Gürültüsü ve Kararsızlık:** 3D baskı helikopter gövdesine monte edilen load cell ve HX711 amplifikatörlerindeki titreşim/elektriksel gürültü kaynaklı dalgalanmaları çözmek için optimize edilmiş **low-pass filtreleme** uygulandı.
*   **Otonom Konumlandırma:** Çift eksenli step motorlar ve **lead-screw (vida mili)** mekanizması kullanılarak hareketli karşı ağırlığın X-Y düzleminde kontrollü konumlandırılması sağlandı. Geliştirme sürecini yönetmek için sisteme özel manuel motor kontrol test altyapısı eklendi.
*   **Gerçek Zamanlı Takip:** Python ve Tkinter tabanlı masaüstü arayüzü ile ölçüm sonuçlarının ve otonom sistem davranışlarının grafiksel olarak izlenmesi sağlandı.

### 🧠 Kritik Mühendislik Kararları
> **⚙️ Karar 1 — Tekil ve Odaklanmış Mekanik Mimari:** 
> Kontrol yapısını sadeleştirmek ve sistemin tekrarlanabilirliğini artırmak amacıyla, alternatif tasarım fikirlerinden tamamen uzaklaşılarak **tekil bir hareketli mekanik karşı ağırlık sistemine** odaklanılmıştır.
> 
> **⚙️ Karar 2 — Pivot Noktasının (0,0) Orijinine Sabitlenmesi:** 
> Dinamik hareket sırasında oluşabilecek referans sapmalarını önlemek için, karşı ağırlık kolunun dönme hareketindeki sabit ucu hem fiziksel sistemde hem de dinamik simülasyonda tam olarak **(0,0) koordinat merkezine** kilitlenmiştir.
>
> **⚙️ Karar 3 — Filtreleme Yaklaşımının Korunması:**
> Sensör verilerindeki geçici değişimlerin davranışları bozmasını önlemek adına, low-pass filtre aşamasındaki zamanlama kalibrasyon ayarlamaları (timing calibration) bypass edilerek, sistemin baseline filtreleme kurallarının o katı yapısı korunmuştur.

---

## 📂 Diğer Projeler

### 🧠 Physics-Informed Deep Learning — Dynamic Balance Prediction
Sensör verilerinden hava aracının dinamik dengesini tahmin etmek amacıyla 1D CNN, LSTM ve özel geliştirilmiş *Physics-Informed Attention* mimarisi kurgulandı. Modelin fiziksel kısıtları dikkate alması için Attention mekanizmasına özel bir *Physical Penalty Matrix* ve eğitim sürecine *speed-limit loss* fonksiyonu eklendi.
*   **Teknolojiler:** Python, PyTorch, CNN, LSTM, Attention Mechanisms
*   🔗 **[GitHub Repository](#)** | 📝 **[Medium Yazısı](#)**

### 📊 Bank Marketing Prediction
Bankacılık müşterilerinin kampanya sonucunu tahmin etmek amacıyla veri ön işleme, özellik seçimi, dengesiz veri yönetimi ve makine öğrenmesi modellerinin uçtan uca kullanıldığı tahmin modellemesi.
*   **Teknolojiler:** Python, Pandas, Scikit-learn
*   🔗 **[GitHub Repository](#)** | 🌐 **[Canlı Web Uygulaması](#)**

### 💻 Veritabanı Entegreli Araç Kiralama Sistemi
Kullanıcı, araç ve kiralama işlemlerini yöneten, SQL mimarisi üzerine inşa edilmiş ilişkisel veritabanı entegreli yazılım uygulaması.
*   **Teknolojiler:** Java, MySQL, SQL
*   🔗 **[GitHub Repository](#)**

---

## 🏭 Deneyim

**⚙️ ANDRITZ Hydro** | *Otomasyon Mühendisliği Stajyeri* 
📅 *Temmuz 2025 – Ağustos 2025*
*   PLC tabanlı HIPASE sistemi üzerinde çalışarak endüstriyel kontrol süreçlerini uygulamalı olarak deneyimledim.
*   Otomasyon sistemlerinin farklı bileşenleri arasındaki donanım-yazılım entegrasyonu ve kontrol süreçleri üzerine analizler gerçekleştirdim.

**💻 Limak Teknoloji** | *Yazılım Geliştirme Stajyeri*
📅 *Temmuz 2024 – Ağustos 2024*
*   Kurumsal yazılım projelerinde **React.js** ile frontend, **.NET** ile backend katmanlarının geliştirilmesine katkı sağladım.
*   Farklı mimari katmanların birbiriyle haberleştiği canlı bir proje ortamında uçtan uca ekip çalışması deneyimi kazandım.

---

## 🎓 Eğitim

**TED Üniversitesi** | *Bilgisayar Mühendisliği (Lisans)*
📅 *2021 – 2026* | 📍 *%100 İngilizce* | 🎯 *GPA: 3.38/4.00*
*   Yazılım mimarileri, bilgisayar ağları, donanım programlama ve yapay zeka sistemleri üzerine kapsamlı mühendislik eğitimi.

**Ek Dal:** *Uygulamalı Veri Analizi (Applied Data Analysis)*
*   Veri işleme, istatistiksel indeksleme yöntemleri ve makine öğrenmesi algoritmalarının sistemsel uygulamaları.

---

<div align="center">
  <i>Projeler, iş birlikleri veya teknik konularda fikir alışverişi için benimle iletişime geçebilirsiniz.</i>
</div>
