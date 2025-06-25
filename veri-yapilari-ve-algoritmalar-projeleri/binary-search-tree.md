# Binary Search Tree Projesi

## Soru:

Aşağıdaki dizinin Binary Search Tree (BST) aşamalarını yazınız:  
`[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`

## Cevap:

- **Root:** 7

- **5** → 7'den küçük → Soluna yerleşir.
- **1** → 7'den küçük → 5'ten küçük → 5'in soluna yerleşir.
- **8** → 7'den büyük → Sağında yerleşir.
- **3** → 7'den küçük → 5'ten küçük → 1'den büyük → 1'in sağına yerleşir.
- **6** → 7'den küçük → 5'ten büyük → 5'in sağına yerleşir.
- **0** → 7'den küçük → 5'ten küçük → 1'den küçük → 1'in soluna yerleşir.
- **9** → 7'den büyük → 8'den büyük → 8'in sağına yerleşir.
- **4** → 7'den küçük → 5'ten küçük → 1'den büyük → 3'ten büyük → 3'ün sağına yerleşir.
- **2** → 7'den küçük → 5'ten küçük → 1'den büyük → 3'ten küçük → 3'ün soluna yerleşir.

---

### Son Ağaç Yapısı:

                  7
                /   \
               5     8
              / \     \
             1   6     9
            / \
           0   3
              / \
             2   4

---

_Bu proje, Veri Yapıları ve Algoritmalar eğitimi kapsamında hazırlanmıştır._
