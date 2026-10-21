# 🔉 Sound Detector dengan DFPlayer

![Platform](https://img.shields.io/badge/Platform-Arduino-00979D?logo=arduino&logoColor=white) ![Module](https://img.shields.io/badge/Audio-DFPlayer_Mini-black) ![Bahasa](https://img.shields.io/badge/Bahasa-C%2B%2B-00599C?logo=cplusplus&logoColor=white)

Sistem **deteksi suara dengan output audio menggunakan modul DFPlayer Mini**. Proyek kelompok (Kelompok 6) mata kuliah berbasis mikrokontroler — alat mendeteksi kondisi suara lingkungan dan memutar respons audio sesuai logika program.

## ✨ Fitur

- Deteksi suara/kebisingan lingkungan secara real-time.
- Output audio melalui modul DFPlayer Mini (file audio dari microSD).
- Dua versi kode: `SourceCode.ino` (versi awal) dan `FINISHER_.ino` (versi final).

## 📁 Struktur

```
sound-detector-dfplayer/
├── firmware/
│   ├── SourceCode.ino     # Versi awal pengembangan
│   └── FINISHER_.ino      # Versi final
└── docs/
    ├── alat-bahan.jpg     # Foto komponen yang digunakan
    └── flowchart.jpg      # Diagram alur kerja sistem
```

## 🚀 Cara Menggunakan

1. Siapkan Arduino IDE dan library komunikasi serial untuk DFPlayer.
2. Buka `firmware/FINISHER_.ino` (versi final).
3. Isi microSD DFPlayer dengan file audio yang dibutuhkan.
4. Upload ke board sesuai rangkaian, lalu uji respons audionya.

## 📄 Dokumentasi

Lihat foto perakitan alat dan flowchart sistem pada folder [`docs/`](docs/).
