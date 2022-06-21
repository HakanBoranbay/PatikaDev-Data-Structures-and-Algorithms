# Proje 1
```
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```


## Answer 1:

```
Dizideki en küçüğü bul ve ilk sıradakiyle yer değiştir:
[2,27,16,22,18,6]
İkinci en küçüğü bul ve ikinci sıradakiyle yer değiştir:
[2,6,16,22,18,27]
Üçüncü en küçük ve üçüncü sıradaki, dokunmadan devam et:
[2,6,16,22,18,27]
Dördüncü en küçüğü bul ve dördüncü sıradakiyle yer değiştir:
[2,6,16,18,22,27]
Beşinci en küçük ve beşinci sıradaki, dokunmadan devam et:
[2,6,16,18,22,27]
Altıncı en küçük ve altıncı sıradaki, bitir:
[2,6,16,18,22,27]
```

## Answer 2
```
Big O notation: O(n^2)=O(6^2)=O(36)
```

## Answer 3
```
Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı dizinin ortasında yer aldığı için average case kapsamına dahildir.
```

## Answer 4
```
Birinci adım:
[2,3,5,8,7,9,4,15,6]
İkinci adım:
[2,3,5,8,7,9,4,15,6]
Üçüncü adım:
[2,3,4,8,7,9,5,15,6]
Dördüncü adım:
[2,3,4,5,7,9,8,15,6]
```