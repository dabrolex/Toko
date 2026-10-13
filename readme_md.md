<!-- STREAMING_CHUNK: Mengkonfigurasi Header & Badges README... -->
# Kérastase Official Online Store & AI Hair Advisor 🛍️✨

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Gemini AI](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat&logo=google&logoColor=white)](https://ai.google.dev/)

Aplikasi web e-commerce *single-file* interaktif untuk e-store resmi **Kérastase Paris**, dilengkapi dengan sistem **AI Hair Specialist Advisor** (berbasis Google Gemini API) untuk diagnosa masalah rambut secara pintar dan fitur pesanan langsung via **WhatsApp Checkout**.

---

## 🌟 Fitur Utama

- 🎨 **Desain Mewah & Responsif**: Tampilan modern bertema *luxury luxury gold & dark* yang disesuaikan penuh untuk perangkat Mobile, Tablet, maupun Desktop.
- 🛍️ **Katalog Produk Dinamis**:
  - Filter produk berdasarkan kategori (Bain/Sampo, Serum & Oil, Masque/Masker, Fondant/Kondisioner).
  - Filter cepat berdasarkan permasalahan rambut (*Hair Concern*: Rontok, Kering, Kusam, Rusak, Ketombe).
  - Pencarian *live search* langsung berdasarkan kata kunci nama atau deskripsi produk.
- 🛒 **Keranjang Belanja Interaktif**: *Slide-over drawer* dengan manajemen jumlah item dan kalkulasi total otomatis.
- 🤖 **Kérastase AI Hair Advisor**:
  - Konsultasi masalah rambut secara personal dengan AI Specialist.
  - Rekomendasi takaran/dosis dan rutinitas pemakaian *step-by-step* pada setiap *modal* detail produk.
- 📱 **WhatsApp Quick Checkout**: Form pemesanan mudah yang langsung memformat dan mengirim rincian pesanan ke WhatsApp Official Store.
- 📷 **Ganti Foto Produk On-the-Fly**: Fitur pengubahan URL foto produk secara dinamis langsung di UI.

---

## 🛠️ Teknologi yang Digunakan

- **Frontend**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS CDN](https://tailwindcss.com/)
- **Icons & Typography**: Font Awesome 6, Google Fonts (*Playfair Display* & *Inter*)
- **AI Integration**: [Google Gemini 3 Flash REST API](https://ai.google.dev/)

---

## 🚀 Panduan Penggunaan & Jalankan Lokal

Karena aplikasi ini dibangun dengan konsep **Single-File App**, Anda tidak perlu melakukan instalasi `npm` atau proses *build* yang rumit!

1. **Clone Repositori ini**:
   ```bash
   git clone https://github.com/username-anda/kerastase-online-store.git
   cd kerastase-online-store
   ```

2. **Buka di Browser**:
   Cukup klik ganda pada berkas `index.html` atau buka menggunakan ekstensi *Live Server* di Visual Studio Code.

3. *(Opsional)* **Konfigurasi API Key Gemini**:
   Untuk menggunakan fitur AI Konsultasi secara mandiri, masukkan API Key Google Gemini Anda pada variabel `apiKey` di fungsi `handleAiConsultation()` dan `askAiProductRoutine()` pada berkas `index.html`:
   ```javascript
   const apiKey = "YOUR_GEMINI_API_KEY_HERE";
   ```

---

## 📂 Struktur Repositori

```text
.
├── index.html        # Seluruh kode HTML, CSS (Tailwind), dan JavaScript App
├── README.md         # Dokumentasi proyek
└── LICENSE           # Berkas Lisensi proyek (MIT)
```

---

## 📄 Lisensi

Proyek ini dipublikasikan di bawah lisensi [MIT License](LICENSE). Bebas untuk dipelajari dan dikembangkan kembali.