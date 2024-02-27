# patikadevkotlinpatika-Sort-Projeleri

# Proje 1 - Selection Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-  Average case: Aradığımız sayının ortada olması
-  Worst case: Aradığımız sayının sonda olması
-  Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Proje 1 Cevabı
[22,27,16,2,18,6] (Insertion Sort) aşamaları :

* [22] (27, 16, 2, 18, 6)
* [22, 27] (16, 2, 18, 6)
* [16, 22, 27] (2, 18, 6)
* [2, 16, 22, 27] (18, 6)
* [2, 16, 18, 22, 27] (6)
* [2, 6, 16, 18, 22, 27]

Big-O -> O(n^2)

Avarage case kapsamına girer.

[7,3,5,8,2,9,4,15,6] (Selection Sort) aşamaları :
* [2, 3, 5, 8, 7, 9, 4, 15, 6]
* [2, 3, 5, 8, 7, 9, 4, 15, 6]
* [2, 3, 4, 8, 7, 9, 5, 15, 6]
* [2, 3, 4, 5, 7, 9, 8, 15, 6]

# Proje 2 - Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

## Proje 2 Cevabı

* [16, 21, 11] <|> [8, 12, 22]
* [16] <|> [21, 11] <|> [8] <|> [12, 22]
* [16] <|> [11, 21] <|> [8] <|> [12, 22]
* [11, 16, 21] <|> [8, 12, 22]
* [8, 11, 12, 16, 21, 22]

  Big-O -> O(nlogn)

# Proje 3 - Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Proje 3 Cevabı
```
Root -> 5

        5
     3     7
   1   4  6  8
 0   2         9

```

Kök 5'tir solunda 3 sağında 7 bulunur.

3'ün solunda 1 sağında 4 bulunur.

1'in solunda 0 sağında 2 bulunur.

7'nin solunda 6 sağında 8 bulunur.

8'in sağında 9 bulunur.
              
