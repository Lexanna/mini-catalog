# Mini Katalog Uygulaması

Flutter ile geliştirilmiş, görseldeki Apple Store tasarımından ilham alan minimal bir e-ticaret kataloğu.

## Ekranlar

| Discover | Ürün Detayı | Sepet (Dolu) | Sepet (Boş) |
|----------|-------------|--------------|-------------|
| Ürün grid, arama, kategori filtresi | Fotoğraf, açıklama, spec tablosu | Ürün listesi, adet kontrolü | Boş durum gösterimi |

## Özellikler

- ✅ Fake Store API'dan gerçek ürün verisi
- ✅ Shimmer loading efekti
- ✅ Kategori filtresi (chip)
- ✅ Arama (gerçek zamanlı)
- ✅ Hero animasyonu (ürün görseli)
- ✅ Sepet (ekle / çıkar / adet artır-azalt)
- ✅ Provider ile state yönetimi
- ✅ CachedNetworkImage

## Kullanılan Flutter Sürümü

Flutter 3.x (Dart 3.x)

## Kurulum

```bash
# Projeyi klonla veya klasörü aç
cd mini_catalog

# Bağımlılıkları yükle
flutter pub get

# Emülatörde çalıştır
flutter run
```

## Proje Yapısı

```
lib/
├── main.dart
├── models/
│   ├── product.dart
│   └── cart_item.dart
├── providers/
│   ├── cart_provider.dart
│   └── api_service.dart
├── screens/
│   ├── discover_screen.dart
│   ├── detail_screen.dart
│   └── cart_screen.dart
└── widgets/
    └── product_card.dart
```

## API

[Fake Store API](https://fakestoreapi.com) — Ücretsiz, kayıtsız test API'ı.
