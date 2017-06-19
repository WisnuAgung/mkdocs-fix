# **APACHE**
***

## **A. Penjelasan**
Apache adalah sebuah nama web server yang bertanggung jawab pada request-response HTTP dan logging informasi secara detail. Suatu web server yang kompak, modular, mengikuti standar protokol HTTP

a. Penggunaan

Apache adalah komponen server web dari paket perangkat lunak LAMP (Linux, Apache, MySQL, PHP/Perl/bahasa pemrograman Python). 

b. Kegunaan

* Sifatnya yang opensource dan mudahnya mengkostumisasikannya

c. Kelebihan

* Apache termasuk dalam kategori freeware
* Apache mudah sekali proses instalasinya jika dibanding web server lainnya seperti NCSA, IIS, dan lain-lain
* Mampu beroperasi pada berbagai paltform sistem operasi
* Mudah mengatur konfigurasinya. Apache mempunyai hanya empat file konfigurasi
* Mudah dalam menambahkan peripheral lainnya ke dalam platform web servernya

d. Kekurangan

* Web server Apache tidak memiliki kemampuan mengatur load seperti IIS, sehingga akan terus mem-fork proses baru hingga nilai MaxClients tercapai atau hingga batas yang diizinkan oleh OS. Ini tentunya menguntungkan penyerang karena habisnya RAM akan lebih cepat tercapai
* Apache tidak memproses karakter kutip dalam string Referrer dan User-Agent yang dikirimkan oleh Client. Ini berarti Client dapat memformulasi inputnya secara hati-hati untuk merusak format baris log akses
* Terganggunya proses upload data, yang bisa menyebabkan software salah dalam menerjemahkan ukuran data yang masuk.
***

## **B. Tutorial Installasi**

### Install Apache
**Tutorial install APACHE di Linux Ubuntu 16.04 desktop :**

Apache tersedia di dalam repositori perangkat lunak default Ubuntu, jadi kami akan menginstalnya menggunakan alat manajemen paket konvensional.

Kami akan memulai dengan memperbarui indeks paket lokal untuk mencerminkan perubahan hulu terbaru. Setelah itu, kita bisa menginstal paket apache2:

    Sudo apt-get update
    Sudo apt-get install apache2

Setelah mengkonfirmasikan instalasi, apt-get akan menginstal Apache dan semua dependensi yang dibutuhkan.
