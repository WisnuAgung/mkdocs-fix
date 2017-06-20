#**Keyword PHP Array**
***

## **A. Penjelasan**

Array merupakan suatu struktur data yang dapat menyimpan banyak nilai dalam sebuah variabel.Tipe data array dapat menyimpan satu atau lebih data dalam variabel tunggal, sesuai dengan fungsinya, tipe data array sangat berguna untuk menyimpan banyak data dalam satu variabel.


## **B. Bentuk Syntax Umum**


		array(
			key  => value,
			key2 => value2,
			key3 => value3,
			...
		) 

## **C. Implementasi**

### Contoh Case

       <?php
                //membuat variabel $buah bertipe array, index/key tidak ditentukan
                $buah[] = "Anggur";
                $buah[] = "Rambutan";
                $buah[] = "Pepaya";
                $buah[] = "Pisang";
                echo $buah[1];
               //Hasilnya Rambutan
                echo "<p>";
                for($i=0;$i<count($buah);$i++)
               {
               echo "buah #$i: ".$buah[$i]."<br>";
               }
      	?> 

* Output

![Screenshot](img/array.png) 
