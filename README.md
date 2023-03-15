# Selection-Sort-Algoritma-Projeleri
patika.dev algoritma projeleri

*Proje 1 [22,27,16,2,18,6] -> Insertion Sort Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması.

Çözüm 1: 1. aşama en küçük elemanı buluruz ve birinci sıradaki elemanla yerlerini değiştiririz. Dizimiz : [22,27,16,2,18,6].

1.aşama: [2,27,16,22,18,6] olur. 
2.aşama: [2,6,16,22,18,27] olmalı. Çünkü bu diziyi sıralamalıyız. Bu yüzden 6 ile 2. elemanın yani 27 ile yerini değiştiririz. 
3.aşama: [2,6,16,22,18,27] 16 doğru yerde olduğu için yerini değiştirmeyiz. 
4.aşama: [2,6,16,18,22,27] 18 ile 4. eleman yani 22 ile yerlerini değiştiririz. 

Big-O gösterimi: O(n^2)
