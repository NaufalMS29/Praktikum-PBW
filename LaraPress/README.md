<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# LaraPress - Aplikasi Blog Sederhana

LaraPress adalah aplikasi blog sederhana yang dibangun menggunakan Laravel 12 untuk tujuan pembelajaran dan pengembangan keterampilan web development.

<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/d92db5f6-9eb2-434a-a821-42640d6ed601" />

Tampilan halaman utama LaraPress

## 📋 Tentang Proyek

Proyek ini dibuat sebagai bagian dari pembelajaran Laravel framework. LaraPress mendemonstrasikan konsep-konsep dasar Laravel seperti routing, views, dan struktur MVC.

## 🚀 Fitur yang Sudah Diimplementasikan

### 1. *Halaman Utama (Welcome Page)*
   - Mengubah tampilan default Laravel menjadi halaman sederhana
   - Menampilkan judul "Selamat Datang di LaraPress"
   - Struktur HTML yang bersih dan minimal

### 2. *Halaman Tentang Kami*
   - Route: /about
   - Menampilkan informasi tentang LaraPress
   - Menjelaskan tujuan proyek sebagai pembelajaran Laravel 12

### 3. *Halaman Kontak*
   - Route: /contact
   - Menampilkan informasi kontak pengembang

## 📁 Struktur File yang Dimodifikasi

### File yang Dibuat/Dimodifikasi:

1. **resources/views/welcome.blade.php**
   - Mengubah tampilan default Laravel yang kompleks menjadi struktur HTML sederhana
   - Menampilkan pesan sambutan untuk pengunjung blog

2. **resources/views/about.blade.php** (BARU)
   - File view baru untuk halaman "Tentang Kami"
   - Berisi informasi tentang LaraPress sebagai proyek pembelajaran

3. **resources/views/contact.blade.php** (BARU)
   - File view baru untuk halaman "Contact"
   - Berisi informasi tentang kontak pengembang

4. **routes/web.php**
   - Menambahkan route baru /about yang mengarah ke view about.blade.php
   - Menambahkan route baru /contact yang mengarah ke view contact.blade.php

## 🛠 Langkah-langkah Implementasi

### Step 1: Modifikasi Halaman Welcome
Mengubah file resources/views/welcome.blade.php dari tampilan default Laravel (266 baris) menjadi HTML sederhana:

html
<!DOCTYPE html>
<html>
<head>
    <title>Selamat Datang di LaraPress</title>
</head>
<body>
    <h1>Selamat Datang di Blog LaraPress</h1>
    <p>Ini adalah halaman utama dari aplikasi blog kita.</p>
    <a href="/about">Lihat Halaman Tentang Kami</a>
    <br>
    <a href="/">Kembali ke Halaman Utama</a>
</body>
</html>


### Step 2: Membuat Route Baru
Menambahkan route baru di routes/web.php:

php
Route::get('/about', function () {
    return view('about');
});
Route::get('/contact', function () {
    return view('contact');
});


### Step 3: Membuat View About
Membuat file baru resources/views/about.blade.php:

html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tentang Kami - LaraPress</title>
</head>
<body>
    <h1>Tentang LaraPress</h1>
    <p>LaraPress adalah aplikasi blog sederhana yang dibuat dengan Laravel 12.</p>
    <p>Proyek ini dibuat untuk tujuan pembelajaran dan pengembangan keterampilan.</p>
</body>
</html>


### Step 4: Membuat View Contact
Membuat file baru resources/views/contact.blade.php:

html
<!DOCTYPE html>
<html>

<head>
    <title>Kontak Kami - LaraPress</title>
</head>

<body>
    <h1>Kontak LaraPress</h1>
    <p>Nama : Naufal Maulana Saputra</p>
    <p>NPM : 4523210083</p>
    <p>Email : naufal4523083@univpancasila.ac.id</p>
    <p>No.Hp : 082118768976</p>
    <a href="/tentang-kami">Lihat Halaman Tentang Kami</a>
    <br>
    <a href="/">Kembali ke Halaman Utama</a>
</body>

</html>


## 🌐 Endpoint yang Tersedia

| Route | Method | Deskripsi |
|-------|--------|-----------|
| / | GET | Halaman utama LaraPress |
| /tentang-kami | GET | Halaman tentang LaraPress |
| /contact | GET | Halaman tentang kontak pengembang |

## 💻 Teknologi yang Digunakan

- *Framework*: Laravel 12
- *PHP Version*: 8.x
- *Database*: MySQL
- *Frontend*: Blade Template Engine, HTML, CSS
- *Build Tool*: None

## 📦 Instalasi

1. Clone repository ini:
bash
git clone https://github.com/NaufalMS29/Praktikum-PBW.git


2. Masuk Ke Directory LaraPress: cd .\LaraPress\


3. Install dependencies:
bash
composer install
npm install


4. Buat file .env:
bash
cp .env.example .env


5. Generate application key:
bash
php artisan key:generate


6. Jalankan development server:
bash
php artisan serve


7. Akses aplikasi di browser:

http://localhost:8000


## 📸 Screenshot

### Halaman Utama
<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/d92db5f6-9eb2-434a-a821-42640d6ed601" />
Halaman utama menampilkan sambutan sederhana kepada pengunjung blog LaraPress.

### Halaman Tentang Kami
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dc8c20a7-6f13-4eac-9aec-95e69067c91f" />
Halaman Tentang LaraPress berisi informasi tentang LaraPress sebagai proyek pembelajaran

### Halaman Kontak
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cd76033f-d3ea-4cf9-8f39-14705617c1a8" />
Halaman Kontak LarapPress berisi informasi kontak pengembang
