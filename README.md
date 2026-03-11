# ASP.NET Core MVC & Role-Based System Architecture

## Genel Bakış
Bu proje, .NET Core MVC mimarisi ve Entity Framework Core kullanılarak geliştirilmiş, rol tabanlı erişim kontrolü ve veri yönetim sistemlerini kapsayan teknik bir çalışmadır.

## Teknik Özellikler
* **Role-Based Authorization:** Identity altyapısı ile Admin ve Standart Kullanıcı rolleri için farklılaştırılmış erişim seviyeleri kurgulanmıştır.
* **Business Logic & Constraints:** Veri bütünlüğünü korumak adına sunucu taraflı iş mantığı kuralları (Business Rules) ve doğrulama süreçleri entegre edilmiştir.
* **Data Management (ORM):** Entity Framework Core kullanılarak asenkron CRUD operasyonları ve veritabanı ilişkileri optimize edilmiştir.
* **Architecture:** Sorumlulukların ayrılması (Separation of Concerns) prensibine uygun modüler Controller yapısı uygulanmıştır.

## Teknoloji Yığını
* **Language:** C#
* **Framework:** .NET Core MVC
* **ORM:** Entity Framework Core
* **Security:** ASP.NET Core Identity (Authentication & Authorization)
* **Database:** SQLite
