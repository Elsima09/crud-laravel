# CRUD Pemesanan Makanan Sederhana

## Deskripsi

Project ini merupakan aplikasi CRUD (Create, Read, Update, Delete) sederhana untuk sistem pemesanan makanan. Aplikasi ini digunakan untuk mengelola data pesanan seperti nama pelanggan, menu makanan, jumlah pesanan, dan alamat pembeli.

## Fitur

* Menampilkan daftar pesanan
* Menambahkan pesanan baru
* Mengedit data pesanan
* Menghapus pesanan

## Teknologi yang Digunakan

* Laravel
* PHP
* MySQL
* Bootstrap

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
* git

## Cara Instalasi

1. Clone repository:
   git clone https://github.com/Elisma09/crud-laravel.git

2. Masuk ke folder project:
   cd crud-laravel

3. Install dependency:
   composer install

4. Copy file environment:
   cp .env.example .env

5. Generate application key:
   php artisan key:generate

6. Atur koneksi database pada file .env:
   DB_DATABASE=nama_database
   DB_USERNAME=root
   DB_PASSWORD=

7. Jalankan migrasi database:
   php artisan migrate

## Cara Menjalankan Aplikasi

Jalankan server Laravel:
php artisan serve

Buka di browser:
http://127.0.0.1:8000

## Tampilan Aplikasi

Aplikasi ini memiliki halaman:

* Halaman daftar pesanan
* Halaman tambah pesanan
* Halaman edit pesanan

## Author

Nama: Elsimawati Berutu
