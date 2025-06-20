LunaTune adalah sebuah prototipe website streaming musik yang terinspirasi dari Spotify, namun didesain dengan estetika melankolis yang unik dan modern, ditujukan khusus untuk kalangan Gen Z. Tujuannya adalah untuk menyediakan platform yang tidak hanya memutar musik, tetapi juga menciptakan suasana emosional yang mendalam namun tidak membosankan.

Berikut adalah rinciannya:

**1. Nama & Konsep:**

  * **Nama:** **LunaTune** (gabungan "Luna" yang berarti bulan, melambangkan ketenangan dan melankolis, serta "Tune" yang berarti nada/lagu).
  * **Konsep Desain:** Mengusung tema "melankolis namun tidak membosankan", yang diwujudkan melalui palet warna, tipografi, dan elemen visual yang dipilih dengan cermat.

**2. Desain Visual (UI/UX):**

  * **Palet Warna:**
      * **Primer:** Dominasi warna gelap seperti `Dark Navy (#1A2B3C)` untuk latar belakang utama, dan `Charcoal Gray (#2C3A4D)` untuk sidebar, bilah pemutar, dan kartu. Ini menciptakan kesan kedalaman dan ketenangan.
      * **Sekunder/Aksen:** Warna-warna lembut seperti `Deep Plum (#4A2C3F)`, `Dusty Rose (#B599AB)`, `Smoky Teal (#5D7B7A)`, dan `Soft Gold (#C5A070)`. Warna-warna ini digunakan untuk teks, ikon, highlight interaktif, dan memberikan sentuhan hangat serta elegan yang mencegah tampilan menjadi terlalu suram.
  * **Tipografi:** Menggunakan font 'Inter' (sans-serif) yang modern, bersih, dan mudah dibaca, memastikan informasi tersampaikan dengan jelas.
  * **Efek Visual:**
      * **Glassmorphism:** Banyak elemen UI (sidebar, bilah pemutar, kartu playlist) memiliki efek *glassmorphic* (buram transparan) yang memberikan kesan modern, mewah, dan kedalaman visual.
      * **Gradien Latar Belakang Beranimasi:** Latar belakang utama `body` memiliki gradien linear yang bergerak perlahan (`gradientShift` animation), membuat tampilan terasa lebih hidup dan dinamis tanpa mengganggu.
      * **Shadows dan Sudut Membulat:** Penggunaan bayangan lembut dan sudut yang membulat pada elemen-elemen seperti kartu album dan tombol, menambah kesan *soft* dan modern.
      * **Custom Scrollbar:** Scrollbar didesain ulang agar sesuai dengan estetika melankolis website.
  * **Responsivitas:** Desain menggunakan Tailwind CSS, memastikan tata letak website beradaptasi dengan baik di berbagai ukuran layar, dari desktop hingga perangkat seluler. Tersedia tombol untuk membuka/menutup sidebar di tampilan mobile.

**3. Fitur Utama & Fungsionalitas (Simulasi/Prototipe):**

  * **Pemutar Musik Interaktif:**
      * Dilengkapi dengan elemen `<audio>` HTML yang sebenarnya dapat memutar file MP3 (menggunakan URL dummy dari https://www.google.com/search?q=SoundHelix.com).
      * Menampilkan sampul album, judul lagu, dan nama artis dari lagu yang sedang diputar.
      * Tombol **Play/Pause**, **Next Song**, dan **Previous Song** berfungsi untuk mengontrol pemutaran audio.
      * **Progress Bar:** Bilah kemajuan lagu diperbarui secara real-time saat lagu diputar.
      * **Auto-play Next Song:** Lagu berikutnya akan otomatis diputar setelah lagu saat ini selesai.
      * **Visualizer Mini:** Indikator visualizer sederhana yang beranimasi di sebelah nama artis memberikan umpan balik visual bahwa musik sedang diputar.
  * **Tampilan Daftar Putar (Playlists):**
      * Bagian "Untuk Anda" menampilkan kartu-kartu daftar putar yang direkomendasikan.
      * Mengklik kartu daftar putar akan memuat daftar lagu dari playlist tersebut ke bagian "Daftar Putar Anda".
  * **Daftar Lagu (Song List):**
      * Menampilkan daftar lagu dari playlist yang sedang dipilih, lengkap dengan sampul album mini, judul lagu, artis, dan durasi.
      * Mengklik lagu di daftar akan langsung memuat dan memutar lagu tersebut di bilah pemutar.
  * **Fungsi Pencarian:**
      * Bilah pencarian di bagian atas memungkinkan pengguna mencari lagu atau daftar putar berdasarkan judul lagu, artis, atau nama/deskripsi daftar putar.
      * Hasil pencarian akan difilter dan ditampilkan di area playlist serta di bagian daftar lagu.
  * **Mood Mixer (Simulasi):**
      * Fitur inovatif ini mensimulasikan pembuatan playlist baru berdasarkan "mood" acak (Reflektif, Nostalgia, Menenangkan, dll.).
      * Ketika tombol ini diklik, sebuah playlist baru dengan beberapa lagu acak akan dibuat dan ditampilkan di bagian daftar lagu, memberikan ide tentang bagaimana fitur personalisasi AI bisa bekerja di masa depan.
  * **Kotak Pesan Kustom:** Menggantikan fungsi `alert()` bawaan browser untuk menampilkan notifikasi atau informasi kepada pengguna dengan gaya visual yang konsisten dengan desain website.
  * **Navigasi Sidebar:**
      * Menu di sidebar memungkinkan navigasi ke "Beranda", "Jelajahi", "Daftar Putar Anda", dan "Artis Favorit".
      * Tautan "Artis Favorit" dan "Pengaturan" adalah placeholder untuk fitur yang dapat dikembangkan di kemudian hari.

**4. Teknologi yang Digunakan:**

  * **HTML5:** Struktur dasar website.
  * **CSS3:** Untuk styling dan kustomisasi tampilan.
  * **Tailwind CSS:** Framework CSS yang digunakan untuk membangun UI dengan cepat dan responsif menggunakan kelas utility.
  * **JavaScript (Vanilla JS):** Untuk mengelola logika interaktif, seperti kontrol pemutar musik, pemuatan data dummy, fungsi pencarian, dan simulasi Mood Mixer.

Meskipun saat ini adalah versi prototipe dengan data dummy dan beberapa fitur simulasi, LunaTune sudah memiliki fondasi yang kuat dalam desain visual dan fungsionalitas inti untuk memberikan pengalaman streaming musik yang menarik dan emosional bagi Gen Z.
