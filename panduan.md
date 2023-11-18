### Pendahuluan Module Bundler

Salah satu module bundler yang populer digunakan pada saat ini adalah Webpack. Dengan ini, kita dapat mengubah dynamic code dan modules menjadi static code (kode yang siap digunakan pada tahap production). 

### Apa itu Webpack

Pada dasarnya, webpack merupakan salah satu module bundler untuk aplikasi JavaScript modern. Ketika webpack dijalankan pada proyek, webpack akan mengobservasi module apa saja yang kita digunakan dan membuat modul-modul tersebut dibungkus menjadi satu berkas (atau lebih) di belakang layar.


![Alt text](gambar.gif)

Dengan menggunakan Webpack, kita dapat leluasa menggunakan module yang saling bergantungan. Webpack akan menggabungkan seluruh module yang digunakan baik itu modul yang kita tuliskan sendiri atau module yang kita dapatkan melalui NPM menjadi static assets yang siap digunakan pada tahap produksi.

Webpack pertama kali rilis pada 10 Maret 2012. Sebelum ada webpack, sebenarnya sudah ada tools lain yang serupa seperti Browserify. Disamping sebagai module bundler, sejatinya ia memiliki tujuan sebagai tools yang dapat membawa node package apa pun agar dapat berjalan pada browser (kita dapat melihat tujuan dari namanya, “Browserify”).


Secara tidak langsung, browserify perlu berperan sebagai module bundler. Sebabnya, ketika menggunakan node package, tentu package tersebut terpisah dari kode yang kita tuliskan sendiri. Untuk menggabungkannya, Node.js menggunakan perintah require(). Dengan menggunakan browserify ini, perintah require() tersebut dapat kita gunakan pada browser (melalui transpiling).

Dari segi konsep, browserify dan webpack sangatlah berbeda. Namun kita dapat mengkategorikan keduanya sebagai module bundler. Kelebihan webpack dibandingkan dengan browserify adalah webpack dapat memproses berkas/modul lain di luar JavaScript seperti TypeScript atau Sass tanpa bantuan task runner seperti Grunt atau Gulp.

Sekitar awal tahun 2014 hingga pertengahan tahun 2015, Browserify ini populer digunakan oleh para developer. Hingga pada akhir tahun 2015, webpack-lah yang menggantikan kepopulerannya. Saat ini, webpack sudah menyentuh versi 5.

