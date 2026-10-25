PrinceRyy - APK offline (Capacitor)

Isi folder:
  www/index.html                 -> aplikasi web (ini yang dibungkus jadi APK)
  package.json, capacitor.config.json
  .github/workflows/build-apk.yml -> otomatis membangun APK di GitHub

Cara pakai (tanpa Android Studio):
  1. Buat repo baru di GitHub (mis. princeryy-apk), upload SEMUA isi folder ini
     (termasuk folder .github).
  2. Buka tab Actions -> "Build APK" -> Run workflow (atau otomatis jalan saat upload).
  3. Tunggu +-5-10 menit sampai centang hijau, buka run-nya, lalu unduh
     "PrinceRyy-apk" di bagian Artifacts. Ekstrak zip-nya -> app-debug.apk.
  4. Kirim ke HP, buka, izinkan "install dari sumber tidak dikenal", lalu install.

Mengganti isi aplikasi: ganti www/index.html lalu commit -> APK baru dibangun lagi.
