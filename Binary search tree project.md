# Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

-----------
- Root 6 olarak seçilirse,
- 7, 6'nın sağında olacaktır
- 5, 6'nın solunda olacaktır
- 1, 6'nın solunda, 5'in de solunda olacaktır.
- 8, 6'nın sağında, 7'nin de sağında olacaktır.
- 3, 6'nın solunda, 5'in solunda, 1'in de sağında olacaktır.
- 0, 6'nın solunda, 5'in solunda, 1'in de solunda olacaktır.
- 9, 6'nin sağında, 7'nin sağında, 8'in de sağında olacaktır.
- 4, 6'nın solunda, 5'in solunda, 1'in sağında, 3'ün sağında olacaktır.
- 2, 6'nın solunda, 5'in solunda, 1'in sağında, 3'ün solunda olacaktır.

```
   6
  5 7
 1   8
0 3   9
 2 4
```
