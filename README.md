# Uzay Gemisi Savaşı Oyunu

Bu proje, HTML5 Canvas ve JavaScript kullanılarak geliştirilmiş bir uzay gemisi savaş oyunudur. Oyuncu uzay gemisini kontrol ederek düşman gemileri ve meteorları yok etmeye çalışır.

## Teknolojiler

- **HTML5** - Oyun arayüzü ve yapısı
- **CSS3** - Stil ve görsel tasarım
- **JavaScript** - Oyun mantığı ve animasyonlar
- **Canvas API** - 2D grafik rendering

## Oyun Kontrolleri

### Temel Kontroller
- **← →** (Sol/Sağ Ok Tuşları) - Uzay gemisini hareket ettir
- **SPACE** (Boşluk) - Normal mermi ateşle
- **S** - Kalkan aktive et (3 saniye sürer, cooldown var)
- **F** - Alev topu fırlat (3 hak, delip geçer)

### Ek Mermi Türleri
- **B** - Seken mermi (kenarlardan sekip 3 kez zıplar)
- **A** - Animasyonlu mermi (parıldayan efekt)

## Oyun Özellikleri

- **Düşman Gemileri**: Otomatik hareket eden ve ateş açan düşmanlar
- **Meteorlar**: Rastgele yönlerden gelen tehlikeli kayalar
- **Güç Sistemleri**: Kalkan ve alev topu yetenekleri
- **Hareketli Yıldızlar**: Dinamik arka plan
- **Skor Sistemi**: Düşman yok etme puanları

## Kurulum ve Çalıştırma

1. Projeyi bilgisayarınıza indirin
2. `index.html` dosyasını web tarayıcınızda açın
3. "BAŞLAT" butonuna tıklayarak oyuna başlayın

## Bilinen Sorunlar

- **Tam Ekran Butonu**: Şu anda tam ekran özelliği henüz düzgün çalışmamaktadır
- Ses dosyaları internet bağlantısı gerektirir (CDN üzerinden yüklenir)

## Oyun Mekanikleri

- **Can Sistemi**: 3 can ile başlarsınız
- **Kalkan**: S tuşu ile aktive edilir, 3 saniye sürer
- **Alev Topu**: F tuşu ile kullanılır, 3 hakkınız var
- **Skor**: Her düşman 10 puan değerindedir

## Geliştirme Notları

Oyun tamamen vanilla JavaScript ile yazılmıştır, herhangi bir framework kullanılmamıştır. Canvas API kullanılarak 2D grafik rendering yapılmaktadır.

---

İyi eğlenceler! 🚀
