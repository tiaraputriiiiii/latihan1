**Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

 - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
 ![Images](https://user-images.githubusercontent.com/115775237/195970717-c95c3898-db95-442c-aab5-f85adc7466f3.png)

- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.
 

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.** 
 
 
 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*
![image](https://user-images.githubusercontent.com/115775237/195970901-b5ff1bcb-5be0-43e3-97ff-bfac0a2bae84.png)

-  Setelah selesai mengisi user name dan user email anda klik daftar akun GitHub, lalu next select a plan dan pilih yang gratis


- Pada langka selanjutnya pilih sesuai keinginan anda atau boleh langsung diskip saja.

-  Kemudian  anda akan dialihkan Gmail untuk memverifikasi email, klik Verivy email address

### _Membuat repositori baru_

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

### _Membuat Reposiory Local_

- Lalu kita buka file explorer pilih dilocal disk e (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .

- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.name “nama_user”**
      **$ git config --global user.email “nama_user”**
      
_Nb : Ingat harus melaukukan konfigurasi terlebih dahulu apabila belum nanti akan mengalami kegagalan saat melakukan perintah git   commit. “nama_user” DIGANTI, diganti dengan akun user github anda_

- Buatlah direktori baru dengan menggunakan perintah *" mkdir latihan1"*  LALU *" cd latihan1 "*.

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_

- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_

##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git
   
 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.

##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah _“ls -1"_

-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya

#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**. 

#### **Selanjutnya klik write, jika sudah selesai klik saja commit change**
![image](https://user-images.githubusercontent.com/115775237/195971052-aa357d16-b3f4-4749-9d7d-131816fa03ff.png)

