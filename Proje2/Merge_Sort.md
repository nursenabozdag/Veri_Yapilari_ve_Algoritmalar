## Merge Sort

Merge Sort algoritması bir dizinin parçalanması işlemidir.

Parçalama işlemleri daima ikili gruplarla olur. Böylece dizi parçalara ayrılarak zaman karmaşıklığı logaritmik zamana iner.


Bize verilen dize:

[16,21,11,8,12,22]

### Merge Sort Algortimasının Aşamaları:

1.Aşama

-  Öncelikle dizi orta indexten ikili grup şeklinde ayrılır.

- [16,21,11,8,12,22]
        
     
   [16,21,11]   [8,12,22]

2.Aşama

Orta indexinden parçalanan dizinin alt gruplarını da parçalama işlemidir.

[16] , [21,11] 

[8,12], [22]

3.Aşama

Parçaladığımız dizinin tek bir elamanı kalana kadar parçalama işlemidir.

[16], [21], [11]

[8] , [12], [22]

4.Aşama


Parçaladığımız diziyi şimdi birleştireceğiz. Fakat birleştirme işleminde bir kıyaslama yapılacaktır.

[16],[21],[11] dizisinde karşılaştırma yaparak en küçük elemanı en başa alıp küçükten büyüğe doğru sıralama yaparak birleştiriyoruz.

  - [11,16,21]

Aynı şekilde [8],[12],[22] dizisinde aynı adımları uyguluyoruz ve birleştiriyoruz.

- [8,12,22]

5.Aşama

Yapılan aşamalarda elde ettiğimiz 2 adet diziye 4.aşamayı uygulayarak elimizdeki diziye merge sort algortitması uygulamış oluyoruz.

Dizileri birleştirirken küçükten büyüğe doğru sıralama yapıyoruz.

Dizinin son hali:

- [8,11,12,16,21,22] ' dir.

Merge Sort Algoritmasının aşamalarının gösterimi:

            [16,21,11,8,12,22]

         [16,21,11]     [8,12,22]

       [16]  [21,11]    [8,12]  [22]

       [16] [21] [11]   [8] [12] [22]

           [11,16,21]   [8,12,22]

             [8,11,12,16,21,22]


Kısaca özetlersek Merge Sort Algoritması bir böl parçala fethet tekniğine benzetebiliriz.


### Big-O Gösterimi


Merge Sort algoritmasında Big-O gösterimi

- O(n.logn)





 
