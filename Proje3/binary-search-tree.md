### Binary Search Tree

Binary Seaarch Tree ikili ağaç yapısı olarakta bilinmektedir.

Binary Search Tree veri yapılarından biridir ve bu veri yapısının en temel birimi node'dır.

Node'lar arasında bağlantılar bulunmaktadır ve her biri node'la en fazla iki boğum bağlanabilmektedir.

- Binary Search Tree de en üstte bulunan node **Root** olarak adlandırılır.

- Root'tan küçük değere sahip olan node'lar Root'un sol tarafında yer alır.

- Root'tan büyük değere sahip olan node'lar ise Root'un sağ tarafında yer alır.


Root değeri dizinin başında ki değerdir.

Proje içindeki dizimiz [7,5,1,8,3,6,0,9,4,2] 



#### Binary Search Tree Aşamaları


Dizinin en başında ki değer 7 olduğu için bizim dizinin root değeri 7 dir.

1- Root = x = 7 . Root değerimizi ağacın en başına yazarız.

                   7

2- Dizi içindeki 2.elamana bakarız eğer 7 den büyük ise root'un sağ tarafına, küçük ise sol tarafına yazılacaktır.  5<7 olduğuna göre;

               7
             /
            5

3- İlk olarak 1<7 küçük olduğu için root'un sol tarafında yazılır. 1<5 olduğu için 1 değeri 5'in sol tarafına yazılır.

                7
               / 
              5
             / 
            1

4- 8 değeri 7 den büyük olduğu için root'un sağ tarafına yazılır.

                7
               /  \
              5    8 
             /
            1    

5- 3 değeri 7 den küçük olduğu için sol tarafa gider ve en sondaki node 1 olduğu için ve 3 değeri 1 den büyük olduğu için, 3 değeri 1 değerinin sağ tarafına yazılır.

                 7
                / \
               5   8
             / 
            1
              \
               3


6- 6 değeri 7 den küçük olduğu için root'un sol tarafına yazılır, 6 değeri 5'ten büyük olduğu için 5 değerinin sağ tarafına yazılır.


                  7
                /  \
               5    8
             /  \
            1    6
              \
               3

7- 0 değeri 7 den küçük olduğu için root'un sol tarafına yazılır, 0 değeri 1'den küçük olduğu için 1 değerinin sol tarafına yazılır.   



                  7
                /  \
               5    8
             /  \
            1    6
           /  \
          0    3

8- 9 değeri 7'den büyük olduğu için root'un sağ tarafına yazılır, 9 değeri 8'den büyük olduğu için 8 değerinin sağ tarafına yazılır.


                  7
                /   \
               5     8
             /  \     \
            1    6     9
           /  \
          0    3

9- 4 değeri 7 den küçük olduğu için root'un sol tarafına yazılır, 4 değeri 3'den büyük olduğu için 3 değerinin sağ tarafına yazılır.

                  7
                /   \
               5     8
             /  \     \
            1    6     9
           /  \
          0    3
                 \
                  4

10- 2 değeri 7 den küçük olduğu için root'un sol tarafına yazılır,2 değeri 3'den küçük olduğu için 3 değerinin sol tarafına yazılır.

                  7
                /   \
               5     8
             /  \     \
            1    6     9
           /  \
          0    3
              /  \
             2     4


Binary Search Tree algoritması bu şekildedir.






