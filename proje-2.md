__Proje 2 Ödevi Soru ve Cevapları:__

>Soru 1:
>[16,21,11,8,12,22] -> Merge Sort
>- a-) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
>- b-) Big-O gösterimini yazınız.


Cevap a-)
```
[16,21,11,8,12,22] dizisinin Merge Sort türüne göre aşamaları:

1.Adım: [16,21,11,8,12,22] diziyi yerleştirdim. Diğer adımlarda 2 gruba ayıracağım.

2.Adım:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
3.Adım:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
4.Adım:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
5.Adım:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
6.Adım:                [11,16,21]                            [8,12,22]
                                  
7.Adım:                               [8,11,12,16,21,22]

```

---

Cevap b-)
```
[16,21,11,8,12,22] dizisinin Big-O gösterimi:

[16,21,11,8,12,22] dizisi en performanslı halini Merge Sort verecektir.

Merge Sort = O(nlogn)


```
