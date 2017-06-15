# **SQL**
***

## **A. Penjelasan**
SQL (Structured Query Language) merupakan sebuah bahasa yang digunakan untuk mengakses data dalam basis data (database) relasional. SQL banyak 
diterapkan pada pemrograman berbasis client-server seperti PHP, ASP, Java J2EE, dan sebagainya. 
Contoh software SQL yang terkenal adalah MySQL, MsSQL (Microsoft), Oracle 
SQL, Postgre SQL (open source). Masing-masing software mempunyai keunggulan sendiri-
sendiri, sejauh yang saya tahu Oracle SQL handal dalam hal keamanan dan ukuran database 
yang bisa mencapai tera byte, sedang MsSQL lebih banyak bermain di Memory untuk 
processing. Dari ketiga software ini, Oracle SQl bisa dikatakan sebagai pemegang pertama. 
Perintah dasar SQL pada dasarnya hampir sama baik MySQL, Postgre SQL, MsSQL atau 
Oracle SQL.

a. Apa itu SQL ?

* SQL adalah singkatan dari Structured Query Language
* SQL memungkinkan Anda mengakses dan memanipulasi database
* SQL adalah standar ANSI (American National Standards Institute)

b. Apa kegunaan SQL ?

* SQL dapat mengeksekusi query terhadap database
* SQL bisa mengambil data dari database
* SQL bisa memasukkan record dalam database
* SQL bisa mengupdate record dalam database
* SQL dapat menghapus record dari database
* SQL bisa membuat database baru
* SQL dapat membuat tabel baru dalam database
* SQL dapat membuat prosedur tersimpan dalam database
* SQL dapat membuat tampilan dalam database
* SQL dapat mengatur hak akses pada tabel, prosedur, dan tampilan

c. SQL adalah sebuah standar 

Meskipun SQL adalah standar ANSI (American National Standards Institute), ada beberapa versi bahasa SQL yang berbeda.
Namun, agar sesuai dengan standar ANSI, semuanya mendukung setidaknya perintah utama (seperti SELECT, UPDATE, DELETE, INSERT, WHERE) dengan cara yang sama.

Note : Most of the SQL database programs also have their own proprietary extensions in addition to the SQL standard!

d. SQL di situs web

Untuk membangun situs web yang menampilkan data dari database, Anda memerlukan :

* Program database RDBMS (yaitu MS Access, SQL Server, MySQL)
* Untuk menggunakan bahasa script sisi server, seperti PHP atau ASP
* Untuk menggunakan SQL dengan mendapatkan data yang anda inginkan
* Untuk menggunakan HTML / CSS ke style halaman

e. RDBMS

RDBMS adalah singkatan dari Relational Database Management System.

RDBMS adalah basis untuk SQL, dan untuk semua sistem database modern seperti MS SQL Server, IBM DB2, Oracle, MySQL, dan Microsoft Access.

Data dalam RDBMS disimpan dalam objek database yang disebut tabel. Tabel adalah kumpulan entri data terkait dan terdiri dari kolom dan baris.
***

## **B. Bentuk Syntax Umum**

		SELECT * FROM (tabel1, tabel2, ..); 
***

## **C. Implementasi**
### Contoh Case 
* Desaigner Database :

		Database = db_magang_2
![Screenshot](img/img_select/a.png) 

* Soal dan Penyelesaian :

**Menampilkan seluruh data di tabel siswa**

		SELECT * FROM siswa;

* Output                                              
![Screenshot](img/img_select/a1.png) 

