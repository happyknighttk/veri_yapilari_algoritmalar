# Proje 1
### [22, 27, 16, 2, 18, 6] dizisinin Insertion Sort'a göre aşamaları

1. aşama [*22, 27, 16, 2, 18, 6] --> 22'nin solunda bir sayı olmadığı için sıralanmış olarak algılar.
2. aşama [22, *27, 16, 2, 18, 6] --> 27, 22'den büyük olduğu için değişim olmaz.
3. aşama [*16, 22, 27, 2, 18, 6] --> 16, 27 ve 22'den küçük olduğu için sırasıyla yer değiştirir.
5. aşama [*2, 16, 22, 27, 18, 6] --> 2, 27, 22 ve 16'dan küçük olduğu için sırasıyla yer değiştirir.
6. aşama [2, 16, *18, 22, 27, 6] --> 18, 27 ve 22'den küçük olduğu için sırasıyla yer değiştirir.
7. aşama [2, *6, 16, 18, 22, 27] --> 6, 27, 22, 18 ve 16'dan küçük olduğu için sırasıyla yer değiştirir.

Sonuç olarak aşağıdaki şekilde sıralanmıştır.
- [2, 6, 16, 18, 22, 27]

---

### Big-O gösterimi

Average ve worst-case Big-O gösterimi --> O(n^2).

---

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı

- [2, 6, 16, 18, 22, 27]
Average case: Aradığımız sayının ortada olması

---

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını

1. adım [*2, 3, 5, 8, 7, 9, 4, 15, 6] --> 2, 7'den küçük olduğu için yer değiştirir. 
2. adım [2, *3, 5, 8, 7, 9, 4, 15, 6] --> 3'ün sağında 3'ten küçük sayı olmadığı için yer değiştirmez.
3. adım [2, 3, *4, 8, 7, 9, 5, 15, 6] --> 4, 5'ten küçük olduğu için yer değiştirir.
4. adım [2, 3, 4, *5, 7, 9, 8, 15, 6] --> 5, 8'den küçük olduğu için yer değiştirir.

4 adımda aşağıdaki şekilde sıralanmıştır.
- [2, 3, 4, 5, 7, 9, 8, 15, 6]
