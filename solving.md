# Insertion Sort Project

[22,27,16,2,18,6] -> Insertion Sort

## 1. Yukarıda verilen dizinin sort türüne göre aşamaları

1. temp = 22 &rarr; do nothing &rarr; [22,27,16,2,18,6]
2. temp = 27 &rarr; do nothing &rarr; [22,27,16,2,18,6]
3. temp = 16 &rarr; swap 16 and 27 &rarr; swap 16 and 22 &rarr; [16,22,27,2,18,6]
4. temp = 2 &rarr; swap 2 and 27 &rarr; swap 2 and 22 &rarr; swap 2 and 16 &rarr; [2,16,22,27,18,6]
5. temp = 18 &rarr; swap 18 and 27 &rarr; swap 18 and 22 &rarr; [2,16,18,22,27,6]
6. temp = 6 &rarr; swap 6 and 27 &rarr; swap 6 and 22 &rarr; swap 6 and 18 &rarr; swap 6 and 16 &rarr; [2,6,16,18,22,27]

## 2. Big-O gösterimi

1. (n * (n-1)) / 2 = O(n^2)

## 3. Time Complexity

Best case = O(n)
Avg.case = O(n^2)
Worst case = O(n^2)

## 4.

Dizi sıralandıktan sonra 18 sayısı worst case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. temp = 7 &rarr; do nothing &rarr; [7,3,5,8,2,9,4,15,6]
2. temp = 3 &rarr; swap 3 and 7 &rarr; [3,7,5,8,2,9,4,15,6]
3. temp = 5 &rarr; swap 5 and 7 &rarr; [3,5,7,8,2,9,4,15,6]
4. temp = 8 &rarr; do nothing &rarr; [3,5,7,8,2,9,4,15,6]