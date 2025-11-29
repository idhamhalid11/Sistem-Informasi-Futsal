PROJECT INI HASIL MODIFIKASI DAN BERSUMBER DARI : [https://github.com/muhazmi/futsal] DAN TIDAK DIIZINKAN UNTUK DIPERJUAL BELIKAN KEPADA SIAPAPUN KECUALI SUDAH ANDA MODIFIKASI

---

<div align="center">
  <br>
  <b>🚀Sistem Informasi🚀</b>
  <h1>⚽ Booking Lapangan Futsal ⚽</h1>
  <br>
</div>

<p align="center">
  <img src="https://img.shields.io/github/languages/code-size/muhazmi/futsal" alt="GitHub code size in bytes">
  <img src="https://img.shields.io/github/commit-activity/w/muhazmi/futsal" alt="GitHub commit activity">
  <a href="https://github.com/muhazmi/futsal/issues">
    <img src="https://img.shields.io/github/issues/muhazmi/futsal" alt="GitHub issues">
  </a>
  <a href="https://github.com/muhazmi/futsal/releases">
    <img src="https://img.shields.io/github/v/release/muhazmi/futsal.svg?style=flat" alt="GitHub Release">
  </a>
</p>

![cover](ss_project/SSSistemFutsal-Dashboard.jpg)

## PERUBAHAN DAN UPDATE TERBARU :

1. Migrasi dari SQLite ke MySQL
2. Hapus Sistem Captcha
3. Perbaikan bug dan Optimasi Kode

## Fitur

1. Booking lapangan secara online
2. Nominal Omset Harian, Bulanan, dan Tahunan
3. Grafik/Statistik Omset Bulanan dalam 1 Tahun berjalan
4. Total data pada modul album, foto, event, lapangan, kategori, kontak, slider dan customer
5. Manajemen Transaksi (generate invoice berdasarkan tahun-bulan-tanggal yang akan reset setiap bulan secara otomatis)
6. Manajemen Lapangan
7. Manajemen Album dan Foto
8. Manajemen Event
9. Manajemen Kategori
10. Manajemen Slider
11. Manajemen Kontak
12. Manajemen User dan Customer
13. Profil Bisnis
14. Set Nominal Diskon Member

## Requirement

1. PHP 7.2^
2. MySQL
3. Web Server (Apache/Nginx)

## Library

1. IonAuth 2
2. Codeigniter 3 (3.1.8)
3. Bootstrap 3
4. AdminLTE 2

## Instalasi

## Menggunakan XAMPP

1. Download/Clone Project ini
2. Letakkan di folder `htdocs` (rename folder menjadi `futsal`)
3. Buat database baru di phpMyAdmin dengan nama `futsal`
4. Import file `database.sql` yang tersedia
5. Akses ke `http://localhost/futsal`

## Konfigurasi Database

Edit file `application/config/database.php`:

```php
$db['default'] = array(
    'hostname' => 'localhost',
    'username' => 'root',
    'password' => '',
    'database' => 'futsal',
    // ... konfigurasi lainnya
);


## Cara Login

1. Backend: Sebagai SuperAdmin atau Admin:
    - Akses ke `/admin/auth/login`
    - Gunakan akun SuperAdmin dengan email superadmin@gmail.com dan password: superadmin, Admin: administrator@gmail.com dan password: administrator
2. Frontend: Sebagai Customer Biasa dan Sudah Berlangganan Member
    - Akses ke `/futsal/auth/login`
    - Gunakan akun biasa dengan email `batistuta@gmail.com` dan password: asdfghjkl, Admin: `userpremium@gmail.com` dan password: asdfghjkl

## Catatan
1. TANPA CAPTCHA - Sistem login sudah dimodifikasi tanpa captcha untuk kemudahan testing
2. DATABASE MYSQL - Menggunakan MySQL sebagai database utama

3. Created by Muhammad Azmi - [muhazmi.my.id](https://muhazmi.my.id) / AmperaKoding - [amperakoding.com](https://amperakoding.com)
4. Sistem membership dilakukan secara manual dengan cara Customer menghubungi SuperAdmin. Kemudian SuperAdmin akan mengganti Tipe User Customer tersebut di backend panel sebagai SuperAdmin.

## Cara Install Local Development Server

Anda bisa menginstall xampp/wampp atau LAMPP Stack di pc/komputer/laptop yang dipakai. Tutorialnya bisa Anda ikuti disini:

1. [Cara Install Apache, MySQL, dan PHP di OS Linux (LAMPP)](https://amperakoding.com/article/cara-install-apache-mysql-dan-php-di-os-linux-lampp)
2. [Cara Install Xampp di OS Linux](https://www.muhazmi.com/2016/12/cara-install-xampp-yang-baik-dan-benar.html)
3. [Cara Install Xampp di OS Windows](https://www.muhazmi.com/2017/08/cara-install-xampp-yang-baik-dan-benar.html)

Referensi lainnya terkait SQLite3:

1. [Dari Nol: Pengalaman Menggunakan SQLite dan PHP di Laragon](https://rachmad.dev/blog/dari-nol-pengalaman-menggunakan-sqlite-dan-php-di-laragon)


👨‍💻 Developer
Kelompok 4 SMARTIC TI A UNTAD :
1. Idham Halid (F55124040)
2. Haerul Ilman (F55124018)
3. Javier Geraldo Immanuel Koagouw (F55124034)
4. Fauzhira Dwi Septiana (F5512407)
5. Ismi Fadilah (F55124024)

📝 Note: Project ini untuk keperluan edukasi dan tugas kuliah. Dilarang memperjualbelikan tanpa modifikasi signifikan/ hubungi [https://github.com/muhazmi/futsal].
```
