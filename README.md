# 🏥 HealthPoint – Aplikasi Pencarian Fasilitas Kesehatan
 
## 📱 Deskripsi Aplikasi 
**HealthPoint** adalah aplikasi mobile berbasis **Flutter** yang dirancang untuk membantu pengguna menemukan **fasilitas kesehatan terdekat di Kota Palembang** secara cepat, akurat, dan real-time. 

Aplikasi ini memanfaatkan teknologi **Location-Based Service (LBS)** dengan dukungan **GPS** dan **Google Maps API** untuk memberikan informasi lokasi serta navigasi menuju fasilitas kesehatan seperti rumah sakit, klinik, dan apotek.

Aplikasi ini dikembangkan sebagai proyek mata kuliah **Pengembangan Aplikasi Bergerak II**.

---

## 🎯 Tujuan Pengembangan
- Mengembangkan aplikasi mobile berbasis Flutter
- Membantu pengguna menemukan fasilitas kesehatan terdekat
- Menyediakan informasi lokasi secara real-time menggunakan GPS
- Menyediakan fitur pencarian, navigasi, dan informasi detail fasilitas kesehatan
- Menghasilkan aplikasi dengan tampilan yang user-friendly

---

## 🚀 Fitur Utama

### 🔐 Autentikasi Pengguna
- Registrasi (Sign Up)
- Login (Email & Password)
- Login dengan Google / Facebook
- Lupa Password

---

### 🏠 Home Screen
- Menampilkan informasi utama aplikasi
- Pencarian cepat fasilitas kesehatan
- Menampilkan lokasi pengguna
- Rekomendasi fasilitas kesehatan terdekat
- Tips kesehatan

---

### 🗺️ Maps (Peta)
- Menampilkan lokasi fasilitas kesehatan menggunakan marker
- Menampilkan jarak dari pengguna
- Navigasi menuju lokasi menggunakan GPS

---

### 🔍 Search (Pencarian)
- Mencari fasilitas kesehatan berdasarkan:
  - Nama
  - Kategori (Rumah Sakit, Klinik, Apotek)
- Filter berdasarkan:
  - Jarak
  - Rating

---

### ❤️ Favorite
- Menyimpan fasilitas kesehatan favorit
- Akses cepat tanpa perlu mencari ulang

---

### 💬 Komentar
- Menambahkan komentar pada fasilitas kesehatan
- Mengedit dan menghapus komentar

---

### 👤 Profile
- Menampilkan data pengguna
- Edit profil (nama, foto, dll)
- Pengaturan aplikasi (notifikasi, preferensi)

---

## 📍 Teknologi yang Digunakan

- **Flutter (Dart)**
- **Firebase Firestore (Database Real-time)**
- **Firebase Authentication**
- **Google Maps API**
- **GPS (Global Positioning System)**

---

## 🧠 Konsep Teknologi

Aplikasi ini menggunakan:
- **Location-Based Service (LBS)** untuk menentukan lokasi pengguna
- **GPS** untuk mendapatkan koordinat (latitude & longitude)
- **Firestore** untuk penyimpanan data real-time
- **Prototyping Method** dalam pengembangan sistem

---

## 🗄️ Struktur Data (Firestore)

Data yang disimpan meliputi:
- Data pengguna
- Data fasilitas kesehatan
- Komentar
- Data favorit

---

## 📊 Fitur Berdasarkan Use Case

Aktor: **User**

Fitur utama:
- Registrasi & Login
- Mengelola Komentar
- Mengelola Favorit
- Melihat Peta
- Mengelola Profil

Semua fitur membutuhkan autentikasi (login)

---

## 🎨 Desain Aplikasi

- Menggunakan prinsip **Material Design**
- UI responsif dan user-friendly
- Fokus pada kemudahan navigasi dan akses informasi

---

## 📅 Waktu Pengembangan
- Mulai: April 2026  
- Selesai: Juni 2026  
- Durasi: ± 4 bulan  

---

## 📍 Lokasi Pengembangan
- Universitas Multi Data Palembang  
- Rumah masing-masing anggota tim 
- Channel Discord Khusus Development

---

## 👨‍💻 Tim Pengembang
- Achmad Faiz Yudha Ramadhan  
- Rizky Apryandi Triadmojo  
- Wasilah Maulia  
- Nabila Syahwalrani  

Program Studi: Sistem Informasi  
Universitas Multi Data Palembang  

---

## 📚 Dasar Proyek

Aplikasi ini dikembangkan berdasarkan proposal:  
**"Rancang Bangun Aplikasi Mobile Pencarian Fasilitas Kesehatan di Kota Palembang Menggunakan Flutter"**

---

## 📤 Deployment

Aplikasi ditujukan untuk platform:
- Android (Google Play Store)

---

## 📦 Instalasi Project

```bash
git clone https://github.com/FaizZzhue/health-point.git
cd HealthPoint
flutter pub get
flutter run