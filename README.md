Flappy Bird Ultimate Edition
Game Flappy Bird versi "ultimate" yang dibuat dengan HTML, CSS, dan JavaScript murni (tanpa framework, tanpa library tambahan). Lengkap dengan pilihan karakter, tingkat kesulitan, jenis rintangan, koleksi bintang bonus, medali, leaderboard, dan background langit yang berubah otomatis mengikuti skor.

Flappy Bird game built with pure HTML, CSS & JavaScript — multiple characters, difficulty levels, obstacle skins, star collectibles, medals, a top-10 leaderboard, and dynamic day-night backgrounds.

Fitur
4 karakter pilihan: Butterfly, Monkey, Owl, dan Bird
3 tingkat kesulitan: Easy (3 nyawa), Medium (2 nyawa), Hard (1 nyawa) — kecepatan pipa, lebar celah, dan gravitasi berbeda di tiap level
3 jenis rintangan: Pipa Putih, Moai Batu (dengan wajah dan retakan batu), dan Lilin Api (dengan efek nyala api dan tetesan lilin)
Bintang bonus: muncul di celah pipa dengan peluang 30%, bernilai +5 poin
Sistem nyawa: tabrakan tidak langsung game over — pemain mendapat masa kebal sekitar 2 detik setelah kena
Medali: Emas (skor 50+), Perak (30+), Perunggu (10+)
Leaderboard: 10 skor terbaik tersimpan di localStorage beserta karakter dan kesulitan yang dipakai
Background dinamis: pagi (skor < 10), siang (< 25), sore (< 40), malam (40 ke atas) dengan animasi awan
Responsif: mendukung desktop dan mobile (viewport dinamis, tanpa pull-to-refresh)
Cara Bermain
Pilih tingkat kesulitan, karakter, dan jenis rintangan di menu awal
Tekan Spasi, klik mouse, atau ketuk layar untuk membuat karakter lompat
Lewati pipa sebanyak mungkin — setiap pipa yang berhasil dilewati bernilai 1 poin
Kumpulkan bintang di antara pipa untuk bonus +5 poin
Hindari pipa, tanah, dan batas atas layar; nyawa habis berarti game over
Cara Menjalankan
Buka file gameflappy.html langsung di browser (double-click), atau jalankan lewat local server:

bash
python -m http.server 8000
# lalu buka http://localhost:8000/gameflappy.html
Teknologi
HTML5 Canvas untuk seluruh rendering game (karakter, pipa, bintang, tanah, bunga)
CSS3: gradient background, animasi awan, glassmorphism pada menu, media query responsif
JavaScript: game loop requestAnimationFrame, deteksi tabrakan (body + cap pipa), localStorage untuk skor dan leaderboard
Struktur File
text
gameflappy.html   # seluruh game (HTML + CSS + JS dalam satu file)
Ide Pengembangan Berikutnya
Efek suara saat lompat, kumpul bintang, dan tabrakan
Tombol pengatur waktu (pagi/siang/sore/malam) manual
Skor online lintas perangkat (misalnya dengan Firebase)
Karakter tambahan dengan kemampuan unik
