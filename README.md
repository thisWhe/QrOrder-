# 🍽️ QrOrder

# Çok İşletmeli QR Restoran Sipariş Sistemi

ASP.NET Core ile geliştirilmiş, restoran ve kafelerin QR kod üzerinden sipariş almasını sağlayan çok işletmeli (Multi-Tenant) restoran otomasyon sistemidir.

Bu proje tek bir uygulama üzerinden birden fazla işletmenin bağımsız olarak yönetilebilmesine olanak sağlar.

> ⚠️ Bu proje ticari olarak geliştirilmektedir. Kaynak kodu bu nedenle herkese açık olarak paylaşılmamaktadır.

---

# 🚀 Başlıca Özellikler

- ✅ Çok İşletmeli (Multi-Tenant) Mimari
- ✅ QR Menü Sistemi
- ✅ Gerçek Zamanlı Sipariş Yönetimi (SignalR)
- ✅ Mutfak Paneli
- ✅ Servis Paneli
- ✅ İşletme Yönetim Paneli
- ✅ Super Admin Paneli
- ✅ JWT Kimlik Doğrulama
- ✅ Rol Bazlı Yetkilendirme
- ✅ Ürün ve Kategori Yönetimi
- ✅ Sipariş Takibi
- ✅ Mobil Uyumlu Tasarım

---

# 🛠 Kullanılan Teknolojiler

- ASP.NET Core MVC
- C#
- Entity Framework Core
- SQL Server
- SignalR
- JWT Authentication
- Bootstrap
- HTML
- CSS
- JavaScript

---

# 📖 Sistem Nasıl Çalışıyor?

1. Müşteri masadaki QR kodu okutur.
2. Menü açılır ve sipariş oluşturulur.
3. Sipariş veritabanına kaydedilir.
4. SignalR ile sipariş anlık olarak mutfak ekranına iletilir.
5. Mutfak siparişi hazırladıktan sonra "Hazır" durumuna geçirir.
6. SignalR ile sipariş servis ekranına aktarılır.
7. SignalR bağlantısı kesilse bile siparişler veritabanında tutulduğu için bağlantı tekrar kurulduğunda sistem kaldığı yerden devam eder.

---

# 📸 Ekran Görüntüleri

## Ana Menü

![Ana Menü](images/menu.png)

---

## Menü (Alternatif Görünüm)

![Menü](images/menu2.png)

---

## Sepet

![Sepet](images/sepet.png)

---

## Mutfak Giriş Ekranı

![Mutfak Giriş](images/MutfakGirişEkranı.png)

---

## Mutfak Paneli

![Mutfak Paneli](images/MutfakEkranı.png)

---

## Servis Giriş Ekranı

![Servis Giriş](images/ServisGirişEkranı.png)

---

## Servis Paneli

![Servis Paneli](images/ServisEkranı.png)

---

## İşletme Admin Girişi

![İşletme Admin Giriş](images/İşletmeAdminPanelGirişi.png)

---

## İşletme Yönetim Paneli

![Admin](images/İşletmeAdminPaneli.png)

![Admin2](images/İşletmeAdminPaneli2.png)

![Admin3](images/İşletmeAdminPaneli3.png)

![Admin4](images/İşletmeAdminPaneli4.png)

![Admin5](images/İşletmeAdminPaneli5.png)

---

## Super Admin Giriş

![Super Admin Login](images/SuperAdminLogin.png)

---

## Super Admin Paneli

![Super Admin](images/SuperAdminPaneli.png)

---

# 💡 Teknik Özellikler

- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- SignalR
- JWT Authentication
- Multi-Tenant Mimari
- Responsive Tasarım

---

# 🔒 Kaynak Kodu

Bu proje aktif olarak geliştirilen ticari bir projedir.

Kaynak kodu herkese açık olarak paylaşılmamaktadır.

Vds ile test edilmiştir
