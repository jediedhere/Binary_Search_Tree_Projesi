# Binary_Search_Tree_Projesi
# 1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Öncelikle root belirlemeliyiz root = 6 olsun.
```
    1.  7 eklersek
         6
          \
           7
    2. 5 eklersek
       6
     /  \
    5    7
    3.  1 eklersek
       6
     /  \
    5    7
   /
  1
    4.  8  eklersekk
       6
     /  \
    5    7
   /      \
  1        8
    5.   3 eklersek
       6
     /  \
    5    7
   /  \    \
  1    3    8
    6.    0 eklersek
       6
     /  \
    5    7
   /  \    \
  1    3    8
 /
0
    7.    9 eklersek
         6
       /  \
      5    7
     /  \    \
    1    3    8
   /           \
  0             9
    8.    4 eklersek
         6
       /  \
      5    7
     /  \    \
    1    3    8
   /      \    \
  0        4    9
     9.    2 eklersek
         6
       /  \
      5    7
     /  \    \
    1    3    8
   / \    \    \
  0   2    4    9
```
Bu şekilde olacaktır. Burada sayıları büyüklük küçüklük kıyaslamasına göre yerleştiriyoruz. eğer  sayı büyükse sağa küçükse sola yazılmalıdır.
