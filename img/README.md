Tugas Konversi Source Code Java ke PHP (PBO)

Repositori ini berisi hasil konversi kode program Pemrograman Berbasis Objek (PBO) dari bahasa pemrograman Java ke PHP untuk Pertemuan 01 sampai Pertemuan 06.

Struktur Folder Project
.
├── 01 Class/
├── 02 Contructor/
├── 03 Inheritance/
├── 04 Polymorphsim/
├── 05 AsosiasiKomposisi/
├── 06 Abstarcktinterface/
├── img/
└── README.md

Modul, Penjelasan, & Hasil Eksekusi Output
1. Pertemuan 01 - Class (01 Class)
Penjelasan & Konversi:
Pada modul ini, dilakukan konversi pembuatan dasar Class, Attributes, Methods, serta proses instansiasi Object dari Java ke PHP. Di PHP, deklarasi atribut/properti diawali dengan tanda $ dan method dibuat menggunakan keyword function.
Hasil Output:
 php Main.php
Space Gray256GBSpesifikasi iPhone 13
Warna: Red
Storage: 128GB

Spesifikasi iPhone 14
Warna: Grey
Storage: 256GB

2. Pertemuan 02 - Constructor (02 Contructor)
Penjelasan & Konversi:
Materi ini membahas inisialisasi nilai awal objek saat pertama kali dibuat. Berbeda dengan Java yang menggunakan nama class sebagai nama constructor, pada PHP digunakan magic method khusus yaitu public function __construct().
Hasil Output:
 php Aplikasi.php
Nama: Belum Diisi
NIM: Belum Diisi
Umur: 0
Nama : Soja Purnamasari
NIM : 4523210104
Umur : 15
Nama: Nenden Nuraini
NIM: 4523210144
Umur: 17

3. Pertemuan 03 - Inheritance / Pewarisan (03 Inheritance)
Penjelasan & Konversi:
Menerapkan konsep penurunan sifat dari Parent Class (Class Induk) ke Child Class (Class Anak) menggunakan keyword extends. Di PHP, Child Class harus mengimpor file Parent Class secara eksplisit menggunakan require_once sebelum meng-extends class tersebut.
Hasil Output:
php Main.php
Nama: Paolo Dicanio
NIM: INT12345
Umur: 21
Negara Asal: Italy

Nama: Sarah
NIM: INT67890
Umur: 22
Negara Asal: Australia

Nama: David
NIM: INT54321
Umur: 23
Negara Asal: UK

4. Pertemuan 04 - Polymorphism (04 Polymorphsim)

Penjelasan & Konversi:
Menerapkan kemampuan objek untuk memiliki banyak bentuk melalui Method Overriding. Di PHP, pengecekan tipe/instansi objek menggunakan operator instanceof (seperti halnya instanceof pada Java) untuk menjalankan method khusus tiap objek.
Hasil Output:
php Main.php
Smartphone Samsung Galaxy S21 sedang booting.
Melakukan panggilan video ke nomor 08123456789
Smartphone Samsung Galaxy S21 sedang shutdown.

Feature Phone Nokia 3310 dinyalakan.
Melakukan panggilan suara ke nomor 08123456789
Feature Phone Nokia 3310 dimatikan.

Mengakses internet melalui Smartphone.
Memainkan game Snake.

5. Pertemuan 05 - Asosiasi & Komposisi (05 AsosiasiKomposisi)

Penjelasan & Konversi:
Membahas hubungan antar objek, baik hubungan longgar (Association) maupun hubungan ketergantungan yang kuat di mana suatu objek menjadi bagian dari objek lain (Composition). Di PHP, objek dari class lain dimasukkan sebagai argumen constructor atau disimpan dalam properti array/objek.
Hasil Output:
php Main.php
Dokter Dr. Andi merawat pasien Budi

Tim Garuda memiliki pemain:
- Eko
- Dina

Buku Belajar Java memiliki bab:
- Pendahuluan
- Isi
- Penutup

6. Pertemuan 06 - Abstract Class & Interface (06 Abstarcktinterface)
Penjelasan & Konversi:
Menerapkan konsep abstraksi menggunakan abstract class dan interface.
Abstract Class: Diimplementasikan dengan keyword abstract dan diturunkan dengan extends.
Interface: Didefinisikan dengan keyword interface dan diimplementasikan pada class menggunakan implements.
Hasil Output:
php Main.php
Kendaraan: Mobil Sport
Mobil Sport bergerak di jalan raya.
Mengisi bahan bakar umum.

Kendaraan: Perahu Motor
Perahu Motor bergerak di air.
Perahu Motor mengisi bahan bakar solar khusus kapal.

Kendaraan: Motor Gravel
Motor Gravel bergerak di tanah gravel.
Mengisi bahan bakar umum.

Kendaraan: Gedung Tinggi