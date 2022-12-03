# Selection Sort 
**[22,27,16,2,18,6]** -> Insertion Sort
Dizideki en küçük değeri bulur ve index üzerinde bulunan değer ile yer değiştirir.
1. -> En küçük değer "2".
2. [2| 27,16,22,18,6]
3. -> En küçük değer "6".
4. [2,6|16, 22,18,27]
5. ....
6. [2,6,16,18,22,27]

Big-O Gösterimi: n(n+1)/2 = (n^2+n)/2 
Sonuç: O(n^2)

İstenilen 18 değeri ortada olmasından dolayı Average Case olur.

[7,3,5,8,2,9,4,15,6] Selection Sort'a göre ilk 4 adım:
1.-> [2|3,5,8,7,9,4,15,6]
2.-> [2,3|5,8,7,9,4,15,6]
3.-> [2,3,4|8,7,9,5,15,6]
4.-> [2,3,4,5|7,9,8,15,6]
