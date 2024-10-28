# Aplikasi Penghitung Umur

Aplikasi ini adalah program Java berbasis GUI yang memungkinkan pengguna untuk menghitung umur, mengetahui tanggal ulang tahun berikutnya, dan mendapatkan informasi tentang peristiwa penting yang terjadi pada tanggal lahir yang dipilih.

## Identitas
- Nama  : Muhammad Raihan
- NPM   : 2210010364
- Kelas : 5B NonReg Banjarmasin

## Fitur
- **Menghitung Umur**: Menghitung umur pengguna berdasarkan tanggal lahir yang dipilih.
- **Tanggal Ulang Tahun Berikutnya**: Menampilkan tanggal ulang tahun berikutnya berdasarkan tahun saat ini.
- **Peristiwa Penting**: Menarik dan menampilkan peristiwa penting dari Wikipedia yang terjadi pada tanggal yang dipilih.

## Cara Menggunakan
1. Klik pada komponen pemilih tanggal dan pilih tanggal lahir Anda.
2. Klik tombol "Hitung" untuk menghitung umur Anda dan melihat tanggal ulang tahun berikutnya.
3. Aplikasi akan menampilkan peristiwa penting yang terjadi pada tanggal tersebut di area teks.

## Teknologi yang Digunakan
- **Java**: Bahasa pemrograman untuk mengembangkan aplikasi.
- **Swing**: Framework GUI untuk membangun antarmuka pengguna.
- **API**: Wikipedia REST API untuk mendapatkan peristiwa penting
- **Library JSON**: org.json untuk memproses data JSON
- **Library JCalendar**: jcalendar-1.4.jar untuk menggunakan komponen jDateChooser

## Keunggulan
- **User-Friendly**: Antarmuka yang sederhana dan intuitif membuatnya mudah digunakan oleh siapa saja.
- **Informasi Real-Time**: Mengambil data langsung dari Wikipedia untuk memastikan informasi yang ditampilkan selalu terbaru.
- **Multi-Fungsi**: Tidak hanya menghitung umur tetapi juga memberikan konteks historis tentang tanggal lahir pengguna.

## Screenshot
![2](https://github.com/user-attachments/assets/0a0524d4-39bb-4b32-8366-0323e8731d37)
![2_](https://github.com/user-attachments/assets/a02f054b-0f52-45bd-b1f1-9a4b522bf505)

## Cara Menjalankan Program
1. Pastikan Anda memiliki **Java Development Kit (JDK)** terinstal di sistem Anda.
2. Clone repositori ini ke mesin lokal Anda.
   ```bash
   git clone https://github.com/username/repo-name.git
3. Tambahkan jcalendar-1.4.jar dari folder lib ke Libary Anda.
4. Jalankan aplikasi dengan mengkompilasi dan mengeksekusi file `NewJFrame.java`.
