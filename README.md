# 🔄 File Converter Tools – HTML & JS

Proyek ini berisi kumpulan tools konversi berbagai format file berbasis **HTML + JavaScript**, yang berfungsi 100% secara **client-side** (tanpa server). Dirancang modular, ringan, dan dapat diakses langsung melalui browser.

---

## 🎯 Fitur Utama

- ✅ TXT ke PDF (`txttopdf.html`)
- ✅ HTML ke PDF (`htmltopdf.html`)
- ✅ JPG ke PDF (`jpgtopdf.html`)
- ✅ Multi JPG ke PDF (`multijpgtopdf.html`)
- ✅ JPG ↔ PNG (`jpgtopng.html`)
- ✅ PDF ke JPG (`pdftojpg.html`)
- ✅ PDF ke PNG (`pdftopng.html`)
- ✅ Extract Teks dari PDF (`txttopdf.html` → versi extractor)

Semua converter dilengkapi:
- Antarmuka interaktif dan responsif
- Tombol kembali ke `index.html`
- Animasi loading selama proses
- Penyimpanan nama file ke `localStorage`
- Fungsi unduh langsung (tanpa server)

---

## 📁 Struktur Folder

```plaintext
/ (root)
├── index.html
├── txttopdf.html
├── htmltopdf.html
├── jpgtopdf.html
├── multijpgtopdf.html
├── pdftojpg.html
├── pdftopng.html
├── jpgtopng.html
├── /tools/ (opsional untuk script modular)
└── README.md
🚀 Cara Menggunakan
Buka index.html di browser modern

Pilih jenis konversi sesuai kebutuhan

Upload file dan klik tombol konversi

Unduh hasil langsung atau simpan ke perangkat

Klik “⬅️ Kembali ke Index” untuk kembali ke dashboard

📌 Catatan
Semua tool dijalankan di browser, tidak ada data dikirim ke server.

Untuk konversi Word, Excel, PowerPoint, dll mungkin butuh API tambahan.

Proyek ini dapat dikembangkan menjadi PWA atau aplikasi desktop berbasis Electron.

🧑‍💻 Author
Mohamad Akhirudin Website/Portfolio: [Link kamu di sini] Email: [Email kamu opsional]

🛠️ Lisensi
Lisensi bebas digunakan dan dimodifikasi. Kredit tetap disarankan saat publikasi ulang.
