✅ TEST PLAN — Trendyol Web Application
Version: 1.0
Author: Elif Taş
Date: November 2025

# 🇬🇧 1. Introduction
This Test Plan outlines the testing scope, approach, environment, and deliverables for Trendyol’s web application.
The goal is to validate the quality and stability of core user workflows, including login, product search, product display, and shopping cart operations.
# 🇹🇷 1. Giriş
Bu Test Planı, Trendyol web uygulaması için test kapsamını, yaklaşımını, test ortamını ve teslimatları tanımlar.
Amaç; giriş, ürün arama, ürün detay görüntüleme ve alışveriş sepeti işlemleri gibi temel kullanıcı akışlarının kalite ve stabilitesini doğrulamaktır.

# 🇬🇧 2. Scope of Testing
In Scope
✔ Login functionality
✔ Product search, filtering, and display
✔ Shopping cart operations (add/remove/update items)
✔ Checkout redirection (mock flow only)
✔ Basic UI & navigation
✔ Validation & error messages
✔ API response validation (high-level only)
Out of Scope
✘ Real payment processing
✘ Integration with external payment services
✘ Native mobile application
✘ Performance & load testing (separate project)
# 🇹🇷 2. Test Kapsamı
Kapsam Dahilinde
✔ Giriş (Login) fonksiyonu
✔ Ürün arama, filtreleme ve ürün detay sayfaları
✔ Alışveriş sepeti işlemleri (ekleme/kaldırma/miktar güncelleme)
✔ Ödeme yönlendirmesi (mock akış)
✔ Temel arayüz ve navigasyon
✔ Doğrulama & hata mesajları
✔ API yanıtlarının temel seviyede doğrulanması
Kapsam Dışında
✘ Gerçek ödeme işlemleri
✘ Harici ödeme servisleri entegrasyonu
✘ Native mobil uygulama
✘ Performans ve yük testleri (başka projede ele alınacak)

# 🇬🇧 3. Test Approach
Testing will be performed manually and will include:
Positive and negative test scenarios
UI/UX validation
Form validation rules
Error message verification
Test data–based checks
Retesting of fixed defects
Regression testing
Bug reporting in Jira-compatible format (simulated)
# 🇹🇷 3. Test Yaklaşımı
Testler manuel olarak gerçekleştirilecek ve şu adımları içerecektir:
Pozitif ve negatif senaryolar
UI/UX doğrulaması
Form doğrulama kuralları
Hata mesajlarının kontrolü
Test verisine dayalı kontroller
Düzeltilen hataların yeniden testi
Regresyon testleri
Jira uyumlu hata raporlama formatı (simülasyon)

# 🇬🇧 4. Test Types
Smoke Testing
Functional Testing
Regression Testing
UI Testing
Validation & Error Handling Testing
# 🇹🇷 4. Test Tipleri
Smoke Testleri
Fonksiyonel Testler
Regresyon Testleri
Arayüz (UI) Testleri
Doğrulama & Hata Yönetimi Testleri

# 🇬🇧 5. Test Environment
Browsers
Chrome (latest)
Firefox (latest)
Safari (MacOS)
Edge (optional)
Devices
Desktop
Mobile web (iOS Safari, Android Chrome)
Test Data
Predefined user accounts
Sample product data
# 🇹🇷 5. Test Ortamı
Tarayıcılar
Chrome (güncel)
Firefox (güncel)
Safari (MacOS)
Edge (opsiyonel)
Cihazlar
Masaüstü
Mobil web (iOS Safari, Android Chrome)
Test Verileri
Önceden tanımlanmış kullanıcı hesapları
Demo ürün verileri

# 🇬🇧 6. Test Deliverables
Test Plan (this document)
Test Case Set (Login, Search, Add to Cart, Checkout)
Smoke Test Checklist
Bug Reports
Test Summary Report (optional)
# 🇹🇷 6. Test Teslimatları
Test Planı (bu doküman)
Test Senaryoları Seti (Login, Search, Add to Cart, Checkout)
Smoke Test Kontrol Listesi
Hata Raporları
Test Özet Raporu (opsiyonel)

# 🇬🇧 7. Entry Criteria
Testing may begin when:
Test environment is stable
Test data is ready
Requirements are understood
Core features are accessible
# 🇹🇷 7. Giriş Kriterleri
Testlere şu durumlarda başlanabilir:
Test ortamı stabil olduğunda
Test verileri hazır olduğunda
Gereksinimler anlaşıldığında
Temel fonksiyonlara erişilebilir olduğunda

# 🇬🇧 8. Exit Criteria
Testing is complete when:
All critical tests are executed
No open blocker/critical defects remain
Smoke suite fully passes
Major regressions have been retested
# 🇹🇷 8. Çıkış Kriterleri
Testler şu koşullarda tamamlanır:
Kritik tüm testler çalıştırıldığında
Açık bloklayıcı veya kritik hata kalmadığında
Smoke suite tamamen geçtiğinde
Büyük regresyonlar yeniden test edildiğinde

# 🇬🇧 9. Risks & Assumptions
Risks
Unstable environment
Missing or unclear requirements
Delayed defect fixes
Assumptions
Requirements remain stable
Test data remains unchanged
Required browsers/devices are available
# 🇹🇷 9. Riskler & Varsayımlar
Riskler
Stabil olmayan test ortamı
Eksik veya belirsiz gereksinimler
Hata düzeltmelerinde gecikmeler
Varsayımlar
Gereksinimlerin sabit kalacağı
Test verisinin süreç boyunca değişmeyeceği
Gerekli tarayıcı ve cihazların erişilebilir olacağı

# 🇬🇧 10. Schedule
Activity	Date
Test planning	Week 1
Test case design	Week 1
Test execution	Week 2
Defect reporting & retesting	Week 2
# 🇹🇷 10. Zaman Çizelgesi
Aktivite	Tarih
Test planlama	1. Hafta
Test senaryosu tasarımı	1. Hafta
Test yürütme	2. Hafta
Hata raporlama & yeniden test	2. Hafta
