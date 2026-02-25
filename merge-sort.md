# Merge Sort Projesi

**[16,21,11,8,12,22]** -> Merge Sort

### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Merge Sort diziyi sürekli ikiye bölüp, en küçük parçadan başlayerek sıralı birleştirmektir.

- **Bölme Aşaması:**
    - [16,21,11] - [8,12,22]
    - [16] - [21,11] --- [8] - [12,22]
    - [16] - [21] - [11] --- [8] - [12] - [22]
- **Birleştirme (Merge) Aşaması:**
    - [16] - [11,21] --- [8] - [12,22]
    - [11,16,21] --- [8,12,22]
    - **Sonuç:** [8, 11, 12, 16, 21, 22]

### 2. Big-O gösterimini yazınız.
Recursive (özyinelemeli) bir fonksiyon olduğu için ve her adımda dizi ikiye bölündüğü için:
**O(nlogn)**
