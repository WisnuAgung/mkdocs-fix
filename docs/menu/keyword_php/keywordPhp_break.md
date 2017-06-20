#**Keyword PHP Break**
***

## **A. Penjelasan**

Break berfungsi sebagai perintah kepada web server untuk menghentikan  perulangan secara premature,yaitu menghentikan perulangan diluar dari yang direncanakan.Fungsi break dalam php digunakan untuk menghentikan proses yang dilakukan oleh perintah php  : for, foreach, while, do-while atau switch.

## **B. Bentuk Syntax Umum**

       while (text expression) {
	               //codes
			if (condition for break)
		{
			break;
		}
			//codes
		}

## **C. Implementasi**

       <?php
                   $Mahasiswa= array("Andi","Zulfan","Rahmi","Dodi","Doni");

                   foreach ($Mahasiswa as $value)
                   {
                   if($value=="Rahmi")
                   {
                   break;
                   }    
                   echo "$value";
                   echo "<br />";
                   }
       ?>

* Output

![Screenshot](img/break.png) 
	
