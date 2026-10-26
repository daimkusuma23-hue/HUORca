# OrcaDash

Launcher sederhana untuk head unit Android (Android 5+), isinya dashboard web
(jam, jadwal sholat Depok, notifikasi adzan, musik) plus tombol Aplikasi untuk membuka aplikasi lain.

## Cara mendapat APK tanpa Android Studio
1. Buat repo baru di github.com, upload seluruh isi folder ini (termasuk folder .github).
2. Buka tab Actions, pilih Build APK, klik Run workflow.
3. Setelah selesai (sekitar 3-5 menit), unduh artifact OrcaDash-debug-apk, ekstrak, lalu salin app-debug.apk ke flashdisk.
4. Di head unit, pasang APK dari file manager (izinkan install dari sumber tidak dikenal).

## Dengan Android Studio
Buka folder ini, tunggu sync, lalu Build > Build APK(s).

Dashboard ada di app/src/main/assets/index.html, bisa diedit langsung.
