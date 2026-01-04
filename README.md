# 🌍 Sistem Informasi Geografis (GIS)

![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![GeoJSON](https://img.shields.io/badge/Data-GeoJSON-orange?style=for-the-badge&logo=json)

Repositori ini berisi kumpulan kode sumber (source code) untuk proyek **Sistem Informasi Geografis (GIS)** berbasis web. Proyek ini dibuat untuk memvisualisasikan data spasial ke dalam peta interaktif.

## 👤 Identitas Pembuat
* **Nama:** Abdullah Azzam
* **GitHub:** [@Zaammm16](https://github.com/Zaammm16)
* **Status:** Mahasiswa Teknik Informatika (UNSULBAR)

## 📖 Deskripsi Proyek
Aplikasi ini bertujuan untuk menampilkan informasi geografis pada peta digital. Fitur utamanya meliputi:
* Menampilkan **Peta Dasar (Basemap)** (OpenStreetMap / Google Maps / Satellite).
* Memvisualisasikan **Data Spasial** (Titik Lokasi, Garis Jalan, atau Area Wilayah) menggunakan format GeoJSON.
* Fitur **Pop-up Informasi** saat objek pada peta diklik.
* (Opsional) Analisis spasial sederhana atau pemetaan tematik.

## 🛠️ Teknologi yang Digunakan
Proyek ini dibangun menggunakan teknologi web standar:
* **Bahasa:** HTML, CSS, JavaScript (atau PHP).
* **Library Peta:** [Leaflet.js](https://leafletjs.com/) (Library open-source untuk peta interaktif).
* **Data:** Format GeoJSON.
* **Styling:** CSS Framework (Bootstrap / Tailwind) atau Native CSS.

## 📂 Struktur File
Berikut adalah gambaran umum struktur folder dalam repositori ini:

```bash
GIS/
├── assets/           # Gambar, ikon marker, atau file CSS/JS tambahan
├── data/             # File data spasial (.geojson / .json)
├── index.html        # File utama antarmuka peta
├── map.js            # Logika script untuk memuat peta & layer
└── README.md         # Dokumentasi proyek
