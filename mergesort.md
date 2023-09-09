# Proje 2

### [16, 21, 11, 8, 12, 22] -> Merge Sort türüne göre aşamaları

1. aşama Dizi [16, 21, 11] ve [8, 12, 22] olarak ikiye bölünür.
2. aşama [16, 21, 11] dizisi tekrar ikiye bölünür. --> [16] [21, 11]
3. aşama [21, 11] dizisi tekrar ikiye bölünür. --> [16], [21], [11]
5. aşama [21] ve [11] sıralanıp birleştirilir. --> [11, 21]
6. aşama [16] ve [11, 21] dizilerindeki ilk olarak 16 ve 11 karşılaştırılır, küçük olan sayı birleşecekleri yeni diziye yazılır. --> [11, , ]
7. aşama 16 ve 21 karşılaştırılır ve yeni diziye yazılır. --> [11, 16, 21]
8. aşama [8, 12, 22] dizisi tekrar ikiye bölünür. --> [8], [12, 22]
9. aşama [12, 22] dizi tekrar ikiye bölünür. --> [12], [22]
10. aşama [12], [22] dizileri sıralanarak birleştirilir. --> [12, 22]
11. aşama [8] ve [12, 22] dizisinde 8 ve 12 sayıları karşılaştırılır, küçük olan sayı birleşecekleri yeni diziye yazılır. --> [8, , ]
12. aşama çoktan sıralanmış olan [12, 22] dizisi yeni diziye yazılır. --> [8, 12, 22]
13. aşama çoktan sıralanmış olan bu iki dizinin ([11, 16, 21] ve [8, 12, 22]) en küçük sayıları teker teker karşılaştırılarak yeni diziye yazılır, sıralanır. --> [8, 11, 12, 16, 21, 22]

Aşamalar sonucunda sıralama: [8, 11, 12, 16, 21, 22]

---

### Big-O gösterimi

Merge Sort'un Big-O gösterimi --> O(nlogn).
