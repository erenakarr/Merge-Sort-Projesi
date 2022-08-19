# Merge-Sort-Projesi
Veri Yapıları ve Algoritmalar dersi için açtığım 2. ödev reposu.


## Proje 2

[16,21,11,8,12,22] -> Merge Sort

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2.  Big-O gösterimini yazınız.

### Cevaplar:

1.  Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]

[16,21,11]____[8,12,22]

[16,21]___[11]____[8,12]___[22]

[16]__[21]___[11]____[8]__[12]___[22]

Bütün kümeler 1 adet sayıya sahip olduğu için artık karşılaştırma kısmına geçiyoruz.

[16]_[21]____[11]_____[8]_____[12]____[22]

[11,16,21]______[8]__[12]__[22]

[11,16,21]______[8,12,22]

...

[8,11,12,16,21,22]

2.  Big-O gösterimini yazınız.

O(n*(logn))
