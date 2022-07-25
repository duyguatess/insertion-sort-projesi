# insertion-sort-projesi
SORU1-Sort türüne göre aşamalar.

[22,27,16,2,18,6]-n
[2,27,16,22,18,6]-(n-1)
[2,6,16,22,18,27]-(n-2)
[2,6,16,18,22,27]-(n-3)

SORU2-Big O gösterimi.
   Big-O= O(n^2)
   
SORU3-Time Complexity.
  Worst case = 1+..+(n-3)+(n-2)+(n-1)+n = O(n^2)
  Average case = O(n^2)
  Best case = O(n)

SORU4-18 sayısı hangi case?
   Dizi sıralandığında 18 sayısı ortada olduğu için Average case'dir.

SORU5-[7,3,5,8,2,9,4,15,6] Insertion Sort'a göre ilk 4 adımı.
   [2,3,5,8,7,9,4,15,6]
   [2,3,4,8,7,9,5,15,6]
   [2,3,4,5,7,9,8,15,6]
   [2,3,4,5,6,9,8,15,7]
