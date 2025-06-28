# D4S - Dijital Sürdürülebilirlik Çözümleri

Sürdürülebilirlik kapsamında kurumlara özel dijitalleşme hizmeti veren ve yapay zeka alanında uzmanlaşmış kuluçka firması web sitesi.

## 🚀 Web Sitesini Çalıştırma

### Basit Yöntem (Lokal)
1. `index.html` dosyasını çift tıklayarak doğrudan tarayıcınızda açabilirsiniz
2. Veya dosyaya sağ tıklayıp "Birlikte Aç" > "Web Tarayıcısı" seçeneğini kullanabilirsiniz

### Geliştirme Sunucusu ile (Önerilen)
Python kullanarak:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Node.js kullanarak:
```bash
npx serve .
```

Ardından tarayıcınızda `http://localhost:8000` adresine gidin.

## 📁 Dosya Yapısı

```
d4s/
├── index.html      # Ana HTML dosyası
├── styles.css      # CSS stilleri
├── script.js       # JavaScript işlevleri
└── README.md       # Bu dosya
```

## 🎨 Özellikler

### Ana Bölümler
- **🏠 Hero Section** - Etkileyici başlangıç ve animasyonlu kartlar
- **📖 Hakkımızda** - Şirket vizyonu, misyonu ve başarı istatistikleri
- **🔧 Hizmetlerimiz** - 4 ana hizmet kategorisi
- **👥 Ekibimiz** - Takım üyeleri ve uzman profilleri
- **💬 Müşteri Görüşleri** - Otomatik dönen testimonial slider
- **🤝 Ortaklarımız** - İş ortağı logoları ve bağlantılar
- **📞 İletişim** - İletişim formu ve iletişim bilgileri

### Teknik Özellikler
- ✅ **Responsive Tasarım** - Mobil, tablet ve masaüstü uyumlu
- ✅ **Modern CSS Grid & Flexbox** - Esnek layout sistemi
- ✅ **Smooth Animations** - CSS ve JavaScript animasyonları
- ✅ **Progressive Enhancement** - Aşamalı geliştirme yaklaşımı
- ✅ **Cross-browser Compatibility** - Tüm modern tarayıcılar desteklenir
- ✅ **SEO Friendly** - Arama motoru optimizasyonu
- ✅ **Accessibility** - Erişilebilirlik standartları

### İnteraktif Özellikler
- 🎯 **Sticky Navigation** - Scroll ile değişen navigasyon
- 📱 **Mobile Menu** - Hamburger menü sistemi
- 🔄 **Auto-play Testimonials** - Otomatik değişen müşteri yorumları
- ⚡ **Smooth Scrolling** - Yumuşak sayfa geçişleri
- 📊 **Counter Animations** - Animasyonlu sayaç efektleri
- 🌊 **Parallax Effects** - Scroll bazlı paralaks efektler

## 🎨 Renk Paleti

```css
/* Ana Renkler */
--primary-color: #2563eb    /* Mavi */
--secondary-color: #10b981  /* Yeşil */
--accent-color: #f59e0b     /* Turuncu */
--dark-color: #1f2937       /* Koyu Gri */
--light-color: #f8fafc      /* Açık Gri */
--white: #ffffff            /* Beyaz */
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px ve üzeri
- **Tablet**: 768px - 1199px
- **Mobile**: 767px ve altı

## 🔧 Özelleştirme

### Renkleri Değiştirme
`styles.css` dosyasındaki `:root` bölümündeki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary-color: #yeni-renk;
    --secondary-color: #yeni-renk;
    /* ... */
}
```

### İçerik Güncelleme
`index.html` dosyasındaki ilgili bölümleri düzenleyin:
- Şirket bilgileri
- Hizmet açıklamaları
- Ekip üyeleri
- İletişim bilgileri

### Animasyon Ayarları
`script.js` dosyasında animasyon sürelerini değiştirebilirsiniz:

```javascript
// Testimonial değişim süresi (milisaniye)
setInterval(nextTestimonial, 5000);

// Counter animasyon süresi
function animateCounter(element, target, duration = 2000)
```

## 🌐 Tarayıcı Desteği

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📞 İletişim Formu

Form şu anda frontend-only'dir. Gerçek form gönderimi için:

1. **Backend entegrasyonu** (Node.js, PHP, vb.)
2. **Form servisleri** (Formspree, Netlify Forms, vb.)
3. **Email servisleri** (EmailJS, vb.)

kullanabilirsiniz.

## 🚀 Canlı Yayına Alma

### Netlify
1. Projeyi GitHub'a yükleyin
2. Netlify'da "New site from Git" seçin
3. Repository'yi seçin ve deploy edin

### Vercel
1. Vercel CLI'ı yükleyin: `npm i -g vercel`
2. Proje klasöründe: `vercel`
3. Talimatları takip edin

### GitHub Pages
1. Projeyi GitHub repository'sine yükleyin
2. Settings > Pages > Source'u "Deploy from a branch" seçin
3. Branch'i "main" olarak ayarlayın

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'Add amazing feature'`)
4. Branch'i push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

---

**D4S Ekibi** tarafından ❤️ ile geliştirilmiştir. 