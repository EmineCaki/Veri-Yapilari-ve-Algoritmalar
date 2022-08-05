Proje 2
[16,21,11,8,12,22] -> Merge Sort
• Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
• Big-O gösterimini yazınız.

CEVAPLAR

1.                                                                 [16,21,11,8,12,22]
                                                  [16,21,11]                                  [8,12,22]
                                           [16,21]          [11]                         [8,12]          [22]
                                     [16]        [21]         [11]                   [8]       [12]        [22]
                                           [16,21]          [11]                         [8,12]          [22]
                                                  [11,16,21]                                  [8,12,22]
                                                                   [8,11,12,16,21,22]

2.                2^X  =   n     logn=x   ,
                  Her adımda O(n) ise
                  Big-O    =>     O(nlogn)  olur.
