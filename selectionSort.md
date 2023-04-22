1.soru

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


2.Soru

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


1- 

Önce en düşük karakteri buluyoruz. ki kendisi 2 oluyor en başa getirdiğimiz için 22 ile
yer değiştiriyor.

2,27,16,22,18,6

Şimdi en baştaki karakterimiz en ufağı oldu, sırada ikinci karakteri yerleştirmek var.

2,6,16,22,18,27

Şimdi 3.sıraya ilk ikiden büyük ancak diğerlerinden küçük olan elemanı yerleştiriyoruz.

2,6,16,22,18,27

Şimdi 4.sıra

2,6,16,18,22,27

4 Adımda bitirmiş olduk ilk adımda n ikinci adımda n-1 üçüncü adımda n-2 kadar karakter kontrolü yaptık.

Big O Notation: n.(n+1)/2 = O(n^2)

Time Complexity: Average Case'dir.


2-

[7,3,5,8,2,9,4,15,6]

Önce en ufağı buluyoruz ve bulunduğu yerden ilk indis ile yerini değiştiriyoruz.

2,3,5,8,7,9,4,15,6

Şimdi aynı işlemi geri kalan indisler için yapıyoruz.

2,3,5,8,7,9,4,15,6

2,3,4,8,7,9,5,15,6

2,3,4,5,7,9,8,15,6

4.işlem sonunda listemiz bu şekilde gözükür.