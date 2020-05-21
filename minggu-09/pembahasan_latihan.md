Praktikum Minggu 9 (Docker for Beginners - Linux)
Login akun Docker

Untuk dapat mengakses terminal linux pada web ini yakni dengan login terlebih dahulu menggunakan akun Docker kita.

Task 0: Prerequisites
Meng-clone repo dari github dengan nama linux_tweet_app pada akun dockersamples.


Task 1: Run some simple Docker containers
Run a single task in an Alpine Linux container

Run an interactive Ubuntu container

Menjalankan Docker container dan mengakses terminal ubuntu

//Menampilkan daftar folder atau file yang ada
$ ls /

//Menampilkan proses container yang sedang berjalan
$ ps aux

//Menampilkan distro linux yang container yang digunakan
$ cat /etc/issue
Keluar dari terminal ubuntu

Task 2: Package and run a custom app using Docker
Build a simple website image

//Melihat isi dari Dockerfile
$ cat Dockerfile
Mengexport variabel dockerid dengan isian id docker

//Menampilkan isi dari variabel dockerid
$ echo $DOCKERID
Membuat docker image

Task 3: Modify a running website
Start our web app with a bind mount

Menjalankan container untuk menghosting image yang telah dibuat

Mengecek bahwasanya image berhasil di hosting dengan menekan link yang telah disediakan

Modify the running website

index.html container dan merefresh web sblmnya untuk melihat hasilnya

Push your images to Docker Hub

Melihat daftar image yang telah di hosting

Sebelumnya login menggunakan akun docker kita agar tepat dan lancar di push atau upload pada akun docker
