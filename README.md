# Merge-Sort
Kodluyoruz eğitim kapsamında merge-sort ödev
Proje 2 [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

         [16,21,11,8,12,22]
        [16,21,11] [8,12,22]
     [16] [21,11]  [8] [12,22]
    [16] [21] [11]  [8] [12] [2]
     [16] [11,21]  [8] [2,12]
        [11,16,21]  [2,8,12]
         [2,8,11,12,16,21]

         o(n) -> o(nlogn)
