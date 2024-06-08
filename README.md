# Project Management App
Sebuah aplikasi website untuk mengelola list proyekan dalam sebuah tim untuk kepentingan kerjaan dan pembagian tugas untuk masing - masing orang yang terlibat dalam proyekan tersebut


## Daftar Isi
- [Tumpukan Teknologi](#tumpukan-teknologi)
- [Fitur](#fitur)
- [Dokumentasi Halaman](#dokumentasi-halaman)
- [Cara Instalasi](#cara-instalasi)
- [Cara Penggunaan](#cara-penggunaan)

## Tumpukan Teknologi
### Frontend
- **ReactJS**: Perpustakaan UI untuk membangun antarmuka pengguna
- **Tailwind CSS**: Kerangka kerja CSS berbasis utilitas
- **Vite**: Alat pengembangan front-end generasi berikutnya untuk pengembangan yang lebih cepat

### Backend
- **Laravel 11**: Kerangka kerja PHP untuk pengembangan web yang elegan dan ekspresif
- **Laravel Breeze**: Alat yang ringan untuk membuat aplikasi Laravel dengan autentikasi default yang sederhana

### DBMS
- **MySQL**: Sistem manajemen basis data relasional open-source

## Fitur
- Merangkum Website Artikel : Merangkum isi keseluruhan isi website artikel agar menghemat waktu dengan tahu isinya secara umum.
- Menampilkan Hisotri Pencarian : Menampilkan histori pencarian agar dapat melihat kembali isi webiste yang telah dicari
- Menghapus Histori Pencarian : Menghapus histori pencarian agar dapat melihat histori yang diinginkan saja

## Dokumentasi Halaman
![Dokumentasi Halaman](Dokumentasi.png)

## Cara Instalasi
```bash
# Clone repository ini
git clone https://github.com/username/repository-name.git

# Masuk ke direktori proyek
cd repository-name

# Instal dependensi
npm install

# Jalankan server artisan
php artisan serve

# Jalankan server frontendnya secara live
npm run dev --watch

# Buka url server artisannya
http://localhost:8000/

```

## Cara Penggunaan
1. Cari website artikel dengan contoh link url ini ```https://en.wikipedia.org/wiki/Avatar:_The_Last_Airbender```
2. Paste url tersebut ke kolom pencarian
3. Hasil akan tampil di kolom histoti


