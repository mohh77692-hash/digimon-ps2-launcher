# Build APK tanpa PC (GitHub Actions)

1. Buat akun atau masuk ke GitHub melalui browser HP.
2. Buat repository baru, misalnya `digimon-ps2-launcher` (boleh Public atau Private).
3. Upload seluruh isi folder project ZIP ini ke root repository. Pastikan folder `.github/workflows/` ikut ter-upload dan file `build-apk.yml` berada di dalamnya.
4. Buka tab **Actions** pada repository.
5. Pilih workflow **Build Android APK**, tekan **Run workflow**, lalu tekan tombol hijau **Run workflow**.
6. Tunggu sampai job selesai dengan tanda centang hijau.
7. Buka hasil run tersebut, cari bagian **Artifacts**, lalu unduh `DigimonPS2Launcher-debug-apk`.
8. Ekstrak ZIP artifact dan pasang `app-debug.apk` di HP.

APK ini adalah debug APK untuk instalasi/pengujian. Launcher bukan emulator PS2; emulator, BIOS, dan game tidak disertakan.
