#**Keyword PHP If Elseif Else**
***

## **A. Penjelasan**

If..Elseif..Else digunakan untuk memilih salah satu dari banyak blok kode yang akan dieksekusi.


## **B. Bentuk Syntax Umum**

	if (condition)
	code to be executed if condition is true;
	elseif (condition)
	code to be executed if condition is true;
	else
	code to be executed if condition is false;
		

## **C. Implementasi**

	<?php
	$nilai=75;

	if($nilai<=55){
		$nilai_huruf="D";
	}elseif($nilai<=65){
		$nilai_huruf="C";
	}elseif($nilai<=80){
		$nilai_huruf="B";
	}elseif($nilai<=100){
		$nilai_huruf="A";
	}else{
		$nilai_huruf="Tidak Valid";
	}

	echo"Nilai : $nilai_huruf";
	?>

* Output

![Screenshot](img/ifelseifelse.PNG) 
