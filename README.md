# mergesortodevi
merge sort ödevi

# Sorular 
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

# Cevaplar
1. *Veri dizisini, her adımda paraçalara ayırıp tek eleman kalıncaya kadar ikiye bölüp, daha osnra her iki parçayı her adımda sıralayarak birleştiririz.*
   - [16,21,11][8,12,22]
   - [16,21][11][8,12][22]
   - [16][21][11][8][12][22]
   - [16,21][8,11][12,22]
   - [8,11,16,21][12,22]
   - [8,11,12,16,21,22]

<br>

2. *Dizi hep ikiye bölünmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından Big O Notation O(n.logn) olacaktır.*
