# merge_sort_project-ilbaba
Merge Sort Projesi - Patika - Ilgar Babashli
* [16,21,11,8,12,22] -> Merge Sort
# _Q1_ 
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
# _Ans_
 1) [16,21,11,8,12,22] 
 2) [16,21,11] & [8,12,22]
 3) [16,21] - [11] & [8,12] - [22]
 4) [16] - [21] - [11] & [8] - [12] - [22]
 5) [11,16,21] & [8,12,22]
 6) [8,11,12,16,21,22]
# _Q2_ 
Big-O gösterimini yazınız.
# _Ans_
 2^x = n --> logn = x
 
 n-1 kere sorgulama olduğu için sorgu sayısının Big O Notation'u - O(n)
 
 Her defasında 2'ye bölerek ilerlediğimiz için ilerleme Big O Notation'u - O(logn)
 
 Tüm işlemlerin Big-O'su - O(nlogn)
