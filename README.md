# Portofolio Akademik - Fazry Ilham Sulaeman (HTN 1B)

Website portofolio akademik berbasis *single-page* modern dengan estetika **Neo-Brutalism** terinspirasi dari arsitektur desain [api.jaky.dev](https://api.jaky.dev). Dibuat khusus untuk memenuhi tugas mata kuliah **Bahasa Arab / Siyasah Syar'iyyah** pada Program Studi **Hukum Tata Negara (HTN 1B)**, Fakultas Syari'ah dan Hukum, UIN Sunan Gunung Djati Bandung.

---

## 🌟 Fitur Utama & Desain

1. **Arsitektur Neo-Brutalisme (api.jaky.dev Style):**
   - Garis batas tegas hitam pekat (`border-[3px] border-black`), sudut kartu tebal (`rounded-2xl`), dan efek bayangan padat asimetris (`shadow-[6px_6px_0px_0px_#000]`).
   - Palet warna kontras berani: Vibrant Yellow (`#FFE600`), Cyan (`#00F0FF`), Neo-Pink (`#FF3366`), Lime Green (`#00FF88`), serta latar belakang abu-abu terang bersih (`#F8FAFC`).
   - Tipografi modern Google Fonts **Plus Jakarta Sans** untuk teks Latin dan **Amiri** untuk teks beraksara Arab dengan dukungan penuh tata letak RTL (*Right-to-Left*) dan harakat yang presisi.

2. **Panel Admin Interaktif (Full Customizer):**
   - Dilengkapi sistem otentikasi login aman:
     - **Username**: `fazry`
     - **PIN**: `060508`
   - **Upload Foto Profil**: Unggah langsung file gambar dari HP/laptop (disimpan otomatis sebagai data gambar Base64) atau gunakan tautan URL online.
   - **Kelola Biodata**: Ubah nama lengkap, NIM, kelas, program studi, fakultas, mata kuliah, dan catatan bio mahasiswa.
   - **Kelola Tugas 1 (10 Mufradat Siyasah)**: Saklar toggle status tugas (Kosong vs Selesai), edit 10 kosakata Arab berharakat, transliterasi, arti, dan contoh kalimat siyasah. Tersedia tombol *1-Click Preset* untuk mengisi 10 istilah siyasah standar secara otomatis.
   - **Kelola Tugas 2 (Qira'ah & Audio)**: Saklar toggle status tugas, edit judul, naskah Arab, terjemahan Indonesia, serta pemutar dan pengunggah rekaman suara audio MP3 / WAV.
   - **Kelola Tugas 3 (UAS Makalah)**: Saklar toggle status tugas, edit judul makalah, dosen pengampu, abstrak, dan pengunggah dokumen PDF.
   - **Penyimpanan Lokal (localStorage)**: Semua perubahan tersimpan secara aman di browser tanpa ketergantungan server database eksternal.

3. **Status Bawaan (Default State):**
   - Sesuai instruksi, secara bawaan seluruh slot tugas berstatus **Kosong** (*"Belum Ada Tugas yang Dikerjakan"*) hingga diisi atau diaktifkan melalui Panel Admin.

---

## 🔐 Kredensial Panel Admin

Untuk membuka Panel Admin dan mengelola portofolio:
1. Klik tombol **[Panel Admin]** atau **[Kelola di Admin]** di navbar atau banner website.
2. Masukkan:
   - **Username**: `fazry`
   - **PIN**: `060508`
3. Klik **Verifikasi & Masuk Dashboard**.
4. Lakukan kustomisasi yang diinginkan, lalu klik **Simpan Semua Perubahan**.

---

## 📁 Struktur Berkas

```text
fazry-portofolio/
├── index.html       # Seluruh kode website + Panel Admin (Tailwind CSS CDN & Vanilla JS)
└── README.md        # Dokumentasi lengkap proyek
```

---

## 🚀 Tautan Live & Deployment

- **Website Live (Vercel)**: [https://fazry-portofolio.vercel.app](https://fazry-portofolio.vercel.app)
- **Repositori GitHub**: [https://github.com/aetheriashop/fazry-portofolio](https://github.com/aetheriashop/fazry-portofolio)

Setiap perubahan yang di-*push* ke cabang `main` pada GitHub akan memicu *auto-deployment* secara instan ke Vercel.
