IPB PLUS — DENISYA WEB v1

CARA ONLINE GRATIS (GITHUB PAGES)
1. Buat akun di https://github.com jika belum punya.
2. Klik + > New repository. Nama: ipb-plus-denisya. Pilih Public > Create repository.
3. Klik Add file > Upload files. Unggah index.html, manifest.webmanifest, sw.js, dan .nojekyll dari folder ini. Klik Commit changes.
4. Buka Settings > Pages. Pada Build and deployment: Source = Deploy from a branch, Branch = main, Folder = /(root), lalu Save.
5. Tunggu beberapa menit. Situs akan muncul di https://USERNAME.github.io/ipb-plus-denisya/ (ganti USERNAME dengan username GitHub milikmu).
6. Buka URL situs dan isi jadwal kuliah sebenarnya. Gunakan tombol Aktifkan / Tes Notifikasi di menu Jadwal & Pengingat.
7. Untuk backup buka Pengaturan & Backup > Unduh Backup. Untuk memindahkan data ke HP, kirim file backup secara privat lalu pulihkan dari menu yang sama.

BATASAN
- GitHub Pages gratis untuk repository publik. Jangan unggah data akademik pribadi atau file backup ke repository. Data default pada source code termasuk mata kuliah dan IPK. Jika tidak ingin data ini terlihat publik, gunakan hosting privat dengan kontrol akses atau hilangkan data pribadi dari source sebelum upload.
- Browser menyimpan data lokal per perangkat, belum sinkron antarperangkat.
- Notifikasi kelas dan tugas bekerja selama situs terbuka, browser memberi izin, dan perangkat aktif. Tidak ada push notification saat browser ditutup.
- Jadwal awal kosong karena pengguna belum memberikan hari dan jam sebenarnya.
- Integrasi IPB masih berupa tautan, bukan akses API otomatis.
- Tidak perlu Node.js atau bayar hosting.
