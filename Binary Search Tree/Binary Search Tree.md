# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---
![](/Merge%20Sort/Merge%20Sort.png)

---

- Dizinin başında olduğu için root 7'dir.
- 7'den küçük olduğu için 7'nin soluna 5 yazılır.
- 1, 7 ve 5'ten küçük olduğu için 5'in soluna yazılır.
- 7'den büyük olduğu için 7'nin sağına 8 yazılır.
- 3, 1'in sağına yazılır çünkü 7 ve 5'ten küçük ama 1'den büyüktür.
- 6, 7'den küçük 5'ten büyük olduğu için 5'in sağına yazılır.
- 0, 7, 5 ve 1'den küçük olduğu için 1'in soluna yazılır.
- 9, 7 ve 8'den büyük olduğu için 8'in sağına yazılır.
- 4, 7 ve 5'ten küçük ama 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır.
- 2, 7, 5, 3'ten küçük ama 1'den büyük olduğu için 3'ün soluna yazılır.