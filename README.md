# Spor Salonu (Fitness Center) Yönetim ve Randevu Sistemi

##  Proje Hakkında

Bu proje, Sakarya Üniversitesi 2025-2026 Güz Dönemi Web Programlama dersi kapsamında geliştirilmektedir. Projenin temel amacı; spor salonlarının hizmetlerini, antrenörlerin uzmanlık alanlarını ve üyelerin randevu süreçlerini dijital ortamda yönetebilen kapsamlı bir web uygulaması geliştirmektir.

Sistem, ASP.NET Core MVC mimarisi kullanılarak geliştirilecek olup, veritabanı işlemlerinde Entity Framework Core ve arayüz tasarımında Bootstrap 5 teknolojilerinden yararlanılacaktır. Ayrıca proje, kullanıcı deneyimini artırmak adına Yapay Zeka (AI) destekli egzersiz/diyet öneri sistemini de barındıracaktır.

##  Özellikler ve Kapsam

### 1. Spor Salonu ve Hizmet Yönetimi

* Spor salonu çalışma saatleri, hizmet türleri (Fitness, Yoga, Pilates vb.) tanımlanabilir.

* Hizmetlerin süre ve ücret bilgileri dinamik olarak yönetilebilir.

### 2. Antrenör (Eğitmen) Yönetimi

* Antrenörlerin uzmanlık alanları (Kilo verme, Kas geliştirme vb.) sisteme tanımlanabilir.

* Antrenör müsaitlik saatleri belirlenebilir ve randevular bu saatlere göre organize edilir.

### 3. Üye ve Randevu Sistemi

* Üyeler, uygun antrenör ve hizmete göre randevu oluşturabilir.

* Çakışma Kontrolü: Sistem, dolu saatlere randevu alınmasını engeller.

* Randevu onay mekanizması ile süreç yönetimi sağlanır.

### 4. Yapay Zeka Entegrasyonu

 Kullanıcıların vücut tipi, boy/kilo bilgileri veya yükledikleri fotoğraflar analiz edilerek *OpenAI API** (veya benzeri bir model) aracılığıyla kişiselleştirilmiş egzersiz veya diyet programı önerileri sunulur.

### 5. Raporlama ve REST API

 Sistem içerisindeki veriler (Antrenör listesi, uygunluk durumları vb.) *REST API** üzerinden dışarıya sunulur.

* LINQ sorguları ile gelişmiş filtreleme işlemleri gerçekleştirilir.

## 🛠 Kullanılan Teknolojiler

* Backend: ASP.NET Core MVC, C#

* Veritabanı: SQL Server / PostgreSQL, Entity Framework Core (ORM)

* Frontend: HTML5, CSS3, JavaScript, jQuery, Bootstrap 5

* AI Servisi: OpenAI API / Hazır AI Modelleri

* Versiyon Kontrol: Git & GitHub

##  Kullanıcı Rolleri

Projede rol bazlı yetkilendirme (Identity) kullanılacaktır:

1.  Admin: Sistemdeki tüm tanımlamaları (Salon, Antrenör, Hizmet) yapar ve raporları görüntüler.

2.  Üye: Randevu alır, geçmiş randevularını görüntüler ve AI öneri sistemini kullanır.

##  Proje Takvimi (Roadmap)

- [x] Proje konusunun belirlenmesi ve GitHub reposunun oluşturulması

- [ ] Veritabanı modellemesi ve Entity Framework kurulumu

- [ ] Admin paneli ve temel CRUD işlemlerinin kodlanması

- [ ] Üye kayıt (Register) ve Giriş (Login) ekranlarının yapılması

- [ ] Randevu sistemi ve çakışma algoritmalarının geliştirilmesi

- [ ] REST API servislerinin yazılması

- [ ] Yapay zeka entegrasyonunun sağlanması

- [ ] Arayüz iyileştirmeleri ve son kontroller

---

Geliştirici: Ümit Çetin

Öğrenci No: B231210070
