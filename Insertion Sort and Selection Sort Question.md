# Soru
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---------------
# Insertion Sort Tanım
Insertion sort en küçük dizi elemanının bulunup (n adımda) en başa yazılması ile başlar. Bundan sonraki aşamada ilk dizi elemanı es geçilip diğer kalan (n-1) dizi elemanlarından en küçüğü seçilip ikinci sıraya yazılır. Son elemana kalana kadar (1) bu şekilde devam eder. 
## 6 elemanlı dizi için tüm aşamaları yazalım:
- [22,27,16,2,18,6] ⟹ 1. eleman (n)
- [2,27,16,22,18,6] ⟹ 2. eleman (n-1)
- [2,6,16,22,18,27] ⟹ 3. eleman (n-2)
- [2,6,16,22,18,27] ⟹ 4. eleman (n-3)
- [2,6,16,18,22,27] ⟹ 5. eleman (n-4)
- [2,6,16,18,22,27] ⟹ 6. eleman (n-5)

- Toplamda 6 aşamada tamamlanmıştır.

## Big-O-Notation
- Bu sort yöntemi için $O(n^2)$ olacaktır. Çünkü bu işlem toplamda $(n) + (n-1) + ... + 1 = \frac{n*(n+1)}{2}$ adımda tamamlanacaktır.

## Time Complexity
- 18 sayısı average case'tir.

---------------
# Selection Sort Tanım
n elemanlı bir dizi içerisinden en büyük eleman bulunur ve sona yerleştirilir. Kalan baştaki n-1 elemandan en büyüğü bulunup sondan ikinci konuma yerleştirilir. En küçük elemana kadar işlem tekrarlanır.
## 9 elemanlı dizi için tüm aşamaları yazalım:
- [7,3,5,8,2,9,4,15,6]
- [7,3,5,8,2,9,4,6,15]
- [7,3,5,8,2,6,4,9,15]
- [7,3,5,4,2,6,8,9,15]
- [6,3,5,4,2,7,8,9,15]
- [2,3,5,4,6,7,8,9,15]
- [2,3,4,5,6,7,8,9,15]
- 
- Toplamda 7 aşamada tamamlanmıştır.
