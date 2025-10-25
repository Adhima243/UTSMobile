# Aplikasi Wisata Indonesia

Aplikasi Wisata Indonesia adalah aplikasi Flutter sederhana yang menampilkan daftar tempat wisata populer di Indonesia.
Aplikasi ini dibuat menggunakan data dummy (tanpa integrasi API atau database eksternal) dan bertujuan untuk melatih pemahaman dasar tentang UI Flutter, navigasi antar halaman, serta pengelolaan state sederhana.

##📱 Fitur Aplikasi

**🏖️ Beranda**

Menampilkan daftar tempat wisata lengkap dengan gambar, nama, lokasi, dan rating.
Terdapat kolom pencarian serta filter kategori seperti Pantai, Gunung, dan Budaya.

**❤️ Halaman Favorit**

Pengguna dapat menandai tempat wisata favorit dengan ikon hati, dan data akan tampil di halaman ini.

**👤 Profil**

Menampilkan informasi pengembang serta deskripsi singkat tentang aplikasi.

**📄 Detail Wisata**

Menampilkan deskripsi lengkap dari setiap tempat wisata yang dipilih pengguna.


## 🧱 Struktur Folder

```lib/
│
├── main.dart                # File utama aplikasi
├── models/
│   └── wisata.dart          # Model data dummy tempat wisata
├── screens/
│   ├── home_screen.dart     # Halaman beranda
│   ├── favorite_screen.dart # Halaman favorit
│   ├── profile_screen.dart  # Halaman profil
│   └── detail_screen.dart   # Halaman detail wisata
└── widgets/
    └── wisata_card.dart     # Widget tampilan kartu wisata
```

## 🧩 Teknologi yang Digunakan

- Flutter SDK
  
- Dart
  
- State Management sederhana (setState)
  
- Data Dummy lokal
