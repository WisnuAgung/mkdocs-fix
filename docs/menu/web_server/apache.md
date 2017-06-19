# **Installasi Apache, PHP**
***

## **A. Penjelasan**

a. Apache

Apache adalah komponen server web dari paket perangkat lunak LAMP (Linux, Apache, MySQL, PHP/Perl/bahasa pemrograman Python). 

b. PHP

PHP adalah singkatan dari "PHP: Hypertext Prepocessor", yaitu bahasa pemrograman yang digunakan secara luas untuk penanganan pembuatan dan pengembangan sebuah situs web dan bisa digunakan bersamaan dengan HTML.
***

## **B. Tutorial Installasi**

### Install Apache
**Tutorial install APACHE di Linux Ubuntu 16.04 desktop :**

Apache tersedia di dalam repositori perangkat lunak default Ubuntu, jadi kami akan menginstalnya menggunakan alat manajemen paket konvensional.

Kami akan memulai dengan memperbarui indeks paket lokal untuk mencerminkan perubahan hulu terbaru. Setelah itu, kita bisa menginstal paket apache2:

    $ sudo apt-get update

    $ sudo apt-get install apache2

Setelah mengkonfirmasikan instalasi, apt-get akan menginstal Apache dan semua dependensi yang dibutuhkan.

### Install PHP
**Tutorial install PHP di Linux Ubuntu 16.04 desktop :**

	$ sudo apt-get install php

	$ sudo apt-get install libapache2-mod-php

	$ cd /var/www/

	$ sudo chown username:www-data . - R
