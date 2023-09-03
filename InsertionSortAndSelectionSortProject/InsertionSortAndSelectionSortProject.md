# Insertion Sort ve Selection Sort Ödevi

## Ödev

**[22,27,16,2,18,6]** -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Cevap

*Insertion Sort algoritması dizinin ilk ögesinden başlayarak yeni bir dizi oluşturmuş gibi davranır.*
*Sonraki öge geldiğinde belirlediği bölge içinde sıralı olması için o ögenin olması gereken araya ekler.*

**[22,27,16,2,18,6]** -> Insertion Sort

 **[22,27,16,2,18,6] dizi n kadar**
1. 22 | 27,16,2,18,6 n-1
2. 22,27 | 16,2,18,6 n-2
3. 16,22,27 | 2,18,6 n-3
4. 2,16,22,27 | 18,6 n-4
5. 2,16,18,22,27 | 6 n-5
6. 2,6,16,18,22,27   n-6

Big-O Gösterimi (n+(n-1)+(n-2)+(n-3)+(n-4)+(n-5)+(n-6)) -> (n*(n+1))/2 -> (n2+n)/2 -> O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı **Average case** kapsamına girer.


*Selection Sort algoritması diziyi tarar ve en küçük sayıyı bulur ve 0 dan başlayarak indexlere yerleştirir*
*Her değişimde yerleştirmesi gereken index ile bulunan index yer değiştirir sonra yerleştirilmesi gereken index artar.*

**[7,3,5,8,2,9,4,15,6]** dizisi Selection Sort'a göre ilk 4 adımı:

1. [2,3,5,8,7,9,4,15,6] 2 ile 7 yer değiştirir.
2. [2,3,5,8,7,9,4,15,6] 3 kalan indexlerde en küçük sayıdır  değişim yapılmaz.
3. [2,3,4,8,7,9,5,15,6] 4 ile 5 yer değiştirir.
4. [2,3,4,5,7,9,8,15,6] 5 ile 8 yer değiştirir.
