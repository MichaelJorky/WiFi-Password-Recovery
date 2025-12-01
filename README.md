# 🛡️ WiFi Password Recovery — Recover Saved WiFi Passwords on Windows

## 📌 Deskripsi

**WiFi Password Recovery** adalah aplikasi Windows ringan yang membantu pengguna menampilkan kembali **password WiFi yang pernah terhubung ke perangkat mereka**. Aplikasi ini sangat berguna ketika pengguna lupa kata sandi WiFi dan ingin mengaksesnya kembali tanpa harus mereset router atau meminta ulang kepada administrator jaringan.

Aplikasi ini **tidak melakukan hacking**, melainkan hanya membaca **profil WiFi yang sudah tersimpan** di sistem Windows, lalu menampilkannya secara jelas dan terstruktur melalui antarmuka grafis yang modern.

---

## ✨ Fitur Utama

* 🔍 **Scan otomatis semua profil WiFi** yang tersimpan di komputer.
* 🔐 Menampilkan **detail keamanan**, termasuk:

  * Jenis keamanan (WPA2, WPA3, Open Network)
  * Metode enkripsi (GCMP, CCMP, dll.)
  * Antarmuka jaringan yang digunakan.
* 🔑 **Menampilkan password WiFi** secara langsung (jika tersedia).
* 💾 **Simpan daftar WiFi dan password** ke file untuk backup.
* 🖥️ Antarmuka pengguna (UI) modern, gelap, dan mudah digunakan.
* ⚡ Proses cepat tanpa memerlukan konfigurasi tambahan.
* 📁 Kompatibel dengan Windows 10 dan Windows 11.

---

## 📸 Tampilan Aplikasi

*(Sisipkan gambar aplikasi seperti pada screenshot)*

---

## 🧩 Cara Kerja

Aplikasi membaca profil WiFi yang sudah disimpan oleh Windows melalui perintah `netsh wlan show profiles`. Jika password tersimpan, aplikasi menampilkannya. Jika tidak, ditandai sebagai *“Password not found”*.

Aplikasi **tidak menembus keamanan WiFi**, tidak melakukan brute force, dan tidak dapat melihat password WiFi yang belum pernah tersimpan di perangkat.

---

## 🚀 Cara Menggunakan

1. Jalankan aplikasi sebagai **Administrator** (disarankan).
2. Klik tombol **Scan** untuk memindai semua profil WiFi.
3. Pilih profil yang ingin dilihat.
4. Klik **Recover** untuk menampilkan password.
5. Opsional: simpan hasilnya menggunakan tombol **Save**.

---

## 🔒 Catatan Keamanan

* Aplikasi ini hanya menampilkan password WiFi yang **telah tersimpan** di komputer Anda sendiri.
* Jangan gunakan aplikasi ini untuk tujuan ilegal.
* Gunakan sesuai ketentuan hukum dan etika.

---

## 🛠️ Teknologi yang Digunakan

* Bahasa Pemrograman: **C# (.NET Framework / .NET 6)**
* UI Framework: **WinForms / WPF** (sesuaikan)
* Perintah sistem: **netsh**

---

## 📥 Download & Instalasi

*(Tambahkan link rilis GitHub jika ada)*

---

## 🤝 Kontribusi

Pull request selalu diterima! Jika ingin meningkatkan UI, fitur, atau dokumentasi, silakan kirim kontribusi Anda.

---

## 📄 Lisensi

Proyek ini dirilis di bawah lisensi **MIT License**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kembali selama mencantumkan atribusi yang sesuai.

---
