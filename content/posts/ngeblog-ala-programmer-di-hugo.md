---
author: "Giri Diwa Adam"
title: "Ngeblog Ala Programmer Di Hugo"
date: 2022-07-17T20:15:07+07:00
draft: false
featured_image: "ngeblogdi-hugo.png"

tags:
- hugo
---
## Pembukaan ##
Hugo merupakan sebuah SSG yang flexibel dan mudah dalam penggunaanya,tak heran banyak orang
yang ingin menggunakanya,terutama para programmer yang ingin bebas ber-experiment dengan tema
mereka, lain halnya jika kita menggunakan CMS kita harus mengikuti aturan yang telah di buat
oleh si pengembang CMS jadi kita tidak punya standar sendiri dalam memodifikasi atau mengembangkan
ide yang kita punya.

Pada kesempatan kali ini saya akan membahas sedikit mengenai Hugo, dan di kesempatan kali ini juga
kita akan belajar membuat blog dengan gaya programmer, hanya menggunakan IDE seperti visual studi code
atau sublime text, kita sudah bisa menulis isi dari blog kita sendiri.

Oke tanpa ber lama-lama lagi kita masuk pembahasanya.

1. Kalian sudah harus menginstall hugo Jika kalian belum menginstall kalian bisa pergi ke halaman ini (https://github.com/gohugoio/hugo/releases),
   dan pilih sesuai dengan windows yang kalian pakai Jika kalian pakai windows jika kalian pakai linux gunakan perintah ini ``wget`` atau ``sudo``
   pastikan ketika kalian install sesuaikan dengan system operasi yang kalian pakai.

2. Jika sudah terinstall silahkan masuk ke folder dimana hugo berada,kalau saya berada di ``C:\Hugo\Sites`` sesuaikan dengan tempat
   kalian menginstall hugo.

3. Lalu jalankan perintah ``hugo new sites`` dan isikan dengan nama situs kalian masing-masing contoh **Kode Blog** ini hanya contoh
   untuk nama situs terserah kalian masing-masing.

4. Jika kalian ingin membuat tema kalian bisa gunakan perintah ``hugo new theme [nama_tema]`` dan buka folder ``theme\nama_tema``,
   dan silahkan ber-experiment dengan tema baru.

5. Dan untuk membuat sebuah post gunakan perintah ``hugo new posts/nama_konten.md`` dan isi dengan markdown berikut:

6. setelah selesai jalankan server hugo dengan perintah ``hugo server`` masuk terlebih dahulu ke folder situs kalian
7. dan jika tampilanya kosong,maka tandanya ada yg terlewat maka dari itu setting di ``config.toml`` dan aktifkan 
   tema kalian di sana jangan lupa kalian sudah mengisi halaman ``header.html``,``head.html``,``index.html`` dan juga halaman ``single.html`` di folder
   ``_default``.

Oke Jika semua sudah beres kini tinggal kalian lihat hasilnya di ``localhost:1313``.

Demikian tutorial singkat yang dapat saya sampaikan mohon maaf jika belum ada gambar di sini saya masih terus
mengembangkan blognya agar lebih baik lagi kedepanya, Jika kurang jelas dapat bertanya di kolom komentar atau
kunjungi situs refrensi berikut ini: petanikode, wibucode





