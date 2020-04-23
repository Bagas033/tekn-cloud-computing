#Pembahasan praktikum pertemuan 10
1.docker network  adalah perintah utama untuk mengkonfigurasi dan mengelola jaringan kontainer
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/1.png)
2.docker network ls yaitu perintah untuk melihat jaringan kontainer yang ada pada host Docker
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/2-1.png)
3.docker network inspect berupa nama jaringan atau ID jaringan untuk menunjukkan detail konfigurasi untuk jaringan yang disebut "jembatan". 
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/2-3.png)
4.docker info perintah menunjukkan banyak informasi menarik tentang instalasi Docker.
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/3-1.png)
5.menunjukkan bahwa jaringan jembatan dicakup secara lokal. Ini berarti bahwa jaringan hanya ada pada host Docker ini, berlaku untuk semua jaringan yang menggunakan driver sebagai jembatan - driver yang menyediakan jaringan host tunggal.
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/%232.1.png)
6.docker run -dt ubuntu sleep infinity untuk membuat wadah baru berdasarkan ubuntu:latest dan akan menjalankan sleepperintah untuk menjaga wadah berjalan di latar belakang.
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/%232.6.png)
7.brctl show menghubungkan jembatan docker0 ke wadah baru yang baru saja dibuat.
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-10/%232.4.png)
8. 