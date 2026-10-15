# milestone1-2

#Cashere

Cashere adalah prototype aplikasi kasir dan manajemen stok sederhana yang dibuat menggunakan HTML, CSS, dan JavaScript. Aplikasi ini terdiri dari halaman login dan dashboard untuk menambah serta mengelola data produk seperti nama produk, kategori, harga, dan jumlah stok.

## Gambaran Umum Proyek

Proyek ini dibuat sebagai prototype frontend untuk sistem manajemen usaha kecil atau toko. Aplikasi ini meniru alur kerja kasir di mana admin dapat:

- login ke sistem
- melihat dashboard
- menambahkan produk baru
- mengisi kategori, harga, dan stok produk
- melihat daftar produk
- mensimulasikan proses input produk yang berhasil

## Fitur

- Halaman login dengan input username dan password
- Layout dashboard dengan sidebar navigasi
- Form produk untuk menambahkan menu atau item baru
- Tabel daftar produk dan stok
- Tampil waktu dan tanggal secara real-time di dashboard
- Interaksi sederhana berbasis JavaScript
- Desain UI dasar yang responsif menggunakan CSS

## Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript
- Aplikasi web statis (belum ada backend/database)

## Struktur Proyek

```text
.
├── index.html          # Halaman login
├── dashboard.html      # Halaman dashboard pengelolaan produk
├── jscript.js          # Logika JavaScript untuk jam, login, dan form produk
├── README.md           # Dokumentasi proyek
└── .gitignore          # File ignore opsional jika ditambahkan nanti
```

## Cara Menjalankan

1. Buka folder proyek di browser.
2. Mulai dengan membuka `index.html`.
3. Masukkan username dan password, lalu kirim form.
4. Anda akan diarahkan ke `dashboard.html`.

Anda juga dapat menjalankannya dengan server lokal sederhana, misalnya:

```bash
python3 -m http.server 8000
```

Lalu buka:

```text
http://localhost:8000
```

## Catatan Penggunaan

Versi saat ini masih merupakan prototype frontend dan belum terhubung ke database atau API backend yang nyata. Saat tombol simpan produk ditekan, aplikasi menampilkan alert dan mereset form untuk mensimulasikan proses input.

## Pengembangan Selanjutnya

- menghubungkan ke database yang nyata
- menambahkan fitur edit dan hapus produk
- membuat fitur transaksi penjualan
- membuat laporan pendapatan dan stok
- menambahkan validasi autentikasi dan session login
- meningkatkan desain UI dan responsivitas mobile

## Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan prototype.
