# Pembahasan Praktikum pertemuan 14

dimulai dari ;

Menjalankan perintah ls.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/1.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/1.1.png)

Inisialisasi cluster.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/2.png)

Terlihat bahwasanya cluster telah berhasil di inisialisasi.
Menjalankan perintah kubectl apply -n kube-system -f
"https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 |tr -d '\n')".

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/3.png)

Mengcloning repository dockercoins.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/4.png)

Berpindah ke direktori hasil repo yang telah berhasil di clone dan menjalankan perintah docker-compose up.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/5.png)

Menjalankan perintah kubectl get node.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/6.png)

Terlihat bahwasanya terdapat 1 buah node yang siap digunakan.
Menjalankan perintah kubectl get nodes -o wide.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/7.png)

Terlihat bahwasanya terdapat 1 buah node yang siap digunakan.
Menjalankan perintah kubectl get no -o yaml.

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/8.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/9.png)

Terlihat bahwasanya menampilkan informasi yang lebih detail.
Menjalankan perintah kubectl get nodes -o json | jq ".items[] | {name:.metadata.name} + .status.capacity".

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/10.png)

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/11.png)

Terlihat bahwasanya menampilkan informasi node dengan format JSON.
Menjalankan perintah kubectl get services. 

![hasil](https://github.com/Bagas033/tekn-cloud-computing/blob/master/minggu-14/12.png)

Terlihat bahwasanya menampilkan service kubernetes yang sedang berjalan.