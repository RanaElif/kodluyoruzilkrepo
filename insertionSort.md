# [22,27,16,2,18,6]

## Insertion Sort Aşamaları

1. Aşama
27 22'den büyük olduğu için yer değiştirme işlemi yapılmaz.
[22,27,16,2,18,6]

2. Aşama
16 27'den küçük olduğu için uygun sıralamaya gelene kadar kaydırılır.
[22,16,27,2,18,6] [16,22,27,2,18,6]

3. Aşama
2 27'den küçük olduğu için uygun yerine gelene kadar kaydırılır.
[16,22,2,27,18,6] [16,2,22,27,18,6] [2,16,22,27,18,6]

4. Aşama
18 27'den küçük olduğu için kaydırılır.
[2,16,22,18,27,6] [2,16,18,22,27,6]

5. Aşama
6 sıralama doğru olana kadar kaydırılır.
[2,16,18,22,6,27] [2,16,18,6,22,27][2,16,6,18,22,27] 

    [2,6,16,18,22,27] dizimiz doğru şekilde sıralandı.

## Big O Gösterimi

Worst case senaryosunda yani dizinin ters bir şekilde sıralı olduğu durumda; n elemanlı dizide 1+ 2+ ... + (n-1)+n defa yer değiştirme işlemi yapılır. Bunun toplamı da n*(n+1)/2=(n^2+n)/2 olur. Domine eden n^2 olduğu için Big O gösterimi __O(n^2)__ olur.

## Time Complexity

Average case: n^2
Worst case: n^2
Best case: n

# [7,3,5,8,2,9,4,15,6]

## Insertion Sort Aşamaları

1. Aşama
3 7'den küçük olduğu için kaydırılır.
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]

2. Aşama
5 7'den küçük olduğu için kaydırılır.
[3,5,7,8,2,9,4,15,6]

3. Aşama
8 7'den büyük olduğu için işlem yapılmaz.

4. Aşama
2 8'den küçük olduğu için kaydırılır.
[3,5,7,2,8,9,4,15,6]
[3,5,2,7,8,9,4,15,6]
[3,2,5,7,8,9,4,15,6]
[2,3,5,7,8,9,4,15,6]

5. Aşama
9 8'den büyük olduğu için işlem yapılmaz.

6. Aşama
4 9'dan küçük olduğu için kaydırlır.
[2,3,5,7,8,4,9,15,6]
[2,3,5,7,4,8,9,15,6]
[2,3,5,4,7,8,9,15,6]
[2,3,4,5,7,8,9,15,6]

7. Aşama
15 9'dan büyük olduğu için işlem yapılmaz.

8. Aşama
6 15'den küçük olduğu için kaydırlır.
[2,3,4,5,7,8,9,6,15]
[2,3,4,5,7,8,6,9,15]
[2,3,4,5,7,6,8,9,15]
[2,3,4,5,6,7,8,9,15]

    [2,3,4,5,6,7,8,9,15] dizimiz sıralandı.

