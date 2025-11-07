# UTS_WEB1

---

## 📘 README.md — Toko Buku IT (UTS Pemrograman Web 1)

```markdown
# 📚 UTS PEMROGRAMAN WEB 1

**Nama:** Zaenal Maulana Rizki  
**NIM:** 312410332  
**Kelas:** TI.24.A.4  
**Mata Kuliah:** Pemrograman Web1  
**Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom.  

---
```
## 💻 Deskripsi Proyek
Proyek ini merupakan implementasi tugas **UTS Pemrograman Web 1** dengan membuat aplikasi web bernama **Toko Buku Online (Bookstore App v3)**.  
Aplikasi ini dikembangkan menggunakan **HTML, CSS, dan JavaScript murni (tanpa framework)** dengan konsep interaktif berbasis **DOM Manipulation** dan penyimpanan data menggunakan **LocalStorage**.

Tujuan dari proyek ini adalah untuk melatih kemampuan mahasiswa dalam membangun website dinamis sederhana menggunakan data statis (JSON/JavaScript Object) dan simulasi transaksi secara lokal.

---

## 🚀 Fitur Aplikasi

1. **Login & Register**
   - Login berdasarkan data pengguna dari file `data.js`.
   - Register user baru disimpan otomatis ke LocalStorage.
2. **Katalog Buku**
   - Menampilkan daftar buku dari data di `data.js`.
   - Dilengkapi gambar cover, harga, dan stok.
3. **Checkout**
   - User dapat memilih buku dan menentukan jumlah.
   - Data pesanan disimpan dan ditampilkan di history.
4. **Tracking**
   - Menampilkan status dan riwayat pengiriman pesanan.
5. **History Transaksi**
   - Menampilkan seluruh pesanan dan riwayat pengiriman pengguna.

---

## 🗂️ Struktur Folder

```

bookstore_app_v3/
├─ index.html              → Halaman utama (menu navigasi)
├─ login.html              → Halaman login user/admin
├─ dashboard.html          → Beranda setelah login
├─ stok.html               → Daftar katalog buku (menampilkan cover & data buku)
├─ checkout.html           → Form pemesanan buku
├─ tracking.html           → Cek status pengiriman pesanan
├─ history.html            → Riwayat transaksi user
│
├─ css/
│   └─ style.css           → File CSS untuk tampilan dan layout
│
├─ js/
│   ├─ data.js             → Data pengguna, buku, dan tracking (simulasi database)
│   └─ main_v3.js          → Logika utama untuk login, katalog, checkout, tracking, dll.
│
└─ screenshots/
├─ login_page.png      → Screenshot halaman login
├─ katalog_page.png    → Screenshot katalog buku
├─ checkout_page.png   → Screenshot pemesanan buku
├─ tracking_page.png   → Screenshot halaman tracking
└─ history_page.png    → Screenshot riwayat transaksi

```

---

## 🖼️ Menu Menyimpan Screenshot

Buat folder bernama **`screenshots/`** di root proyek kamu.  
Gunakan folder ini untuk menyimpan hasil tangkapan layar (screenshot) dari setiap halaman web kamu.  
Berikut daftar screenshot yang disarankan:

| Halaman | Nama File | Keterangan |
|----------|------------|------------|
| Login | `login_page.png` | Tampilan login user/admin |
| Katalog Buku | `katalog_page.png` | Daftar buku IT dengan gambar cover |
| Checkout | `checkout_page.png` | Form pemesanan buku |
| Tracking | `tracking_page.png` | Hasil pencarian status DO |
| History | `history_page.png` | Riwayat transaksi pengguna |

> 💡 Tips: Gunakan fitur Screenshot dari browser (Ctrl + Shift + S atau Snipping Tool), lalu simpan dengan nama seperti di atas ke folder `screenshots/`.

---

## 🧠 Teknologi yang Digunakan

- **HTML5** → Struktur halaman web  
- **CSS3** → Desain tampilan dan layout  
- **JavaScript (Vanilla JS)** → Logika interaktif, manipulasi DOM, dan LocalStorage  

---

## 👨‍💻 Pengembang
Dikerjakan oleh mahasiswa dalam rangka memenuhi tugas **UTS Pemrograman Web 1**.  
Seluruh data (pengguna, katalog, dan tracking) bersifat lokal dan digunakan hanya untuk simulasi pembelajaran.

---

## 🏁 Cara Menjalankan Aplikasi

1. Download repository ini (ZIP) dan ekstrak.  
2. Buka file `index.html` menggunakan browser (tidak perlu server lokal).  
3. Login menggunakan salah satu akun berikut:
   - **User:** `rina@gmail.com` / `rina123`
   - **Admin:** `siti@gmail.com` / `siti123`
4. Jelajahi menu katalog, checkout, history, dan tracking.

---

## 🏷️ Catatan
Aplikasi ini bersifat statis dan digunakan untuk **keperluan akademik** (bukan komersial).  
Seluruh aset gambar pada katalog hanya digunakan sebagai ilustrasi.

```

---

### ✨ Petunjuk

Salin teks di atas ke file bernama `README.md`, lalu:

* Letakkan di dalam folder `bookstore_app_v3`
* Upload seluruh isi folder ke GitHub

---

Kalau kamu mau, aku bisa kirimkan file `README.md` versi ini langsung (siap diunduh) biar kamu tinggal upload ke repo.
Apakah mau saya buatkan file-nya (`README.md`) biar kamu tinggal drag ke GitHub?
