# Proje 1
## Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```

[22,27,16,2,18,6]
[22,16,27,2,18,6]
[16,22,27,2,18,6]
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]
[2,16,22,18,27,6]
[2,16,18,22,27,6]
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]

```


Big-O gösterimini yazınız.

```
Big O algoritmanın performansını en kötü durumda ölçer. O(n^2) verilerin boyutu büyüdükçe algoritmanın çalışma süresi çok daha hızlı olur. Veri boyutu arttıkça çalışma süresini tanımlar.
```


Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız


Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

```

[2,6,16,18,22,27]
Average case kapsamına girer.
```




[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```

1.Adım
[2,3,5,8,7,9,4,15,6]

2.Adım
[2,3,5,8,7,9,4,15,6]

3.Adım
[2,3,4,8,7,9,5,15,6]

4.Adım
[2,3,4,5,7,9,8,15,6]
```


# Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
[16,21,11] [8,12,22]

[16] [21,11]   [8,12] [22]

[16] [11,21]   [8,12] [22]

[11,16,21]    [8,12,22]

[8,11,12,16,21,22]
```


Big-O gösterimini yazınız. 

```
O(n*logn)

```

# Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

```
Root 7 dir

      7
     /  \
    5    8
   / \     \
  1   6     9
 / \
0    3
    / \
   2   4


```



