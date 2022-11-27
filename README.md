# Lab8Web
### Praktikum 8: PHP dan Database MySQL
### Apa itu Database?
kumpulan data terstruktur yang saling berelasi. Kumpulan data, yang terorganisir secara logika,
dikelola menggunakan metode tertentu yang menjamin konsistensi data.
### Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.
![gambar1](screenshoot/ss1.png)
### Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka
melalui browser: http://localhost/phpmyadmin/
![gambar2](screenshoot/ss2.png)
### Membuat Database: Studi Kasus Data Barang
Membuat database dengan nama latihan1
![gambar3](screenshoot/ss3.png)
### Membuat Table data_barang
Lalu buatlah table dengan nama data_barang lalu klik buat
![gambar4](screenshoot/ss4.png)
### Mengisi tabel pada data barang
Lalu isilah table pada data barang sesusai dengan intuksi praktikum lalu klik simpan
![gambar5](screenshoot/ss5.png)
### Menambahkan data
Lalu tambahkan data sesuai dengan data yang ada di praktikum, dengan cara masuk ke menu SQL lalu klik kolom insert dan masukan data yang akan di tambahkan lalu klik kirim
![gambar6](screenshoot/ss6.png)
### Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)
Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/
![gambar7](screenshoot/ss7.png)
### Membuat file koneksi database
Buat file baru dengan nama koneksi.php.
Lalu masukan kode seperti berikut ini:
Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan
koneksi berhasil, uncomment pada perintah echo "koneksi berhasil";
![gambar8](screenshoot/ss8.png)
### Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php
Lalu masukan kode seperti berikut ini:
![gambar9](screenshoot/ss9.png)
dan ini hasilnya :
![gambar10](screenshoot/ss10.png)
### Menambah Data (Create)
Buat file baru dengan nama tambah.php
lalu masukan kode seperti berikut:
![gambar](screenshoot/ss11.png)
dan ini form penambahan nya :
![gambar12](screenshoot/ss12.png)
dan ini hasilnya :
![gambar13](screenshoot/ss13.png)
### Mengubah Data (Update)
Buat file baru dengan nama ubah.php
lalu masukan kode seperti berikut :
![gambar14](screenshoot/ss14.png)
dan ini form ubah nya :
![gambar15](screenshoot/ss15.png)
### Menghapus Data (Delete)
Buat file baru dengan nama hapus.php
lalu masukan kode seperti berikut ini :
![gambar16](screenshoot/ss16.png)
dan hasilnya seperti ini, barang iphone telah di hapus :
![gambar17](screenshoot/ss17.png)
### Masukan Style untuk table nya
Jangan lupa buat koding style pada css untuk menambahkan variasi pada table nya dengan memasukan kode berikut :
![gambar18](screenshoot/ss18.png)


