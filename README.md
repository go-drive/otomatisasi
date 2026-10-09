# Robot Otomasi Digital AI

Aplikasi otomatisasi cerdas berbasis teknologi AI yang dirancang untuk mempermudah dan mempercepat pengelolaan produk digital di berbagai platform yang didukung.

Melalui eksekusi file `Robot.exe`, sistem menjalankan tugas-tugas rutin secara otomatis, cepat, dan presisi tanpa perlu proses manual.

## 🚀 Fungsi Utama Aplikasi

Daftar modul otomatisasi yang tersedia berdasarkan platform layanan yang didukung:

### DigiFlazz (Buyer)
1. **Perbaiki Produk Gangguan**  
   Mencari dan mengganti *seller/supplier* pada produk yang mengalami gangguan dengan alternatif cadangan yang lebih stabil.
2. **Tambah Produk Baru**  
   Melakukan pemindaian (*scanning*) pada zona atau kategori tertentu untuk menambahkan daftar produk baru secara otomatis.
3. **Perbaiki Produk Spesifik**  
   Menjalankan proses perbaikan khusus pada produk target berdasarkan daftar yang Anda tentukan.
4. **Perbaiki Kode Produk**  
   Menyelaraskan dan merapikan penamaan kode produk secara massal.
5. **Perbaiki Status Produk**  
   Mengecek dan memperbarui status produk (dari OFF menjadi ON) secara otomatis setelah gangguan selesai.
5. **Pengaturan Robot**
   Konfigurasi parameter kerja robot dapat disesuaikan langsung melalui menu **Pengaturan Robot** di terminal:
   - Mengubah batas maksimal produk yang diproses.
   - Menentukan daftar *seller/supplier* prioritas.
   - Menentukan daftar *seller/supplier* yang dihindari.
   - Menambah atau menghapus target nama produk spesifik.

### Prodeskel (Profil Desa & Kelurahan)
1. **Tambah Data**  
   Mengambil data penduduk dari Google Spreadsheet lalu mengisi formulir DDK Kontinyu di situs Prodeskel secara otomatis — mulai dari pencarian KK, pengisian data Anggota Keluarga (AK), hingga penyimpanan. Dilengkapi sistem *checkpoint* agar bisa dilanjutkan jika terhenti.
2. **Hapus Data**  
   Membaca daftar Kode Keluarga dari tab *Penghapusan* di Spreadsheet, lalu mencari dan menghapus data KK tersebut satu per satu dari sistem Prodeskel secara otomatis.
3. **Salin Spreadsheet Master (Setup)**  
   Membuka tautan *template* Spreadsheet resmi yang sudah dilengkapi *Apps Script* bawaan. Pengguna cukup menyalin (*Make a Copy*), menjalankan otorisasi satu kali, dan Spreadsheet siap digunakan sebagai sumber data robot.

   > **Catatan Otorisasi:** Saat menjalankan Apps Script untuk pertama kali, Google akan menampilkan peringatan *"Google belum memverifikasi aplikasi ini"*. Ini adalah hal yang **normal dan aman** — script tersebut hanya menjembatani koneksi antar-file di dalam Akun Google Anda sendiri. Klik *Lanjutan (Advanced)* → *Buka Program Prodeskel (tidak aman)* → *Izinkan (Allow)*.

<!-- Tambahkan platform baru di bawah ini sesuai ketersediaan layanan -->

## ⚙️ Cara Penggunaan

1. Jalankan file **`Robot.exe`**.
2. Ketik angka pada menu terminal untuk memilih platform layanan dan tugas yang ingin dijalankan.
3. Robot akan bekerja secara otomatis hingga proses selesai.

## 🤖 Teknologi AI & Kontribusi

Proyek ini memanfaatkan teknologi AI untuk mengoptimalkan otomatisasi tugas dan alur navigasi sistem. Seiring dengan terus bertambahnya dukungan integrasi platform layanan di masa depan, **bantuan kontribusi dari pengguna dan pengembang sangat dibutuhkan**.

Jika Anda menggunakan proyek ini dan ingin membantu pengembangannya (seperti menambahkan modul layanan baru, perbaikan bug, atau optimalisasi logika AI), Anda sangat diundang untuk berkontribusi melalui *pull request* atau menyampaikan ide di bagian *issues*.
