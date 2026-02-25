# Binary Search Tree Projesi

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamaları:

- **Root 7'dir.**
- 5, 7'den küçük olduğu için soluna eklenir.
- 1, 5'ten küçük olduğu için soluna eklenir.
- 8, 7'den büyük olduğu için sağına eklenir.
- 3, 1'den büyük olduğu için sağına eklenir.
- 6, 5'ten büyük olduğu için sağına eklenir.
- 0, 1'den küçük olduğu için soluna eklenir.
- 9, 8'den büyük olduğu için sağına eklenir.
- 4, 3'ten büyük olduğu için sağına eklenir.
- 2, 3'ten küçük olduğu için soluna eklenir.

### Ağaç Yapısı:

```text
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
