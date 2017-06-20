#**Keyword PHP Function**
***

## **A. Penjelasan**

Function yaitu kode program yang dirancang untuk menyelesaikan sebuah tugas tertentu, dan  merupakan bagian dari program utama. Kita dapat membuat fungsi sendiri, atau menggunakan fungsi yang dibuat oleh programmer lain.Argumen fungsi ditulis dalam  tanda kurung dan dapat berupa tipe data apapun baik string, array, object,boelan, dsb.., selain itu argumen juga dapat dikosongkan.


## **B. Bentuk Syntax Umum**

             function nama_fungsi ($parameter1, $parameter2)
             {
              // kode program fungsi
             return $nilai_akhir
             }

## **C. Implementasi**
     <?php
            //pemanggilan fungsi
              echo "Luas Lingkaran dengan jari-jari 7cm = ".luas_lingkaran(7)."cm";
 
            //pembuatan fungsi
              function luas_lingkaran($jari2)
            {
            return M_PI*$jari2*$jari2;
            }
     ?>

* Output

![Screenshot](img/function.PNG) 
	

         
