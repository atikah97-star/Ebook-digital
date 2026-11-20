BUKU DIGITAL "PUPUK DARI SAMPAH MAKANAN" — PAKET OFFLINE
================================================

CARA MEMBUKA
- Ukuran halaman: A4 (210 x 297 mm). Tampilan dua halaman di laptop, satu halaman di ponsel.
- Tombol "PDF A4" di bawah buku mencetak/menyimpan seluruh isi sebagai PDF ukuran A4.
- Ekstrak zip, lalu buka index.html dengan browser (Chrome/Edge/Firefox, HP atau laptop).
- Tidak perlu internet. Semua teks, gambar (SVG), kuis, kalkulator, dan font sistem sudah ada di index.html.
- Progres baca, penanda, jawaban kuis, dan tulisan murid tersimpan di browser (localStorage).

STRUKTUR FOLDER
index.html
video/   <- taruh file video .mp4 di sini (nama harus sama persis)
img/     <- cadangan untuk foto tambahan (opsional)

VIDEO (2 video YouTube, perlu internet)
- Bab 1d: Bahaya Sampah Makanan            https://youtu.be/X2oMo3Q8Tek
- Bab 2c: Membuat Pupuk Kompos (Shorts)    https://youtube.com/shorts/CRg_uT-JUIA

Cara video tampil saat sampulnya diklik:
- Buku dibuka lewat http/https (di-hosting, server lokal, atau WebView aplikasi)
  -> video YouTube langsung diputar DI DALAM halaman buku.
- Buku dibuka langsung sebagai file (dobel-klik index.html, alamat file://)
  -> YouTube menolak pemutar tertanam untuk file lokal, jadi video otomatis
     diputar di jendela pemutar YouTube; halaman buku menampilkan "Video sedang diputar".
- Video sudah tersimpan di folder video/ sehingga diputar TANPA internet.
     video/bab1d-bahaya-sampah-makanan.mp4  dan  video/bab2c-kompos.mp4
  (hanya untuk video yang boleh Anda unduh/gunakan).

MENGUBAH KONTEN
- Teks materi: cari <section class="page" id="..."> di index.html.
- Soal evaluasi: array QZ di bagian <script>.
- Glosarium: array GL di bagian <script>.
- Menambah foto: <img src="img/nama.jpg"> di dalam section mana pun.

DIBUNGKUS JADI APK (opsional): folder ini bisa langsung dipakai di WebView Android,
Capacitor, atau Cordova sebagai asset lokal.
