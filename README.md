# Portofolio: Alvino Aldorino

Website portofolio pribadi Alvino Aldorino, Full-Stack Developer spesialis Laravel, sistem web modular, dan REST API. Dibangun dengan Semantic HTML5, Tailwind CSS, dan Vanilla JavaScript siap tayang di GitHub Pages.

## Live Demo
Website dapat diakses secara publik di:
`https://alvinoaldorino.github.io/portofolio/` (setelah mengaktifkan GitHub Pages di settings repositori).

## Karakteristik & Tech Stack
- **HTML5 & Semantic Markup**: Struktur semantik dengan tag landmark, heading hierarchy yang rapi, dan atribut ARIA untuk aksesibilitas inklusif.
- **Tailwind CSS**: Desain responsif dengan dukungan tema ganda (Light Mode dan Dark Mode) yang dapat diganti secara interaktif.
- **Vanilla JavaScript**: Tanpa dependensi pihak ketiga yang membebani kinerja. Penanganan pergantian tema dengan penyimpanan status lokal (localStorage), laci navigasi seluler, modal pratinjau sertifikat dengan aksesibilitas keyboard (ESC), dan penyalinan email sekali klik.
- **Validasi Sertifikat & Prestasi**: Menampilkan dokumen asli dan foto sertifikat beresolusi tinggi untuk verifikasi kompetisi nasional (JHIC 2026, ITechno Cup 2026, Cisco Networking Academy, Dibimbing.id).

## Proyek Pilihan
- **[Aurea](https://github.com/alvinoaldorino/aurea)**: Aplikasi pelacak kebiasaan dan kesehatan mental berbasis gamifikasi dengan integrasi Livewire 3, Gemini AI, dan Midtrans.
- **[MyTurn](https://github.com/alvinoaldorino/Myturn)**: Sistem antrean digital layanan publik terencana berbasis REST API dan Docker (karya kompetisi ITechno Cup 2026 oleh Tim Gotei13).
- **[Weather Dashboard (Noir)](https://github.com/alvinoaldorino/Weather-Dashboard)**: Dashboard cuaca cepat berbasis Vanilla JS dengan integrasi Open-Meteo dan Nominatim geocoding.

## Struktur Berkas
```text
├── index.html        # Berkas utama portofolio
├── sertifikat/       # Foto dan dokumen PDF sertifikat resmi
│   ├── jhic-grand-finalist.png
│   ├── itechno-cup-2026.png
│   ├── jhic-quarter-finalist.png
│   ├── cisco-it-essentials.png
│   ├── it-essentials.png
│   ├── dibimbing-web-dev.png
│   └── *.pdf
├── prd.md            # Product Requirements Document
├── README.md         # Dokumentasi repositori
└── .gitignore        # Aturan pengabaian git
```

## Panduan Deploy ke GitHub Pages
1. Masuk ke halaman repositori di GitHub: `https://github.com/alvinoaldorino/portofolio`.
2. Klik tab **Settings** -> **Pages**.
3. Di bagian **Build and deployment > Source**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`.
5. Klik **Save**.
