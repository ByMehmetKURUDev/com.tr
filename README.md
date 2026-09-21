By Mehmet KURU Dev | Full Stack Developer
Favicon Samandıra'dan Global'e Kod
⚡ PageSpeed 100/100 (Desktop & Mobile) | CLS 0 | LCP <1.5s | Ultra Optimize
🌐 Live Demo
Site: https://mehmetkuru.dev | https://bymehmetkurudev.github.io/com.tr/
GitHub: https://github.com/ByMehmetKURUDev
📸 Önizleme
Desktop
Mobile
Performance
Best Practices
SEO
Accessibility
✨ Özellikler
BY MEHMET KURU DEV curved banner
Hero: "mehmet — Full Stack, Samandıra merkezli, sokak × kod"
Avatar: 3D tilt (CSS only), WebP optimize (23KB)
Projeler: NEXT.JS • STRIPE • 2025, Shopify dönüşüm hikayeleri
Testimonial: %40 dönüşüm artışı
Blog: Next.js 15, Tailwind v4, Freelance'tan Global'e
Samandıra Terminal v4.1 + Samandıra Jump oyunu
İletişim: WhatsApp + Telefon + E-posta entegrasyonu
🚀 Ultra Optimizasyon - Nasıl 100 Skor Alındı?
Bu proje orijinal 2.1MB React bundle'dan ~48KB ultra optimize hale getirildi.
Optimizasyon	Önce	Sonra	Kazanç
HTML	2.1MB (React)	~48KB minify	98% ↓
Avatar	1.3MB base64 PNG	23KB WebP (512w) + 17KB (400w)	98% ↓
CSS	49KB Tailwind	~3KB critical inline	94% ↓
JS	2MB bundle	~1KB vanilla (defer)	99.9% ↓
Font	Google Fonts blocking	System font stack (0 blocking)	100% ↓
Favicon	Yok	ICO + PNG (6KB)	-
Teknik Detaylar:
html
<!-- LCP Optimize -->
<link rel="preload" as="image" 
      href="avatar-512.webp" 
      imagesrcset="avatar-400.webp 400w, avatar-512.webp 512w"
      fetchpriority="high">

<img src="avatar-512.webp"
     srcset="avatar-400.webp 400w, avatar-512.webp 512w"
     sizes="(max-width:768px) 400px, 512px"
     width="512" height="512"
     fetchpriority="high"
     decoding="async"
     alt="Mehmet Kuru Dev">

<!-- Favicon -->
<link rel="icon" type="image/x-icon" href="favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
<link rel="apple-touch-icon" sizes="180x180" href="favicon-180.png">

<!-- Fonts - System stack (0 blocking) -->
font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
CLS 0: width/height + aspect-ratio: 1/1 + min-height container
LCP <1.5s: Avatar + hero text preload, kritik CSS inline, fetchpriority=high
INP <150ms: Passive listeners, rAF throttled, JS defer
Render-blocking 0: Tek dosya HTML, CSS inline, JS defer, preconnect only
Responsive: srcset 400w/512w, sizes, mobile particle %50 azaltıldı
Ajan Tabanlı Tarama 3/3: Lighthouse Best Practices, SEO, Accessibility 100
📁 Dosya Yapısı
com.tr/
├── index.html              # Ultra optimize ~48KB (eski 2.1MB)
├── avatar-512.webp         # Desktop LCP - 23KB (eski 1.3MB)
├── avatar-400.webp         # Mobile LCP - 17KB
├── favicon.ico             # Multi-size ICO (16,32,48)
├── favicon-16.png          # 629 bytes
├── favicon-32.png          # 1.6KB
├── favicon-180.png         # Apple Touch - 30KB
├── favicon-192.png         # Android - 34KB
├── favicon.png             # Genel - 1.6KB
├── CNAME                   # mehmetkuru.dev
└── README.md               # Bu dosya
🛠️ Kurulum
GitHub Pages ile:
Repo'yu klonla veya dosyaları indir:
bash
git clone https://github.com/ByMehmetKURUDev/com.tr.git
cd com.tr
Dosyaları GitHub'a yükle:
index.html + avatar-*.webp + favicon.* + CNAME
GitHub Pages aktif et:
Settings > Pages > Source: main / (root) > Save
2 dakika bekle
PageSpeed test et:
https://pagespeed.web.dev/analysis/https-bymehmetkurudev-github-io-com-tr/
Desktop 100/100, Mobile 100/100 ✅
Lokal Çalıştırma:
bash
# Python ile
python -m http.server 8000

# Node ile
npx serve .
Tarayıcıda: http://localhost:8000
🎨 Tasarım Sistemi
Renkler:
Background: #0a0a0a (koyu tema sabit)
Accent: #FF00FF (magenta)
Text: #ffffff / #a1a1aa (zinc)
Fontlar: System font stack (performans için)
Eski: Anton + Space Grotesk (Google Fonts blocking)
Yeni: system-ui, -apple-system, Segoe UI, Roboto
Kartlar: border: 1px solid #27272a, border-radius: 12px, backdrop-blur
Animasyon: Sadece CSS transform + transition (JS yok)
📱 İletişim
Telefon / WhatsApp: 0541 296 58 78 - tel:+905412965878
E-posta: mehmetkuru.dev@gmail.com
GitHub: https://github.com/ByMehmetKURUDev
Konum: Samandıra, İstanbul - Global'e Kod
html
<!-- İletişim Linkleri -->
<a href="https://wa.me/905412965878">WhatsApp: 0541 296 58 78</a>
<a href="tel:+905412965878">Tel: 0541 296 58 78</a>
<a href="mailto:mehmetkuru.dev@gmail.com">mehmetkuru.dev@gmail.com</a>
<a href="https://github.com/ByMehmetKURUDev">GitHub</a>
🔧 Değişiklik Geçmişi
v5.0 (Ultra 100):
Favicon eklendi + "By Mehmet KURU Dev | Full Stack Developer" başlık
Alt açıklama metni kaldırıldı (temiz footer)
Ultra optimize: 2.1MB → 48KB, PageSpeed 100/100
Avatar WebP 400w/512w preload, CLS 0, LCP <1.5s
v4.1:
Sesli komut butonu kaldırıldı (V tuşu / mikrofon)
Açık/koyu tema butonu kaldırıldı (sadece koyu tema sabit)
İletişim güncellendi: 0541 296 58 78 / mehmetkuru.dev@gmail.com
v4.0:
Samandıra Terminal v4.1 + Voice + 3D
Samandıra Jump oyunu
📊 PageSpeed Sonuçları
Test edilen URL: https://bymehmetkurudev.github.io/com.tr/
Desktop: 100/100 Performance, 100 Accessibility, 100 Best Practices, 100 SEO
Mobile: 100/100 Performance, 100 Accessibility, 100 Best Practices, 100 SEO
Tarama: 3/3 yeşil (Ajan Tabanlı)
Önceki analiz (düşük skor): ggca0fximj → Düzeltildi ✅
📄 Lisans
© 2025 mehmetkuru.dev - By Mehmet KURU Dev | Full Stack Developer
Samandıra'dan Global'e Kod — Sokak × Kod
🙏 Teşekkürler
Samandıra - İlham kaynağı
PageSpeed Insights - 100 skor rehberliği
GitHub Pages - Free hosting
Made with ❤️ in Samandıra, Istanbul
"Fikrini, hedefini, rakibini didik didik ediyorum. Samandıra'da çay + not defteri."
