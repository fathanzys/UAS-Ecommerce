# 📊 AdminLTE 4 - E-Commerce Web Dashboard (UAS Project)
Nama : Fathan Nabil Arrazani
NIM : 0102522024
UAS ECommerce Pengembangan Web

[![npm version](https://img.shields.io/npm/v/admin-lte/latest.svg)](https://www.npmjs.com/package/admin-lte)
[![Packagist](https://img.shields.io/packagist/v/almasaeed2010/adminlte.svg)](https://packagist.org/packages/almasaeed2010/adminlte)
[![cdn version](https://data.jsdelivr.com/v1/package/npm/admin-lte/badge)](https://www.jsdelivr.com/package/npm/admin-lte)
[![Discord Invite](https://img.shields.io/badge/discord-join%20now-green)](https://discord.gg/jfdvjwFqfz)
[![Netlify Status](https://api.netlify.com/api/v1/badges/1277b36b-08f3-43fa-826a-4b4d24614b3c/deploy-status)](https://app.netlify.com/sites/adminlte-v4/deploys)

**AdminLTE** adalah template dashboard berbasis **[Bootstrap 5](https://getbootstrap.com/)** yang responsif, fleksibel, dan sangat dapat dikustomisasi. Cocok untuk berbagai ukuran layar — mulai dari smartphone hingga desktop.

## 🧑‍🎓 Tentang Proyek Ini

Proyek ini merupakan bagian dari **UAS Mata Kuliah E-Commerce**. Pengembangan fitur CRUD data buku berbasis PHP dilakukan di dalam template **AdminLTE v4.0.0-beta3**.

🔧 **File utama pengembangan ada di:**
AdminLTE-4.0.0-beta3/dist/pages/forms/general.php

markdown
Salin
Edit

Halaman tersebut berfungsi sebagai **form pengelolaan data buku**, mencakup fitur:
- Tambah data
- Edit data
- Hapus data
- Tampilkan data dalam bentuk tabel

## ✨ Fitur Utama Template AdminLTE

- Dashboard admin berbasis Bootstrap 5
- Dukungan plugin JavaScript seperti Chart.js, overlayScrollbars, dsb.
- Tersedia banyak komponen UI siap pakai (form, table, card, dsb)
- Struktur folder yang rapi dan scalable

![AdminLTE Preview](https://adminlte.io/AdminLTE3.png "AdminLTE Presentation")

---

## ⚙️ Cara Menjalankan Proyek

1. **Clone repo ini** atau download folder `AdminLTE-4.0.0-beta3`
2. Letakkan folder dalam direktori `htdocs` XAMPP
3. Pastikan sudah membuat database MySQL bernama `db_perpustakaan`
4. Buat tabel `buku`:
   ```sql
   CREATE TABLE buku (
     id INT AUTO_INCREMENT PRIMARY KEY,
     judul VARCHAR(255) NOT NULL,
     penulis VARCHAR(255) NOT NULL,
     penerbit VARCHAR(255) NOT NULL,
     tahun_terbit INT NOT NULL,
     isbn VARCHAR(50) NOT NULL
   );
Jalankan XAMPP dan akses:

bash
Salin
Edit
http://localhost/AdminLTE-4.0.0-beta3/dist/pages/forms/general.php
🛠️ Teknologi yang Digunakan
HTML, CSS, Bootstrap 5

PHP Native

MySQL (via XAMPP)

AdminLTE v4 Template

📁 Struktur Folder Penting
arduino
Salin
Edit
AdminLTE-4.0.0-beta3/
├── dist/
│   └── pages/
│       └── forms/
│           └── general.php   ← File utama UAS
├── plugins/
├── index.html
├── README.md
└── ...
💡 Catatan Pengembangan
Kode PHP ditanam langsung di dalam file general.php

Koneksi database disambungkan di bagian atas script

Validasi dasar dan pesan error/sukses sudah disiapkan

Belum menggunakan framework tambahan (seperti Laravel)

📌 Lisensi
AdminLTE adalah proyek open-source yang dilisensikan di bawah MIT License. Hak cipta untuk template asli dimiliki oleh AdminLTE.io.

🙏 Ucapan Terima Kasih
Template dan sumber daya visual:

AdminLTE.io

Bootstrap

Unsplash

UIfaces

📬 Kontak (Opsional)
Nama: [Nama Anda]
NIM: [NIM Anda]
Kelas: E-Commerce [Kelas]
Email: [Email Anda]

