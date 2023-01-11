# Selection-Sort-Projesi
Patika.dev  Veri Yapıları ve Algoritmalar Eğitim Sonu Selection Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


[22,27,16,2,18,6] - İlk önce tüm sayılara bakar, En küçük olanı en başa yazar daha sonra ilk değeri sabit tutup kalan elemanlar için aynısnı yapar.

- [22*,27,16,2,18,6]
- [22,27*,16,2,18,6] 
- [16*,22,27,2,18,6]
- [2*,16,22,27,18,6]
- [2,16,18*,22,27,6]
- [2,6*,16,18*,22,27]


Big-O gösterimini yazınız.

Her elemana tek tek bakıp bir azaltarak devam edeceğimiz için 1 den n'e kadar olan sayıların toplamı kadar işlem yapılacaktır.
n*(n+1)/2 => ((n^2)+n)/2 => O(n^2)
 
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

- Average case: Aradığımız sayının ortada olması
- Worst case: Aradığımız sayının sonda olması
- Best case: Aradığımız sayının dizinin en başında olması.

Sıralandıktan sonra 18 ortanca eleman olduğu için Avarage Case kapsamına girer.


--------------------------------------------------------------------------------------------


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Selection Sort;İlk önce tüm sayılara bakar, En küçük olanı en baştaki ile yer değiştirip yazar daha sonra ilk değeri sabit tutup kalan elemanlar için aynısnı yapar.

- [7,3,5,8,2,9,4,15,6]
- [2|,3,5,8,7,9,4,15,6]
- [2,3|,5,8,7,9,4,15,6]
- [2,3,4|,8,7,9,5,15,6]
- [2,3,4,5|,7,9,8,15,6]
- [2,3,4,5,6|,9,8,15,7]
- [2,3,4,5,6,7|,8,15,9]
- [2,3,4,5,6,7,8|,9,15]
- [2,3,4,5,6,7,8,9|,15]

- [2,3,4,5,6,7,8,9,15|]
