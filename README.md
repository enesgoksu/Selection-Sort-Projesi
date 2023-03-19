# Selection-Sort-Projesi
Selection Sort Projesi Çalışması

## Proje 1
### [22,27,16,2,18,6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case' lerden hangisinin kapsamına girer?
4. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Çözümler
1. ```
    [22,27,16,2,18,6] -> Insertion Sort
    [2,27,16,22,18,6] -> min = 2, change 2 and 22
    [2,6,16,22,18,27] -> min = 6, change 6 and 27
    [2,6,16,22,18,27] -> min = 16, no need to change
    [2,6,16,18,22,27] -> min = 18, change 18 and 22
    [2,6,16,18,22,27] -> min = 22, no need to change
    [2,6,16,18,22,27] -> min = 27, no need to change(Finish)
    ```
2. ```
    1. -> n
    2. -> n-1
    3. -> n-2
    .
    .
    .
    n-1 -> 1
    O(n**2)
    ```
3. ```
    Dizi Sıralandıktan sonra([2,6,16,18,22,27]) 18 sayısı Average Case' dir.
    ```
4. ```
    [7,3,5,8,2,9,4,15,6] -> Insertion Sort
    [2,3,5,8,7,9,4,15,6] -> min = 2, change 2 and 7
    [2,3,5,8,7,9,4,15,6] -> min = 3, no need to change
    [2,3,4,8,7,9,5,15,6] -> min = 4, change 4 and 5
    [2,3,4,5,7,9,8,15,6] -> min = 5, change 5 and 8
    ```
    
    
 


