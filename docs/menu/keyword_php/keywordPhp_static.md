#**Keyword PHP Static**
***

## **A. Penjelasan**

Jika kita mendeklarasikan function atau variable sebagai static berarti kita tidak perlu membuat instance untuk mengakses function atau variable 
tersebut.Karena metode statis dapat dipanggil tanpa turunan dari objek yang dibuat, variabel pseudo-$ ini tidak tersedia di dalam metode yang dinyatakan statis.

## **B. Bentuk Syntax Umum**

	// static property
	public static $harga_beli;

	// static method
	public static function beli_laptop() {
	//...isi method
	}
       
## **C. Implementasi**

		<?php
	// buat class laptop
	class laptop {
	   public $merk;
	   public $pemilik;

	   // static property
	   public static $harga_beli;
	 
	   //static method
	   public static function beli_laptop() {
		 return "Beli Laptop";
	   }
	}
	 
	// set static property
	laptop::$harga_beli=4000000;
	 
	// get static property
	echo "harga beli : Rp".laptop::$harga_beli;
	 
	echo "<br />";
	 
	// panggil static method
	echo laptop::beli_laptop();
	?>
	
* Output

![Screenshot](img/static.PNG) 

