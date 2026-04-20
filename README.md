# CRUD Pemesanan Makanan Sederhana

## Deskripsi

Aplikasi ini merupakan sistem pemesanan makanan berbasis web yang dibangun menggunakan framework Laravel.
Aplikasi ini memungkinkan pengguna untuk melakukan pengelolaan data pesanan makanan secara lengkap (CRUD) serta menghitung total harga secara otomatis.
## Fitur

* ✅ Tambah data pesanan makanan
* ✅ Tampilkan daftar pesanan
* ✅ Edit data pesanan
* ✅ Hapus data pesanan
* ✅ Perhitungan total harga otomatis (harga × jumlah)
* ✅ Tampilan modern menggunakan Bootstrap

## Teknologi yang Digunakan

* PHP 8+
* Laravel 10
* MySQL
* Bootstrap 5
* Laragon (Local Development)

## Struktur Data

Data yang dikelola dalam aplikasi ini meliputi:

* Nama Pelanggan
* Nama Menu
* Jumlah Pesanan
* Alamat Pelanggan

## Persyaratan Sistem

Sebelum menjalankan project ini, pastikan telah menginstall:

* PHP >= 8.x
* Composer
* Laravel
* MySQL / MariaDB
* XAMPP / Laragon

## Cara Instalasi

1. **Clone repository:**
   bash
   git clone https://github.com/Elisma09/crud-laravel.git
   cd pemesanan-makanan

2. **Install Dependency**
bash
composer install

3. **Copy File Environment**
bash
cp .env.example .env

4. **Generate Key**
bash
php artisan key:generate

5. **Konfigurasi Database**
Edit file .env:

env
DB_DATABASE=db_makanan
DB_USERNAME=root
DB_PASSWORD=

6. **Migrasi Database**
bash
php artisan migrate


Jika terjadi error atau ingin reset database:

bash
php artisan migrate:fresh

7. **Jalankan Aplikasi**
bash
php artisan serve


Buka di browser:


http://127.0.0.1:8000/pesanan

## 🌐 Alternatif (Laragon)

Jika menggunakan Laragon:

* Simpan project di folder:


C:\laragon\www\


* Jalankan Laragon → Start All
* Akses melalui:


http://pemesanan-makanan.test/pesanan


## 🧮 Cara Kerja Perhitungan

Total harga dihitung secara otomatis dengan rumus:


Total = Harga × Jumlah


Perhitungan dilakukan:

* Di *frontend (JavaScript)* → untuk tampilan real-time
* Di *backend (Laravel Controller)* → untuk menjaga keamanan data



## 📁 Struktur Folder Penting


app/
 ├── Models/
 │   └── Pesanan.php
 ├── Http/
 │   └── Controllers/
 │       └── PesananController.php

resources/
 └── views/
     └── pesanan/
         ├── index.blade.php
         ├── create.blade.php
         └── edit.blade.php


---

## 👨‍💻 Author
Nama: Elsimawati Berutu
