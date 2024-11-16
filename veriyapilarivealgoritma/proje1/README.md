# Soru 1
# [22,27,16,2,18,6] -> Insertion Sort
# Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Cevap : 
1. Adım : 
    - ilk değerin sol tarafında bir değer olmadığı için bir sonraki değere geçer. 
    - Yerini korur.
    - Dizi : [22,27,16,2,18,6]
2. Adım :
    - İkinci değere geçilir solundaki değer ile karşılaştırılır.
    - 27 sayısı 22 değerinden büyük olduğu için swap işlemi yapılmaz.
    - Dizi : [22,27,16,2,18,6]
3. Adım :
    - 16 değeri 27 ile karşılaştırılır. 
    - 16, 27'den küçük olduğu için swap işlemi yapılır.
    - 16 değeri 22 ile karşılaştırılır.
    - 16, 22'den küçük olduğu için swap işlemi yapılır.
    - Dizi : [16,22,27,2,18,6]
4. Adım :
    - 2 değeri 27 ile karşılaştırılır.
    - 2, 27'den küçük olduğu için swap işlemi yapılır.
    - 2 değeri 22 ile karşılaştırılır.
    - 2, 22'den küçük olduğu için swap işlemi yapılır.
    - 2 değeri 16 ile karşılaştırılır.
    - 2, 16'dan küçük olduğu için swap işlemi yapılır.
    - Dizi : [2,16,22,27,18,6]
5. Adım :
    - 18 değeri 27 ile karşılaştırılır.
    - 18, 27'den küçük olduğu için swap işlemi yapılır.
    - 18 değeri 22 ile karşılaştırılır.
    - 18, 22'den küçük olduğu için swap işlemi yapılır.
    - 18 değeri 16 ile karşılaştırılır.
    - 18, 16'dan büyük olduğu için swap işlemi yapılmaz.
    - Dizi : [2,16,18,22,27,6]
6. Adım :
    - 6 değeri 27 ile karşılaştırılır.
    - 6, 27'den küçük olduğu için swap işlemi yapılır.
    - 6 değeri 22 ile karşılaştırılır.
    - 6, 22'den küçük olduğu için swap işlemi yapılır.
    - 6 değeri 18 ile karşılaştırılır.
    - 6, 18'den küçük olduğu için swap işlemi yapılır.
    - 6 değeri 116 ile karşılaştırılır.
    - 6, 16'dan küçük olduğu için swap işlemi yapılır.
    - 6 değeri 2 ile karşılaştırılır.
    - 6, 2'den büyük olduğu için swap işlemi yapılmaz.
    - Dizi : [2,6,16,18,22,27]
# Soru 2
# Big O gösterimini yazınız.

Cevap : İlk adım n olacağından dolayı sonraki adımlar n-1 , n-2 .. şeklinde gidecektir ve +1 ile sonlanacaktır. Bu sayıların toplamının ( n*(n+1)/2) şeklinde formülü var idi. Bu da O(n²) ile ifade edilir.

# Soru 3
# Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Çözüm : Tamamlanan dizemiz [2,6,16,18,22,27] olduğundan dolayı 18 sayısı ortada yer aldığı için Time Complexitymiz Average Case'dir.

# Soru 4
# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevap :
1. Adım :
    - İlk olarak dizedeki en küçük sayı aranarak birinci sıraya yerleştirilir.
    - Dizedeki en küçük sayı 2 olduğundan 7 ile yer değiştirilerek yazılır.
    - Dizi : [2,3,5,8,7,9,4,15,6]
2. Adım : 2 Eleman 
    - İkinci dizeden itibaren en küçük sayı aranır.
    - Burada 3 sayısı en küçük olduğundan dolayı yerinde kalır ve dize değişmez.
    - Dizi : [2,3,5,8,7,9,4,15,6]    
3. Adım : 3 Eleman 
    - Üçüncü dizeden itibaren en küçük sayı aranır.
    - Buradaki 4 sayısı en küçük sayı olduğundan dolayı 5 ile yer değiştirilir.
    - Dizi : [2,3,4,8,7,9,5,15,6]
4. Adım : 4 Eleman 
    - Dördüncü dizeden itibaren en küçük sayı aranır
    - 5 sayısı dizedeki en küçük sayı olduğundan dolayı 8 ile yer değiştirilir.
    - Dizi : [2,3,4,5,7,9,8,5,6]
İlk 4 adımdaki dize sırası [2,3,4,5,7,9,8,5,6] şeklinde olur.