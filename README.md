# Kütüphane Yönetim Sistemi
Bu proje, bir kütüphane yönetim sistemi için temel entity'leri ve ilişkileri içeren bir Java projesidir. Aşağıda proje kurulumu ve entity'ler hakkında detaylı bilgi bulabilirsiniz.


## Kurulum
### 1.Projeyi bilgisayarınıza klonlayın veya indirin.
### 2.PostgreSQL veritabanı oluşturun.
### 3.application.properties dosyasını düzenleyerek PostgreSQL veritabanı bağlantı bilgilerinizi girin.

## Kullanılan Teknolojiler
* Java
* Spring Boot
* Maven
* PostgreSQL

## Entity Sınıfları ve İlişkileri
### Kitap (Book)
### Yazar (Author)
### Kategori (Category)
### Yayınevi (Publisher)
### Kitap Ödünç Alma (BookBorrowing)
Bu entity sınıfları ve ilişkileri, kütüphane yönetim sistemi için temel veri yapılarını ve ilişkileri sağlar. Her bir entity sınıfı, ilişkileri belirtilen şekilde tanımlanmıştır. Ayrıca, gerekli fetch ve cascade anotasyonları kullanılmıştır.
