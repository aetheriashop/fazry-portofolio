# Portofolio Akademik - Fazry Ilham Sulaeman (HTN 1B)

Website portofolio akademik modern berarsitektur **Neo-Brutalism** terinspirasi dari [api.jaky.dev](https://api.jaky.dev). Dirancang khusus untuk tugas mata kuliah **Bahasa Arab / Siyasah Syar'iyyah**, Program Studi **Hukum Tata Negara (HTN 1B)**, Fakultas Syari'ah dan Hukum, UIN Sunan Gunung Djati Bandung.

---

## 🌟 Fitur Desain & Animasi Non-Scroll

1. **Animasi Berbasis Deck / View Transition (Bukan Scroll Membosankan):**
   - Halaman tidak menggunakan scrolling vertikal yang panjang dan monoton.
   - Menggunakan sistem **App Deck & View Transition** dengan efek *spring pop-in* yang asimetris dan tegas (`@keyframes neoViewIn`).
   - Setiap tab navigasi (`Beranda`, `Profil`, `Kosakata`, `Baca Teks`, `Tugas UAS`, `Kontak`) beralih secara instan dan mulus tanpa harus men-scroll layar.

2. **Landing Page Kaya Visual & Interaktif:**
   - **Continuous Running Marquee**: Running text neon kuning (`#FFE600`) dengan animasi tak terbatas berisi identitas mahasiswa dan mata kuliah.
   - **Floating Sticker Badges**: Label beranimasi mengapung (*subtle floating animation*) dengan kemiringan neo-brutalisme.
   - **Interactive Explore Cards**: 4 kartu jalan pintas interaktif dengan efek *hover lift* dan *shadow pop* untuk langsung membuka tiap tugas.
   - **Hikmah Siyasah Syar'iyyah Widget**: Kotak kutipan politik Islam interaktif lengkap dengan tombol **Ganti Kutipan** (*shuffle* beranimasi) yang memuat kaidah fiqh siyasah, kutipan Al-Mawardi, As-Suyuthi, dan QS. An-Nisa': 58.

3. **Status Bawaan Tugas (Default State):**
   - Seluruh slot tugas 1, 2, dan 3 berstatus bawaan **Kosong** (*"Belum Ada Tugas yang Dikerjakan"*) hingga diisi atau diaktifkan melalui Panel Admin.

---

## 🔒 Akses Panel Admin Tersembunyi (Secret Admin Access)

Panel Admin disembunyikan secara rapi dari pengunjung umum. Untuk membuka modal autentikasi pengelola:

1. **Cara 1 (Triple-Click Logo)**: Klik logo brand **"FS"** di pojok kiri atas navbar sebanyak **3 kali berturut-turut**.
2. **Cara 2 (Triple-Click NIM)**: Klik badge nomor **NIM (1263030076)** di bagian footer sebanyak **3 kali**.
3. **Cara 3 (Kombinasi Tombol Pintas)**: Tekan tombol keyboard `Ctrl + Shift + A` (atau `Alt + A`) di mana saja pada halaman website.
4. **Cara 4 (URL Hash)**: Tambahkan `#admin` pada alamat URL browser (contoh: `https://fazry-portofolio.vercel.app/#admin`).

### 🔑 Kredensial Login:
- **Username**: `fazry`
- **PIN**: `060508`

Setelah login berhasil:
- Muncul badge melayang di pojok kiri bawah: `[ ⚙️ Dashboard (fazry) | Logout ]` yang memudahkan Fazry mengelola konten selama sesi berlangsung.
- Pengunjung reguler tidak akan melihat tombol admin apa pun di halaman utama.

---

## 🎛️ Fitur di Panel Pengelola

- **Upload Foto Profil**: Unggah foto dari HP/laptop (dikonversi ke data Base64) atau gunakan URL gambar online, dengan pratinjau dan tombol hapus/reset.
- **Edit Biodata & Kontak**: Ubah Nama Lengkap, NIM, Kelas, Program Studi, Fakultas, Mata Kuliah, Catatan Bio, serta konfigurasi **Nomor WhatsApp** dan **Alamat Email**.
- **Tugas 1 (10 Mufradat)**: Toggle status tugas Kosong vs Selesai, form kustom 10 mufradat berharakat, dan tombol *1-Click Preset* mufradat siyasah standar.
- **Tugas 2 (Qira'ah & Audio)**: Toggle status, naskah Arab RTL font Amiri, terjemahan Indonesia, dan pengunggah rekaman suara audio MP3.
- **Tugas 3 (UAS PDF)**: Toggle status, judul tugas, dosen pengampu, abstrak, dan pengunggah berkas PDF makalah.
- **Data Persistence**: Disimpan permanen di memori browser pengguna (`localStorage`).

---

## 🚀 Tautan Live & Deployment

- **Website Live (Vercel)**: [https://fazry-portofolio.vercel.app](https://fazry-portofolio.vercel.app)
- **Repositori GitHub**: [https://github.com/aetheriashop/fazry-portofolio](https://github.com/aetheriashop/fazry-portofolio)
