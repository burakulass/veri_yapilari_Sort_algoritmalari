# VERİ YAPILARI VE ALGORİTMALAR ALIŞTIRMALARI - Patika.dev

## Insertion Sort Projesi - Patika.dev

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  


A= [22,27,16,2,18,6]

### Cevap 1:
[2,27,16,22,18,6] 

[2,6,16,22,18,27]  

[2,6,16,22,18,27]  

[2,6,16,18,22,27]  


### Cevap 2:
+ Worst and Avarage case Big o gösterimi O(n^2)
+ Best case O(n)

### Cevap 3:
+ Best Case : [2,6,16,18,22,27]
+ Worst Case: [27,22,18,16,6,2]

## Cevap 4:
+ 18 Sayısı dizi sıralandıktan sonra ortada olduğu için AVARAGE CASE olur.

### Cevap 5:
B= [7,3,5,8,2,9,4,15,6]  

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6] 

[2,3,4,8,7,9,5,15,6] 

[2,3,4,5,7,9,8,15,6]  





## Merge Sort Projesi


C= [16,21,11,8,12,22]

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


C= [16,21,11,8,12,22] 


### Cevap 1:

[16,21,11], [8,12,22]

[16], [21,11]    ,      [8,12],    [22]

[16],   [11],[21]   ,   [8],[12],  [22]

[16],   [11,21]     ,   [8,12],    [22]

   [11,16,21]       ,      [8,12,22]


[8,11,12,16,21,22]


### Cevap 2:

Big-O gösterimi: O(nlogn)