# proje1
Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

Insertion Sort dizideki en küçük elemanı bularak dizinin en başına taşıyarak yapılan sıralam algoritmasıdır.
En küçükten en büyüğe doğru sıralayarak bu şekilde devam eder.
 *Diziye baktığımızda en küçük sayının 2 olduğunu görüyoruz.
2yi başa çekerken başta olan sayıyı yani 22yi, 2nin yerine gönderiyoruz.
  n[2,27,16,22,18,6] 
 İkinci sıraya 6nın gelmesi gerektiğini biliyoruz o yüzden 6yı ikinci sıraya çekerken 27yi 6 nın yerine gönderiyoruz.
  n-1[2,6,16,22,18,27] 
 Son olarak doğru bir sıralama olması için 18 ile 22nin yerlerini değişmesi gerektiğini görüyoruz.
  n-2[2,6,16,18,22,27] 

 *Big-O gösterimi
  On(^2)

 *Average case: Aradığımız sayının ortada olması,
 Worst case: Aradığımız sayının sonda olması,
 Best case: Aradığımız sayının dizinin en başında olması.
 Bu bilgiler doğrultusunda dizi sıralandıktan sonra ;" [2,6,16,18,22,27] " 18 sizinin ortasında olduğu için Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
 [2,3,5,8,7,9,4,15,6]
 [2,3,4,8,7,9,5,15,6]
 [2,3,4,5,7,9,8,15,6]
 [2,3,4,5,6,9,8,15,7]

www.patikadev.com
