#**Keyword PHP Require**
***

## **A. Penjelasan**

Perintah ini digunakan untuk menggabungkan suatu script PHP atau teks dari file lain dengan script PHP yang memanggilnya. Script atau file  
yang digabung tidak harus berisi script atau kode program PHP. Apabila script atau file yang digabungkan itu berupa script PHP, maka PHP akan mengevaluasi dan menjalankannya.
 
## **B. Bentuk Syntax Umum**

	<?php
	// Panggil file function looping.php
	//dengan require()

	require ("_functtion_looping.php
       
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
	
	3. Buat file require.php
	
			<!-- ini file header.php -->
	<?php require('header.php');?>
	<hr/>
	<!-- ini isi dari file require.php -->
	 <h1>Ini Adalah Isi</h1>
	 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam nulla turpis, pulvinar eu dui gravida, mattis blandit odio. Aliquam sit amet ex ullamcorper, consectetur ipsum quis, mattis tortor.</p>
	<hr/>
	<!-- ini file footer.php -->
	<?php require('footer.php');?>

* Output

![Screenshot](img/require.PNG) 
         
