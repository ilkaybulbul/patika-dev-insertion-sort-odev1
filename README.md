# patika-dev-insertion-sort-odev1
** Yapılacaklar

** Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**Cevaplar

-Insertion sort aşamaları
[ . ] ile ayrılmış kısımlar sıralanmış aralığı temsil eder.

    * [7] 3 5 8 2 9 4 15 6
    * [3 7] 5 8 2 9 4 15 6
    * [3 5 7] 8 2 9 4 15 6
    * [3 5 7 8] 2 9 4 15 6
    * [2 3 5 7 8] 9 4 15 6
    * [2 3 5 7 8 9] 4 15 6
    * [2 3 4 5 7 8 9] 15 6
    * [2 3 4 5 7 8 9 15] 6
    * [2 3 4 5 6 7 8 9 15]


- Big O gösterimi = O(n^2)

   * [2 3 4 5 6 7 8 9 15] 18 => Dizi sıralandıktan sonra 18 sayısı worst case kapsamına girmektedir.

-

   * [7] 3 5 8 2 9 4 15 6
   * [3 7] 5 8 2 9 4 15 6
   * [3 5 7] 8 2 9 4 15 6
   * [3 5 7 8] 2 9 4 15 6
