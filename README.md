**Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

 - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
 ![Images](https://user-images.githubusercontent.com/115775237/195970717-c95c3898-db95-442c-aab5-f85adc7466f3.png) Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.
![Screenshot](https://user-images.githubusercontent.com/115775237/195986680-c60d81ff-cf4d-43fa-aabe-84a8b9ebe06b.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah *git --version.*  Saya memakai versi 2.38.0.windows.1
![2022-10-15 (29)](https://user-images.githubusercontent.com/115775237/195987076-fb96605d-e24f-472d-9db5-c6527df35a49.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Cara membuat akun git
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut http://github.com
![2022-10-15 (7)](https://user-images.githubusercontent.com/115775237/195987412-9df5aab3-0a2a-4e5e-8ac7-8085a07d1fa0.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### Membuat repositori baru

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git
![2022-10-15 (13)](https://user-images.githubusercontent.com/115775237/195987581-2529edc4-218b-4001-a07c-f15aacc336c8.png)


- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 
![2022-10-15 (15)](https://user-images.githubusercontent.com/115775237/195987750-67776099-1a42-40d4-a996-1c09b4abcc78.png)


-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![2022-10-15 (17)](https://user-images.githubusercontent.com/115775237/195987863-7dffcc54-078c-45eb-9988-f8d4d36f036f.png)


### Membuat Reposiory Local

- Lalu kita buka file explorer pilih dilocal disk e (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih *Git Bash here* .
![2022-10-15 (18)](https://user-images.githubusercontent.com/115775237/195987822-2cca298c-6968-4ae0-ab3b-ff97a7ab630f.png)

- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      *$ git config --global user.email “nama_user”*
      *$ git config --global user.name “nama_user”*
![2022-10-15 (20)](https://user-images.githubusercontent.com/115775237/195988128-75d271be-9310-420c-b411-4f47f763f331.png)

- Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 "  LALU *" cd lab_pemrograman1!
![2022-10-14 (3)](https://user-images.githubusercontent.com/115775237/195988047-4eb531b3-eaa4-435f-926c-08565431ab89.png)

##### Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local 

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
![git init](https://user-images.githubusercontent.com/115775237/195988250-c469c392-1bb5-4468-98b5-09ffcf3acd66.jpeg)

-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 
![2022-10-14](https://user-images.githubusercontent.com/115775237/195988614-289165b2-94a9-4a21-822a-26bd7852d237.png)

##### Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.
![2022-10-14](https://user-images.githubusercontent.com/115775237/195988675-85db2ced-c9a5-4110-b5cc-46320e1b2189.png)

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit"
![2022-10-14 (4)](https://user-images.githubusercontent.com/115775237/195988744-9e560662-87a6-4fd9-aca8-c5a62765c73d.png)

##### *File berhasil tersimpan*

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda "https://github.com/tiaraputriiiiii/latihan1.git"
![2022-10-14 (4)](https://user-images.githubusercontent.com/115775237/195988783-a1a6c5fa-5787-48c6-ad2c-11929aefa17a.png)

##### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
![2022-10-14 (4)](https://user-images.githubusercontent.com/115775237/195988840-9adc297e-11b7-4575-a358-47f1bcd0621c.png)

##### Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda "https://github.com/tiaraputriiiiii/latihan1.git" . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
![2022-10-14 (4)](https://user-images.githubusercontent.com/115775237/195988875-03134ec0-6499-4ef4-b07e-18932e8d6d91.png)

-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### *FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas*.
