# Insertion Sort 

Insertion Sort algoritması genel olarak araya ekleme sıralama algoritması olarak bilinmektedir. Dizideki sıralama karışıktır. Aslında diğer sıralama algoritmalarına göre daha kolaydır.
 
Aslında fark etmeden kart oyunlarında bu algoritmayı kullanıyoruz :))

1-Proje de bize verilen dizi

[22,27,16,2,18,6]

İlk başta en soldan küçük değeri arama işlemi yapıyoruz. Arama yaptıkta bulduğumuz küçük değeri en başa alıyoruz.

1.Adım = Büütn dizi arasında en küçük sayıyı bulma ve baştaki ile yer değiştirme.

[**2**,27,16,**22**,18,6]

2.Adım = İkinci en küçük sayıyı bulma.

[2,**6**,16,22,18,**27**]

3.Adım

[2,6,16,**18**,**22**,27]

Dizinin son hali:

 - [2,6,16,18,22,27]

Insertion Sort algoritması kullanılarak 3 adımda dizi küçükten büyüğe sıralanmıştır.


2-Big-o Gösterimi

- Best Case için:

   - O(N)

 - Average Case için:

   - O(N^2)

  - Worst Case için:
   
    - O(N^2)

3- Time Complexity:

 - Average Case: Aradığımız sayının ortada olmasıdır.

   - Worst Case: Aradığımız sayının sonda olmasıdır.
    
      - Best Case:  Aradığımız  sayının  dizinin en başında  olmasıdır.


4- Dizi sıralandıktan sonra 18 sayısı **Average Case** kapsamına girer çünkü aradığımız sayı dizinin ortasındadır.


-[7,3,5,8,2,9,4,15,6] dizisinin ilk dört adımını yazınız.

1.Adım = [**2**,3,5,8,**7**,9,4,15,6]

2.Adım = [2,3,**4**,8,7,9,**5**,15,6]

3.Adım = [2,3,4,**5**,7,9,**8**,15,6]

4.Adım = [2,3,4,5,**6**,9,8,15,**7**]


[Patika.dev](https://www.patika.dev/)

[Kodluyoruz](https://kodluyoruz.org/tr/kodluyoruz/)












