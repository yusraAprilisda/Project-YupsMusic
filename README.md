# 🎵 Yup'sMusic — Kotak Musik Digital

**Yup'sMusic** adalah aplikasi web pemutar musik dan katalog artis interaktif berbasis HTML5 dan CSS3. Proyek ini dirancang sebagai wadah kurasi lagu-lagu favorit lengkap dengan audio player langsung, lirik/kutipan cerita, serta profil mendalam dari masing-masing musisi dan grup musik di baliknya.

---

## 📑 Daftar Isi
1. [Fitur Utama](#-fitur-utama)
2. [Struktur Direktori](#-struktur-direktori)
3. [Daftar Lagu & Musisi](#-daftar-lagu--musisi)
4. [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
5. [Cara Menjalankan](#-cara-menjalankan)
6. [Catatan Tambahan](#-catatan-tambahan)

---

## ✨ Fitur Utama

- **🏠 Beranda Interaktif (`index.html`)**: Memperkenalkan konsep portal Yup'sMusic, navigasi cepat ke Playlist dan Artist, serta ringkasan statistik koleksi lagu.
- **🎧 Pemutar Musik Langsung (`playlist.html`)**: Menyediakan daftar lagu pilihan dengan pemutar audio bawaan (*HTML5 Audio Player*), sampul album, info genre, tahun rilis, dan latar belakang cerita lagu.
- **🎤 Profil Artis & Musisi (`artist.html`)**: Menampilkan biografi lengkap musisi internasional dan grup OST drama, asal negara, genre musik, serta tautan cepat untuk mendengarkan karya mereka.
- **📱 Desain Bersih & Responsif**: Menggunakan palet warna bertema modern dengan kontras tinggi, tata letak grid fleksibel, serta batas kontainer yang rapi di berbagai resolusi layar.

---

## 📂 Struktur Direktori

```plaintext
MyMusicBox/
│
├── index.html              # Halaman Beranda (Landing Page)
├── playlist.html           # Halaman Katalog Pemutar Lagu
├── artist.html             # Halaman Biografi & Profil Musisi
│
├── css/
│   └── style.css           # Lembar gaya global, layout container, kartu & navbar
│
├── image/                  # Sampul Album & Foto Profil Artis
│   ├── Yungkai.jpg
│   ├── olivia.jpg
│   ├── taylor.jpg
│   ├── golden.jpg
│   ├── rude.jpg
│   ├── with.jpg
│   ├── Rosé.jpg
│   ├── sunjae.jpg
│   ├── rex.jpg
│   ├── blue.jpg
│   ├── dropdead.jpg
│   ├── honeybe.jpg
│   ├── whitehorse.jpg
│   ├── august.jpg
│   ├── amazing.jpg
│   ├── Untitled.jpg
│   └── suddenshower.jpg
│
└── music/                  # Berkas Audio Lagu (.mp3)
    ├── blue.mp3
    ├── drop.mp3
    ├── honeybe.mp3
    ├── whitehorse.mp3
    ├── august.mp3
    ├── amazing.mp3
    ├── happiness.mp3
    ├── golden.mp3
    ├── rude.mp3
    ├── with.mp3
    ├── gone.mp3
    └── sudden.mp3
