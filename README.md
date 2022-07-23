Insertion Sort Projesi
[22,27,16,2,18,6]-- Insertion

1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[2|,22,27,16,18,6]-- 2 rakamının en küçük olduğunun tespiti ve başa yazılması
[2,6|,22,27,16,18]-- 6 rakamının doğru yerine yazılması
[2,6,16|,22,27,18]-- 16 sayısının doğru yerine yazılması
[2,6,16,18|,22,27]-- 18 sayısının doğru yere yazılması
[2,6,16,18,22|,27]-- 22 sayısının doğru yerde olduğunun tespit edilmesi
[2,6,16,18,22,27]-- dizinin son hali

2)Big-O gösteriminin yazılması
Worstcase-- O(n²)
Avaragecase-- O(n²)
Bestcase-- O(n)

3)Time complexity yazınız.(Aranan sayının 2 olduğunu varsayalım.)
Worstcase[2'nin en sonda olması]--[22,27,16,18,6,2]
Avaragecase[2'nin ortada olması]--[22,27,16,2,18,6]
Bestcase[2'nin en başta olması]--[2,22,27,16,18,6]

4) 18 sayısı dizinin son hali göz önüne alındığında Avaragecase kapsamına girer.

5)[7,3,5,8,2,9,4,15,6]dizisinin ilk 4 adımını yazınız.
[2|,7,3,5,8,9,4,15,6] 2'nin en başa alınması
[2,3|,7,5,8,9,4,15,6] 3'ün yerine yazılması
[2,3,4|,7,5,8,9,15,6] 4'ün yerine yazılması
[2,3,4,5|,7,8,9,15,6] 5'in yerine yazılması
