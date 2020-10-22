# LatihanVCS2

Repository ini dibuat untuk memenuhi tugas Pertemuan 4-Bahasa Pemrograman

**Nama : Rafi Ubaidillah**

**NIM : 312010090**

**KELAS : TI.20.A.1**

## Langkah-Langkah Penggunaan Git

* Langkah pertama Download Git,buka website resminya git : [click here](https://git-scm.com)

![git scm](poto/GitScm.png) <br>

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini : *Git Installation Guide* 

![GitScm](poto/gitscmm.png) <br>

* Setelah installasi selesai, buka software GitBash pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut :  <br>

`git --version` <br>

![GitVersion](poto/gitversion.png) <br>

* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan syntax berikut :  <br>

`git config --global user.name "masukan nama anda`"
`git config --global user.email "masukan email anda`"

![gitname](poto/gitname.png) <br>

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>

`git config --global user.name`
`git config --global user.email` <br>

![gitneme](poto/gitneme.png) <br>

* Buat akun di GitHub,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar. <br>

* Jika akun GitHub sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: Penjelasan <br>



    `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)` <br>

    `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)` <br>

    `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)` <br>

    ` Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda` <br>

    `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.` <br>

    `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan` <br>

![repisotory](poto/repisotory.png.png) <br>

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy. <br>

![linkcode3](poto/linkcode3.png.png) <br>


* Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut : <br>

`git clone [URL] pada contohnya, saya akan memasukan git clone` <br>

https://github.com/Rafi09/LatihanVCS2 <br>

![gitsatu](poto/gitsatu.png) <br>


* Saat ini kita sudah masuk kedalam folder LatihanVCS, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor (Sublime Text, Notepad, Notepad++, Visual Studio Code). Edit sesuai dengan keinginan. Aturan file .md (Markdown) bisa dilihat di Link berikut ini : click here <br>

![gittwo](poto/gittwo.png) <br>


*  Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara CTRL+S atau File -> Save <br>

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini : <br>

`git add.` <br>

![gittree](poto/gittree.png) <br>


* Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan commit. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :

`git commit "Update README.md"`

![gitfor](gitfor.png) <br>













