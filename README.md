# Patika-Projeleri


# PROJE 1  

[22,27,16,2,18,6] -> Insertion Sort 


                                     [22,27,16,2,18,6]      n
Önce küçük elamanı bul yer değiştir  [2, 27, 16, 22, 18, 6] n-1
Küçük elaman                         [2, 6, 16, 22, 18, 27] n-2
Elaman aynı kaldı                    [2, 6, 16, 22, 18, 27] n-3         hepsi O(n^2)
                                     [2, 6, 16, 18, 22, 27] n-4
Elemanlar aynı işlem tamam           [2, 6, 16, 18, 22, 27] n-5      


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


1. [2,3,5,8,7,9,4,15,6] 
2. [2,3,5,8,7,9,4,15,6] 
3. [2,3,4,8,7,9,5,15,6] 
4. [2,3,4,5,7,9,8,15,6] 


# PROJE 2


[16,21,11,8,12,22] -> Merge Sort           

[16,21,11]    -      [8,12,22]               

[16] - [21,11]    -   [8] - [12, 22]           

[16] - [21]  -[11]  -  [8]  -  [12]  - [22]                       

[16] - [11,21] - [8] - [12,22]               

[11, 16, 21] - [8, 12, 22]                 

[8, 11, 12, 16, 21, 22]                     


# PROJE 3 

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

                                 7 'yi root alalım. 
                               /   \
                              5     8
                             / \     \ 
                             1  6     9
                            / \
                            0  3
                              / \
                              2  4
