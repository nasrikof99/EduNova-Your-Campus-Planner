# EduNova: Your Campus Planner (Full Version)

Projek lengkap aplikasi Android **EduNova: Your Campus Planner** yang sedia untuk dijana menjadi fail pemasangan `.apk` dan `.aab` (Google Play Store) secara automatik melalui GitHub Actions.

## Cara Jana APK & AAB Secara Automatik di GitHub
1. Ekstrak semua fail dalam ZIP ini ke dalam satu folder.
2. Buat *repository* baru di **GitHub** (contoh: `edunova-campus-planner`).
3. Muat naik semua fail termasuk folder tersembunyi `.github/workflows/build-apk.yml`.
4. Klik tab **Actions** > pilih **Build EduNova Full Version (APK & AAB)** > klik **Run workflow**.
5. Apabila selesai (tanda hijau ✓), muat turun dua pakej dari bahagian **Artifacts**:
   - **`EduNova-FullVersion-APK`**: Mengandungi `EduNova-FullVersion-Signed.apk` untuk dipasang terus ke dalam telefon Android.
   - **`EduNova-GooglePlay-AAB`**: Mengandungi `EduNova-PlayStore.aab` dan fail kunci `edunova-release.keystore` (kata laluan: `edunova123`) untuk muat naik ke **Google Play Console**.
