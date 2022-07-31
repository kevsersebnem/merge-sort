# merge-sort
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

Elemanları daha kolay sıralayabilmek için küçük gruplara ayırıp kendi aralarında sıralayıp sonra tekrardan sıralıyoruz. 


1. basamak:             [16 21 11]           [8 12 22]

2. basamak: [16 21]           [11]           [8]              [12 22]

3. basamak: [16]    [21]      [11]           [8]      [12]       [22]

4. basamak: [16 21]           [11]           [8]               [12 22]

5. basamak:             [11 16 21]           [8 12 22]

6. basamak:                   [8 11 12 16 21 22]

2. Big-O gösterimi = O(nlogn)


Patika hesabım: https://app.patika.dev/kevsersebnem









