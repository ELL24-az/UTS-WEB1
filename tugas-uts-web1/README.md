# 📚 Project UTS Pemrograman Web - Book Store UPB

Dokumentasi resmi untuk aplikasi web **Book Store UPB** yang dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) Pemrograman Web 1.

---

## 🎥 Video Presentasi Project

Saksikan video demonstrasi dan penjelasan kodingan project melalui tautan YouTube berikut:

- 🔗 **Link Video YouTube:** https://youtu.be/jkF9JYJCWPs?si=GjLxLTsSYL6_3TFC
- 👤 **Nama Mahasiswa:** Elisia Putri Sarmelinda
- 🆔 **NIM:** 312510456
- 🏫 **Kelas:** I252A

---

## 📌 Deskripsi Singkat

**Book Store UPB** adalah platform toko buku berbasis web yang memungkinkan pengguna untuk memantau katalog buku secara interaktif, mengecek ketersediaan stok, melakukan pengisian form checkout pemesanan, serta melacak status pengiriman barang secara _real-time_ berdasarkan nomor DO (_Delivery Order_).

Web ini didesain menggunakan antarmuka modern bertema hangat (_warm warm-aesthetic / cream & maroon_) yang responsif di berbagai ukuran layar.

---

## 🗂️ Struktur Folder Project

Sesuai dengan ketentuan struktur project yang ditetapkan:

```text
tugas-uts-web1/
├── index.html            # Halaman Login Utama
├── dashboard.html        # Halaman Utama / Katalog Buku
├── stok.html             # Halaman Tabel Inventaris Stok Buku
├── checkout.html         # Halaman Form Pemesanan Buku
├── tracking.html         # Halaman Lacak Status Pengiriman (Nomor DO)
├── css/
│   └── style.css         # Styling UI (Theme Warm Cream/Maroon + Responsive)
├── js/
│   ├── data.js           # Database Statis (User, Katalog, & Tracking)
│   └── script.js         # Logika JS (DOM Manipulation & Auth)
└── img/
    ├── pengantar_komunikasi.jpg
    ├── manajemen_keuangan.jpg
    ├── kepemimpinan.jpg
    ├── mikrobiologi.jpg
    └── paud_perkembangan.jpg
```

---

## 🚀 Fitur Utama

1. **Sistem Login & Logout:**
   - Otentikasi pengguna terhubung dengan `dataPengguna` di `data.js`.
   - Penyimpanan sesi aktif menggunakan `localStorage`.
2. **Katalog Buku Interaktif (Dashboard):**
   - Tampilan _Card Grid_ dinamis lengkap dengan gambar cover, kode buku, edisi, dan harga.
3. **Pengecekan Stok Inventaris:**
   - Data ketersediaan buku ditampilkan secara rapi dalam tabel HTML.
4. **Form Checkout:**
   - Dropdown buku dinamis yang otomatis mengambil daftar buku dari katalog.
5. **Tracking Status Pengiriman:**
   - Fitur pencarian riwayat pengiriman paket berdasarkan Nomor DO (misal: `20230012`).

---

## 🔑 Data Pengujian (Testing Credentials)

### 1. Akun Login (`index.html`)

| Email            | Password  | Role  | Nama Pengguna  |
| :--------------- | :-------- | :---- | :------------- |
| `rina@gmail.com` | `rina123` | User  | Rina Wulandari |
| `agus@gmail.com` | `agus123` | User  | Agus Pranoto   |
| `siti@gmail.com` | `siti123` | Admin | Siti Marlina   |

### 2. Nomor DO Tracking (`tracking.html`)

- **`20230012`** — Rina Wulandari (Status: _Dalam Perjalanan_)
- **`20230013`** — Agus Pranoto (Status: _Dikirim / Selesai_)

---

## 🛠️ Teknologi yang Digunakan

- **HTML5:** Struktur utama halaman web.
- **CSS3:** Custom Styling (Variabel CSS, Grid Layout, Flexbox, & Font Google _DM Sans / Playfair Display_).
- **JavaScript (ES6):** Manipulasi DOM, Array Methods (`map`, `find`), Event Listeners, dan `localStorage`.
