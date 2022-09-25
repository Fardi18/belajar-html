# Writing and Presentation Week 1

## Unix Command Line <hr>

- ### Command Line Interface (CLI)

  Command Line Interface (CLI) adalah sebuah program dimana user bisa mengetikkan perintah dalam bentuk teks dan memberikan instruksi pada komputer untuk mengerjakan tugas tertentu. Singkatnya CLI adalah jenis shell yang berbasis teks

- ### Shell

  Shell adalah program yang digunakan untuk berkomunikasi dengan sistem operasi. Perintah-perintah CLI akan dibaca dan diterjemahkan oleh Shell agar sistem operasi mengerti dan menginstruksikan sistem operasi untuk menjalankan task sesuai permintaan. Dengan kata lain, shell merupakan user interface yang mengelola CLI dan berperan sebagai perantara yang menghubungkan user dan sistem operasi.

- ### Terminal Emulator

  Terminal emulator adalah software yang digunakan untuk mengakses CLI.

- ### File System

  File System adalah adalah bagaimana data diatur di dalam sebuah sistem. Sistem operasi Windows & mirip Unix menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree (pohon)
  ![file system](/file-system.png)

  > relative path name untuk file harry-potter.mov dari current working directory adalah ./film/harry-potter.mov

- ### Command (Perintah) pada CLI

  - pwd (Print Working Directory)
    Command untuk melihat current working directory
  - cd (Change Directory)
    Command untuk berpindah direktori.
  - ls (List)
    Command untuk melihat isi file yang ada di sebuah direktori
  - mkdir (Make Directory)
    Command untuk membuat suatu directory
  - touch
    Command untuk membuat suatu file
  - cat
    Command untuk melihat isi suatu file
  - head
    Command untuk melihat beberapa baris pertama dari sebuah file teks
  - tail
    Command untuk melihat beberapa baris terkahir dari sebuah file teks
  - cp (copy)
    Command untuk menyalin sebuah file
  - mv (move)
    Command untuk memindahkan file/directory dan untuk rename file
  - rm (remove)
    Command untuk menghapus file/directory

## Git dan GitHub <hr>

- ### Git

  Git adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file. Git biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif. File -file yg disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah dan apa perubahann yang dilakukan.

- ### GItHub

  GitHub adalah sebuah website dan layanan berbasis cloud bagi para developer untuk menyimpan dan mengelola kode, serta mendokumentasikan dan mengontrol perubahannya.

- ### Pentingnya menggunakan Git dan GitHub

  Sebagai seorang programmer, kita tidak akan pernah bisa bekerja sendirian selamanya. Dengan menggunakan GIT dan Github, kita bisa bekerja dalam sebuah tim. Tujuan besarnya adalah kita bisa berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate.
  Kita juga tidak perlu menunggu rekan dalam satu tim menyelesaikan suatu program dahulu untuk berkolaborasi. Kita bisa membuat file didalam projek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.

- ### Command (Perintah) pada Git dan GitHub

  - **git --version** untuk melihat versi dari git dan mengetahui apakah git telah terinstal
    ![git --version](git%20--version.png)

  - **git config** untuk mengkonfigurasi user dan emailnya
    ![git config](git%20config.png)
    > pastikan email sama dengan email pada akun GitHub
  - **git config --list** untuk melihat apakah konfigurasi berhasil atau tidak

    ![git config --list](git%20config%20--list.png)

    > terdapat user dengan nama dan email yang sama dengan yang dimasukkan ke pada command git config di atas.

  - **git init** digunakan untuk membuat reposiroty baru
    ![git init](git%20init.png)

  - **git status** digunakan untuk menampilkan untracked files
    ![git status](git%20status.png)

  - **git add** digunakan untuk menambahkan mengubah untracked files menjadi modified
    ![git add](/git%20add.png)

    > Setelah dilakukan git add, maka untracked files sebelumnya berubah menjadi siap untuk di-commit

  - **git commit** digunakan untuk commit
    ![git commit](git%20commit.png)
  - **git log** digunakan untuk menampilkan daftar commits yang ada di branch beserta detail-nya
    ![git log](git%20log.png)
  - **git remote** digunakan untuk menghubungkan ke remote repository
