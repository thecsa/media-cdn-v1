# 🌐 media-cdn-v1

> **Statik Medya & Varlık Dağıtım Deposu (Static Media CDN)**  
> Web siteleri, açık kaynak projeler, dokümantasyonlar ve bloglar için küresel CDN ağları üzerinden hızlı ve optimize edilmiş görsel barındırma çözümü.

---

[![GitHub Repo Size](https://img.shields.io/github/repo-size/thecsa/media-cdn-v1?style=flat-square&color=blue)](https://github.com/thecsa/media-cdn-v1)
[![CDN Status](https://img.shields.io/badge/CDN-jsDelivr%20%7C%20Fastly-orange?style=flat-square)](https://www.jsdelivr.com/)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](#lisans)

---

## 🚀 CDN Erişim Yöntemleri

Bu depodaki tüm medya dosyalarına küresel CDN altyapıları veya doğrudan GitHub üzerinden erişebilirsiniz. En yüksek hız ve önbellekleme (caching) performansı için **jsDelivr** önerilir.

### 1. jsDelivr CDN *(Önerilen)*
Küresel Edge sunucuları (Cloudflare & Fastly) üzerinden anında dağıtım ve yüksek performans sağlar:
```text
https://cdn.jsdelivr.net/gh/thecsa/media-cdn-v1@main/<dosya-adi>
```
*Örnek:*
```text
https://cdn.jsdelivr.net/gh/thecsa/media-cdn-v1@main/20261102_171450.png
```

### 2. GitHub Raw
Doğrudan kaynak erişimi:
```text
https://raw.githubusercontent.com/thecsa/media-cdn-v1/main/<dosya-adi>
```

### 3. Statically CDN
Alternatif global statik içerik dağıtım ağı:
```text
https://cdn.staticaly.com/gh/thecsa/media-cdn-v1/main/<dosya-adi>
```

---

## 💻 Kullanım Örnekleri

### Markdown İçerisinde
```markdown
![Örnek Görsel](https://cdn.jsdelivr.net/gh/thecsa/media-cdn-v1@main/20261102_171450.png)
```

### HTML (`<img>` Etiketi)
```html
<img 
  src="https://cdn.jsdelivr.net/gh/thecsa/media-cdn-v1@main/20261102_171450.png" 
  alt="Örnek Görsel" 
  loading="lazy" 
/>
```

### CSS İçerisinde
```css
.hero-banner {
  background-image: url('https://cdn.jsdelivr.net/gh/thecsa/media-cdn-v1@main/20261102_171450.png');
  background-size: cover;
  background-position: center;
}
```

---

## ✨ Özellikler

- ⚡ **Ultra Düşük Gecikme:** Global CDN POP noktalarından önbelleklenmiş içerik teslimatı.
- 📦 **Bant Genişliği Tasarrufu:** Ana sunucunuzdan statik dosya yükünü alarak maliyet ve performans avantajı sağlar.
- 🔒 **Güvenilir & Kesintisiz:** GitHub ve jsDelivr altyapısı sayesinde yüksek erişilebilirlik (%99.9+ SLA).
- 🏷️ **Versiyonlanabilir:** `@main` yerine belirli bir commit hash veya tag kullanılarak değişmez (immutable) önbellek oluşturulabilir.

---

## 📁 Dosya Adlandırma Kuralları

Depoya dosya eklerken çakışmaları önlemek için aşağıdaki formatlar tercih edilir:
- **Tarih Damgası:** `YYYYMMDD_HHMMSS.ext` *(Örn: `20261104_152332.jpeg`)*
- **Kategori / İsim:** `kategori-aciklama.ext` *(Örn: `banner-docs-hero.png`)*

---

## 📄 Lisans

Bu depoda barındırılan içerikler aksi belirtilmedikçe [MIT](LICENSE) lisansı altındadır.
