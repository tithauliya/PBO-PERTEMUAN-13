# Tugas Pertemuan 13 — Penerapan Login dengan Java Persistence API (JPA)

Proyek ini merupakan implementasi sistem **Login dan Manajemen Akun** menggunakan **Java Swing** dan **JPA (EclipseLink)** yang terhubung ke database **MySQL**.  
Aplikasi ini dikembangkan sebagai bagian dari tugas mata kuliah **Pemrograman Berorientasi Objek (PBO)**, dengan fokus pada penerapan **Java Persistence** dan **Entity Relationship** dalam aplikasi berbasis GUI.

---

## Fitur Utama

###  1. Login User
- Validasi username dan password menggunakan data dari tabel `akun` di database.  
- Jika login berhasil, pengguna diarahkan ke halaman utama dengan sapaan “Selamat datang, username!”.  
- Jika gagal, muncul notifikasi kesalahan.

###  2. Register (Buat Akun)
- Pengguna dapat membuat akun baru melalui form pendaftaran.  
- Data tersimpan otomatis ke tabel `akun` dengan validasi agar tidak ada username yang sama.  

###  3. Lupa/Ubah Password
- Pengguna dapat mencari username-nya.  
- Jika username ditemukan, field untuk memasukkan password baru akan muncul.  
- Password diperbarui langsung di database menggunakan **EntityManager JPA**.  

###  4. Integrasi Database
- Menggunakan **MySQL** sebagai sistem manajemen basis data.  
- Dikelola melalui `persistence.xml` dengan **EclipseLink (JPA 2.2)**.  

---

## ⚙️ Teknologi yang Digunakan
- ☕ Java 17+  
- 🧩 NetBeans IDE  
- 🗄️ MySQL Database  
- 🔗 EclipseLink (JPA 2.2)  
- 💻 Swing GUI  

---

## Langkah-Langkah Pembuatan

### 1 Membuat Database
Buat database `TUGASPBO12` dan tabel `akun` dengan struktur berikut:

### 2 Membuat Jframe Login
<img width="583" height="568" alt="Screenshot 2025-11-13 140916" src="https://github.com/user-attachments/assets/38e92028-827b-4c9e-9dbe-b23c189deddf" />

### 3 Membuat Jframe Ubah password
<img width="600" height="526" alt="Screenshot 2025-11-13 150531" src="https://github.com/user-attachments/assets/c000b570-0f9d-43fe-851c-10e255106250" />

### 4 Membuat JFrame Buat akun
<img width="650" height="555" alt="Screenshot 2025-11-13 145553" src="https://github.com/user-attachments/assets/aff0dd4e-8337-4f50-bd9d-08c771bf68a2" />

# Penulis
Titha Auliya Khotim
Mahasiswa Sistem Informasi
Semester 3
Universitas Islam Negeri Sunan Ampel Surabaya
