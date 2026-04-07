# Database Java CRUD System - MUHAMMAD ZIBRIL TAFA TABIA (I.2510056)

## 📌 Deskripsi Proyek
Proyek ini adalah aplikasi Desktop berbasis Java yang mengimplementasikan sistem **CRUD (Create, Read, Update, Delete)** untuk manajemen data karyawan. Aplikasi ini dibangun menggunakan pustaka **Java Swing** untuk antarmuka pengguna (GUI) dan **JDBC (Java Database Connectivity)** sebagai jembatan komunikasi dengan database **MySQL**.

---

## 🛠️ Arsitektur & Teknologi
* **Bahasa Pemrograman**: Java 17 (LTS)
* **GUI Framework**: Java Swing & FlatLaf
* **Build Tool**: Apache Maven
* **Database**: MySQL 8.0 / MariaDB

---

## 🏗️ Struktur Project
* `src/main/java/javatutorial/`: Kode sumber aplikasi.
* `zibril_db.sql`: Skema database (ada di root).
* `Assets/`: Folder bukti pengujian.

---

## 🚀 Panduan Instalasi & Penggunaan
1. Aktifkan MySQL di XAMPP.
2. Import `zibril_db.sql` ke phpMyAdmin.
3. Jalankan perintah:
```bash
mvn compile exec:java "-Dexec.mainClass=javatutorial.Main"