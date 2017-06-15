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
| EXTRACT()       | untuk mendapatkan informasi bagian-bagian dari data waktu tertentu, seperti tahun, bulan, hari, jam, menit, dan detik |
| DATE_ADD()      | untuk menambahkan interval waktu tertentu pada sebuah tanggal 									                      |
| DATE_SUB()      | untuk untuk pengurangan sebuah tanggal dengan interval tertentu 								 					  |
| DATEDIFF()      | untuk mendapatkan informasi waktu di antara 2 buah tanggal          					 		            		  |
| DATE_FORMAT()   | untuk untuk menampilkan informasi jam dan tanggal dengan format tertentu                                              |  			    				

**b. SQL Server Fungsi Tanggal**

| Fungsi   		  | Kegunaan                                               						  |
|-----------------| ----------------------------------------------------------------------------- |
| GETDATE()  	  | untuk mengembalikan tanggal dan waktu sekarang							      |
| DATEPART()   	  | untuk mengembalikan satu bagian dari tanggal / waktu			    		  |		              
| DATEADD()       | untuk menambahkan atau mengurangi interval waktu yang ditentukan dari tanggal |
| DATEDIFF()      | untuk mendapatkan informasi waktu di antara 2 buah tanggal 	                  |
| CONVERT()       | untuk mengkonversi dari satu karakter set menjadi karakter set yang lain      | 

**c. SQL Tipe Data Fungsi Tanggal dan Waktu**

| Fungsi   		  | Kegunaan                                               		 |
|-----------------| ------------------------------------------------------------ |
| FORMAT()  	  | untuk memformat sebuah nomor 								 |
| NOW()   	      | untuk mendapatkan informasi waktu (tanggal dan jam saat ini) | 

**d. SQL Tipe Data Tanggal**

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