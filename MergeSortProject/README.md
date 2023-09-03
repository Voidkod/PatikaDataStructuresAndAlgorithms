# Merge Sort Ödevi

## Ödev

**[16,21,11,8,12,22]** -> Merge Sort

Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Cevap

*Merge Sort (Birleştirme Sıralaması), diziyi ardışık olarak en küçük alt dizilerine kadar yarılayan sonra da onları sıraya koyarak bireştiren özyineli bir algoritmadır.*

**[16,21,11,8,12,22]** -> Merge Sort

1. [16,21,11] [8,12,22]          
2. [16,21] [11] [8,12] [22]      
3. [16] [21] [11] [8] [12] [22]  
4. [16,21] [8,11] [12,22]        
5. [8,11,16,21] [12,22]          
6. [8,11,12,16,21,22]            

Big O gösterimi -> (n+n+n+n+n+n) ->(6n) Her işlem O(n) olduğundan ve her seferinde yarıya düştüğünden ve -> O(nLogn) kadardır.