# Proje 2
```
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
```


## Answer 1:

```
Adım 1: Dizi 2 parçaya ayrılır:
                         [16,21,11]    -    [8,12,22]
Adım 2: Bu diziler de ikişer parçalara ayrılır:
                    [16]    [21,11]    -    [8]    [12,22]
Adım 3: Tek elemana kadar düşmemiş diziler de ikiye ayrılır:
     [16]    -    [21]    -    [11]    -    [8]    -    [12]    -    [22]
Adım 4: Ayrılan diziler elemanları sıralanarak tekrar birleşir:
                    [16]    [11,21]    -    [8]     [12,22]
Adım 5: Birleşme işlemi elemanlar sıralanarak devam eder:
                         [11,16,21]    -    [8,12,22]
Adım 6: Dizinin tüm elemanları sıralanmış olur ve işlem sona erer:
                               [8,11,12,16,21,22]
```

## Answer 2
```
Big O notation: O(nlogn)=O(6log6)
```