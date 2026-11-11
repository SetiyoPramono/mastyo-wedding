# 💍 MasTyo Wedding — Galeri Undangan Digital & Otomasi Pengiriman

Platform galeri desain undangan pernikahan digital (*online invitation*) eksklusif persembahan **MasTyo Wedding**. Dilengkapi 12 tema responsif, musik latar, animasi pembuka interaktif, personalisasi nama tamu dinamis (`?to=NamaTamu`), serta **Halaman Generator & Otomasi Kirim Undangan** langsung ke WhatsApp dan Email tamu.

---

## ✨ Fitur Utama

### 1. 💌 Halaman Otomasi Kirim Undangan (`kirim-undangan.html`)
- **Tautan Personal Otomatis**: Cukup tempel link website undangan Anda, sistem otomatis menyematkan parameter `?to=NamaTamu`.
- **Template Greeting Siap Pakai**: Pilihan 5 preset pesan (Formal, Islami, Kristiani, Santai, Ringkas) dengan variabel dinamis `{nama}`, `{url}`, `{pengantin}`, `{tanggal}`.
- **Simulasi Obrolan WhatsApp**: Pratinjau gelembung chat WhatsApp secara *real-time*.
- **Kirim WhatsApp 1-Klik**: Tombol instan yang otomatis membuka aplikasi WhatsApp di HP (Android/iOS) atau WhatsApp Web di PC dengan nomor tujuan dan pesan yang terisi lengkap.
- **⚡ Kirim Tamu Berikutnya**: Tombol antrean cepat untuk memproses pengiriman satu per satu tanpa harus mencari baris di tabel.
- **Kirim via Email**: Mendukung pengiriman melalui aplikasi email bawaan (*mailto*).
- **Penyimpanan Lokal (LocalStorage)**: Seluruh daftar tamu dan template pesan tersimpan otomatis di browser secara aman.
- **Input Fleksibel**: Mendukung input satu per satu maupun *paste massal* dari Microsoft Excel / Google Sheets sekaligus.
- **Peralatan Data**: Ekspor CSV, filter status (*Belum Dikirim* vs *Sudah Terkirim*), dan pencarian nama instan.

### 2. 🏛️ Katalog Tema Undangan (`index.html`)
- **12 Koleksi Desain Eksklusif**:
  - **Tema 12**: Japandi & Zen Garden (Modern & Minimalis)
  - **Tema 11**: Modern Luxury Glass (Translucent Aura)
  - **Tema 10**: Classic Royal Gold (Imperial Heritage)
  - **Tema 9**: Emerald Botanical (Secret Garden)
  - **Tema 8**: Sunset Terracotta (Warm Bohemian)
  - **Tema 7**: Midnight Celestial (Starry Night)
  - **Tema 6**: Minimalist Mono (Monochrome Modern)
  - **Tema 5**: Rustic Vintage (Earthy Autumn)
  - **Tema 4**: Traditional Javanese (Batik & Keraton)
  - **Tema 3**: Elegant Navy (Royal Sapphire)
  - **Tema 2**: Rose Gold Romance (Blush Pink)
  - **Tema 1**: Pure Floral Garden (Pastel Spring)
- **Navbar Tetap (*Fixed on Scroll*)**: Desain kaca buram (*glassmorphism*) yang tetap menempel di atas layar saat discroll.
- **Floating Back-to-Top**: Tombol melayang di pojok kanan bawah untuk kembali ke puncak halaman dengan satu ketukan.
- **Personalisasi Demo**: Uji coba nama tamu langsung di katalog untuk melihat sampul undangan berganti nama secara langsung.

---

## 📁 Struktur Berkas

```text
MasTyo Weddings/
├── index.html                   # Beranda & Katalog 12 Koleksi Tema
├── kirim-undangan.html          # Halaman Otomasi Pengiriman Undangan WA/Email
├── tema1.html - tema12.html     # Halaman Template Undangan Digital
├── logo-mastyo.png              # Aset Logo Resmi MasTyo Wedding
├── Payung Teduh - Akad (...).mp3 # Audio Latar Suasana
├── .gitignore                   # Konfigurasi Git Ignore
└── README.md                    # Dokumentasi Proyek
```

---

## 🚀 Cara Menjalankan Secara Lokal

1. **Clone Repository**:
   ```bash
   git clone https://github.com/SetiyoPramono/mastyo-wedding.git
   cd mastyo-wedding
   ```
2. **Buka di Browser**:
   - Klik ganda pada `index.html` untuk membuka katalog tema.
   - Buka `kirim-undangan.html` untuk mengelola daftar tamu dan mengirim undangan via WhatsApp.
   - Atau jalankan dengan Live Server (VS Code) / server lokal:
     ```bash
     npx serve .
     ```

---

## 📱 Panduan Penggunaan Halaman Kirim Undangan

1. Buka `kirim-undangan.html`.
2. Pada panel **URL / Tautan Undangan**, tempelkan tautan website undangan pernikahan Anda (misal: `https://domainanda.com/undangan` atau `tema12.html`).
3. Sesuaikan template pesan pada panel **Template Pesan (Greeting)**.
4. Masukkan daftar nama dan nomor WhatsApp tamu:
   - Pilih tab **Input Satu Per Satu**, atau
   - Pilih tab **Paste Banyak Tamu Sekaligus** untuk menempelkan daftar tamu dari Excel.
   - Gunakan tombol **"Isi Contoh Demo"** jika ingin melihat contoh format baris.
5. Klik **"Proses & Masukkan Semua Tamu"**.
6. Klik tombol hijau **"Kirim WA"** pada setiap baris tamu atau klik **"⚡ Kirim Tamu Berikutnya"** untuk memproses antrean secara berurutan.

---

## 📄 Hak Cipta & Lisensi

© 2026 **[MASTYO](https://mastyo.my.id/)** Undangan Digital • All Rights Reserved.

