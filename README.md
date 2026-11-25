# psas-mtk — Simulasi Ujian PSAS Ganjil Kelas 12 Matematika

Website simulasi ujian PSAS Ganjil Kelas 12 Matematika.

- 100 soal di bank (4 varian untuk tiap dari 25 indikator PSAS)
- Dua mode latihan: Simulasi (25 soal dipilih acak, 1 per indikator, porsi tetap: Peluang 6, Pencacahan 4, Lingkaran 7, Statistika 8; timer 90 menit, 4 poin/soal) dan Latihan Semua Soal (100 soal, timer 360 menit, 1 poin/soal); skor maksimal tetap 100 di kedua mode
- Pilihan ganda, isian faktorial (No. 9 dan variannya), MCMA pilih 3 jawaban benar (No. 13 dan variannya)
- Timer, navigasi nomor soal, tanda ragu-ragu
- Skor total (maks 100), skor per blok, dan pembahasan tiap soal
- Pembahasan Materi: panduan rumus & strategi lengkap (Bab 1 Peluang & Pencacahan, Bab 2 Lingkaran, Bab 3 Statistika, plus 3 contoh hitung cepat), bisa dibuka dari beranda dan dari halaman hasil
- Tema: putih bersih, indigo (#4338CA) + teal (#0D9488), font Space Grotesk / Inter / JetBrains Mono, sudut tajam

## Menjalankan lokal

Buka `index.html` di browser, atau jalankan server statis apa pun dari folder ini.

## Deploy di Vercel

Situs ini statis, tanpa build step. Di Vercel, buat project dari repository ini
dengan framework preset "Other" dan tanpa build command — `index.html` di root
akan disajikan sebagai halaman utama.
