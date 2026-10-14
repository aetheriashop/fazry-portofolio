# Portofolio Akademik Bahasa Arab & Siyasah Syar'iyyah

Website portofolio akademik berbasis *single-page* yang dirancang secara modern, elegan, responsif, dan bernuansa islami/akademis. Website ini dibuat untuk memenuhi tugas mata kuliah **Bahasa Arab / Siyasah Syar'iyyah**.

---

## 🌟 Fitur Utama

1. **Tema & Desain Elegan:**
   - Paduan warna **Emerald Green** (`#064e3b`), **Gold Accents** (`#d97706`), dan latar belakang putih pudar bersih.
   - Menggunakan tipografi Google Fonts **Poppins** (Latin) dan **Amiri** / **Scheherazade New** (Arab) dengan tampilan harakat yang jelas dan nyaman dibaca (RTL support).
   - Sticky Navigation Bar dengan transisi *smooth scrolling* dan menu responsif untuk mobile.

2. **Hero Section & Biodata Mahasiswa:**
   - Menampilkan Nama, NIM, Kelas, serta foto profil berbingkai melingkar elegan.
   - Informasi akademik lengkap: Program Studi Hukum Tatanegara Islam (*Siyasah Syar'iyyah*), Fakultas, dan Universitas.
   - Deskripsi motivasi dan minat studi turats & ketatanegaraan Islam.

3. **Tugas 1: 10 Mufradat Siyasah (Interaktif):**
   - 10 Kosakata politik & ketatanegaraan Islam lengkap dengan harakat, transliterasi Latin, arti, serta contoh kalimat aplikatif.
   - Fitur pencarian langsung (*Live Search*).
   - Tombol pengalih tampilan (*View Toggler*): Tampilan Kartu (*Grid*) & Tabel Lengkap.
   - Tombol salin teks (*Copy to Clipboard*) dan fitur pelafalan audio (*Text-to-Speech*).

4. **Tugas 2: Tugas Baca Teks (Qira'ah):**
   - Paragraf teks Arab bertema esensi Siyasah Syar'iyyah dan keadilan politik Islam dengan teks ayat Al-Qur'an (Surat An-Nisa: 58).
   - Pemutar audio bawaan (*HTML5 Audio Player*) untuk rekaman suara membaca teks qira'ah.
   - Fitur buka-tutup (*Accordion/Toggle*) terjemahan bahasa Indonesia.

5. **Tugas 3: Portofolio Tugas UAS:**
   - Showcase dokumen tugas akhir semester berupa makalah analisis terminologi siyasah.
   - Tombol unduh dokumen PDF dan tombol modal pratinjau (*Preview Modal*).

6. **Footer & Kontak:**
   - Tautan email, WhatsApp, dan GitHub.
   - Tombol melayang *Back to Top*.

---

## 📁 Struktur Berkas

```text
fazry-portofolio/
├── index.html       # Berkas utama website (HTML, Tailwind CSS CDN & Vanilla JS)
└── README.md        # Dokumentasi dan panduan kustomisasi
```

---

## 🛠️ Panduan Kustomisasi Data Pribadi

Buka berkas `index.html` menggunakan teks editor (misalnya Antigravity / VS Code). Cari tanda komentar `[EDIT DISINI]` untuk mengganti data Anda:

1. **Nama, NIM, dan Kelas:**
   - Cari kata `Muhammad Fazry`, `123456789`, dan `Siyasah Syar'iyyah - A` di bagian Hero dan Profil. Ganti dengan data Anda.
2. **Foto Profil:**
   - Ganti atribut `src="..."` pada elemen foto di bagian Hero dan Profil dengan link gambar atau foto lokal (contoh: simpan file `foto.jpg` di folder yang sama, lalu ubah menjadi `src="foto.jpg"`).
3. **Rekaman Suara Qira'ah:**
   - Ganti atribut `src="..."` pada tag `<audio id="readingAudio">` dengan berkas audio Anda (contoh: `src="audio-tugas.mp3"`).
4. **Tautan Unduh PDF UAS:**
   - Ganti atribut `href="#"` pada `<a id="downloadPdfBtn">` dengan link atau file PDF naskah UAS Anda (contoh: `href="tugas-uas-fazry.pdf"`).

---

## 🚀 Akses Online & Cara Menjalankan

### 1. Tautan Live Online
- **Vercel (Production)**: [https://fazry-portofolio.vercel.app](https://fazry-portofolio.vercel.app)
- **GitHub Pages**: [https://aetheriashop.github.io/fazry-portofolio/](https://aetheriashop.github.io/fazry-portofolio/)

### 2. Menjalankan di Komputer Lokal
Cukup klik ganda (*double-click*) file `index.html` untuk langsung membukanya di browser Google Chrome, Edge, atau Firefox tanpa instalasi server tambahan.

### 3. Otomasi CI/CD
Repositori GitHub ini telah terhubung langsung dengan **Vercel**. Setiap kali Anda melakukan `git push` ke cabang `main`, Vercel akan otomatis melakukan pembaruan (*auto-deploy*) ke website live Anda.

