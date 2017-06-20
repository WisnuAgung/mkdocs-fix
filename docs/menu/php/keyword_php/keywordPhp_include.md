#**Keyword PHP Include**
***

## **A. Penjelasan**

Perintah ini digunakan untuk menggabungkan suatu script PHP atau file dengan script pemanggilnya. Perintah include() akan memanggil selalu 
akan melakukan evaluasi kembali script yang ada yang dispesifikasikan dalam perintah tersebut.

## **B. Bentuk Syntax Umum**

	<?php
	// Bentuk fungsi
	include ('includes/header.php');

	// Bentuk statement
	include 'includes/header.html'; 
       
## **C. Implementasi**

	1. Buat file header.php
	
		 <!DOCTYPE html>
	<html>
	<head>
	 <meta charset="utf-8">
	 <title>Contoh Require dan Include</title>
	 <h1>ini header.php</h1>
	 <style type="text/css">
	  body{
	   background-color:#eee;
	   text-align:center;
	   font-family:Calibri;
	   font-size:18px;
	  } 
	 </style>
	</head>
	<body>

	2. Buat file footer.php
	
		<footer>
	  <h1>Ini adalah file footer.php</h1>
	 </footer>
	</body>
	</html>
	
	3. Buat file include.php
	
		<?php include 'header.php';?>
	<hr/>
	<!-- ini isi dari file include.php -->
	 <h1>Ini Adalah Isi</h1>
	 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam nulla turpis, pulvinar eu dui gravida, mattis blandit odio. Aliquam 		sit amet ex ullamcorper, consectetur ipsum quis, mattis tortor.</p>
	<hr/>
	<!-- ini file footer.php -->
	<?php include 'footer.php';?>

* Output

![Screenshot](img/include.PNG) 
         
