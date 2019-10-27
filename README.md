Instalasi Git
# Download Git, buka website resminya Git (git-scm.com).
# Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
menggunakan 64bit, unduh yang 64bit. Begitu juga kalau
menggunakan 32bit.
# ![download git](https://user-images.githubusercontent.com/57026867/67633744-555f8280-f8e6-11e9-9b50-9fa68dc0786d.png)
# Selamat, Git sudah terinstal di Windows. Untuk mencobanya,
silahkan buka CMD atau PowerShell, kemudian
![git version](https://user-images.githubusercontent.com/57026867/67633769-ae2f1b00-f8e6-11e9-82b8-dd2cc56412f7.png)
# Menambahkan Global Config
# Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email
# konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.
# apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah *git commit*
# Config Global Repository
![git config](https://user-images.githubusercontent.com/57026867/67633839-8db39080-f8e7-11e9-80dd-803bac2bcb7a.png)
Perintah Dasar Git
# Buka direktory aktif, misal: d:\latihan1picky (buka
menggunakan Windows Explorer)
# klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
# sehingga muncul git bash commad ![git bash2](https://user-images.githubusercontent.com/57026867/67634069-14696d00-f8ea-11e9-9ef7-a35d5ef28ed9.png)
![git bash](https://user-images.githubusercontent.com/57026867/67634008-7fff0a80-f8e9-11e9-9194-7d05e714e5cd.png)
# Buat direktory project praktikum pertama dengan nama latihan1picky
# Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya
# masuk kedalam direktori tersebut dengan perintah cd (change
 directory)
# direktory aktif menjadi: d:\latihan1picky
![git cd mkdir](https://user-images.githubusercontent.com/57026867/67633983-4fb76c00-f8e9-11e9-8e07-c85aecb99bb5.png)
Membuat Reposiory Local
# Jalankan perintah git init, untuk membuat repository local.
# Repository baru berhasil di inisialisasi, dengan terbentuknya satu
# direktori hidden dengan nama .git
# Pada direktori tersebut, semua perubahan pada working directory
  akan disimpan.![Screenshot git init](https://user-images.githubusercontent.com/57026867/67634089-4ed30a00-f8ea-11e9-9c9c-d954ce103a32.png)
