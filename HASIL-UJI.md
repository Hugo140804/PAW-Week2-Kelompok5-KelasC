# Hasil pemeriksaan

## Sudah diperiksa
- Kedua file HTML memiliki deklarasi bahasa, charset, dan viewport.
- Homepage menghubungkan style.css melalui link eksternal.
- Landing page menghubungkan landing-page.css melalui link eksternal; aturan CSS sama dengan versi tertanam sebelumnya.
- CSS memuat :root, reset, hero, grid, serta media query pada 1000px dan 700px.
- Sebanyak 23 tautan internal/referensi file diperiksa: semua file dan target anchor tersedia.
- Konten penelitian serta kelima nama dan NIM pada landing page dipertahankan.
- Homepage tidak bergantung pada font, gambar, atau script dari CDN.

## Belum selesai: uji visual browser
Browser pengujian tidak tersedia dan unduhan browser gagal, sehingga tidak ada klaim bahwa uji desktop/mobile telah lulus. Media query sudah diimplementasikan, tetapi perlu diverifikasi secara visual.

Sebelum pengumpulan:
1. Buka index.html di Chrome/Edge, lalu tekan F12 dan aktifkan device toolbar (Ctrl+Shift+M).
2. Uji kedua halaman pada 1440 × 900, 768 × 1024, 390 × 844, dan 320 × 740.
3. Pastikan tidak ada scroll horizontal, teks bertumpuk, atau konten terpotong.
4. Pada homepage, pastikan card tersusun empat kolom di desktop, dua di tablet, satu di mobile. Hero menjadi satu kolom di bawah 700px.
5. Klik seluruh navigasi, tombol ulasan, tautan card, tautan anggota, dan tautan kembali ke homepage.
6. Uji tombol Tab untuk melihat fokus keyboard dan uji zoom 200% untuk keterbacaan.
7. Link sumber paper eksternal memerlukan internet dan belum diuji akses langsung dalam pengerjaan ini.

Jika dosen meminta dua landing page berbeda, tambahkan landing page kedua yang belum diberikan. Paket saat ini memenuhi minimum dua halaman: homepage dan satu landing page.
