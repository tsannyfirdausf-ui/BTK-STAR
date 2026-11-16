BTK STAR — DEMO ANDROID
======================

ISI DEMO
- Login/daftar lokal di perangkat
- Bonus pertama 10.000.000 koin demo
- Beranda dan daftar room contoh
- Halaman room dengan 12 kursi simulasi
- Gift virtual yang mengurangi saldo demo
- Profil, dompet, dan riwayat transaksi
- Penyimpanan akun/saldo melalui localStorage browser
- PWA: dapat ditambahkan ke layar utama saat dibuka melalui hosting HTTPS

BATASAN PENTING
Ini adalah DEMO satu perangkat. Tidak ada server, akun lintas perangkat, chat antar pengguna,
audio/mikrofon real-time, top up, atau transaksi uang sungguhan. Kata sandi demo disimpan
lokal dan tidak boleh digunakan sebagai kata sandi akun penting. Bonus koin hanya simulasi.

MENJALANKAN DEMO
1. Ekstrak ZIP.
2. Cara cepat: buka folder www dan jalankan index.html di browser modern.
3. Untuk fitur PWA/offline, host folder www di HTTPS, lalu buka alamatnya di Chrome Android
   dan pilih menu browser > Tambahkan ke layar utama / Install app.

MEMBUNGKUS MENJADI APK DENGAN CAPACITOR
Persyaratan: Node.js LTS, Android Studio, Android SDK, dan JDK yang kompatibel.
Dari folder proyek:
  npm install
  npx cap add android
  npx cap sync android
  npx cap open android
Di Android Studio pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
APK debug biasanya tersedia di android/app/build/outputs/apk/debug/app-debug.apk.

Catatan: APK belum dikompilasi dalam paket ini karena lingkungan pembuatan saat ini tidak
memiliki Android SDK maupun Gradle. Nama aplikasi dan applicationId demo: BTK STAR / id.btkstar.demo.
