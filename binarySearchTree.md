[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

İlk eklenen eleman olarak düşünürsek **root [7]** olur.

                         [7]
                        /    \
                     [5]      [8]
                   /    \         \
                [1]      [6]      [9]    
               /    \
            [0]      [3]
                    /   \
                 [2]     [4]

Verilen sırayla diğer elemanları da eklediğimizde bu şekilde bir yapı oluşur.

* 7'den sonra eklediğimiz sayı 5 oldu. 5 7'den küçük olduğu için sol tarafına ekleriz.
* 1, 7'den küçük olduğu için sola yöneliriz, 5'ten de küçük olduğu için 5'in sol tarafına ekleriz.
* 8, 7'den büyük olduğu için sağ tarafa ekleriz.
* 3, 7'den ve 5'ten küçük olduğu için sola yöneliriz. 1'den büyük olduğu için 1'in sağına ekleriz.
* 6, 7'den küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına ekleriz.
* 0 (sıfır) da 7, 5 ve 1'den küçük olduğu için 1'in soluna ekleriz.
* 9 da 7 ve 8'den büyük olduğu için 8'in sağına ekleriz.
* 4, 7 'den küçük olduğu için soluna, 5'ten de küçük olduğu için soluna yöneliriz. 1'den büyük olduğu için * 1'in sağına bakarız, 3'ten de büyük olduğu için 3'ün sağına ekleriz.
* 2 için de 1'e kadar geliriz, 1'den büyük olduğu için 1'in sağına, 3'ten küçük olduğu için 3'ün soluna ekleriz.