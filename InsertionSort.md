www.patika.dev

Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.
 
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Answers

1.
Algorithm starts with the 2nd element

22 27 | 16 2 18 6 => 1st step

16 < 27 and 16 < 22 so it will goes on top

16 22 27 | 2 18 6 => 2nd step

2 < 16, 22 and 27 so our new first element is 2

2 16 22 27 | 18 6 => 3rd step

same comparison processes between 18 and the other sorted elements so it goes between 16 and 22

2 16 18 22 27 | 6 => 4th step

same comparison processes between 6 and the other sorted elements so it goes between 2 and 18

2 6 16 18 22 27 => 5th and final step

2. 
As we can see, each element which starts 2nd is compared with the elements before it. Bigger elements shift to the right, smaller elements shift to the left.

3. 
 Worst case = O(n²) 
 Avarage case = O(n²)
 Best case = O(n)

4. 

2 6 16 18 22 27 
 
 18 is in the middle of the array which makes this case avarage. O(n²)

5. 
 
 7 3 5 8 2 9 4 15 6

 3 7 | 5 8 2 9 4 15 6 => 1st step
 
 3 5 7 | 8 2 9 4 15 6 => 2nd step
 
 3 5 7 8 | 2 9 4 15 6 => 3rd step
 
 2 3 5 7 8 9 | 4 15 6 => 4th step
