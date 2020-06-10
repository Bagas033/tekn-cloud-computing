# Pembahasan Praktikum pertemuan 14

dimulai dari ;

1. Menjalankan perintah ls pada terminal, kemudian  membuat peninisialisaian pada alamat yang sesuai dengan host name, seperti dibawah ini

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/1.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/1.1.png)

2. Inisialisasi cluster.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/2.png)

    dari hasil diatas dapat terlihat bahwasanya cluster telah berhasil di inisialisasi, dengan di buktikan ada kalimat "initialized successfully".

3. Menjalankan perintah kubectl apply -n kube-system -f
    "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 |tr -d '\n')". hasil output dibawah ini;

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/3.png)

    apabila diatas telah berhasil berarti Cluster telah berhasil diatur.

4. Mengcloning repository dockercoins.
    ini dapat dilakukan pada repositori apa saja yang mingkin telah dibuat pada praktikum sebelumnya. 

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/4.png)

5. berpindah atau masuk direktori yang dibuat
    Dilhal ini dilakukan untuk berpindah ke direktori hasil repo yang telah berhasil di clone dan menjalankan perintah docker-compose up, 

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/5.png)

6. Menjalankan perintah kubectl get node.
    
![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/6.png)

   Dari hasil diatas dapat dilihat dan dipastikan bahwa terdapat 1 (satu) node yang dapat digunakan.

7. Menjalankan perintah kubectl get nodes -o wide.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/7.png)

     Dari hasil diatas dapat dilihat dan dipastikan bahwa terdapat 1 (satu) nodes yang dapat digunakan dari.

8. Menjalankan perintah kubectl get no -o yaml.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/8.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/9.png)

  Diatas menampilkan detai dari informasi yang mungkin di perlikan untuk pengembangan informasi. contoh disitu terdapat apiVersion, kindnode, operatingsystem, dan osimage.  

9. Menjalankan perintah kubectl get nodes -o json | jq ".items[] | {name:.metadata.name} + .status.capacity".

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/10.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/11.png)

    Diatas menampilkaninformasi dari  semua node yang memiliki aliran objek yang menggunkan format JSON

10. Menjalankan perintah kubectl get services. 

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/12.png)

    Diatas untuk menampilkan service kubernetes yang sedang berjalan, atau layanan dari kubectl untuk 