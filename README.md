# Landing Page Pengumuman Kelulusan MA MA'ARIF NU 5 SEKAMPUNG

Ini adalah halaman landing sederhana untuk menampilkan pengumuman kelulusan siswa/i berdasarkan NISN menggunakan Google Spreadsheet sebagai basis data.

## 🔧 Fitur
- Halaman sambutan dari Kepala Sekolah
- Tombol login untuk mengecek kelulusan
- Pencarian berdasarkan NISN
- Status kelulusan ditampilkan langsung dari Spreadsheet

## 📄 Cara Deploy

### 1. Clone atau Download Repository ini
```
git clone https://github.com/username/pengumuman-kelulusan.git
```

### 2. Buka `index.html` di browser lokal untuk testing

### 3. Deploy ke GitHub Pages
- Push file ini ke repository GitHub kamu
- Masuk ke **Settings > Pages**
- Pilih source: `main branch`, folder: `/root`
- Setelah aktif, akan muncul link seperti:
```
https://username.github.io/pengumuman-kelulusan/
```

## 🔗 API Google Spreadsheet
Data siswa diambil secara real-time dari SheetDB:
```
https://sheetdb.io/api/v1/o92xhth4o65mg/search?NISN=1234567890
```

## 📋 Format Spreadsheet
Pastikan spreadsheet kamu memiliki kolom berikut:
- NISN
- Nama Peserta
- Status

## ✨ Contoh Tampilan
- Sambutan
- Form input NISN
- Hasil kelulusan

---

Jika kamu menemukan bug atau ingin menambahkan fitur, silakan buka _issue_ atau kirim _pull request_.

---

**Dibuat dengan ❤️ untuk MA MA'ARIF NU 5 SEKAMPUNG**
