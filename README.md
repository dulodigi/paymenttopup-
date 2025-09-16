# Halaman Pembayaran Top-Up & PPOB

Halaman pembayaran modern untuk website **Top-Up Game / PPOB**, dibuat dengan **HTML, CSS, dan JavaScript** tanpa framework tambahan.

## ✨ Fitur
- Input **Nama Member** (tersimpan otomatis di browser).
- Pilihan metode pembayaran: **Bank Transfer, E-Wallet, QRIS**.
- Popup detail rekening dengan tombol **Salin Nomor Rekening**.
- Popup QRIS dengan tombol **Salin Kode** dan **Download QRIS**.
- **Kode unik transfer (3 digit)** untuk memudahkan verifikasi pembayaran.
- **Notifikasi otomatis ke Telegram** via Bot API.
- Countdown 24 jam untuk pembayaran (auto batal jika lewat waktu).
- Tombol **Kembali ke Beranda**.

## 🚀 Cara Menggunakan
1. Edit file `pembayaran.html`:
   - Ganti `{{jumlah_topup}}` dan `{{id_transaksi}}` dengan data dari backend/server.
   - Isi **TOKEN BOT TELEGRAM** dan **CHAT ID** kamu di fungsi `sendTelegram()`.
   - Ubah link `goHome()` sesuai halaman utama website kamu.
2. Upload file ini ke hosting / GitHub Pages.

## 📂 Struktur
```
.
├── pembayaran.html   # Halaman pembayaran utama
└── README.md         # Dokumentasi proyek
```

## 🌐 Deploy GitHub Pages
1. Push ke repo `username/username.github.io`.
2. Aktifkan GitHub Pages via **Settings > Pages**.
3. Akses: `https://username.github.io/pembayaran.html`
