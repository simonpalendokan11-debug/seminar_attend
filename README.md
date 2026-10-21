# SeminarAttend

## Deskripsi Aplikasi

SeminarAttend adalah aplikasi mobile berbasis Flutter yang dikembangkan untuk mendukung proses pengelolaan informasi seminar dan kehadiran peserta. Proyek ini menggunakan Firebase sebagai teknologi backend yang direncanakan untuk mendukung layanan aplikasi.

Saat ini, pengembangan berfokus pada fondasi aplikasi, tampilan awal, navigasi dasar, dan konfigurasi Firebase.

## Tujuan

- Menyediakan aplikasi mobile untuk mendukung kegiatan seminar.
- Memudahkan pengguna melihat informasi acara seminar.
- Mengembangkan sistem kehadiran peserta menggunakan QR Code sesuai rencana proyek.
- Menyiapkan fondasi aplikasi yang dapat dikembangkan lebih lanjut.

## Fitur dan Progres

### Fitur yang sudah tersedia
- Halaman Login.
- Halaman Beranda dengan contoh daftar acara seminar.
- Navigasi dasar menuju menu Acara, Riwayat, dan Profil.
- Inisialisasi Firebase pada aplikasi Flutter.

### Fitur yang masih dalam pengembangan
- Login dan registrasi menggunakan Firebase Authentication.
- Penyimpanan dan pengelolaan data menggunakan Cloud Firestore.
- Validasi kehadiran menggunakan QR Code.
- Pengelolaan acara dan pemantauan kehadiran oleh admin.

## Teknologi yang Digunakan

- **Flutter** — pengembangan aplikasi mobile.
- **Dart** — bahasa pemrograman aplikasi.
- **Firebase Core** — inisialisasi Firebase.
- **Firebase** — backend yang disiapkan untuk pengembangan aplikasi.
- **Git dan GitHub** — pengelolaan versi dan penyimpanan kode sumber.
- **Android Studio** — lingkungan pengembangan dan emulator Android.

## Anggota dan Pembagian Peran

| Inisial | Peran | Tanggung Jawab |
|---|---|---|
| SM | Project Manager & Flutter Developer | Koordinasi proyek dan pengembangan aplikasi Flutter |
| NS | UI/UX Designer & Analis Kebutuhan | Analisis kebutuhan dan perancangan antarmuka |
| ARP | Quality Assurance (QA) | Perencanaan pengujian, pemeriksaan aplikasi, dan dokumentasi hasil pengujian |

## Cara Menjalankan Aplikasi

### Persyaratan
- Flutter SDK telah terpasang.
- Android Studio dan Android SDK telah dikonfigurasi, atau tersedia perangkat Android.
- Git telah terpasang.

### Langkah menjalankan
1. Clone repository:
   ```bash
   git clone https://github.com/simonpalendokan11-debug/seminar_attend.git
   ```
2. Masuk ke folder proyek:
   ```bash
   cd seminar_attend
   ```
3. Unduh dependensi:
   ```bash
   flutter pub get
   ```
4. Pastikan emulator atau perangkat Android terhubung.
5. Jalankan aplikasi:
   ```bash
   flutter run
   ```

Pastikan konfigurasi Firebase yang diperlukan tersedia pada proyek sebelum menjalankan aplikasi.

## Kendala dan Rencana Berikutnya

Kendala yang ditemukan selama pengembangan antara lain keterbatasan ruang penyimpanan pada drive sistem dan peringatan kompatibilitas Kotlin Gradle Plugin.

Rencana pengembangan berikutnya:
- Memastikan kode terbaru tersimpan di repository.
- Menyempurnakan README dan dokumentasi proyek.
- Mengimplementasikan Firebase Authentication dan Cloud Firestore.
- Mengembangkan fitur QR Code untuk validasi kehadiran.
- Melakukan pengujian awal, mencatat bug, dan mendokumentasikan hasil pengujian.

## Repository

https://github.com/simonpalendokan11-debug/seminar_attend
