# Insertion Sort Projesi

## Proje 1
**[22,27,16,2,18,6]** -> Insertion Sort

### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- **Adım 1:** [22, 27, 16, 2, 18, 6] (27 sağda kalır)
- **Adım 2:** [16, 22, 27, 2, 18, 6] (16 başa gelir)
- **Adım 3:** [2, 16, 22, 27, 18, 6] (2 en başa gelir)
- **Adım 4:** [2, 16, 18, 22, 27, 6] (18 araya girer)
- **Adım 5:** [2, 6, 16, 18, 22, 27] (6 araya girer)

### 2. Big-O gösterimini yazınız.
O(n^2)

### 3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Sıralı dizi: [2, 6, 16, 18, 22, 27]
18 sayısı dizinin ortasında bulunduğu için **Average Case** kapsamına girer.

---

## Proje 2 (Selection Sort)
**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımı:

- **Adım 1:** [2, 3, 5, 8, 7, 9, 4, 15, 6] (En küçük 2 bulundu, 7 ile değişti)
- **Adım 2:** [2, 3, 5, 8, 7, 9, 4, 15, 6] (İkinci en küçük 3, zaten yerinde)
- **Adım 3:** [2, 3, 4, 8, 7, 9, 5, 15, 6] (Üçüncü en küçük 4 bulundu, 5 ile değişti)
- **Adım 4:** [2, 3, 4, 5, 7, 9, 8, 15, 6] (Dördüncü en küçük 5 bulundu, 8 ile değişti)
