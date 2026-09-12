Berikut adalah draf *Product Requirements Document* (PRD) yang disusun secara terstruktur untuk proyek tugas akhir web Anda. PRD ini dapat digunakan sebagai panduan pengembangan agar semua kriteria submission terpenuhi dengan sempurna.

---

# Product Requirements Document (PRD)

**Nama Proyek:** Tugas Akhir Dasar Pemrograman Web
**Platform:** Web Based (Static HTML & CSS)
**Pengembang:** Faras Sulthan Pratama 

## 1. Ringkasan Proyek

Proyek ini bertujuan untuk membangun sebuah website statis yang sepenuhnya responsif dan semantik. Website ini akan berfungsi sebagai halaman profil atau portofolio pribadi (dengan potensi mengadaptasi estetika antarmuka retro/game yang dibalut dalam tema gelap). Fokus utama pengembangan adalah pemahaman fundamental HTML5 dan CSS tanpa bergantung pada *framework* eksternal.

## 2. Spesifikasi Desain & UI/UX

* **Tema Warna Utama:** *Dark purplish* dan *Black*.
* *Background Utama:* Hitam solid (`#000000` atau `#121212`).
* *Aksen & Elemen:* Nuansa ungu gelap hingga terang (misal: `#3b0764`, `#6b21a8`, atau `#a855f7`).


* **Sistem Layouting:** Wajib menggunakan **Flexbox** untuk mengatur tata letak elemen (navbar, pembagian kolom konten dan sidebar, dll). Penggunaan properti `float` dilarang keras.
* **Responsivitas:** Menggunakan **Media Query** (`@media`) untuk memastikan layout dapat beradaptasi dengan baik di berbagai ukuran layar (mobile, tablet, desktop).

## 3. Struktur HTML & Konten Semantik

Website wajib menggunakan elemen *semantic* HTML5 untuk mendefinisikan struktur halaman:

* `<header>`: Memuat judul utama website atau logo.
* `<nav>`: Memuat menu navigasi. **Wajib** terdapat elemen *anchor* (`<a>`) yang mengarah persis ke URL: `https://www.dicoding.com/users/farasha/academies`.
* `<main>`: Membungkus seluruh konten utama halaman.
* `<article>`: Membungkus konten tulisan atau entri informasi yang berdiri sendiri di dalam `<main>`.
* `<aside>`: Berfungsi sebagai *sidebar*.
* **Konten Wajib:** Harus menampilkan foto menggunakan *placeholder* sementara (misal: `https://via.placeholder.com/300x300`).
* **Konteks Tambahan:** Dapat diisi dengan biodata singkat pengembang (sebagai mahasiswa Informatika UTY) atau informasi ringkas yang relevan dengan artikel.


* `<footer>`: Menampilkan hak cipta atau tautan penutup di bagian bawah halaman.

## 4. Spesifikasi Teknis & Aturan Pengkodean

Untuk mendapatkan penilaian maksimal dan menghindari status *tidak sah*, aturan teknis berikut harus dipatuhi:

1. **Pemisahan Berkas:** Seluruh aturan *styling* harus ditulis di dalam berkas eksternal berekstensi `.css` (contoh: `style.css`), yang dihubungkan ke `index.html` menggunakan tag `<link>`.
2. **Hierarki Heading:**
* Hanya boleh terdapat **satu buah elemen `<h1>**` dalam seluruh halaman HTML.
* Penggunaan heading (`<h2>`, `<h3>`, dst.) harus berurutan secara logis dan tidak boleh melompati level (contoh: setelah `<h2>` harus `<h3>`, dilarang langsung melompat ke `<h4>`).


3. **Aksesibilitas (a11y):** Seluruh elemen gambar (`<img>`) di dalam `index.html` wajib memiliki atribut `alt` (*alternative text*) yang mendeskripsikan gambar tersebut.

## 5. Kriteria Penolakan (Blockers)

Proyek akan dianggap **TIDAK SAH** dan akan langsung ditolak apabila:

* Gagal memenuhi satu atau lebih kriteria wajib (struktur semantik, tautan profil Dicoding, foto di aside, warna, atau layout Flexbox).
* Gagal memenuhi ketentuan struktur berkas submission yang diminta oleh platform.
* Menggunakan *library* atau *framework* CSS seperti **Bootstrap, Tailwind, Materialize, Foundation**, dan sejenisnya. Layout dan *styling* harus 100% *Vanilla CSS*.

---

### Daftar Periksa (Acceptance Criteria Checklist)

Gunakan tabel ini saat proses pengembangan (*development*) untuk memastikan tidak ada poin yang terlewat:

| Status | Komponen / Fitur | Kriteria |
| --- | --- | --- |
| [ ] | **Struktur HTML** | Terdapat `<header>`, `<nav>`, `<footer>`, `<main>`, `<article>`, `<aside>`. |
| [ ] | **Link Profil** | Pada `<nav>`, terdapat `<a href="https://www.dicoding.com/users/farasha/academies">`. |
| [ ] | **Biodata/Aside** | Elemen `<aside>` menampilkan foto (placeholder) dengan atribut `alt`. |
| [ ] | **Layouting** | Tata letak menggunakan **Flexbox**. Tidak ada elemen yang menggunakan `float`. |
| [ ] | **Tema Visual** | Warna dominan *dark purpleish* dan *black*. |
| [ ] | **File CSS** | Kode CSS dipisah pada berkas `.css` mandiri. |
| [ ] | **Aksesibilitas** | Semua tag `<img>` memiliki `alt` text. |
| [ ] | **SEO/Heading** | Hanya ada satu `<h1>`. Level heading berurutan secara logis (`<h2>` ke `<h3>` dst). |
| [ ] | **Responsivitas** | Terdapat implementasi Media Query untuk layar *mobile/tablet*. |
| [ ] | **Validasi Framework** | **Nol** penggunaan framework CSS (Tailwind, Bootstrap, dll). |