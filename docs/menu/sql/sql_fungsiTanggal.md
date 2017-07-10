# **SQL Fungsi Tanggal**
***

## **A. Penjelsan** 
**a. MySQL Fungsi Tanggal**

| Fungsi   		  | Kegunaan                                               														          |
|-----------------| --------------------------------------------------------------------------------------------------------------------- |
| NOW()  		  | untuk mendapatkan informasi waktu (tanggal dan jam saat ini)													      |
| CURDATE()   	  | untuk mendapatkan informasi tanggal saat ini			    				                                          | 
| CURTIME()       | untuk mendapatkan informasi jam saat ini  																			  |
| DATE()          | untuk Ekstrak bagian tanggal dari tanggal atau tanggal / ekspresi waktu												  |
| DATE_ADD()      | untuk menambahkan interval waktu tertentu pada sebuah tanggal 									                      |
| DATE_SUB()      | untuk untuk pengurangan sebuah tanggal dengan interval tertentu 								 					  |
| DATEDIFF()      | untuk mendapatkan informasi waktu di antara 2 buah tanggal          					 		            		  |
| DATE_FORMAT()   | untuk untuk menampilkan informasi jam dan tanggal dengan format tertentu                                              |  			    				

**b. Date Format**

| Fungsi  | Kegunaan                                               			  |
|---------| ----------------------------------------------------------------------------- |
| %a  	  | Nama hari kerja yang disingkat (Sun to Sat)				  	  |
| %b   	  | Nama bulan yang disingkat (Jan to Dec)			  		  |		              
| %c      | Nama bulan numerik (0 sampai 12) 						  |
| %d      | Hari dalam sebulan sebagai nilai numerik (01 sampai 31)	                  |
| %H      | Hour (00-23)      								  | 
| %h      | Jam (00 sampai 12)    							  | 
| %M      | Bulan nama secara penuh (Januari sampai Desember)     			  | 
| %m      | Nama bulan sebagai nilai numerik (00 sampai 12)      			  | 
| %p      | AM atau PM    								  | 
| %W      | Nama hari kerja secara penuh (Minggu sampai Sabtu)      			  | 
| %Y      | Tahun sebagai angka, nilai 4 digit     					  | 
| %y      | Tahun sebagai angka, nilai 2 digit   					  | 

**c. SQL Tipe Data Tanggal**

* MySQL dilengkapi dengan tipe data berikut untuk menyimpan tanggal atau tanggal / nilai waktu dalam database:

	    DATE - format YYYY-MM-DD
	    DATETIME - format: YYYY-MM-DD HH:MI:SS
	    TIMESTAMP - format: YYYY-MM-DD HH:MI:SS
	    YEAR - format YYYY or YY

* SQL Server hadir dengan tipe data berikut untuk menyimpan tanggal atau tanggal / nilai waktu dalam database:


	    DATE - format YYYY-MM-DD
	    DATETIME - format: YYYY-MM-DD HH:MI:SS
	    SMALLDATETIME - format: YYYY-MM-DD HH:MI:SS
	    TIMESTAMP - format: a unique number

* Catatan: Jenis tanggal dipilih untuk kolom saat Anda membuat tabel baru di database Anda
