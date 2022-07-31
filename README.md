# InsertionSortProject
Patika.dev

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6] -> ilk olarak en küçük sayı 2 ile 22'nin yeri değiştirilir.
[2,6,16,22,18,27] -> bir sonraki en küçük sayı olan ile 27'nin yeri değiştirilir.
[2,6,16,18,22,27] -> 16 zaten doğru yerde olduğu için 18 ile 22'nin yerleri değiştirilir.

[2,6,16,18,22,27] -> şekli ile kalan elemanlar doğru yerde olduğu için işlem tamamlanmış olur.

2. Big-O gösterimini yazınız.
[22,27,16,2,18,6] -> ilk durumda n tane eleman kontrol edilir.
[2,27,16,22,18,6] -> bir sonraki adımda n-1 tane eleman kontrol edilir.
bu süreç n, n-1, n-2 ... 1 şeklinde devam ettiğindenn dolayı sonuç olarak toplamda n*(n-1)/2 tane işlem gerçekleştirilir.
n² ifadesi çok büyük en değerlerinde çok büyük olacağından dolayı diğer ifadeler ihmal edilir.
Big-O gösterimi n² olrak ifade edilir.

3. Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[2,6,16,18,22,28] şeklinde sıralandıktan sonra 18 sayısı average case olur.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. adım -> [2,3,5,8,7,9,4,15,6] 
2. adım -> [2,3,4,8,7,9,5,15,6]
3. adım -> [2,3,4,5,7,9,8,15,6]
4. adım -> [2,3,4,5,6,9,8,15,7]
