
# Latihan TCC Minggu-06
A. Membuat program Go untuk koneksi dan membaca data dari MySQL
Sebelum melakukan pembuatan program kita diwajibkan untuk menginstall Mysql Community Edition, compiler Go, dan Mysql driver untuk Go.

Setelah proses instalasi selesai kita langsung membuat sebuah database yang akan digunakan untuk melakukan koneksi, dan pembacaan data menggunakann Go.


Lalu membuat program menggunakan bahasa Go untuk melakukan koneksi, dan membaca data yang sudah dibuat sebelumnya di database mysql. Program Go Mysql


B. Membuat program Go untuk koneksi dan membaca data dari MongoDB
Sebelum melakukan pembuatan program kita diwajibkan untuk menginstall MongoDB (atau gunakan versi cloudnya MongoDB atlas), compiler Go, dan Mongo driver untuk Go.

Setelah proses instalasi selesai kita langsung membuat sebuah database yang akan digunakan untuk melakukan koneksi, dan pembacaan data menggunakann Go.

Karena saya menggunakan MongoDB Atlas maka harus membuat akun untuk bisa membuat cluster sendiri

Lalu mendapatkan URI string dari MongoDB Atlas agar dapat mengakses cluster dan databasenya. Jika tidak menggunakan MongoDB Atlas cukup isi URI string dengan port localhost, dan nama databasenya.

Setelah mendapatkan URI string kita sudah bisa melakukan proses coding dengan Go untuk melakukan koneksi, dan membaca data dari database yang ada di MongoDB. Program Go MongoDB

Untuk output yang disorot warna hijau output yang dikeluarkan jika sukses melakukan koneksi, dan output yang disorot warna kuning adalah isi collection yang ada di database.

