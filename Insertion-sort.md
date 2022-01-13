# Insertion-Sort
## 1-) [22,27,16,2,18,6] verilen dizinin sort türüne göre aşamalarını yazınız.
* [22,27,16,2,18,6] -> Bize verilen sıralama.
* [2,27,16,22,18,6] -> İlk adımda 2 en küçük olduğu için ile 22 yer değiştirir.
* [2,6,16,22,18,27] -> ikinci adımda 6 ile 27 yer değiştirir. 
* [2,27,16,22,18,6] -> Üçüncü adımda 16'dan daha küçük olmadığı için yer değiştirmeye gerek yoktur
* [2,6,16,18,22,27] -> Dördüncü ve son adım olarak 18 ve 22 yer değiştirir ve sıralama bitmiştir.
## 2-) Big-O gösterimini yazınız.
* O(n^2)
## 3-) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
* Average Case : 16,18 
* Worst Case : 27 
* Best Case : 2
## 4-) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* 18 Sayısı dizinin ortasında yer aldğı için Avarage Case kapsamına girer.
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
* [7,3,5,8,2,9,4,15,6] -> Bize verilen sıralama.
* 1- [2,3,5,8,7,9,4,15,6] -> 2 en küçük sayı olduğu için 7 ile yer değiştirir.
* [2,3,4,8,7,9,5,15,6] -> 3 zaten 2'den sonraki en küçük eleman olduğu için değiştirmeye gerek yok
* 2- [2,3,4,8,7,9,5,15,6] -> 4 ile 5 sayısını yer değiştirdik.
* 3- [2,3,4,5,7,9,8,15,6] -> 5 ile 8 yer değiştirir.
* 4- [2,3,4,5,6,9,8,15,7] -> 6 ile 7 yer değiştirir.