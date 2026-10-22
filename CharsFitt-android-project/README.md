# Chars FITT - project Android

## Cara A: tanpa install apa-apa (GitHub Actions)
1. Buat repo baru di github.com, upload SEMUA isi folder ini (termasuk folder .github).
2. Buka tab Actions, tunggu "Build APK" selesai (hijau), kira-kira 3-5 menit.
3. Klik run-nya, scroll ke Artifacts, download "Chars-FITT-apk" (zip), ekstrak, dapat app-debug.apk.
4. Pindahkan app-debug.apk ke HP lewat kabel, buka, izinkan "install dari sumber tidak dikenal".

## Cara B: Android Studio
1. Install Android Studio, File > Open > pilih folder ini, tunggu Gradle sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s).
3. Hasil: app/build/outputs/apk/debug/app-debug.apk
