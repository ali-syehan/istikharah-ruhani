# Istikharah Ruhani - Android WebView APK

Project ini membungkus file HTML menjadi aplikasi Android memakai WebView native.

## Cara build di GitHub

1. Upload semua isi folder ini ke root repository GitHub.
2. Buka tab **Actions**.
3. Pilih **Build Android APK**.
4. Klik **Run workflow**.
5. Setelah selesai, download artifact **Istikharah-Ruhani-debug-apk**.
6. File APK berada di dalam artifact sebagai `app-debug.apk`.

## Struktur penting

- `app/src/main/assets/index.html` = aplikasi HTML asli.
- `app/src/main/java/com/alisyehan/istikharah/MainActivity.java` = pembungkus WebView.
- `.github/workflows/build-apk.yml` = workflow GitHub Actions.
