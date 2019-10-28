# **Instalasi Git**
# Download Git, buka website resminya Git (git-scm.com).
# Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
# menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
# ![download git](https://user-images.githubusercontent.com/57026867/67633744-555f8280-f8e6-11e9-9b50-9fa68dc0786d.png)
# Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian
![git version](https://user-images.githubusercontent.com/57026867/67633769-ae2f1b00-f8e6-11e9-82b8-dd2cc56412f7.png)
# Menambahkan Global Config,Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
# user.name dan user.email
# konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
# apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
# kegagalan saat menjalankan perintah *git commit*
# Config Global Repository
![git config](https://user-images.githubusercontent.com/57026867/67633839-8db39080-f8e7-11e9-80dd-803bac2bcb7a.png)
Perintah Dasar Git
# Buka direktory aktif, misal: d:\latihan1picky (buka menggunakan Windows Explorer)
# klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
# sehingga muncul git bash commad ![git bash2](https://user-images.githubusercontent.com/57026867/67634069-14696d00-f8ea-11e9-9ef7-a35d5ef28ed9.png)
# Buat direktory project praktikum pertama dengan nama --latihan1picky--
# Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya
# masuk kedalam direktori tersebut dengan perintah cd (change
 directory)
# direktory aktif menjadi: d:\latihan1picky
![git cd mkdir](https://user-images.githubusercontent.com/57026867/67633983-4fb76c00-f8e9-11e9-8e07-c85aecb99bb5.png)
# Membuat Repository Local
# Jalankan perintah git init, untuk membuat repository local.
# Repository baru berhasil di inisialisasi, dengan terbentuknya satu
# direktori hidden dengan nama .git
![Screenshot git init](https://user-images.githubusercontent.com/57026867/67634089-4ed30a00-f8ea-11e9-9c9c-d954ce103a32.png)
# Pada direktori tersebut, semua perubahan pada working directoryakan disimpan. Menambahkan File baru pada repository
# Untuk membuat file dapat menggunakan text editor, lalu menyimpan
# filenya pada direktori aktif (repository)
# disini kita akan coba buat satu file bernama README.md (text file)
![GIT README](https://user-images.githubusercontent.com/57026867/67634152-ec2e3e00-f8ea-11e9-8855-86b9c7eeb978.png)
# File README.md berhasil dibuat.Menambahkan File baru pada repository
# Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
# File README.md berhasil ditambahkan.
![file add readme](https://user-images.githubusercontent.com/57026867/67634190-37485100-f8eb-11e9-80e8-7d2b1ec7a64d.png)
Commit (Menyimpan perubahan ke database)
# Untuk menyimpan perubahan yang ada kedalam database repository
# local, gunakan perintah git commit -m “komentar commit”
# Perubahan berhasil disimpan. $ git commit -m “File pertama"
![git commit1](https://user-images.githubusercontent.com/57026867/67634346-24368080-f8ed-11e9-87ef-1bb54c28afbf.png)
Membuat repository server
# Server reopsitory yang akan kita gunakan adalah http://github.com
# Anda harus membuat akun terlebih dahulu.Pada laman github, klik tombol start a project, atau
# Dari menu (icon +) klik New Repository
![github resipotry](https://user-images.githubusercontent.com/57026867/67634370-81323680-f8ed-11e9-9f15-ab195b997bc8.png)
Membuat repository server
# Isi nama repositorynya, misal: labpy1.
# lalu klik tombol Create repository ![git labpy1](https://user-images.githubusercontent.com/57026867/67634396-e5ed9100-f8ed-11e9-907f-4db08fb3598d.png)
# Menambahkan Remote Repository
# Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,
# sehingga dapat diakses oleh banyak user.
# Untuk menambahkan remote repository server, gunakan perintah git remote add origin https://github.com/adepicky12/labpy1.git
![git origin](https://user-images.githubusercontent.com/57026867/67634420-4977be80-f8ee-11e9-8dbc-b0289abbd82c.png)
*Push (Mengirim perubahan ke server)*
# Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
# Perintah ini akan meminta memasukkan username dan password pada akun github.com
![git push origin](https://user-images.githubusercontent.com/57026867/67634449-9cea0c80-f8ee-11e9-8266-d14094b16050.png)
# Melihat hasilnya pada server repository
# Buka laman github.com,arahkan pada repositorinya.
#Maka perubahan akan terlihat pada laman tersebut.![beranda git](https://user-images.githubusercontent.com/57026867/67646617-95178000-f961-11e9-85d8-648620a757b9.png)
Clone Repository
# Clone repository, pada dasarnya adalah meng-copy repository server
dan secara otomatis membuat satu direktory sesuai dengan nama
repositorynya (working directory).
# Untuk melakukan cloning, gunakan perintah git cloneh(url)
![git clone](https://user-images.githubusercontent.com/57026867/67646724-0b1be700-f962-11e9-9cb2-f2c7bd66f8a2.png)
