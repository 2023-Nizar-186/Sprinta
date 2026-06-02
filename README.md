# 🏃 Sprinta

Sprinta adalah aplikasi berbasis web yang dirancang untuk mendukung aktivitas olahraga dalam satu platform terintegrasi. Aplikasi ini memungkinkan pengguna untuk mendaftar sebagai member gym, melakukan reservasi lapangan olahraga, serta mendapatkan informasi mengenai berbagai event olahraga yang sedang berlangsung.

## 📌 Fitur Utama

### 👤 Manajemen Member Gym
- Registrasi akun member
- Login dan logout pengguna
- Pengelolaan data member
- Informasi keanggotaan gym

### 🏟️ Reservasi Lapangan Olahraga
- Melihat daftar lapangan yang tersedia
- Booking lapangan olahraga
- Informasi jadwal penggunaan lapangan
- Pengelolaan data penyewaan

### 🏆 Informasi Event Olahraga
- Daftar event olahraga terbaru
- Informasi jadwal event
- Detail penyelenggaraan event
- Promosi kegiatan olahraga

### 🔐 Sistem Autentikasi
- Login pengguna
- Session management
- Hak akses admin dan user

### 🛠️ Panel Admin
- Mengelola data member
- Mengelola data lapangan
- Mengelola event olahraga
- Mengelola informasi website

---

## 🏗️ Struktur Project

```text
Sprinta/
│
├── admin/                  # Halaman administrasi
├── assets/                 # Asset website
├── img/                    # Gambar dan media
├── user/                   # Halaman pengguna
├── Mentor/                 # Modul mentor/pembimbing
│
├── index.php               # Halaman utama
├── login.php               # Login pengguna
├── logout.php              # Logout pengguna
├── kontak.php              # Halaman kontak
├── functions.php           # Fungsi umum aplikasi
├── session.php             # Pengelolaan session
├── style.css               # Styling website
├── dbfutsal.sql            # Database aplikasi
└── README.md
```

---

## 💻 Teknologi yang Digunakan

- PHP
- HTML5
- CSS3
- JavaScript
- MySQL

---

## ⚙️ Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/2023-Nizar-186/Sprinta.git
```

### 2. Pindahkan ke Web Server

Contoh menggunakan XAMPP:

```text
htdocs/
└── Sprinta/
```

### 3. Import Database

- Buka phpMyAdmin
- Buat database baru
- Import file:

```text
dbfutsal.sql
```

### 4. Konfigurasi Database

Sesuaikan konfigurasi database pada file koneksi PHP.

Contoh:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "dbfutsal";
```

### 5. Jalankan Aplikasi

Buka browser:

```text
http://localhost/Sprinta
```

---

## 🎯 Tujuan Project

Sprinta dikembangkan untuk mempermudah masyarakat dalam:

- Mengelola keanggotaan gym
- Melakukan reservasi lapangan olahraga secara online
- Mendapatkan informasi event olahraga terbaru
- Mendukung digitalisasi layanan olahraga

---

## 📷 Tampilan Sistem

Tambahkan screenshot aplikasi pada folder:

```text
img/screenshots/
```

Contoh:

- Homepage
- Login Page
- Dashboard User
- Dashboard Admin
- Booking Lapangan
- Event Olahraga

---

## 🚀 Pengembangan Selanjutnya

- Sistem pembayaran online
- Notifikasi booking
- QR Code membership
- Dashboard statistik
- Responsive mobile version
- Integrasi Google Maps
- Sistem ranking member aktif

---

---

## 📄 License

Project ini dibuat untuk tujuan pembelajaran dan pengembangan akademik.
