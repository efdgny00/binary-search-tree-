# binary-search-tree-
binary search projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root = 7

                                  7
                              5 /   \ 8
                          1 /   \ 6     \ 9
                      0 /   \ 3     
                          2 /   \4  

binary search tree ile sıralar isek bu şekilde bir sonuç alırız.  

aşamalar--->

* 5 sayısı 7 ten büyük oluğu için 5 7 nin soluna yerleştirilir.
* 1 sayısı 5 ten küçük olduğu için 5 in soluna yerleştirilir.
* 8 sayosı 7 den büyük olduğu için 7 nin soluna yerleştirilir.
* 1 sayısı 5 ten küçük olduğu için 5 in soluna yerleştirilir.
* 6 sayısı 5 ten büyük olduğu için 5 in sağına yerleştirilir.
* 0 sayısı 1 den küçük olduğu için 1 in soluna yerleştirilir.
* 3 sayısı 1 den büyük olduğu için 1 in sağına yerleştirilir.
* 2 sayısı 3 ten küçük olduğu için 3 ün soluna yerleştirilir.
* 4 sayısı 3 ten büyük olduğu için 3 ün sağına yerleştirilir.
