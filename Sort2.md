# Merge Sort

[16, 21, 11, 8, 12, 22] 

[16, 21, 11] ve  [8, 12, 22]

[16, 21] ile [11]  ve [8, 12] ile [22]

[16] [21] [11] ve [8] [12] [22]

[16, 21] ile [11] ve [8, 12] ile [22]

[11, 16, 21] ve  [8, 12, 22]

[8, 11, 12, 16, 21, 22]

Dizi sürekli ikiye bölünüyor. Böylelikle en fazla log2(n) kere bölme işlemi yapılmış oluyor. Her bölünmüş dizinin Merge işlemi içinde n işlem yapıldığı için bu algoritmanın karmaşıklık maliyeti Big-O(nlogn) olur.