# Merge Sort Projesi

---

## Soru 1:

Aşağıdaki dizinin Merge Sort’a göre aşamalarını yazınız:  
`[16, 21, 11, 8, 12, 22]`

## Cevap:

Merge Sort, diziyi sürekli ikiye bölerek tek eleman kalana kadar ayırır, sonra sıralı olarak birleştirir.

### Aşamalar:

- Başlangıç: `[16, 21, 11, 8, 12, 22]`

- Bölme 1: `[16, 21, 11]` ve `[8, 12, 22]`

- Bölme 2: `[16]` `[21, 11]` ve `[8]` `[12, 22]`

- Bölme 3: `[16]` `[21]` `[11]` ve `[8]` `[12]` `[22]`

- Birleştirme 1: `[16]` `[11, 21]` ve `[8]` `[12, 22]`
- Birleştirme 2: `[16, 11, 21]` ve `[8, 12, 22]`

- Son Birleştirme: `[8, 11, 12, 16, 21, 22]`

---

## Soru 2:

Merge Sort algoritmasının Big-O gösterimini yazınız.

## Cevap:

- Best Case: **O(n log n)**
- Average Case: **O(n log n)**
- Worst Case: **O(n log n)**

Merge Sort, her durumda diziyi logaritmik şekilde bölüp, doğrusal zamanda birleştirdiği için sabit olarak O(n log n) zaman karmaşıklığına sahiptir.

---

_Bu çalışma, Veri Yapıları ve Algoritmalar eğitimi kapsamında hazırlanmıştır._
