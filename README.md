# Veri-Yap-lar-ve-Algoritmalar-projeri
Insertion sort proje

## Insertion Sort Aşamaları

Verilen dizi: [22, 27, 16, 2, 18, 6]

1. İlk eleman (22) zaten sıralı kabul edilir.
   - [22, 27, 16, 2, 18, 6]

2. 27 elemanı zaten 22'den büyük olduğu için yer değiştirmez.
   - [22, 27, 16, 2, 18, 6]

3. 16 elemanını doğru yere yerleştirmek için kontrol ederiz:
   - 16, 27'den küçük olduğu için 27'nin yerine geçer.
   - 16, 22'den küçük olduğu için 22'nin yerine geçer.
   - [16, 22, 27, 2, 18, 6]

4. 2 elemanını doğru yere yerleştirmek için kontrol ederiz:
   - 2, 27'den küçük olduğu için 27'nin yerine geçer.
   - 2, 22'den küçük olduğu için 22'nin yerine geçer.
   - 2, 16'dan küçük olduğu için 16'nın yerine geçer.
   - [2, 16, 22, 27, 18, 6]

5. 18 elemanını doğru yere yerleştirmek için kontrol ederiz:
   - 18, 27'den küçük olduğu için 27'nin yerine geçer.
   - 18, 22'den küçük olduğu için 22'nin yerine geçer.
   - [2, 16, 18, 22, 27, 6]

6. 6 elemanını doğru yere yerleştirmek için kontrol ederiz:
   - 6, 27'den küçük olduğu için 27'nin yerine geçer.
   - 6, 22'den küçük olduğu için 22'nin yerine geçer.
   - 6, 18'den küçük olduğu için 18'in yerine geçer.
   - 6, 16'dan küçük olduğu için 16'nın yerine geçer.
   - [2, 6, 16, 18, 22, 27]

### Big-O Gösterimi

Insertion Sort algoritmasının Big-O notasyonu: `O(n^2)`

### Time Complexity

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için Average case kapsamına girer.

## Selection Sort İlk 4 Adım

Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

1. Adım:
   - Dizideki en küçük eleman 2'dir, 2 ile 7 yer değiştirir.
   - [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Adım:
   - Kalan dizideki en küçük eleman 3'tür, yer değiştirmeye gerek yok.
   - [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Adım:
   - Kalan dizideki en küçük eleman 4'tür, 4 ile 5 yer değiştirir.
   - [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Adım:
   - Kalan dizideki en küçük eleman 5'tir, 5 ile 8 yer değiştirir.
   - [2, 3, 4, 5, 7, 9, 8, 15, 6]
