# Persona 3 Reload — Web Portfolio

> **Persona 3 Reload Pause Menu & Interactive Web Portfolio**  
> Developed by **Hazel Altian Athallah** (Informatics Engineering & System Development)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

## Tentang Proyek

Website portofolio interaktif yang mengadaptasi estetika antarmuka (*UI/UX*) game **Persona 3 Reload** buatan ATLUS. Seluruh elemen—mulai dari skema warna *Deep Sea Blue*, tipografi dinamis (*Rodin & Skip Std*), animasi transisi 60 FPS, efek suara autentik, hingga navigasi keyboard menyeluruh—dibuat dengan cermat menggunakan **Pure Vanilla Web Technologies** (HTML5, CSS3, & Vanilla JavaScript).

---

## Fitur Utama

- **Persona 3 Reload Authentic Aesthetic**: Desain visual, tipografi miring khas P3R, sudut dinamis, dan efek *vignette* atmosferik.
- **Zero-Latency Audio Engine**: Efek suara interaksi (SFX navigasi, konfirmasi, pembatalan menu) serta Background Music (*Color Your Night*) dengan kontrol volume dan mute instan.
- **⌨Kontrol Keyboard & Mouse Penuh**:
  - `↑ / ↓` atau `W / S`: Navigasi item menu.
  - `Enter` / `Space`: Membuka menu yang dipilih / detail kartu.
  - `ESC`: Kembali ke menu utama / menutup modal.
  - `M`: Toggle mute/unmute audio.
- **Section Portofolio**:
  - **PROJECT**: Showcase proyek pengembangan sistem (PrestaShop, UML System, SPK SAW, dll).
  - **SKILLS**: Analisis kompetensi teknis, database, dan pemrosesan data.
  - **ABOUT**: Profil pengembang, filosofi, dan riwayat akademis/organisasi.
  - **SYSTEM**: Pengaturan kontrol suara dan pintasan keyboard.
  - **CONTACT**: Saluran kontak langsung (Email, WhatsApp, Portfolio Flipbook).
- **Pure Vanilla Performance**: Tidak menggunakan framework berat (React/Vue/Angular), menghasilkan waktu muat instan dan performa animasi yang sangat ringan.

---

## ⌨Panduan Pintasan Tombol (Keyboard Controls)

| Tombol | Fungsi |
| :--- | :--- |
| `↑` / `↓` atau `W` / `S` | Navigasi atas / bawah pada menu & daftar |
| `Enter` atau `Space` | Memilih / membuka item menu / melihat detail modal |
| `ESC` | Kembali ke Menu Utama / Menutup modal & popup |
| `M` | Mute / Unmute musik latar (BGM) |

---

## Struktur Direktori

```text
Portofolio/
├── assets/             # Background video (.mp4), gambar profil, dan screenshot proyek
├── css/
│   └── style.css       # Styling autentik Persona 3 Reload & animasi CSS
├── fonts/              # Custom font typography (Rodin, Skip Std, NewRodin)
├── js/
│   └── main.js         # Engine interaksi, audio handler, keyboard navigation
├── sfx/                # Background audio (.mp3) dan SFX UI (.wav)
├── index.html          # Markup dokumen web utama
├── server.js           # Server lokal opsional berbasis Node.js
├── .gitignore          # Konfigurasi filter file Git
└── README.md           # Dokumentasi proyek
```

---

## Cara Menjalankan di Komputer Lokal

### Opsi 1: Menggunakan Node.js (Rekomendasi untuk streaming video/audio optimal)
1. Pastikan Anda telah menginstal [Node.js](https://nodejs.org/).
2. Buka terminal di folder proyek ini, lalu jalankan:
   ```bash
   node server.js
   ```
3. Buka browser dan akses: `http://localhost:3000`

### Opsi 2: Menggunakan Live Server (VS Code)
1. Buka folder ini di Visual Studio Code.
2. Pasang ekstensi **Live Server**.
3. Klik kanan pada `index.html` dan pilih **Open with Live Server**.

---

## Cara Deploy ke GitHub Pages (Gratis & Cepat)

Karena website ini berjenis statis, Anda dapat menampilkannya secara publik melalui **GitHub Pages**:

1. Buat repository baru di GitHub dengan status **Public**.
2. Jalankan perintah berikut di terminal:
   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "feat: initial commit Persona 3 Reload portfolio"
   git remote add origin https://github.com/ZelAthallah/portofolio-P3R.git
   git push -u origin main
   ```
3. Buka repository Anda di GitHub, lalu masuk ke tab **Settings** > **Pages**.
4. Pada bagian **Build and deployment** > **Branch**:
   - Pilih branch `main`
   - Pilih folder `/(root)`
   - Klik **Save**.
5. Tunggu sekitar 1-2 menit, website portofolio Anda sudah aktif di:  
   `https://zelathallah.github.io/portofolio-P3R/`

---

## Kontak

- **GitHub**: [github.com/ZelAthallah](https://github.com/ZelAthallah)
- **Email**: [Hazelathallah1@gmail.com](mailto:Hazelathallah1@gmail.com)
- **WhatsApp**: [+62 812-1804-1386](https://wa.me/6281218041386)
- **Flipbook Portfolio**: [heyzine.com/flip-book/145f00c3d1.html](https://heyzine.com/flip-book/145f00c3d1.html)

---

## Penafian (Disclaimer)

*Aset audiovisual, tema antarmuka, dan gaya desain terinspirasi oleh game **Persona 3 Reload**, hak cipta milik **ATLUS / SEGA**. Proyek ini dibuat untuk keperluan portofolio non-komersial dan demonstrasi kemampuan rekayasa web.*

