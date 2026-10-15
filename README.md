# 🌱 Tumbuhin — Tool Konversi File

Kumpulan tool konversi file dalam **satu halaman HTML**, berbasis **HTML + JavaScript** 100% client-side (tanpa server, tanpa backend, tanpa upload ke mana pun).

Tema warna: **Warm Lime `#CFFF74`** + **Olive Ink `#2F3A1D`**.

---

## 🎯 Fitur

Semua tool dibuka lewat satu dashboard (tanpa berpindah halaman):

| Tool | Keterangan |
| --- | --- |
| TXT ke PDF | Tempel teks, simpan jadi PDF A4 |
| HTML ke PDF | Render kode HTML jadi PDF |
| JPG ke PDF | Satu gambar jadi satu halaman PDF |
| Multi JPG ke PDF | Gabung banyak gambar, atur urutan (drag & drop) |
| PDF ke JPG | Render halaman PDF jadi JPG/PNG |
| JPG ke PNG | Konversi format gambar |
| PDF ke PNG | Halaman PDF jadi gambar PNG |
| Extract Teks PDF | Ambil teks dari PDF, salin / unduh `.txt` |
| Gabung PDF | Satukan beberapa PDF, atur urutan |
| PDF + Gambar ke PDF | Campur PDF + gambar, urutkan, jadi satu PDF |
| Tanda Tangan PDF | Upload PDF + TTD PNG, geser posisinya di halaman |
| Kompresor ZIP | Gabung & kompres file jadi satu ZIP |
| Remove Background | Hapus warna latar jadi PNG transparan |
| Split Halaman PDF | Pilih halaman, simpan jadi PDF baru atau pisah per halaman (ZIP) |
| Kompres & Resize Gambar | Perkecil ukuran + ubah format gambar, hasil ZIP |
| Generator QR Code | Teks/URL jadi QR code PNG |
| Watermark PDF | Watermark teks atau gambar, atur posisi & opasitas |
| Putar Halaman PDF | Rotasi per halaman 90/180/270° |
| Metadata PDF | Lihat & ubah Title, Author, Subject, Keywords |
| Crop & Rotasi Gambar | Potong, putar, balik gambar |
| Konversi Satuan | Panjang, berat, luas, volume, suhu, kecepatan, waktu, data |
| Office ke PDF | DOCX, XLSX, CSV, PPTX → PDF |
| OCR Gambar ke Teks | Baca teks dari gambar (Tesseract, ind/eng/ara/jpn) |
| Kompres PDF | Optimasi struktur atau raster ulang (paling kecil) |
| Hapus Halaman PDF | Pilih halaman yang dibuang, simpan sisanya |
| Proteksi PDF | Kunci PDF dengan password pembuka & pemilik |
| Nomor & Tanggal Dokumen | Stempel nomor dokumen + tanggal, posisi bebas |
| URL ke PDF | Simpan halaman web jadi PDF |
| Generator & Hash | Password acak, UUID v4, hash SHA-256 |

Semua工具 berjalan di browser. Library berat (Mammoth, SheetJS, Tesseract, enkripsi PDF) **dimuat on-demand** saat tool dipakai, bukan saat halaman dibuka.

## ✨ Fitur dashboard

- **Favorit** — klik ★ pada kartu atau seret ke area favorit
- **Susun kartu** — seret kartu untuk mengubah urutan
- Keduanya tersimpan di `localStorage` browser masing-masing, dan bisa di-reset lewat tombol **Reset urutan**

Fitur pendukung:

- 🔍 Pencarian tool
- 📤 Upload via klik maupun drag & drop
- 🧾 Riwayat file tersimpan di `localStorage`
- 📱 Responsif (mobile friendly)
- ⌨️ Modal tool dengan tombol `Esc` untuk menutup

---

## 🚀 Cara Menggunakan

Buka `index.html` di browser modern, lalu pilih tool yang dibutuhkan.

---

## 📁 Struktur Folder

```plaintext
/
├── index.html   # satu-satunya file aplikasi
└── README.md
```

---

## 📌 Catatan

Semua tools berjalan sepenuhnya di browser — tidak ada data yang dikirim ke server.

Untuk konversi Word, Excel, PowerPoint, dll. mungkin butuh library tambahan.

Proyek ini dapat dikembangkan menjadi PWA atau aplikasi desktop berbasis Electron.

---

## 🧑‍💻 Author

Mohamad Akhirudin

---

## 🛠️ Lisensi

Bebas digunakan dan dimodifikasi. Kredit tetap disarankan saat publikasi ulang.