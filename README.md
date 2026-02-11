# ChronoDeck | v1.1.0

ChronoDeck adalah website 3D interaktif dengan visual bulan fotorealistik dan bintang berkedip alami, dilengkapi sistem alarm otomatis untuk waktu sholat. Dirancang sebagai teman ngoding, istirahat, dan ibadah.

Dibangun dengan Three.js, Web Audio API, dan Aladhan Prayer API. 100% client-side, tanpa backend, tanpa pelacakan data.

---

## Fitur Utama

- Bulan 3D + ribuan bintang dengan shader autentik
- OrbitControls - bebas memutar dan zoom
- Music player lokal - upload file audio sendiri
- Playlist berurutan dengan auto-next
- Nama lagu berjalan (marquee effect)
- Alarm otomatis 10 menit sebelum waktu adzan
- Adzan otomatis tepat waktu
- Notifikasi berkedip layar penuh saat alarm/adzan
- Volume otomatis maksimal saat alarm/adzan
- Waktu sholat realtime berdasarkan lokasi
- Countdown ke sholat berikutnya
- Refresh lokasi manual
- Desain glassmorphism
- Responsif untuk semua perangkat

---

## Demo

Akses demo di: https://neveerlabs.github.io/ChronoDeck/

Atau jalankan secara lokal dengan membuka index.html.

---

## Teknologi yang Digunakan

- HTML5
- CSS3 - backdrop-filter, glassmorphism, animasi
- JavaScript ES6 Modules
- Three.js - bulan, bintang, shader, orbit controls
- Web Audio API - kontrol musik dan playlist
- Aladhan Prayer API - jadwal sholat global
- Font Awesome 6 - ikon minimalis
- Geolocation API - deteksi lokasi otomatis

---

## Cara Menggunakan

1. Buka index.html di browser modern (Chrome, Edge, Firefox)
2. Upload musik melalui tombol upload
3. Kontrol player:
   - Play / Pause
   - Previous / Next
4. Izinkan akses lokasi untuk jadwal sholat akurat
5. Website otomatis:
   - Menentukan jadwal sholat hari ini
   - Menghitung alarm 10 menit sebelum adzan
   - Memunculkan notifikasi berkedip + suara alarm/adzan
6. Klik ikon lokasi untuk memperbarui koordinat

Semua file audio hanya diproses secara lokal di browser, tidak dikirim ke server manapun.

---

## Struktur File

project/
│
├── index.html # halaman utama
├── style.css # UI glassmorphism dan animasi
├── script.js # Three.js, prayer API, audio engine
│
├── sound/ # folder suara (isi manual)
│ ├── alarm.mp3 # suara alarm sebelum adzan
│ └── adzan.mp3 # suara adzan
└── favicon.png

---

## Catatan Penting

- Browser membutuhkan interaksi pengguna pertama kali sebelum audio dapat diputar (kebijakan autoplay).
- Jika tidak memberikan izin lokasi, fallback ke koordinat Jakarta atau deteksi berbasis IP via ipapi.co.
- API Adzan menggunakan method 2 (ISNA) - dapat diubah di script.js.
- Folder sound/ tidak disertakan dalam repository. Silakan masukkan file alarm.mp3 dan adzan.mp3 secara manual.
- Untuk pengalaman terbaik, gunakan headphone dan redupkan cahaya ruangan.

---

## Rencana Pengembangan

- Progressive Web App - install ke home screen
- Tema lunar eclipse
- Efek hujan meteor
- Alarm kustom
- Visualizer bintang bereaksi ke musik
- Penyimpanan playlist via IndexedDB
- Widget jadwal sholat mingguan

---

## Lisensi

MIT License

Copyright (c) 2026 Neverlabs

Diizinkan untuk digunakan, dimodifikasi, dan didistribusikan secara bebas untuk keperluan pribadi maupun pembelajaran.

---

Dibuat dengan niat untuk teman ngoding dan siapa pun yang ingin tetap ingat waktu di tengah layar.

Neverlabs · 2026

sesibuk sibuknya manusia, jangan pernah lupakan ibadah!
See you...
