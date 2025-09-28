# NIKAHFIX

**NIKAHFIX** adalah sebuah website undangan pernikahan yang terinspirasi dari tampilan _Netflix_, memberikan pengalaman visual menarik dan modern untuk pengguna. Proyek ini dibangun menggunakan **React** dengan bundler **Vite**, dirancang agar mudah diakses, responsif, dan estetis.

## Demo

Anda dapat melihat demo langsung dari NIKAHFIX di sini: [NIKAHFIX - Demo](https://nikahfix-v01.vercel.app/).
Jika anda memiliki tujuan spesifik undangannya, bisa dibuat link seperti berikut [https://nikahfix-v01.vercel.app/?to=tajul+dan+gorbon](https://nikahfix-v01.vercel.app/?to=tajul+dan+gorbon)

## Teknologi yang Digunakan

- **React**: Library JavaScript untuk membangun antarmuka pengguna.
- **Vite**: Bundler modern untuk pengembangan aplikasi web cepat dengan konfigurasi minimal.
- **TailwindCSS**: Untuk mendesain tampilan visual agar lebih menarik.
- **LocalStorage**: Untuk menyimpan data wish/ucapan secara lokal di browser.
- **Vercel**: Platform hosting yang digunakan untuk menyajikan demo.

## Instalasi

Berikut adalah langkah-langkah untuk menginstal proyek ini di lingkungan lokal Anda:

1. **Clone Repository**:

   `git clone https://github.com/arifintajul4/nikahfix.git`

2. **Masuk ke Direktori Proyek**:

   `cd nikahfix`

3. **Instal Dependensi**:
   Pastikan Anda sudah menginstal Node.js. Jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan.

   `npm install`

4. **Menjalankan Proyek**:
   Setelah semua dependensi terpasang, jalankan proyek dengan perintah:

   `npm run dev`

5. **Mengakses Proyek**:
   Buka browser Anda dan akses proyek di

   `http://localhost:5173`

## Fitur Wish/Ucapan

Aplikasi ini dilengkapi dengan fitur wish atau ucapan untuk pasangan pengantin yang:
- Menyimpan data secara lokal menggunakan localStorage browser
- Validasi input nama minimal 3 karakter dan pesan minimal 10 karakter  
- Filter kata kasar menggunakan library indonesian-badwords
- Tampilan yang menarik dengan avatar berwarna acak untuk setiap ucapan
- Data persist ketika browser di-refresh

## Struktur Proyek

Berikut adalah struktur direktori proyek:

- `src/` - Berisi komponen utama dan logika aplikasi.
  - `components/` - Komponen React yang dapat digunakan kembali.
  - `data/` - File konfigurasi JSON untuk data undangan.
- `public/` - Berisi aset-aset statis, seperti gambar dan ikon.

---
