# ShipEntegra Jump

E-ihracat temalı, tarayıcıda çalışan kargo koşusu oyunu. Tek dosya, bağımlılık yok.

- **Mobil:** dikey düzen, dokunarak oyna, ilk dokunuşta tam ekran
- **Masaüstü / TV:** yatay düzen, fuar kiosk modu, boşta kalınca otomatik demo
- **Bölümler:** ShipEntegra · Etsy · AliExpress · Ekspres Hava Koridoru · eBay · Amazon FBA · Temu · Shopify · Balon Hattı · Walmart

## Yayınlama

Statik site. `index.html` ve yanındaki dosyaları herhangi bir statik barındırmaya koymak yeterli.

Cloudflare Pages ayarları:

| Ayar | Değer |
|---|---|
| Build command | *(boş)* |
| Build output directory | `/` |
| Framework preset | None |

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `index.html` | Oyunun tamamı (görseller, müzik ve ses efektleri gömülü) |
| `og.jpg` | Link paylaşım görseli |
| `icon-180.png`, `icon-512.png` | Ana ekran / sekme ikonu |
| `manifest.webmanifest` | Ana ekrana eklenince tam ekran dikey açılması için |
| `_headers` | Cloudflare Pages önbellek ve güvenlik başlıkları |
