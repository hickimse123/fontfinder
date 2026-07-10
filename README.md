# 🔍 Font Bulucu (Font Parser)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-v1.0.0-blue.svg)]()
[![Platform](https://img.shields.io/badge/platform-Web-orange.svg)]()

**Font Bulucu**, özellikle manga, webtoon ve çizgi roman editörleri (scanlation grupları) için geliştirilmiş, web tabanlı gelişmiş bir **PSD Font ve Stil Ayrıştırıcıdır**. Bilgisayarınıza hiçbir şey kurmadan, PSD dosyalarınızı sürükleyip bırakarak içeride kullanılan tüm fontları, yazı stillerini, satır ve kelime aralıklarını saniyeler içinde tespit edebilirsiniz.

Ayrıca tek başına (standalone) çalışabildiği gibi, scanlation yönetim panellerine (Nextcloud eklentileri, TypeR sistemleri) gömülü (embedded) olarak da çalışabilecek esnek bir altyapıya sahiptir.

---

## ✨ Öne Çıkan Özellikler

- **📁 Sürükle ve Bırak ile PSD Analizi:** Birden fazla PSD dosyasını aynı anda taratın, katmanları saniyeler içinde çözümleyin.
- **⚙️ Gelişmiş Tipografi Tespiti:** Sadece font adını değil; *Yapay Kalın (Faux Bold)*, *Yapay İtalik*, *Bitişik Harf (Ligatures)*, *Kerning*, *Dikey/Yatay Ölçek*, *Satır Aralığı (Leading)*, *Harf Aralığı (Tracking)* ve *Kelime Boşluğu* değerlerini tek tek yakalar.
- **📊 Akıllı Oylama (Voting) Sistemi:** Aynı fontun farklı katmanlardaki kullanımları analiz edilerek en kararlı stil varyasyonu otomatik olarak belirlenir (gürültü filtreleme algoritması ile hatalı/istisnai kullanımlar elenir).
- **📋 Tek Tıkla Kopyalama:** Çıkarılan font ayarlarını diğer sistemlerde doğrudan kullanabilmek için özel biçimlendirilmiş ayar dizgesini (`Settings String`) anında panoya kopyalayın.
- **📥 Gelişmiş Dışa Aktarma:** 
  - **TypeR JSON:** Çıkarılan stilleri doğrudan popüler yazı programı TypeR formatında JSON olarak indirin.
  - **Font Listesi:** Kullanılan tüm fontları temiz bir metin (`.txt`) belgesi olarak dışa aktarın.
- **🔗 Panel & Depo Entegrasyonu (Embedded Mod):** Panel içi kullanımda serinin mevcut font deposunu (`admin-api.php`) sorgular; eksik fontları tespit eder, web arayüzünden doğrudan `.ttf/.otf` font yüklemesi yaptırarak eksikleri tamamlar ve serinin veri tabanına otomatik işler.
- **🌓 Dinamik Tema Desteği:** Gözü yormayan modern karanlık (dark) mod ve aydınlık (light) mod seçeneği.

---

## 🛠️ Kullanılan Teknolojiler

Proje tamamen istemci tarafında (Client-Side) çalışır, dosyalarınız hiçbir uzak sunucuya yüklenmez (Gizlilik dostudur).

- **HTML5 & CSS3:** Özelleştirilmiş grid/flex mimarisi ve modern neon/glow animasyonlar.
- **Pure JavaScript (ES6+):** Dosya işleme ve veri dönüştürme mantığı.
- **ag-psd:** PSD dosyalarının ağaç yapısını ve metin katmanı meta verilerini tarayıcıda okumak için kullanılan güçlü kütüphane.
- **Google Fonts:** Arayüz için *Chakra Petch* ve *Inter* fontları.

---

### 🌐 Canlı Uygulama & İndirme Seçenekleri

> 🚀 **Aracı tarayıcınızda canlı kullanmak için tıklayın:**  
> **[Uygulamayı Canlı Aç (GitHub Pages)](https://hickimse123.github.io/fontfinder/)**

> 💾 **İnternetsiz (Çevrimdışı) kullanmak için direkt bilgisayarınıza indirin:**  
> **[index.html Dosyasını Direkt İndir (Sağ Tıkla -> Farklı Kaydet)](https://raw.githubusercontent.com/hickimse123/fontfinder/main/index.html)**
> **[ag-psd.min.js Dosyasını Direkt İndir (Sağ Tıkla -> Farklı Kaydet)](https://raw.githubusercontent.com/hickimse123/fontfinder/main/ag-psd.min.js)**

---

*Sevgiyle üretildi.*

Created with 🚀 by **Hic Kimse**
