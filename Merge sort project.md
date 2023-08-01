# Soru
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

---------
# Tanım
Eleman sayısı tek kalana kadar dizi parçalara ayrılır, sonrasında da birleştirilir, birleştirilirken de sıralama yapılır. En sonunda ba bu küçük sıralı diziler birleştirilir ve dizi sıralanmış olur.
## 6 elemanlı dizi için aşamaları yazalım.
- [16,21,11,8,12,22]
- [16,21,11] [8,12,22]
- [16,21] [11] ve [8,12] ve [22]
- [16] [21] [11] ve [8] [12] [22]
- [16, 21] [11] ve [8, 12] [22]
- [11, 16, 21] ve [8, 12, 22]
- [8, 11, 12, 16, 21, 22]

## Big-O-Notation
- Merge sort'un big o notation'u $O(nlog_2n)$'dir.
