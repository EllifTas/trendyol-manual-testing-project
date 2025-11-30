✅ TEST PLAN — Trendyol Web Application
Version: 1.0
Author: Elif Taş
Date: November 2025
🇬🇧 1. Introduction
This Test Plan outlines the testing scope, approach, environment, and deliverables for Trendyol’s web application.
The goal is to validate core user workflows such as login, product search, product display, and shopping cart operations.
🇹🇷 1. Giriş
Bu Test Planı, Trendyol web uygulaması için test kapsamını, yaklaşımını, test ortamını ve teslimatları tanımlar.
Amaç; giriş, ürün arama, ürün detay görüntüleme ve alışveriş sepeti işlemleri gibi temel kullanıcı akışlarının kalite ve stabilitesini doğrulamaktır.
🇬🇧 2. Scope of Testing
In Scope / Kapsam Dahilinde
 Login functionality / Giriş fonksiyonu
 Product search, filtering, and display / Ürün arama, filtreleme ve görüntüleme
 Shopping cart operations (add/remove/update) / Sepet işlemleri (ekle/kaldır/güncelle)
 Checkout redirection (mock flow only) / Ödeme yönlendirmesi (mock akış)
 Basic UI & navigation / Temel UI ve navigasyon
 Validation & error messages / Doğrulama ve hata mesajları
 API response validation (high-level only) / API temel yanıt doğrulaması
Out of Scope / Kapsam Dışında
 Real payment processing / Gerçek ödeme işlemleri
 External payment provider integrations / Harici ödeme sistemleri entegrasyonu
 Native mobile application / Native mobil uygulama
 Performance & load testing / Performans ve yük testleri
🇬🇧 3. Test Approach
Testing includes / Test Yaklaşımı Şunları İçerir
 Positive test scenarios / Pozitif senaryolar
 Negative test scenarios / Negatif senaryolar
 UI/UX validation / UI/UX doğrulaması
 Form field validation / Form doğrulama kuralları
 Error message verification / Hata mesaj kontrolü
 Data-driven checks / Veri tabanlı kontroller
 Retesting fixed defects / Düzeltilen hataların yeniden testi
 Regression testing / Regresyon testleri
 Jira-style bug reporting (simulated) / Jira uyumlu hata raporlama (simülasyon)
🇬🇧 4. Test Types / Test Tipleri
 Smoke Testing / Smoke Testleri
 Functional Testing / Fonksiyonel Testler
 Regression Testing / Regresyon Testleri
 UI Testing / Arayüz Testi
 Validation & Error Handling Testing / Doğrulama & Hata Yönetimi Testleri
🇬🇧 5. Test Environment / Test Ortamı
Browsers / Tarayıcılar
 Chrome (latest) / Chrome (güncel)
 Firefox (latest) / Firefox (güncel)
 Safari (MacOS) / Safari (MacOS)
 Edge (optional) / Edge (opsiyonel)
Devices / Cihazlar
 Desktop / Masaüstü
 Mobile web: iOS Safari, Android Chrome / Mobil web: iOS Safari, Android Chrome
Test Data / Test Verileri
 Predefined user accounts / Ön tanımlı kullanıcı hesapları
 Sample product data / Demo ürün verileri
🇬🇧 6. Test Deliverables / Test Teslimatları
 Test Plan / Test Planı
 Test Case Set (Login, Search, Add to Cart, Checkout) / Test Senaryoları Seti
 Smoke Test Checklist / Smoke Test Kontrol Listesi
 Bug Reports / Hata Raporları
 Test Summary Report (optional) / Test Özet Raporu (opsiyonel)
🇬🇧 7. Entry Criteria / Giriş Kriterleri
 Test environment is stable / Test ortamı stabil
 Test data is prepared / Test verisi hazır
 Requirements are understood / Gereksinimler anlaşıldı
 Core features are accessible / Temel fonksiyonlara erişim sağlandı
🇬🇧 8. Exit Criteria / Çıkış Kriterleri
 All critical test cases executed / Tüm kritik testler çalıştırıldı
 No open blocker or critical defects remain / Açık bloklayıcı veya kritik hata yok
 Smoke suite fully passed / Smoke testleri tamamen geçti
 Major regressions retested / Büyük regresyonlar tekrar test edildi
🇬🇧 9. Risks & Assumptions / Riskler & Varsayımlar
Risks / Riskler
 Unstable environment / Stabil olmayan test ortamı
 Missing or unclear requirements / Eksik veya belirsiz gereksinimler
 Delayed defect fixes / Hata düzeltmelerinin gecikmesi
Assumptions / Varsayımlar
 Requirements remain stable / Gereksinimlerin stabil kalması
 Test data unchanged / Test verisi değişmemesi
 Required browsers & devices available / Gerekli tarayıcı ve cihazların erişilebilir olması
🇬🇧 10. Schedule / Zaman Çizelgesi
 Test planning — Week 1 / Test planlama — 1. Hafta
 Test case design — Week 1 / Test senaryosu tasarımı — 1. Hafta
 Test execution — Week 2 / Test yürütme — 2. Hafta
 Defect reporting & retesting — Week 2 / Hata raporlama & yeniden test — 2. Hafta
