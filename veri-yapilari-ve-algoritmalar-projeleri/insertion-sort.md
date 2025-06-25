# Veri Yapıları ve Algoritmalar Projesi

---

## Insertion Sort Projesi

### Soru 1:

Aşağıdaki dizinin Insertion Sort’a göre aşamalarını yazınız:  
`[22, 27, 16, 2, 18, 6]`

### Cevap:

- Başlangıç: `[22, 27, 16, 2, 18, 6]`
- Adım 1: `27` zaten `22`den büyük, değişiklik yok.  
  `[22, 27, 16, 2, 18, 6]`
- Adım 2: `16` ile karşılaştır:  
  `16 < 27` → yer değiştir  
  `16 < 22` → yer değiştir  
  `[16, 22, 27, 2, 18, 6]`
- Adım 3: `2` ile karşılaştır:  
  `2 < 27`, `22`, `16` → başa yerleşir  
  `[2, 16, 22, 27, 18, 6]`
- Adım 4: `18` ile karşılaştır:  
  `18 < 27` → swap  
  `18 < 22` → swap  
  `18 > 16` → dur  
  `[2, 16, 18, 22, 27, 6]`
- Adım 5: `6` ile karşılaştır:  
  `6 < 27`, `22`, `18`, `16` → yer değiştir  
  `6 > 2` → dur  
  `[2, 6, 16, 18, 22, 27]`

---

### Soru 2:

Bu algoritmanın Big-O gösterimini yazınız.

### Cevap:

- Best Case (dizi zaten sıralı): **O(n)**
- Average Case: **O(n²)**
- Worst Case (dizi ters sıralı): **O(n²)**

---

### Soru 3:

Dizi sıralandıktan sonra aradığımız sayı 18, aşağıdaki durumlardan hangisine girer?

- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması.

### Cevap:

18 sayısı dizide ortada olduğundan **Average case** kapsamına girer.

---

## Selection Sort Projesi

### Soru 4:

Aşağıdaki dizinin Selection Sort’a göre ilk 4 adımını yazınız:  
`[7, 3, 5, 8, 2, 9, 4, 15, 6]`

### Cevap:

- Başlangıç: `[7, 3, 5, 8, 2, 9, 4, 15, 6]`
- Adım 1: En küçük sayı `2`, 7 ile yer değiştir.  
  `[2, 3, 5, 8, 7, 9, 4, 15, 6]`
- Adım 2: 2. indexten sonra en küçük `3`, zaten 2. sırada, değişim yok.  
  `[2, 3, 5, 8, 7, 9, 4, 15, 6]`
- Adım 3: 3. indexten sonra en küçük `4`, 5 ile yer değiştir.  
  `[2, 3, 4, 8, 7, 9, 5, 15, 6]`
- Adım 4: 4. indexten sonra en küçük `5`, 8 ile yer değiştir.  
  `[2, 3, 4, 5, 7, 9, 8, 15, 6]`

---

_Bu çalışma, Veri Yapıları ve Algoritmalar eğitimi kapsamında hazırlanmıştır._
