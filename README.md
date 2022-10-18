**Hallo nama saya Amanda Puspa Negara. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan ialah** *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan GIT.
## Cara penginstalan GIT
- Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di **git-scm.com .**
![Screenshot (11)](https://user-images.githubusercontent.com/115678845/196313282-a1c77074-7ad0-4a88-b426-cf39a36e2e1e.png)
*Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.
![67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8](https://user-images.githubusercontent.com/115678845/196313833-9622ec3c-6ffa-4e11-868d-e31dd0251b65.png)
Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1
![Screenshot (17)1](https://user-images.githubusercontent.com/115678845/196314974-dded3f93-5fff-4c3e-9a4b-cc175b9d9357.png)
-------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![Screenshot (18)](https://user-images.githubusercontent.com/115678845/196409853-ed8c69a2-7fcc-4616-9c04-f52a63c79987.png)
- Pada langka selanjutnya anda boleh langsung diskip saja.
### _Membuat repositori baru_
- Ini adalah tampilan pertama setelah kalian selesai membuat akun git
![Screenshot (19)](https://user-images.githubusercontent.com/115678845/196410413-2bab42b5-73a8-4bf0-bad2-2dcce4ba510e.png)
- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
![Screenshot (20)](https://user-images.githubusercontent.com/115678845/196410567-3b02147f-f87e-4a91-a7d8-3616a33cd6a7.png)
- Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![Screenshot (21)](https://user-images.githubusercontent.com/115678845/196411071-f3b73fac-c90b-422b-a759-3f1b354494a7.png)
### _Membuat Repository Local_
- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here. 
![Screenshot (22)](https://user-images.githubusercontent.com/115678845/196411542-e096b145-8a78-4a7a-a37e-57f32f886013.png)
- Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user”
![Screenshot (23)](https://user-images.githubusercontent.com/115678845/196416311-dbde3b0b-e6d4-4faa-a12a-428490d9137f.png)
-Buatlah direktori baru dengan menggunakan perintah " _mkdir lab_pemrograman1_ " LALU " _cd lab_pemrograman1_ "
![Screenshot (15)1](https://user-images.githubusercontent.com/115678845/196417040-f50a4c51-c735-42ba-9e5f-417932a97ce7.png)
#### _Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local_
- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
![Screenshot (15)2](https://user-images.githubusercontent.com/115678845/196417758-b8c51c29-1d4f-4403-9169-bd04eaef7c07.png)
Lalu buat 1 file baru bernama README.md, dengan memasukan perintah echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls
![Screenshot (15)3](https://user-images.githubusercontent.com/115678845/196418081-c52eb22e-7e97-42df-97db-a9165daea204.png)
### _Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git _add._ Dengan perintah _$ git add README.md._ Kalau ingin melihat infonya ketik perintah git status.
![Screenshot (15)4](https://user-images.githubusercontent.com/115678845/196418639-a77bb79e-3edf-4cb0-91f4-315888db5a0b.png)
Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
![Screenshot (15)5](https://user-images.githubusercontent.com/115678845/196418974-0df4f0c9-19f1-4f0d-8c8c-fddf057903dc.png)
#### File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah _“git remote add origin [url] “_ DAN PERINTAH GIT CLONE _“ git clone [ url ] “_
#### Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/amandaaaapn/Latihan_1.git
![Screenshot (16)1](https://user-images.githubusercontent.com/115678845/196419888-2b87155d-18c1-46ed-afec-576c8cfa1d51.png)
#### Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
- Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
![Screenshot (16)1](https://user-images.githubusercontent.com/115678845/196420103-3f8acaae-832d-4bbc-b048-79070e0fa5f1.png)
#### Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/amandaaaapn/Latihan_1.git. Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1"
![Screenshot (16)1](https://user-images.githubusercontent.com/115678845/196420512-e1e761d4-2978-44b1-9c20-a8423df8167b.png)
- Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya
#### FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
#### Terimakasih
