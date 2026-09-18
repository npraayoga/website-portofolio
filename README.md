3. Isi README.md dan Strategi Publikasi

README.md untuk proyek statis semacam ini idealnya berisi:

Judul dan deskripsi singkat — nama proyek dan satu-dua kalimat tentang tujuannya
Tech stack — ditegaskan bahwa ini vanilla HTML/CSS3/JavaScript tanpa framework atau build tool, supaya orang lain tahu tidak perlu npm install apa pun
Struktur file — daftar index.html, style.css, script.js dan peran masing-masing
Cara menjalankan secara lokal — cukup buka index.html langsung di browser, atau lewat live server sederhana untuk pengujian
Ringkasan design system — token warna/tipografi yang dipakai, biar konsisten kalau ada perubahan di kemudian hari
Status/roadmap — bagian yang masih placeholder (thumbnail proyek, link sosial) supaya jelas apa yang belum final
Lisensi/kepemilikan — opsional, tapi baik untuk kejelasan

Strategi publikasi — karena situs ini murni statis (tanpa backend, tanpa proses build), publikasinya tidak butuh server aplikasi, cukup hosting file statis:

GitHub Pages — push repo ke GitHub, aktifkan Pages dari branch tertentu; gratis, dan sekaligus jadi bukti workflow version control di laporan
Netlify/Vercel — hubungkan ke repo Git untuk auto-deploy tiap kali ada perubahan, atau drag-and-drop folder langsung; menyediakan HTTPS otomatis
Hosting/domain pribadi — upload ketiga file via FTP/cPanel ke folder public_html, cocok kalau sudah punya domain sendiri
