# Insertion Sort Projesi

**Soru:** 
[22,27,16,2,18,6] -> Insertion Sort gösterimi yapınız.

**Çözüm:**
```
                    (average)
- [2,27,16,22,18,6] (worst)
- [2,6,16,22,18,27] (best)
- [2,6,16,18,22,27] (best)
```

**Big O Gösterimi:**
O(n)

***Açıklama:*** Insertion Sort yönteminin worst case'i "O(n^2)"dir ancak bu örnekte worst yada best case değil, average case'i görmekteyiz. 
n=6 olan bu durumda toplam x=3 adımda sıralama işlemi bitmiştir ki bunu "n=x-3" şeklinde ifade edebiliriz. buradaki -3 ifadesi büyük arrayler içinde anlamsız kalacağından Big O Gösterimimiz **"O(n)"** olacaktır.

***Best Case:*** Algoritmanın çalışabileceği en hızlı senaryodur.

***Worst Case:*** Algoritmanın çalışabilmesi için en yavaş senaryodur.

***Average Case:*** Algoritmanın pratikte karşılaşması en olası senaryodur.
