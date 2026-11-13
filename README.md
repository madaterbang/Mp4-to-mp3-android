# MP4 to MP3 — Android Studio project

Aplikasi Android native sederhana untuk mengambil audio dari video dan menyimpannya sebagai MP3.

## Fitur
- Memilih video melalui Android Storage Access Framework (tanpa izin penyimpanan luas).
- Ekstraksi audio ke MP3 menggunakan FFmpeg + LAME.
- Pilihan bitrate 128, 192, atau 320 kbps.
- Pengguna memilih sendiri lokasi dan nama file MP3 melalui dialog simpan Android.
- Konversi berjalan di thread latar belakang.

## Cara membuka
1. Ekstrak ZIP ini.
2. Buka folder `MP4_to_MP3_Android` melalui Android Studio.
3. Tunggu Gradle Sync dan unduh dependensi saat diminta.
4. Hubungkan HP Android dengan USB debugging aktif atau gunakan emulator.
5. Tekan Run.

## Persyaratan
- Android Studio versi terbaru yang mendukung Android Gradle Plugin 8.7.3.
- JDK 17.
- Android SDK 35.
- Minimum Android 7.0 (API 24).
- Dependensi `dev.ffmpegkit-maintained:ffmpeg-kit-audio:8.1.7` dari Maven Central.

## Catatan
- Paket `ffmpeg-kit-audio` menyediakan encoder MP3 LAME dan merupakan build LGPL.
- Proyek ini adalah source code Android Studio, bukan APK yang sudah ditandatangani/siap dipasang.
- Pengujian build dan instalasi perlu dilakukan di Android Studio dengan koneksi internet untuk mengambil dependensi Gradle.
