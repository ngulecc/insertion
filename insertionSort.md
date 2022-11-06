# Insertion Sort Projesi

## Proje 1

[22,27,16,2,18,6] Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız
3. Time Complexity :Avarage Case : Aradığımız sayının ortada olması, Worst Case : Aradığımız sayının sonda olması, Best Case : Aradığımız sayının dizinin en başında olması.
4. Dizi Sıralandıktan sonra 18 sayısı hangi case kapsamına girer? yazınız.  


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---
# PROJENİN TAMAMLANMASI
---
## Dizinin sort türüne göre aşamaların yazılması.
---
1. [2,27,16,22,18,6] 2, dizinin en küçük sayısı olduğundan en başa alabilmek için 22 ile yer değiştirilir.
2. [2,6,16,22,18,27] dizinin 2 den sonra en küçük rakamı 6 olduğundan 6 ile 27 rakamlarını yer değiştirilir.
3. [2,6,16,18,22,27] dizide 6 dan sonra en küçük rakam 16 olduğundan, üçüncü sıra için işlem yapmamıza gerek kalmadan 16 dan sonraki en küçük rakam olan 18 i dördüncü sıraya alabilmek için 22 ile yer değiştirilir.
Beşinci ve altıncı sıradaki rakamlar zaten sıralı olduğundan dizi sıralanmış olur.
---
## Big-O değerinin hesaplanması
---
* bir dizinin eleman sayısına n dersek bu diziyi sıralayabilmek için ilk adımda büyükmüdür küçükmüdür diye hepsine baktığımda n tane işlem yapıyorum yani 6 tane işlem yapıyorum n=6 en küçük elemanı bulmuş oluyorum.
* ikinci adımda en küçük elemandan sonraki en küçük elamanı bulmak için n-1 tane işlem yapıyorum yani 6-1=5 işlem
* üçüncü adımda iki en küçük elemandan sonraki en küçük elemanı bulmak için n-2 tane işlem yapıyorum yani 6-2=4 işlem
* dördüncü adımda üç en küçük elemandan sonraki en küçük elemanı bulmak için n-3 tane işlem yapıyorum yani 6-3=3 işlem
* beşinci adımdan dört küçük elemandan sonraki en küçük elemanı bulmak için n-4 tane işlem yapıyorum yani 6-4=2 işlem 6 elemanlı bir dizi olduğu için altıncı adıma gerek kalmadan son elaman altıncı elaman olmuş oluyor.
benim algoritmam n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapmış oluyor 6+5+4+3+2+1 den 21 işlemde diziyi sıralamış oluyorum.
Big-O cinsinden açıklarsak olayı
bu bana birden n'e kadar olan sayıların toplamını veriyor. 
birden n'e kadar sayıların toplama formülü ne idi [n(n+1)]/2 bunuda açarsak (n²+n)/2 çıkar. Big-o Notationda ne yapıyorduk bunu domine eden fonksiyonu aldığımız için n² değerini alıyoruz.

#### Big_O degeri: **O(n²)**
___

## Time Complexity
___
 18 sayısı için sıralanırsa;

Best Case:     [18,.,.,.,.,.]

Worst Case:    [.,.,.,.,.,18]

Avarage Case:  [.,.,.,18,.,.]
 ___
## Dizi Sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

___

Avarage Case  : Aranan sayının ortada olmasıdır.
Worst Case    : Aranan sayının sonda olmasıdır.
Best Case     : Aranan sayının dizinin en başında olmasıdır.

[2,6,16,18,22,27] olduğuna göre ve 18 sayısı ortada kaldığı için Avarage Case kapsamına girer.

___

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

___

1. Adım: [2,3,5,8,7,9,4,15,6] 

2. Adım: [2,3,5,8,7,9,4,15,6]

3. Adım: [2,3,4,8,7,9,5,15,6]

4. Adım: [2,3,4,5,7,9,8,15,6]
___

[www.patika.dev](https://www.patika.dev/tr)







