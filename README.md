# Veri-Yap-lar-ve-Algoritmalar-Selection-Sort-Projesi
Insertion sort, verilen dizinin sıralanması için kullanılan bir algoritmadır.

[22,27,16,2,18,6] -> Insertion Sort
Yukarıdaki sayı dizisinin sort türüne göre sıralanma aşamaları;

- Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.
- [27]
- Daha sonra  22 < 27 olduğu için sıralama aynı şekilde kalır.
- [22,27,16,2,18,6] - 

- Dizinin üçüncü elemanı 16 kontrol edilir. 16 < 27 ve 16 < 22 olduğu için dizinin en başına kaydırılır.
- [16,22,27,2,18,6]

- Dizinin dördüncü elemanı 2 kontrol edilir. 2 < 27 ve 2 < 22 ve 2 < 16 olduğu için dizinin en başına kaydırılır.
- [2,16,22,27,18,6]

- Dizinin beşinci elemanı 18 kontrol edilir. 18 < 27 ve 18 < 22 olduğu için dizinin üçüncü sırasına kaydırılır.
- [2,16,18,22,27,6]

- Dizinin son elemanı 6 kontrol edilir. 6 < 27 ve 6 < 22 ve 6 < 18 ve 6 < 16 olduğu için dizinin ikinci sırasına kaydırılır.

- Dizinin Son Hali 
- [2,6,16,18,22,27]

-----------------------------------------

Big-O gösterimini yazınız.

-Big-O=(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
- Average Case

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

-[7,3,5,8,2,9,4,15,6]
(En küçük sayı bulunur. 2 )
[2,3,5,8,7,9,4,15,6]
(En küçük ikinci sayıyı ararız. 3.)
[2,3,5,8,7,9,4,15,6]
(Ardından bir büyük olan 4 seçilir ve 5 ile yer değiştirir)
[2,3,4,8,7,9,5,15,6]
(Bir büyük sayı olan 5 seçilir ve 8 ile yer değiştirir)
[2,3,4,5,7,9,8,15,6]
(Bir büyük sayı olan 6 seçilir ve 7 ile yer değiştirir)
[2,3,4,5,6,9,8,15,7]
(Bir büyük sayı olan 7 seçilir ve 9 ile yer değiştirir)
[2,3,4,5,6,7,8,15,9]
(Bir sonraki sayı 8 )
[2,3,4,5,6,7,8,15,9]
(Sonraki sayı 9 ve 15 ile yer değiştirir)
SONUÇ
-[2,3,4,5,6,7,8,9,15]
