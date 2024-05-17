__Proje 3 Ödevi Soru ve Cevapları:__

>Soru 1:
>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Cevap a-)
```
Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

- Root "7"dir.
- 5, 7'den küçük olduğu için solda bulunur. Dizinden sırayla sorgulamaya devam ediyorum.
- 1, 7 ve 5'den küçük olduğu için 7'nin ve 5'in solunda bulunur. 
- 8, 7'den büyük olduğu için sağda bulunur.
- 6, 7'den küçük olduğu için 7'nin solunda, 5'den büyük olduğu için 5'in sağında bulunur.
- .
- .
- .

yukarıdaki gibi dizinler sırayla sorgulanır ve sorgu tamamlanır.
Şemaya dökecek olursak:

           7
          / \
         5   8
        / \   \
       1   6   9
      / \     
     0   3   
        / \
       2   4


Ağacımız yukarıdaki gibi yerleşmiş olur.
```

