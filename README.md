# Database Java CRUD System - MUHAMMAD ZIBRIL TAFA TABIA (I.2510056)

## 📌 Deskripsi Proyek
Proyek ini adalah aplikasi Desktop berbasis Java yang mengimplementasikan sistem **CRUD (Create, Read, Update, Delete)** untuk manajemen data karyawan. Aplikasi ini dibangun menggunakan pustaka **Java Swing** untuk antarmuka pengguna (GUI) dan **JDBC (Java Database Connectivity)** sebagai jembatan komunikasi dengan database **MySQL**.

Tugas ini merupakan pemenuhan praktikum Pemrograman Berorientasi Objek (OOP) untuk mendemonstrasikan integrasi aplikasi desktop dengan sistem manajemen basis data relasional.

---

## 🛠️ Arsitektur & Teknologi
Aplikasi ini menggunakan stack teknologi sebagai berikut:
* **Bahasa Pemrograman**: Java 17 (LTS)
* **GUI Framework**: Java Swing & FlatLaf (Modern UI Look)
* **Build Tool**: Apache Maven
* **Database**: MySQL 8.0 / MariaDB
* **Driver**: MySQL Connector/J 8.0.33

---

## 🏗️ Struktur Project
Folder project ini disusun dengan standar Maven sebagai berikut:
* `src/main/java/javatutorial/`: Berisi kode sumber aplikasi (Main, GUI, Model, dan Connection).
* `zibril_db.sql`: Skema database yang digunakan (Import file ini ke phpMyAdmin).
* `assets/`: Folder berisi aset dokumentasi dan bukti pengujian aplikasi.
* `pom.xml`: Konfigurasi dependensi Maven.

---

## 🚀 Panduan Instalasi & Penggunaan

### 1. Persiapan Database
1. Pastikan layanan **MySQL** pada panel XAMPP sudah aktif.
2. Buka `localhost/phpmyadmin` dan buat database baru dengan nama `zibril_db`.
3. Gunakan fitur **Import** dan pilih file `zibril_db.sql` yang ada di root folder ini.

### 2. Kompilasi dan Menjalankan Aplikasi
Buka terminal pada folder project, lalu jalankan perintah berikut:
```bash
mvn compile exec:java "-Dexec.mainClass=javatutorial.Main"