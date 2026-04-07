# Database Java - MUHAMMAD ZIBRIL TAFA TABIA - I.2510056

## Deskripsi Tugas
Program ini adalah aplikasi CRUD (Create, Read, Update, Delete) data karyawan sederhana yang dibangun menggunakan Java Swing dan koneksi database JDBC MySQL. Tugas ini merupakan bagian dari praktikum pemrograman Java.

## Prasyarat
* Java Development Kit (JDK) 17
* Apache Maven
* XAMPP (MySQL Server)

## Konfigurasi Database
1. Pastikan MySQL di XAMPP sudah menyala.
2. Import file `zibril_db.sql` yang berada di folder root project ini ke dalam phpMyAdmin.
3. Database menggunakan nama `zibril_db`.
4. Konfigurasi koneksi dapat dilihat pada file `src/main/java/javatutorial/CConnection.java`.

## Cara Menjalankan Program
1. Buka terminal di folder project ini.
2. Jalankan perintah kompilasi dan eksekusi berikut:
   ```bash
   mvn compile exec:java "-Dexec.mainClass=javatutorial.Main"