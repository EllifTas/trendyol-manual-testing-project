✅ TEST PLAN — Trendyol Web Application
Version: 1.0
Author: Elif Taş
Date: November 2025
🇬🇧 1. Introduction
This Test Plan outlines the scope, approach, environment, and deliverables for Trendyol’s web application testing activities. The goal is to ensure the stability and quality of key workflows, including login, search, product display, and cart operations.
🇹🇷 1. Giriş
Bu Test Planı, Trendyol web uygulaması için test kapsamını, yaklaşımını, ortamı ve teslimatları tanımlar. Amaç; giriş, arama, ürün görüntüleme ve alışveriş sepeti işlemleri gibi kritik kullanıcı akışlarının kalite ve stabilitesini doğrulamaktır.

🇬🇧 2. Scope of Testing
In Scope / Kapsam Dahilinde
Login functionality / Giriş fonksiyonu
Product search, filtering, and display / Ürün arama, filtreleme ve görüntüleme
Shopping cart operations (add/remove/update) / Sepet işlemleri (ekle/kaldır/güncelle)
Checkout redirection (mock only) / Ödeme yönlendirme (mock akış)
Basic UI & navigation / Temel arayüz ve navigasyon
Form validation & error messages / Doğrulama ve hata mesajları
API response validation (high-level) / API yanıtlarının temel seviyede doğrulanması
Out of Scope / Kapsam Dışında
Real payment processing / Gerçek ödeme işlemleri
External payment system integrations / Harici ödeme sistemleri entegrasyonu
Native mobile application / Native mobil uygulama
Performance & load testing / Performans & yük testleri

🇬🇧 3. Test Approach
Testing will be conducted manually and will include:
Positive test scenarios / Pozitif senaryolar
Negative test scenarios / Negatif senaryolar
UI/UX validation / UI/UX doğrulaması
Form field validation / Form alanı doğrulaması
Error message checks / Hata mesaj kontrolü
Data-driven checks / Veri odaklı kontroller
Retesting of fixed defects / Düzeltilen hataların yeniden testi
Regression testing / Regresyon testleri
Jira-style bug reporting (simulated) / Jira tarzı hata raporlama (simülasyon)
🇹🇷 3. Test Yaklaşımı
Testler manuel olarak yürütülecek ve aşağıdaki adımları içerecektir:
Pozitif ve negatif senaryolar / Positive & negative scenarios
UI/UX doğrulaması / UI/UX validation
Form doğrulama kuralları / Form validation checks
Hata mesajı doğrulama / Error message checks
Veri tabanlı testler / Data-driven tests
Düzeltilen hataların yeniden testi / Retesting
Regresyon testleri / Regression
Jira uyumlu hata raporlama / Jira-style reporting

🇬🇧 4. Test Types / Test Tipleri
Smoke Testing / Smoke Testleri
Functional Testing / Fonksiyonel Testler
Regression Testing / Regresyon Testleri
UI Testing / Arayüz Testi
Validation & Error Handling Testing / Doğrulama & Hata Yönetimi Testleri

🇬🇧 5. Test Environment
Browsers / Tarayıcılar
Chrome (latest) / Chrome (güncel)
Firefox (latest) / Firefox (güncel)
Safari (MacOS) / Safari (MacOS)
Edge (optional) / Edge (opsiyonel)
Devices / Cihazlar
Desktop / Masaüstü
Mobile Web: iOS Safari & Android Chrome / Mobil Web: iOS Safari & Android Chrome
Test Data / Test Verileri
Predefined user accounts / Ön tanımlı kullanıcı hesapları
Demo product data / Demo ürün verileri

🇬🇧 6. Test Deliverables / Test Teslimatları
Test Plan / Test Planı
Test Case Set (Login, Search, Add to Cart, Checkout) / Test Senaryoları Seti
Smoke Test Checklist / Smoke Test Kontrol Listesi
Bug Reports / Hata Raporları
Test Summary Report (optional) / Test Özet Raporu (opsiyonel)

🇬🇧 7. Entry Criteria / Giriş Kriterleri
Test environment is stable / Test ortamı stabil
Test data is ready / Test verisi hazır
Requirements are understood / Gereksinimler anlaşıldı
Core features accessible / Temel fonksiyonlara erişim var

🇬🇧 8. Exit Criteria / Çıkış Kriterleri
All critical test cases executed / Tüm kritik testler çalıştırıldı
No open blocker or critical defects remain / Açık bloklayıcı veya kritik hata yok
Smoke suite fully passed / Smoke seti tamamen geçti
Major regressions retested / Büyük regresyon testleri yeniden çalıştırıldı

🇬🇧 9. Risks & Assumptions / Riskler ve Varsayımlar
Risks / Riskler
Unstable environment / Stabil olmayan ortam
Missing or unclear requirements / Eksik veya belirsiz gereksinimler
Delayed defect fixes / Hata düzeltmelerinin gecikmesi
Assumptions / Varsayımlar
Requirements remain stable / Gereksinimler sabit kalacak
Test data will remain unchanged / Test verisi süreç boyunca değişmeyecek
Required devices are available / Gerekli cihazlar erişilebilir

🇬🇧 10. Schedule / Zaman Çizelgesi
Test planning — Week 1 / Test planlama — 1. Hafta
Test case design — Week 1 / Test senaryosu tasarımı — 1. Hafta
Test execution — Week 2 / Test yürütme — 2. Hafta
Defect reporting & retesting — Week 2 / Hata raporlama & yeniden test — 2. Hafta
