# Veri-Yapilari-ve-Algoritmalar

## Patika.dev de veri yapıları ve algoritmalar için projeler

## Proje 1

[22,27,16,2,18,6] -> Insertion Sort

- 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- 2. Big-O gösterimini yazınız.
- 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

CEVAPLAR

1.  -> Insertion Sort

    - [22,27,16,2,18,6]
    - [2,27,16,22,18,6]
    - [2,6,16,22,18,27]
    - [2,6,16,22,18,27]
    - [2,6,16,18,22,27]

2.  -> Insertion Sorta göre sıraladık

    - [22,27,16,2,18,6] n tane sorgu
    - [2,27,16,22,18,6] n-1
    - [2,6,16,22,18,27] n-2
    - [2,6,16,22,18,27] n-3
    - [2,6,16,18,22,27] 1

    Kaç işlem yaptığımızı bulmak için 1+(n-3)+(n-2)+(n-1)+n. => ( n.(n+1))/2 yani (n^2+n)/2
    Big-O notation da domine edeni yani en büyüğü alıyoruz yani O(n^2) oluyor.

3.  Time Complexity:
    - Average case: O(n^2)
    - Worst case:O(n^2)
    - Best case: O(n)
4.  Aradığımız 18 sayısı arrayin ortasında yer almaktadır. Avarage case kapsamına girer

5.  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
    - [7,3,5,8,2,9,4,15,6] 1. Adım hepsini tek tek incele en küçüğü bul
    - [2,3,5,8,7,9,4,15,6] 2. Adım en küçüğü bulup başa yaz sonraki en küçüğü bul
    - [2,3,5,8,7,9,4,15,6] 3. Adım 2. Sıradaki en küçük olduğu için değişiklik yapmadan yaz diğer adıma geç
    - [2,3,4,8,7,9,5,15,6] 4. Adım ilk 2 sırayı bulmuştuk zaten, sonraki en küçüğü bul ve 3 sırayla bulduğun yeri değiştir.
