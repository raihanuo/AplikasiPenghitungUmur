# Aplikasi Penghitung Umur

Aplikasi ini adalah program berbasis GUI yang memungkinkan pengguna untuk menghitung umur, mengetahui tanggal ulang tahun berikutnya, dan mendapatkan informasi tentang peristiwa penting yang terjadi pada tanggal lahir yang dipilih.

## Identitas
- Nama  : Muhammad Raihan
- NPM   : 2210010364
- Kelas : 5B NonReg Banjarmasin

## Fitur Program
- **Menghitung Umur**: Menghitung umur pengguna berdasarkan tanggal lahir yang dipilih.
- **Tanggal Ulang Tahun Berikutnya**: Menampilkan tanggal ulang tahun berikutnya berdasarkan tahun saat ini.
- **Peristiwa Penting**: Menarik dan menampilkan peristiwa penting dari Wikipedia yang terjadi pada tanggal yang dipilih.
- **Antarmuka Pengguna Grafis (GUI)**: Memudahkan pengguna dalam berinteraksi dengan aplikasi.

## Cara Menggunakan Program
1. **Jalankan Aplikasi**: Eksekusi program dengan menjalankan file `NewJFrame.java`.
2. **Pilih Tanggal Lahir**: Klik pada komponen pemilih tanggal dan pilih tanggal lahir Anda.
3. **Hitung Umur**: Klik tombol "Hitung" untuk menghitung umur Anda dan melihat tanggal ulang tahun berikutnya.
4. **Lihat Peristiwa Penting**: Aplikasi akan menampilkan peristiwa penting yang terjadi pada tanggal tersebut di area teks.

## Teknologi yang Digunakan
- **Bahasa Pemrograman**: Java
- **Framework GUI**: Swing
- **API**: Wikipedia REST API untuk menarik peristiwa penting
- **Library JSON**: org.json untuk memproses data JSON

## Keunggulan Program
- **User-Friendly**: Antarmuka yang sederhana dan intuitif membuatnya mudah digunakan oleh siapa saja.
- **Informasi Real-Time**: Mengambil data langsung dari Wikipedia untuk memastikan informasi yang ditampilkan selalu terbaru.
- **Multi-Fungsi**: Tidak hanya menghitung umur tetapi juga memberikan konteks historis tentang tanggal lahir pengguna.

## Cara Menjalankan Program
1. **Prasyarat**: Pastikan Anda memiliki Java Development Kit (JDK) terinstal di sistem Anda.
2. **Kompilasi Program**: Buka terminal/command prompt, navigasi ke direktori tempat file `NewJFrame.java` disimpan, dan jalankan perintah berikut:
   ```bash
   javac NewJFrame.java
