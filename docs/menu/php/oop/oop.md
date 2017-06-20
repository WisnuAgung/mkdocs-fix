# **OOP**
***

## **A. Penjelasan**

a. Class 

Merupakan model yang berisi kumpulan attribute dan method dalam suatu unit untuk suatu tujuan tertentu. Method dalam sebuah class dapat merubah attribute yang dimiliki oleh class tersebut. Sebuah class merupakan dasar dari modularitas dan struktur dalam pemrograman berorientasi object.  
Class (Kelas) adalah sebuah konsep yang memperluas dari struktur data, seperti struktur data, mereka dapat berisi data anggota, tetapi mereka juga dapat mengandung fungsi sebagai anggota. Sebuah objek adalah Instansiasi kelas. Dalam hal variabel, kelas akan menjadi tipe, dan objek akan variabel. Kelas didefinisikan baik menggunakan kata kunci class atau kata kunci struct , dengan sintaks berikut.
Dimana class_name adalah identifier yang valid untuk kelas, object_names adalah daftar nama opsional dari objek dari kelas ini. Tubuh deklarasi dapat berisi anggota, yang dapat menjadi data atau deklarasi fungsi, dan specifier akses opsional.

* Contoh Class :
	Class manusia memiliki attribute berat, tinggi, usia kemudian memiliki method makan, minum, tidur. 

b. Inheritance 

Inheritance merupakan pewarisan atribut dan method dari sebuah class ke class lainnya. Class yang mewarisi disebut superclass dan Class yang diwarisi disebut subclass. Adapun inheritance sendiri adalah pewarisan sifat. 

* Contoh Inheritance :
	Terdapat class sepeda dan sepeda gunung, sepeda balap, sepeda motor. Sepeda termasuk superclass.  Sepeda gunung, sepeda balap, sepeda motor termasuk subclass. Hal ini dikarenakan sepeda gunung, sepeda balap, dan sepeda motor  memiliki variabel dan method yang dimiliki oleh sepeda.

c. Encapsulation 

Merupakan proses untuk menutupi semua detail dari sebuah object yang tidak menyokong karakteristik khas dari object. Artinya, data property dan method-method dari object hasil abstraksi dibungkus oleh struktur class agar terlindungi. Rincian implementasi internal suatu object dibuat tersembunyi sehingga tidak bisa diketahui dan diakses oleh object lain. Object lain hanya bisa berkomunikasi dengan object tersebut melalui antarmuka (interface) yang disediakan oleh object tersebut.

d. Polymorphism :

Merupakan konsep yang memungkinkan digunakannya suatu interface yang sama untuk memerintah suatu object agar melakukan suatu tindakan yang mungkin secara prinsip sama tetapi secara proses berbeda.

* Contoh Polymorphism :
	Bila sebuah burung menerima pesan “gerak cepat”, dia akan menggerakan sayapnya dan terbang. Bila seekor singa menerima pesan yang sama, dia akan menggerakkan kakinya dan berlari. Keduanya menjawab sebuah pesan yang sama, namun yang sesuai dengan kemampuan hewan tersebut. Ini disebut polimorfisme karena sebuah variabel tungal dalam program dapat memegang berbagai jenis objek yang berbeda selagi program berjalan, dan teks program yang sama dapat memanggil beberapa metode yang berbeda di saat yang berbeda dalam pemanggilan yang sama.

## **B. Implementasi**

	<?php

	// interface => penerapan polyform
	// new => penerapan object
	// extends => inherent

	interface  BangunRuang
	{
	   public function getLuas();
	}

	class abstract Bidang
	{
	   public function getNama()
	   {
	       return "Bidang";
	   }
	}

	class Lingkaran extends Bidang implements BangunRuang
	{
	   
	   public function getNama()
	   {
	       return "lingkaran";
	   }
	   
	   protected function rumusLuasLingkaran()
	   {
	       
	   }
	}

	class Persegi extends Bidang implements BangunRuang
	{
	   public function rumusLuasPersegi()
	   {
	       
	   }
	}

	class PenghitungLuas()
	{
	   public function hitung(BangunRuang $bangunRuang)
	   {
	       return $bangunRuang->getLuas();
	   }
	}

	$lingkaran = new Lingkaran();



	class Printer
	{
	   public function cetak(FormatData $formatData)
	   {
	       formatDataA();
	       formatDataB
	       $formatData->cetak();
	       
	   }
	}
	?>

