# Binary Search Tree Ödevi

## Ödev

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örnek:** root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap

*Binary Search Tree, node’lardan oluşan ve her bir node’un en fazla 2 child node’a sahip olduğu veri yapılarından bir tanesidir.*
*Node, bir veri yapısının en temel birimidir.*

1. İlk adımda Root girilecek ilk değer olacaktır. 
2. Sonraki adımlarda gelen değer root ile karşılaştırılıp küçükse sol büyükse sağ tarafa doğru ilerler ve yerini alır.

Yukarıdaki dizinin Binary Search Tree algoritmasındaki eklenme aşamalarını görebilirsiniz.

![BinarySearchTree](./BinarySearchTree.gif)