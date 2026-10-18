<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img alt="Tarik Tunc — Studio & Engineering" src="assets/banner-light.svg" width="100%">
  </picture>
</p>

> **Yazılım Mühendisliği, Yüksek Performanslı Masaüstü Sistemleri ve Erişilebilirlik Mimarisi**  
> Masaüstü araçları (Electron, Rust, Swift), modern web bileşenleri ve uluslararası standartlara (WCAG 2.2 AA, EAA 2025, KVKK/GDPR) tam uyumlu bağımsız yazılımlar geliştiriyorum.

---

## Öne Çıkan Ürünler ve Sistemler

| Proje / Sistem | Açıklama ve Temel Yetenekler | Teknoloji Yığını | Canlı ve Dokümantasyon |
|---|---|---|---|
| **Polaris** | Akıllı ekran kaydı ve kurgu stüdyosu. Otomatik tıklama zoom'u, 120 Hz imleç yumuşatma, dinamik kamera balonu ve kayıpsız WASAPI çift kanal ses senkronu. %100 yerel ve gizlilik odaklı. | `TypeScript` `Electron` `Rust` `Swift` `FFmpeg` | [Canlı İndirme Sayfası](https://tariktunc.github.io/polaris-app/)<br>[v0.1.0-beta Sürümü](https://github.com/tariktunc/polaris-app/releases/tag/v0.1.0-beta)<br>[Kaynak Reposu](https://github.com/tariktunc/polaris-app) |
| **Accessibility Widget** | WCAG 2.2 AA ve EAA 2025 uyumlu yerel kullanıcı tercih paneli. Overlay anti-pattern içermez; 7 erişilebilirlik tercihi, 9 dil ve işletim sistemi sinyallerine saygılı mimari. | `Preact` `Web Components` `Shadow DOM` `WCAG 2.2 AA` | [Dokümantasyon & Kod](https://github.com/tariktunc/accessibility-widget)<br>[NPM Paketi](https://www.npmjs.com/package/@blakfy/accessibility-widget) |
| **Blakfy Cookie Consent** | KVKK, GDPR ve CCPA regülasyonlarına uyumlu, sıfır bağımlılıklı çerez onay çözümü. 23 dil desteği, 18 hazır stil şablonu ve otomatik script/iframe engelleme (tag-gating). | `Vanilla JS` `CSS Variables` `Tag-Gating` | [Dokümantasyon & Kod](https://github.com/tariktunc/blakfy-cookie) |
| **NexusDeck** | Masaüstü üretkenlik ve iş akışı yönetim merkezi. Arka plan otomatik güncelleme motoru ve Ed25519 kriptografik imza doğrulama desteği. | `Rust` `Win32 API` `Ed25519` `Auto-Update` | [En Son Sürümler](https://github.com/tariktunc/nexusdeck-releases/releases/latest)<br>[Sürüm Reposu](https://github.com/tariktunc/nexusdeck-releases) |
| **Blakfy Footer** | Kurumsal ve bağımsız web platformları için çok dilli, mevzuata uygun künye ve yasal alt bilgi bileşeni. | `JavaScript` `Custom Elements` `Responsive` | [Dokümantasyon & Kod](https://github.com/tariktunc/blakfy-footer) |

---

## Mühendislik Yaklaşımı ve Prensipler

* **Yerel ve Cihaz Üstü (On-Device) Önceliği**: Kullanıcı verisini asla gereksiz yere buluta taşımayan, düşük kaynak tüketimiyle doğrudan donanım üzerinde çalışan optimizasyonlar.
* **Standartlara Tam Uyum**: Yapay zeka manipülasyonu veya yanıltıcı erişilebilirlik kaplamaları (overlay) yerine W3C WCAG 2.2, EN 301 549 ve yasal gizlilik kurallarına tam riayet.
* **Çoklu Platform ve Hibrit Altyapı**: Kullanıcı arayüzünde modern web teknolojileri, çekirdek yakalama ve sistem seviyesi işlevlerde Rust ve Swift yerel modülleri.

---

## İletişim ve Lisans

* **E-Posta**: [info@blakfy.com](mailto:info@blakfy.com)
* **GitHub**: [@tariktunc](https://github.com/tariktunc)
* **Telif Hakkı**: (c) 2026 Tarık Tunç. Tüm hakları saklıdır.
