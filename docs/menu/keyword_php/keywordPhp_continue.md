#**Keyword PHP Continue**
***

## **A. Penjelasan**

Continue berfungsi untuk menghentikan perulangan untuk 1 iterasi saja kemudian proses berikutnya akan dilanjutkan.


## **B. Bentuk Syntax Umum**

      jump-statement:
continue;

## **C. Implementasi**

     <?php
                  for($i = 0; $1<5; $i++){
                  if($i == 2){
                  continue;
                  }
                  echo("Loop Selesai");
     ?>

## **D. Output**

      Nilai i : 0
      Nilai i : 1
      Nilai i : 3
      Nilai i : 4
      Loop Selesai
