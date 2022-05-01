# Insertion-Sort-Project
Patika-Veri Yapıları ve Algoritmalar-Proje1

** Soru-1 **
[22,27,16,2,18,6] -- n
[2,27,16,22,18,6] -- n-1 -- 2 ile 22 yer değiştirdi
[2,6,16,22,18,27] -- n-2 -- 6 ile 27 yer değiştirdi
[2,6,16,22,18,27] -- n-3 -- 16 zaten en küçük 3 üncü sayı olduğu için değişiklik yapılmadı
[2,6,16,18,22,27] -- n-4 -- 18 ile 22 yer değiştirdi.
[2,6,16,18,22,27] -- n-5 -- 22 zaten en küçük 5 inci sayı olduğu için değişiklik yapılmadı
[2,6,16,18,22,27] -- 1 -- en son sayıya ulaştığımız için sorting tamamlandı

** Soru-2 **
Insertion Sort'un Big O gösterimi: O(n^2)

** Soru-3 **
Best Case: Dizideki sayıların zaten istendiği şekilde sıralı olduğu için algoritma sadece dizideki her elemandan bir kez geçer ve o elemanın doğru yerde olduğunu doğrular. Dolayısıyla best case: N olacaktır.
Worst Case: N^2. Dizideki elemanların istenilenin tam tersi şeklinde olması halinde bu durum oluşacaktır.
Average Case: Worst Case ile Best Case'in ortalamasını aldığımızda N^2 olarak buluruz.

** Soru-4 **
18 sayısı average case kapsamına girmektedir.

** Soru-5 **
[7,3,5,8,2,9,4,15,6] -- n
[2,3,5,8,7,9,4,15,6] -- n-1 -- 2 ile 7 yer değiştirdi.
[2,3,5,8,7,9,4,15,6] -- n-2 -- 3 zaten en küçük ikinci sayı olduğu için değişiklik yapılmadı
[2,3,4,8,7,9,5,15,6] -- n-3 -- 4 ile 5 yer değiştirdi.
[2,3,4,5,7,9,8,15,6] -- n-4 -- 5 ile 8 yer değiştirdi.
