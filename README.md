<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width">
<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Inter, sans-serif;
    line-height: 1.6;
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem;
    background: #0a0c10;
    color: #e3e9f1;
  }
  .container {
    background: linear-gradient(145deg, #0e1217 0%, #080b0e 100%);
    border-radius: 32px;
    padding: 2.5rem;
    border: 1px solid rgba(255, 200, 120, 0.15);
    box-shadow: 0 20px 40px rgba(0,0,0,0.8);
  }
  h1 {
    text-align: center;
    color: #ffdcaa;
    font-weight: 400;
    letter-spacing: 2px;
    text-shadow: 0 0 10px rgba(255,200,100,0.3);
    border-bottom: 1px solid rgba(255,200,120,0.3);
    padding-bottom: 1rem;
  }
  h2 {
    color: #ffd699;
    font-weight: 350;
    border-left: 4px solid #ffb86b;
    padding-left: 1rem;
    margin-top: 2rem;
  }
  a {
    color: #ffb86b;
    text-decoration: none;
    border-bottom: 1px dotted #ffb86b;
  }
  a:hover {
    color: #ffe3b5;
    border-bottom: 1px solid #ffe3b5;
  }
  code {
    background: #1a1e24;
    color: #ffdcaa;
    padding: 0.2rem 0.5rem;
    border-radius: 8px;
    font-size: 0.9rem;
    border: 1px solid #2a2f36;
  }
  pre {
    background: #0b0e12;
    border: 1px solid #2a2f36;
    border-radius: 16px;
    padding: 1.2rem;
    overflow-x: auto;
  }
  pre code {
    background: transparent;
    border: none;
    padding: 0;
    color: #e3e9f1;
  }
  ul, ol {
    padding-left: 1.5rem;
  }
  li {
    margin: 0.5rem 0;
  }
  hr {
    border: none;
    border-top: 1px solid rgba(255,200,120,0.2);
    margin: 2rem 0;
  }
  .badge {
    display: inline-block;
    background: rgba(255,200,100,0.1);
    border: 1px solid rgba(255,200,100,0.3);
    padding: 0.25rem 1rem;
    border-radius: 40px;
    font-size: 0.85rem;
    color: #ffdcaa;
    margin-right: 0.5rem;
    margin-bottom: 0.5rem;
  }
  .footer {
    text-align: center;
    margin-top: 3rem;
    padding-top: 1.5rem;
    border-top: 1px solid rgba(255,200,120,0.2);
    color: #8896a8;
    font-size: 0.9rem;
  }
  .center {
    text-align: center;
  }
</style>
</head>
<body>
<div class="container">

<div class="center">
  <h1>ChronoDeck | v1.1.0</h1>
  <p style="font-size: 1.2rem; color: #cbd5e0;">3D interaktif · alarm adzan · musik lokal · bulan fotorealistik</p>
  
  <div style="margin: 1.5rem 0;">
    <span class="badge">Three.js</span>
    <span class="badge">Web Audio API</span>
    <span class="badge">Aladhan API</span>
    <span class="badge">Glassmorphism</span>
    <span class="badge">100% lokal</span>
  </div>
</div>

<hr>

<h2>Tentang Proyek</h2>
<p>
ChronoDeck adalah website 3D interaktif dengan visual bulan fotorealistik dan bintang berkedip alami, dilengkapi sistem alarm otomatis untuk waktu sholat. Dirancang sebagai teman ngoding, istirahat, dan ibadah — tanpa meninggalkan suasana tenang.
</p>
<p>
Dibangun dengan <strong>Three.js</strong>, <strong>Web Audio API</strong>, dan <strong>Aladhan Prayer API</strong>. 100% client-side, tanpa backend, tanpa pelacakan data.
</p>

<h2>Fitur Utama</h2>
<ul>
  <li>Bulan 3D + ribuan bintang dengan shader autentik</li>
  <li>OrbitControls — bebas memutar dan zoom</li>
  <li>Music player lokal — upload file audio sendiri</li>
  <li>Playlist berurutan dengan auto-next</li>
  <li>Nama lagu berjalan (marquee effect)</li>
  <li>Alarm otomatis 10 menit sebelum waktu adzan</li>
  <li>Adzan otomatis tepat waktu</li>
  <li>Notifikasi berkedip layar penuh saat alarm/adzan</li>
  <li>Volume otomatis maksimal saat alarm/adzan</li>
  <li>Waktu sholat realtime berdasarkan lokasi</li>
  <li>Countdown ke sholat berikutnya</li>
  <li>Refresh lokasi manual</li>
  <li>Desain glassmorphism</li>
  <li>Responsif untuk semua perangkat</li>
</ul>

<h2>emo</h2>
<p>
<a href="https://neveerlabs.github.io/ChronoDeck/">https://neverlabs.github.io/ChronoDeck/</a><br>
Atau jalankan secara lokal dengan membuka <code>index.html</code>.
</p>

<h2>Teknologi yang Digunakan</h2>
<ul>
  <li>HTML5</li>
  <li>CSS3 — backdrop-filter, glassmorphism, animasi</li>
  <li>JavaScript ES6 Modules</li>
  <li>Three.js — bulan, bintang, shader, orbit controls</li>
  <li>Web Audio API — kontrol musik dan playlist</li>
  <li>Aladhan Prayer API — jadwal sholat global</li>
  <li>Font Awesome 6 — ikon minimalis</li>
  <li>Geolocation API — deteksi lokasi otomatis</li>
</ul>

<h2>Cara Menggunakan</h2>
<ol>
  <li>Buka <code>index.html</code> di browser modern (Chrome, Edge, Firefox)</li>
  <li>Upload musik melalui tombol <code>upload</code></li>
  <li>Kontrol player: Play/Pause, Previous/Next</li>
  <li>Izinkan akses lokasi untuk jadwal sholat akurat</li>
  <li>Website otomatis:
    <ul>
      <li>Menentukan jadwal sholat hari ini</li>
      <li>Menghitung alarm 10 menit sebelum adzan</li>
      <li>Memunculkan notifikasi berkedip + suara alarm/adzan</li>
    </ul>
  </li>
  <li>Klik ikon lokasi untuk memperbarui koordinat</li>
</ol>
<p>
<strong>Semua file audio hanya diproses secara lokal di browser, tidak dikirim ke server manapun.</strong>
</p>

<h2>Struktur File</h2>
<pre><code>ChronoDeck/
│
├── index.html          # halaman utama
├── style.css           # UI glassmorphism dan animasi
├── script.js           # Three.js, prayer API, audio engine
│
├── sound/              # folder suara (isi manual)
│   ├── alarm.mp3       # suara 10 menit sebelum adzan
│   └── adzan.mp3       # suara adzan
└── favicon.png</code></pre>

<h2>Catatan Penting</h2>
<ul>
  <li>Browser membutuhkan interaksi pengguna pertama kali sebelum audio dapat diputar (kebijakan autoplay).</li>
  <li>Jika tidak memberikan izin lokasi, fallback ke koordinat Jakarta atau deteksi berbasis IP via ipapi.co.</li>
  <li>API Adzan menggunakan method 2 (ISNA) — dapat diubah di script.js.</li>
  <li>Folder <code>sound/</code> tidak disertakan dalam repository. Silakan masukkan file <code>alarm.mp3</code> dan <code>adzan.mp3</code> secara manual.</li>
  <li>Untuk pengalaman terbaik, gunakan headphone dan redupkan cahaya ruangan.</li>
</ul>

<h2>Rencana Pengembangan</h2>
<ul>
  <li>Progressive Web App — install ke home screen</li>
  <li>Tema lunar eclipse</li>
  <li>Efek hujan meteor</li>
  <li>Alarm kustom</li>
  <li>Visualizer bintang bereaksi ke musik</li>
  <li>Penyimpanan playlist via IndexedDB</li>
  <li>Widget jadwal sholat mingguan</li>
</ul>

<h2>Lisensi</h2>
<p>
MIT License<br>
Copyright (c) 2026 Neverlabs
</p>
<p>
Diizinkan untuk digunakan, dimodifikasi, dan didistribusikan secara bebas untuk keperluan pribadi maupun pembelajaran.
</p>

<div class="footer">
  <p>Dibuat dengan niat untuk teman ngoding dan siapa pun yang ingin tetap ingat waktu di tengah layar.</p>
  <p style="font-size: 1.1rem; color: #ffdcaa; margin-top: 1rem;">Neverlabs · 2026</p>
  <p style="font-style: italic; color: #a0b3c5;">Langit bukan batas, tapi pengingat.</p>
</div>

</div>
</body>
</html>
