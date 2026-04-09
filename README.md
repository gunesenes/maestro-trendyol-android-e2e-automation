# 🚀 Maestro Trendyol Android E2E Automation

Bu proje, Trendyol Android uygulaması üzerinde **Maestro** framework'ü kullanılarak yazılmış, uçtan uca kapsamlı bir test senaryosudur.

## 📋 Test Senaryosu Özeti
- **Arama:** "Kazak" araması ve ürün listeleme.
- **Filtreleme:** Beden, sıralama ve kategori bazlı dinamik filtreler.
- **Ürün Etkileşimi:** Resimler arası `swipe` (kaydırma) ve favorilere ekleme.
- **Sepet Yönetimi:** Ürün ekleme, adet artırma/azaltma ve sepetten silme.
- **Giriş İşlemleri:** Kullanıcı girişi ve Google Autofill yönetimi.
- **Adres Modülü:** Dinamik veri girişi (`inputRandomText`) ile yeni adres ekleme.
- **Hesap Yönetimi:** Hesap silme ve güvenli çıkış yapma.

## 🛠 Kullanılan Teknolojiler
- **Maestro:** Mobil otomasyon framework'ü.
- **ADB:** Cihaz etkileşimleri.
- **YAML:** Test senaryo dili.

## 🏃 Testi Çalıştırma
Cihazınız bağlıyken terminale şunu yazın:
`maestro test TrendyolTest.yaml`
