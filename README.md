# Portfolio Faras Sulthan Pratama

Website portfolio pribadi yang menampilkan profil, project, dan artikel. Dibuat sebagai submission kelas **Dasar Pemrograman Web** di [Dicoding](https://www.dicoding.com/).
sekaligus Website Portofolio Pribadi 
 **Live Demo:** [farassulthan.github.io/portfolio-faras](https://farassulthan.github.io/portfolio-faras/)

---

## Tech Stack

| Teknologi | Kegunaan |
|---|---|
| **HTML5** | Struktur semantik (`header`, `nav`, `main`, `article`, `aside`, `footer`) |
| **CSS3 (Vanilla)** | Styling, Flexbox layout, media query, CSS custom properties |
| **JavaScript** | Toggle dark/light theme dengan `localStorage` |
| **Google Fonts** | Typeface [Inter](https://fonts.google.com/specimen/Inter) (400–800) |
| **Material Symbols** | Ikon UI (Rounded, 24px) |

> Tidak menggunakan framework CSS apapun (Bootstrap, Tailwind, dll). Seluruh styling ditulis manual.

---

## Fitur

- **Dark / Light Mode** — Toggle tema yang tersimpan di `localStorage`, mengikuti preferensi sistem saat pertama kali dibuka
- **Responsive Layout** — Adaptif untuk mobile, tablet, dan desktop via media query
- **Sticky Header** — Navigasi tetap terlihat saat scroll, dengan efek backdrop blur
- **Smooth Scroll** — Navigasi anchor ke setiap section
- **Hover Animations** — Card lift, gradient glow, dan ikon scale-up pada interaksi
- **Code Card** — Tampilan bergaya terminal di hero section yang menampilkan data developer dalam format JavaScript object

---

## Struktur Halaman

```
┌─────────────────────────────────────────────┐
│  Header (sticky + backdrop blur)            │
│  Logo — Nav (Home, About, Projects,         │
│          Articles, LinkedIn) — Theme Toggle  │
├─────────────────────────────────────────────┤
│  Hero Section                               │
│  Perkenalan + Code Card (terminal style)    │
├─────────────────────────────────────────────┤
│  Projects Section (grid 3 kolom)            │
│  6 project card dengan tag teknologi        │
├──────────────────────┬──────────────────────┤
│  Articles (main)     │  Sidebar (aside)     │
│  3 artikel/jurnal    │  Foto profil         │
│                      │  Biodata             │
│                      │  Tech Stack tags     │
│                      │  Social links        │
├──────────────────────┴──────────────────────┤
│  Footer — Copyright + Social Links          │
└─────────────────────────────────────────────┘
```

---

## Projects yang Ditampilkan

| Project | Tech | Deskripsi |
|---|---|---|
| **Portfolio Website** | HTML, CSS, JS | Website ini sendiri |
| **Notes App + RESTful API** | JS, Web Components, REST API | Aplikasi pencatatan terintegrasi Dicoding Notes API |
| **My Personal Notes** | React, Vite | Manajemen catatan dengan pencarian, arsip, dan dark mode |
| **Expense Tracker** | Vanilla JS | Pelacak pemasukan dan pengeluaran |
| **Katalog Barang Lokal** | Flutter, Dart | Aplikasi CRUD katalog barang |
| **To-Do List Flutter** | Flutter, Dart | Manajemen tugas harian |

---

## Struktur File

```
├── index.html          # Halaman utama
├── style.css           # Stylesheet (design system + responsive)
├── assets/
│   └── profile.jpg     # Foto profil
├── Portofolio.MD       # PRD / checklist submission
└── README.md           # Dokumentasi ini
```

---

## Design System

Website menggunakan palet warna yang terinspirasi dari Vercel:

**Dark Mode (default)**
| Token | Warna | Kegunaan |
|---|---|---|
| `--bg-primary` | `#000000` | Background utama |
| `--bg-surface` | `#111111` | Surface / section |
| `--bg-elevated` | `#171717` | Elemen terangkat |
| `--border-default` | `#1e1e1e` | Border standar |
| `--text-primary` | `#ededed` | Teks utama |
| `--text-secondary` | `#a1a1a1` | Teks pendukung |
| `--accent` | `#0070f3` | Aksen (link, tag, highlight) |

**Light Mode**
| Token | Warna |
|---|---|
| `--bg-primary` | `#ffffff` |
| `--bg-surface` | `#f5f5f5` |
| `--text-primary` | `#171717` |
| `--accent` | `#0060d1` |

---
---

## Kriteria Submission Dicoding

Website ini memenuhi seluruh kriteria wajib submission Dasar Pemrograman Web:

- [x] Menggunakan elemen semantik HTML5 (`header`, `nav`, `main`, `article`, `aside`, `footer`)
- [x] Terdapat link ke profil Dicoding di navigasi
- [x] Sidebar menampilkan foto profil dengan atribut `alt`
- [x] Layout menggunakan Flexbox (tanpa `float`)
- [x] CSS terpisah di file `style.css`
- [x] Hanya satu `<h1>`, heading berurutan secara logis
- [x] Semua `<img>` memiliki atribut `alt`
- [x] Responsif dengan media query
- [x] Tanpa framework CSS (100% Vanilla CSS)

---

## Profil

**Faras Sulthan Pratama** — Fresh Graduate Informatika

-  [LinkedIn](https://www.linkedin.com/in/faras-sulthan/)
-  [GitHub](https://github.com/FarasSulthan)
-  [Dicoding](https://www.dicoding.com/users/farasha/academies)

---

© 2026 Faras Sulthan Pratama
