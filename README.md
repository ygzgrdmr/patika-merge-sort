# patika-merge-sort


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

 - [16,21,11,8,12,22] verilen array i birer eleman kalana kadar her işlemde ikiye bölüyoruz
 -   [16,21,11]               [8,12,22]       
 -  [16]    [21,11]         [8]    [12,22]    
 -  [16]   [21] [11]        [8]   [12] [22] sonrasında tekrar birleşirme yapıyoruz ve birleştirirken sıralama yapılıyor
 -  [16]    [11,21]         [8]    [12,22]     
 -    [11,16,21]              [8,12,22]        
 -           [8,11,12,16,21,22] en sonunda sıralanmış array geliyor
 
 
 
 Big-O gösterimini yazınız.
 
  -O(nlogn)
