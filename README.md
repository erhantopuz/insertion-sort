Selection Sort Projesi


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması 
Worst case: Aradığımız sayının sonda olması 
Best case: Aradığımız sayının dizinin en başında olması.



<!-- sondan başa doğru kontrol edip küçüğü ön sıraya alır-->

Big o Notation O(n^2)

1.adım [16,22,27,2,18,6]
2.adım [2,16,22,27,18,6]
3.adım [2,6,16,22,27,18]
4.adım [2,6,16,18,22,27] 

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için Average Case durumu gerçekleşmiş olur.






[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

<!--sırlalamak için rakamları birbirleriyle yer değiştiriyor, önce ilk birim için değişim yapıp sırayla gidiyor-->

1.adım [2,3,5,8,7,9,4,15,6]
2.adım [2,3,4,8,7,9,5,15,6]
3.adım [2,3,4,5,7,9,8,15,6]
4.adım [2,3,4,5,6,9,8,15,7]
