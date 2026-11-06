# 🏫 Sınıf Oturma Planı (Akıllı & Adil Oturma Düzeni)

[![İndirme Sayısı](https://img.shields.io/github/downloads/bbbaysal/Sinif-Oturma-Plani/total.svg?style=flat-square&color=success)](https://github.com/bbbaysal/Sinif-Oturma-Plani/releases)
[![Sürüm](https://img.shields.io/github/v/release/bbbaysal/Sinif-Oturma-Plani?style=flat-square&color=blue)](https://github.com/bbbaysal/Sinif-Oturma-Plani/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square&logo=windows)](https://github.com/bbbaysal/Sinif-Oturma-Plani)
[![Lisans](https://img.shields.io/badge/Lisans-MIT-green?style=flat-square)](LICENSE)

Öğretmenler için geliştirilmiş; sınıf listelerini **e-Okul**'dan tek tıkla çekebilen, öğrencileri haftalık olarak **adil ve dengeli** bir şekilde rotasyona tabi tutan, dönem ortası öğrenci değişimlerini destekleyen, **A4 PDF** ve **Excel (.xlsx)** çıktıları üreten modern ve taşınabilir (portable) bir masaüstü uygulamasıdır.

---

## 🌟 Öne Çıkan Özellikler

- 🌐 **Dahili e-Okul Entegrasyonu:** Dahili WebView2 tarayıcısı ile e-Okul'a güvenle giriş yapın; sınıf listesini (numara ve ad-soyad) tek tıkla programa aktarın.
- 🔄 **Adil Rotasyon Algoritması:** Öğrencilerin yerlerini haftalık periyotlarla otomatik olarak kaydırır. Hiçbir öğrenci sürekli arka sırada ya da kapı kenarında kalmaz.
- 🎯 **Ara Dönem Öğrenci Desteği:** Yıl ortasında yeni öğrenci geldiğinde veya ayrıldığında, geçmiş haftaların düzenini bozmadan seçilen haftadan itibaren planı yeniden optimize eder.
- 🖨️ **Baskıya Hazır A4 PDF:** Sınıf panosuna veya öğretmen masasına asılabilecek yüksek çözünürlüklü A4 oturma krokisi çıktısı.
- 📊 **Modern Excel (.xlsx) Desteği:** Her haftayı ayrı çalışma sayfasında (sheet) sunan, renk kodlu ve uyarısız açılan modern Excel çıktısı.
- 🚀 **Taşınabilir / Portable (Kurulumsuz):** Flash belleğinize atıp okulda, akıllı tahtada veya evinizde doğrudan çalıştırabilirsiniz. Verileriniz programın yanındaki `Veriler` klasöründe saklanır.

---

## 🖥️ Arayüz Önizlemesi

<img width="1166" height="713" alt="2026-11-07 00_26_41-Sınıf Oturma Planı Sistemi" src="https://github.com/user-attachments/assets/3eae191a-0fbe-4334-93a1-a4c27a89f703" />
<img width="1165" height="713" alt="2026-11-07 00_28_04-Sınıf Oturma Planı Sistemi" src="https://github.com/user-attachments/assets/aed92d28-52b9-4b78-933a-825737f6d10d" />

---

## 🚀 Hızlı Başlangıç & Kullanım

1. **İndirin:** [Releases](https://github.com/bbbaysal/Sinif-Oturma-Plani/releases) sayfasından en güncel `Sinif_Oturma_Plani_v1.0.zip` dosyasını indirin.
2. **Arşivden Çıkarın:** ZIP dosyasını dilediğiniz bir klasöre veya doğrudan flash belleğinize çıkartın.
3. **Çalıştırın:** `Sınıf Oturma Planı.exe` dosyasına çift tıklayarak uygulamayı başlatın.
4. **Planınızı Oluşturun:**
   - İster **e-Okul** butonuna basarak listenizi otomatik çekin, ister isimleri kutucuğa yapıştırın.
   - **"Planı Oluştur"** butonuna basarak haftalık krokileri oluşturun.
   - **"PDF Olarak İndir"** veya **"Excel'e Aktar"** butonlarıyla çıktılarınızı alın.

---

## 📁 Dosya ve Klasör Yapısı

Program çalışırken dosyalarınızı otomatik olarak şu hiyerarşide düzenler:

```text
📁 Sınıf Oturma Planı/
│
├── 📁 Veriler/                       <-- Tüm kişisel verileriniz burada toplanır
│   ├── 📁 Planlar/                   (Kayıtlı *.plan.json oturma planları)
│   ├── 📁 Listeler/                  (İçe aktarılan veya e-okuldan çekilen listeler)
│   └── 📁 Çıktılar/                  (Oluşturulan PDF ve .xlsx dosyaları)
│
├── 📁 lib/                           (Gerekli DLL kütüphaneleri)
├── 📁 runtimes/                      (WebView2 çekirdek bileşenleri)
├── 📄 Sınıf Oturma Planı.exe         (Ana çalıştırılabilir dosya)
└── 📄 Sınıf Oturma Planı.exe.config
```

---

## 🛠️ Kullanılan Teknolojiler

- **Dil & Çatı:** C# / .NET Framework 4.7.2
- **Arayüz:** WPF (Windows Presentation Foundation) & WinForms
- **Web Motoru:** [Microsoft.Web.WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
- **PDF İşleme:** [UglyToad.PdfPig](https://github.com/UglyToad/PdfPig)
- **Ofis Entegrasyonu:** Microsoft.Office.Interop.Excel (.xlsx / OpenXML)

---

## ⚙️ Sistem Gereksinimleri

- **İşletim Sistemi:** Windows 10 / Windows 11 (Windows 7/8 için .NET Framework 4.7.2 gerekir).
- **Ek Bileşen:** e-Okul tarayıcısı için *Microsoft Edge WebView2 Runtime* (Windows 10 ve 11'de varsayılan olarak yüklüdür).

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak paylaşılmıştır. Eğitim camiasına faydalı olması dileğiyle!

