# MergeSort

     [16,21,11,8,12,22] Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1.  [16,21,11] [8,12,22]

2.  [16,21] [11]   [8,12] [22]

3.  [16] [21] [11]    [8] [12] [22]

4.  [16,21] [11]   [8,12] [22]

5.  [11,16,21]    [8,12,22]

6.  [8,11,12,21,22]

    Big-O gösterimini yazınız.
    
n her seferinde ikiye bölündüğü için 2ˣ=n x=logn 

her aşamada eleman sayısı kadar işlem yaptığımız için de n

O(nlogn)
