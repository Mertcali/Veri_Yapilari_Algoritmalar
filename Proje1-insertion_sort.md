# Veri Yapilari ve Algoritmalar
## patika.dev
### PROJE 1 :Insertion Sort Projesi
### İsterler : [22,27,16,2,18,6] 
> Insertion Sort

> -> 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

> -> 2.Big-O gösterimini yazınız.

> -> 3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

> -> 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


## Insertion Sort Açıklama:
Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Peki ya devamı? İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktın ki 2.sıradaki eleman en küçük hiç dokunma!!!. Hemen 3. sıraya geç. 4, 5 derken dizi bitti.

Kaynak :[Patika](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort)

## İster 1:
```sh
['22',27,16,2,18,6] --> Tüm elemanlar gezilir en küçük sayı en baştaki ile yer değiştirilir.
[2,27,16,22,18,6] --> Birinci yerimiz tamamlandığı için artık 2. elemandan itibaren aynı işlemler yapılır.
[2,6,16,22,18,27] --> [2,6,16,18,22,27]
```

## İster 2: Big-O Gösterimi
`Best Case`: n

`Worst Case`: n²

`Average Case`: n²

## İster 3: Time Complexity
`Best Case`:Aradığımız sayı ilk sayımız ise.

`Worst Case`:Aradığımız sayı son sayı ise.

`Average Case`:Aradığımız sayı ortalarda ise.

## İster 4: 
[2,6,16,18,22,27] --> Average Case

## İster 5: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```sh
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
```





