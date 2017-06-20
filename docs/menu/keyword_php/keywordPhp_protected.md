#**Keyword PHP Protected**
***

## **A. Penjelasan**

Berbeda dengan public, protected hanya memperbolehkan suatu property atau method yang dinyatakan protected diakses hanya di dalam class tersebut dan class turunannya

## **B. Bentuk Syntax Umum**

       
## **C. Implementasi**

	<?php
	 
	// buat class komputer
	class komputer{
	 
	   // property dengan hak akses protected
	   protected $jenis_processor = "Intel Core i7-4790 3.6Ghz";
	}
	  
	// buat class laptop
	class laptop extends komputer{
	   public function tampilkan_processor() {
	     return $this->jenis_processor;
	   }
	}
	  
	// buat objek dari class laptop (instansiasi)
	$laptop_baru = new laptop();
	  
	// jalankan method
	echo $laptop_baru->tampilkan_processor(); // "Intel Core i7-4790 3.6Ghz"
	?>  
* Output

![Screenshot](img/protected.PNG)
