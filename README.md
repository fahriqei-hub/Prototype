# MIT App Inventor - Sistem Akademik Unla & Web View Fabric

## MIT App Inventor
Aplikasi mobile berbasis Android sederhana yang dibangun menggunakan **MIT App Inventor**. Proyek ini dibuat untuk memenuhi **Tugas Pertemuan 1** dengan tujuan mempermudah akses cepat pengguna ke portal website [Kampus / Berita Teknologi] langsung dari perangkat seluler tanpa perlu membuka browser secara manual, dilengkapi dengan kontrol navigasi dasar.

## Web View Fabric
Aplikasi mobile berbasis Android berperforma tinggi yang dibangun menggunakan **React Native New Architecture (Fabric)** dan mengintegrasikan paket **`react-native-webview`**. Proyek ini mendemonstrasikan bagaimana memuat halaman web eksternal secara langsung di dalam aplikasi seluler dengan rendering yang sinkron, cepat, dan responsif.

---

## Fitur Utama MIT App Inventor

* **Auto-Load Portal Web:** Otomatis memuat halaman utama website tujuan (`https://siakad.unla.ac.id/gate/login`) segera setelah aplikasi dibuka.
* **Navigasi Cepat (Home & Refresh):** Dilengkapi tombol interaktif untuk kembali ke halaman beranda (*Home*) dan memuat ulang halaman (*Refresh*) apabila terjadi kendala koneksi.
* **Antarmuka Ringan & Responsif:** Menggunakan komponen *WebViewer* bawaan sehingga aplikasi memiliki ukuran file yang kecil, ringan dijalankan, dan tampilan yang menyesuaikan layar smartphone Android.

## Fitur Utama Web View Fabric

* **React Native New Architecture (Fabric):** Memanfaatkan sistem rendering baru berbasis Fabric untuk performa UI yang lebih halus dan responsif.
* **Embedded WebView:** Merender halaman web eksternal (`https://siakad.unla.ac.id/gate/login` atau portal kampus) secara *seamless* di dalam aplikasi.
* **Optimasi Interaksi Web:** Dilengkapi dengan dukungan JavaScript aktif (`javaScriptEnabled={true}`) dan indikator status muat (`startInLoadingState={true}`).
* **Antarmuka Kustom:** Desain header aplikasi yang bersih menggunakan `SafeAreaView`, `StatusBar`, dan styling fleksibel khas komponen native.
* 
---

## Teknologi yang Digunakan dalam MIT App Inventor

* **Platform & Visual Programming:** MIT App Inventor (Block-based Coding)
* **Komponen Utama:** `WebViewer`, `Button`, `HorizontalArrangement`
* **Version Control & Kolaborasi:** Git & GitHub
* **Target Sistem Operasi:** Android (`.apk`)

## Teknologi yang Digunakan dalam Web View Fabric

* **Framework:** React Native (New Architecture / Fabric Enabled)
* **Library Utama:** `react-native-webview`
* **Bahasa Pemrograman:** JavaScript / JSX
* **Environment & Tools:** Node.js, Android Studio Emulator, Gradle
* 
---

## Cara Instalasi & Menjalankan MIT App Inventor

Karena proyek ini dikembangkan menggunakan *visual programming* berbasis cloud (MIT App Inventor), terdapat dua cara untuk menjalankan atau memodifikasi proyek ini:

### Instalasi Langsung di Perangkat Android (Menggunakan APK)
1. Unduh file **`fahri.apk`** yang tersedia di bagian *Releases* atau folder `/apk` pada repositori ini.
2. Pindahkan file `.apk` tersebut ke perangkat smartphone Android kamu.
3. Buka file tersebut dan izinkan instalasi dari sumber tidak dikenal (*Install from Unknown Sources*) jika diminta oleh sistem.
4. Setelah terpasang, buka aplikasi dan pastikan perangkat terhubung ke internet.

## 🚀 Cara Instalasi & Menjalankan

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di komputer lokal:

1. Instalasi Dependensi (npm install)
2. Konfigurasi Fabric (newArchEnabled=true)
3. Jalankan Aplikasi ke Emulator (npx react-native run-android)

## Dokumentasi MIT App Inventor
<img width="352" height="676" alt="Screenshot 2026-11-07 155128" src="https://github.com/user-attachments/assets/cfcd3c8b-0de9-44b1-9ca6-79502bf339b5" />
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/40986e24-ac9b-4b71-8e19-07aa6ad9e954" />

## Dokumentasi Web View Fabric
<img width="387" height="891" alt="image" src="https://github.com/user-attachments/assets/653b408a-a208-4276-86f7-ba217d5dec1e" />
