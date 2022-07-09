# Veri_Yapilari_Algoritmalar
patika_dev_sort-search_projeleri

# PROJE 2: Merge SORT

# [16,21,11,8,12,22] -> Merge Sort

>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
>Big-O gösterimini yazınız.

## Dizinin Bulunması

| ADIMLAR | Dizi | 
| ------ | ------ | 
| Diziyi 2ye bölüyoruz. | [16,21,11] [8,12,22] |
| Ayrılan dizileri kendi aralarında tekrar bölüyoruz. | [16,21] [11] [8,12] [22] |
| Bütün diziler tek eleman kalana kadar bölmeye devam ediyoruz.  | [16] [21] [11] [8] [12] [22] |
| Bölme işlemi bittikten sonra bütün elemanlar karşılaştırılarak sıralı bir dizi elde edilerek birleştirilir. | [8,11,12,16,21,22]  |

## Big-O Gösterimi

Big-O Gösterimi O(nlogn) dir. n yaptığım işlemlerdir.
