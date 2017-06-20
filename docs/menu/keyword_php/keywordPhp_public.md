#**Keyword PHP Public**
***

## **A. Penjelasan**

Ketika suatu property ataupun method dinyatakan public maka akan berlaku property ataupun method tersebut dapat diakses dari luar class dan dapat diakses oleh class turunan.

## **B. Bentuk Syntax Umum**

       
## **C. Implementasi**

	<?php
	 
	// buat class laptop
	class laptop {
	 
	   // buat public property
	   public $pemilik;
	 
	   // buat public method
	   public function hidupkan_laptop() {
	     return "Hidupkan Laptop";
	   }
	}
	  
	// buat objek dari class laptop (instansiasi)
	$laptop_anto = new laptop();
	  
	// set property
	$laptop_anto->pemilik="Anto";
	  
	// tampilkan property
	echo $laptop_anto->pemilik; // Anto
	  
	// tampilkan method
	echo $laptop_anto->hidupkan_laptop(); // "Hidupkan Laptop"
	?>
		 
* Output

![Screenshot](img/public.PNG)
