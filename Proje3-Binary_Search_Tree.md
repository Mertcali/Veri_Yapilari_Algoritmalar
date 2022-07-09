# Proje 3
## Veri_Yapilari_Algoritmalar
## patika_dev_sort-search_projeleri

# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Binary search tree, her elemanımızı bir düğüm noktası olarak düşünürsek, kök olarak yani başlangıç noktası olarak seçtiğimiz elemanın sağına ondan büyük olanları soluna ise ondan küçük olanları sıralı yerleştirmemizi ister.

Adım adım ilerler.

`Adım 1`

Kökümüz 8 olsun.

7 Sayısı 8'den küçük olduğu için 8'in soluna bir dal oluşturulur ve oraya yazılır.

7 Sayısı 8 den küçüktür : 8

-------------------------- /

------------------------7    

`Adım 2`

5 Sayısı hem 7'den hem 8'den küçük olduğu için 7'nin de soluna eklenir.

---------------------------- 8
-------------------------- /
------------------------7    
----------------------/
--------------------5

Sırasıyla bütün işlemler sağa ve sola olmak üzere bu şekilde devam edecektir.

`Kalan sayılar sıra izlenerek eklendi. Örneğin; 2-> 8'den küçük soluna, 7'den küçük soluna,5'ten küçük soluna, 1'den büyük sağına, 3'den küçük soluna.`

---------------------------- 8--------------------
-------------------------- /---\\-----------------
------------------------7------9--------------    
----------------------/--------------------
--------------------5--------------------
------------------/----\\------------------
-----------------1------6--------------------
---------------/-- \\--------------------
--------------0-----3--------------------
-------------------/---\\------------------
-----------------2------4---------------
