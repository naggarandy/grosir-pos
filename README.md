# 🛒 Aplikasi Jualan UMKM v2

Aplikasi jualan berbasis web yang **lengkap**, ringan, dan **mobile-friendly**. Cocok untuk toko kecil, warung, atau UMKM.

Semua data disimpan di **localStorage** perangkat Anda (tidak perlu internet setelah dibuka, tidak perlu database/server).

## ✨ Fitur Lengkap

### Manajemen Barang
- Tambah, edit, hapus barang
- Input stok, harga modal (HPP), harga jual
- Kategori & satuan (pcs, kg, botol, dll)
- Pencarian barang
- Notifikasi stok menipis (≤ 5)

### Penjualan
- **Mode Keranjang** → jual banyak barang sekaligus
- **Mode Jual Cepat** → satu barang langsung
- Otomatis mengurangi stok
- Hitung profit otomatis

### Keuangan
- Catat **pengeluaran** (biaya operasional)
- Dashboard: Omzet, Profit, Pengeluaran, **Keuntungan Bersih**
- Laporan penjualan & pengeluaran berdasarkan tanggal
- Hapus transaksi (stok dikembalikan otomatis)

### Lainnya
- **Backup & Restore** data (file JSON)
- Reset semua data
- **PWA** → bisa di-install ke Home Screen HP
- Offline-ready (Service Worker)
- Tampilan mobile-first (nyaman di HP)

## 🚀 Cara Menggunakan

### Langsung di Browser
1. Buka file `index.html` di Chrome/Safari
2. Atau host di GitHub Pages (lihat di bawah)

### Install sebagai Aplikasi di HP
1. Buka di **Chrome**
2. Menu **⋮** → **Add to Home screen** / **Tambahkan ke layar utama**
3. Aplikasi muncul seperti app biasa

## 📦 Deploy ke GitHub Pages (Gratis)

1. Buat repository baru di GitHub
2. Upload semua file ini:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `README.md`
3. Masuk **Settings → Pages**
4. Source: branch `main`, folder `/ (root)`
5. Save → tunggu 1-2 menit
6. Akses lewat: `https://username.github.io/nama-repo`

## 📂 Struktur File

```
aplikasi-jualan/
├── index.html       ← Aplikasi utama
├── manifest.json    ← PWA config
├── sw.js            ← Service Worker (offline)
└── README.md
```

## 🧮 Cara Hitung Keuntungan

```
Profit Kotor     = (Harga Jual - Harga Modal) × Jumlah Terjual
Keuntungan Bersih = Profit Kotor - Total Pengeluaran
```

## 🛠️ Teknologi

- HTML5 + CSS3 (Mobile-first)
- Vanilla JavaScript
- localStorage
- Progressive Web App (PWA)

---

Dibuat untuk memudahkan UMKM mengelola stok dan penjualan harian.
