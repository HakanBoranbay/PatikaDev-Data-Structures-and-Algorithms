# Proje 3:
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```



## Answer:

```
Root 7 olarak belirlenir ve elemanlar Binary Tree'ye eklenir:
Adım 1: 5 7'den küçük olduğu için soluna eklenir.
Adım 2: 1 7'den küçük olduğu için solundan devam eder; 5'ten de küçük olduğu için soluna eklenir.
Adım 3: 8 7'den büyük olduğu için sağına eklenir.
Adım 4: 3 sırasıyla 7'den küçük, 5'ten küçük ve 1'den büyük olduğu için 1'in sağına eklenir.
Adım 5: 6 sırasıyla 7'den küçük, 5'ten büyük olduğu için 5'in sağına eklenir.
Adım 6: 0 sırasıyla 7'den küçük, 5'ten küçük ve 1'den küçük olduğu için 1'in soluna eklenir.
Adım 7: 9 sırasıyla 7'den büyük ve 8'den büyük olduğu için 8'in soluna eklenir.
Adım 8: 4 sırasıyla 7'den küçük, 5'ten küçük, 1'den büyük ve 3'ten büyük olduğu için 3'ün sağına eklenir.
Adım 9: 2 sırasıyla 7'den küçük, 5'ten küçük, 1'den büyük ve 3'ten küçük olduğu için 3'ün soluna eklenir.

                                            7
                                           / \
                                          5   8
                                         / \   \
                                        1   6   9
                                       / \
                                      0   3
                                         / \
                                        2   4
```
