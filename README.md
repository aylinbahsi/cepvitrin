# CepVitrin (DükkanFiyat) 📱🛍️

CepVitrin, mağaza sahiplerinin veya bireysel satıcıların ürünlerini fiyatlarıyla birlikte vitrine çıkarabildiği, **Responsive (Mobil uyumlu)**, şık ve modern bir web uygulamasıdır.

## 🚀 Teknolojiler ve Özellikler

Bu proje, modern web standartları gözetilerek **tamamen statik (HTML/CSS/JS)** yapıda kurgulanmış ve arka uç (backend) işlemleri için **Google Firebase** kullanılarak buluta taşınmıştır.

- **Önyüz (Frontend):** Saf HTML, CSS (Premium Dark Mode) ve Vanilla JavaScript.
- **Kimlik Doğrulama (Auth):** Firebase Authentication kullanılarak güvenli giriş/kayıt sistemi.
- **Veritabanı (Database):** Firebase Cloud Firestore (NoSQL) ile gerçek zamanlı ve kalıcı veri saklama.
- **Tasarım:** Modern Glassmorphism (cam efekti), gradient butonlar, mikro animasyonlar ve %100 Mobil (Responsive) uyumluluk.

## 📌 Neler Yapılabilir?
- **Kullanıcı Sistemi:** Yeni mağaza hesabı açma veya mevcut hesaba giriş yapma.
- **Yönetici Modu:** Giriş yapan kullanıcılar, "Yönet" butonuna basarak kendi ürünlerini fiyatları ve stok durumlarıyla birlikte sisteme ekleyebilir, silebilir veya güncelleyebilir.
- **Arama:** Vitrindeki ürünler içinde anlık olarak (canlı) filtreleme/arama yapılabilir.
- **Bulut Senkronizasyonu:** Sayfa yenilense veya başka bir cihazdan girilse bile veriler Firebase üzerinden otomatik olarak geri yüklenir.

## 🛠️ Kurulum ve Çalıştırma

Projede herhangi bir sunucu (Node.js vb.) çalıştırmanıza gerek yoktur! 
Projeyi bilgisayarınıza indirdikten sonra sadece **`index.html`** dosyasını tarayıcınızda (Chrome, Safari vb.) açmanız yeterlidir.

*(Firebase bağlantı ayarları uygulamanın içine entegre edilmiştir. Kendi Firebase projenizi bağlamak isterseniz, `index.html` içindeki `firebaseConfig` değişkenini kendi projenizin API anahtarlarıyla değiştirebilirsiniz.)*

## 🌐 Canlı Yayın (Deploy)
 **Netlify** üzerinden yayınlandı. https://cepvitrin.netlify.app/ 
