BTK STAR - BUILD APK DARI HP ANDROID SAJA

Isi paket:
- BTK-STAR-DEMO-PROJECT.zip: proyek demo yang sudah kamu miliki
- .github/workflows/build-apk.yml: instruksi otomatis untuk membangun APK di GitHub Actions

LANGKAH:
1. Di Chrome Android buka https://github.com dan masuk/daftar akun.
2. Buat repository baru bernama btk-star-demo. Pilih Public agar GitHub Actions tersedia tanpa pengaturan tambahan; jangan unggah data rahasia.
3. Pada repository, pilih Add file > Upload files. Unggah BTK-STAR-DEMO-PROJECT.zip dari paket ini, lalu Commit changes.
4. Buat file workflow: Add file > Create new file. Pada nama file ketik persis .github/workflows/build-apk.yml
5. Salin seluruh isi file build-apk.yml dari paket ini ke editor GitHub, lalu Commit changes.
6. Buka tab Actions > Build BTK STAR APK > Run workflow > Run workflow.
7. Tunggu sampai job selesai dengan tanda centang hijau.
8. Buka hasil run tersebut, gulir ke Artifacts, unduh BTK-STAR-debug-APK.zip.
9. Buka ZIP hasil unduhan, ekstrak app-debug.apk, lalu ketuk APK untuk memasang. Jika diminta, izinkan Chrome/File Manager memasang aplikasi tidak dikenal.

CATATAN:
- Ini menghasilkan APK debug untuk demo, bukan APK rilis Play Store.
- Demo masih lokal di satu perangkat. Login, koin, dan room adalah simulasi; belum ada voice real-time atau chat antar pengguna.
- Jangan masukkan password, token, atau data pribadi ke repository publik.
