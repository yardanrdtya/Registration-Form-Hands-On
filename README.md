# flutter_application_1

A new Flutter project.
=======
# Registration-Form-Hands-On
Yardan Raditya Rafi' Widyadhana | 2409116037 | Sistem Informasi A 2024

---

## 📋 Registrasi Event Kampus (Flutter)
Aplikasi Registrasi Event Kampus merupakan aplikasi berbasis Flutter yang digunakan untuk melakukan pendaftaran peserta pada sebuah event kampus. Aplikasi ini dibuat sebagai bagian dari tugas Mata Kuliah Pemrograman Aplikasi Bergerak. Aplikasi ini menyediakan form pendaftaran dengan berbagai komponen input seperti text field, radio button, dropdown, date picker, dan checkbox. Data peserta yang telah mendaftar akan disimpan sementara menggunakan Provider State Management dan dapat ditampilkan dalam halaman daftar peserta serta halaman detail peserta.

---

## ⚙️ Fitur Aplikasi
Beberapa fitur yang tersedia dalam aplikasi ini antara lain:
- Form registrasi dengan beberapa field input
- Validasi form secara real-time
- Input widget Flutter
- Manajemen state menggunakan Provider
- Penyimpanan daftar pendaftar
- Halaman List Peserta
- Halaman Detail Peserta
- Validasi email agar tidak terjadi duplikasi pendaftaran

---

## 👨🏻‍💻 Teknologi yang Digunakan
Aplikasi ini dibangun menggunakan teknologi berikut:
- Flutter
- Dart
- Provider (State Management)
- Material UI

---

## 📂 Struktur Folder Project
```
lib/
│
├── models/
│   └── registrant_model.dart        
│
├── providers/
│   └── registration_provider.dart   
│
├── pages/
│   ├── registration_page.dart       
│   ├── registrant_list_page.dart    
│   └── registrant_detail_page.dart  
│
└── main.dart                       

```
Penjelasan:
- models ini berisi struktur data pendaftar
- providers digunakan untuk mengelola state dan daftar peserta
- pages yaitu halaman-halaman pada aplikasi
- main.dart sebagai entry point aplikasi

---

## 🎯 Tujuan Project
Project ini dibuat untuk mempelajari:
- Pembuatan Form pada Flutter
- Penggunaan berbagai Input Widget
- Implementasi State Management menggunakan Provider
- Navigasi antar halaman pada Flutter

---