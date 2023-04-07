# Selection-Sort

[7,3,5,8,2,9,4,15,6] örüntüsünü Selection-Sort ile sıralamak istediğimiz zaman ilk önce EN KÜÇÜK VERİYİ BULUP İLK İNDEXTEKİ İLE YERLERİNİ DEĞİŞTİRİYORUZ.

( " Recursive Mantığı içerir. " ) bus durumu sağlanana kadar tekrar eder yani stop. Buradaki bus durumu örüntünün index boyutunun en sonki yer değişimi yapacağı index'in numarasına eşit olmasıdır.Bu, Array'in ilk index'i 0 ile başlayan bazı programlama dillerinde index-1 e eşit olana kadar sağlanır.

    AŞAMA 1  : ["2",3,5,8,"7",9,4,15,6] en küçük 1. verimiz , "2" ve 0. index'teki veri ile yer değişimi yapılıyor.
    AŞAMA 2  : [2,"3",5,8,7,9,4,15,6] en küçük 2. verimiz , "3" ve 1. index'teki veri ile yer değişimi yapılmasına gerek yok çünkü 3 ikinci indexte yer alıyor.
    AŞAMA 3  : [2,3,"4",8,7,9,"5",15,6] en küçük 3. verimiz , "4" ve 2. index'teki veri ile yer değişimi yapılıyor.
    AŞAMA 4  : [2,3,4,"5",7,9,"8",15,6] en küçük 3. verimiz , "5" ve 3. index'teki veri ile yer değişimi yapılıyor.
    AŞAMA N  : [2,3,4,5,6,7,8,9,15] n boyutlu bir dizinin n. aşaması son aşamadır.

# Insertiopn-Sort

[22,27,16,2,18,6] -> Insertion Sort

->Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    ->AŞAMALAR ;

      AŞAMA 1  : [22,"27",16,2,18,6] 1.index baz alınarak sol taraftaki verilerden büyük olana kadar sola kaydırılır.  
                      ( " 22 < 27 " evet ise bir sonraki index'e geç hayır ise 27'yi bir sola kaydır. )
      AŞAMA 2  : [22,27,"16",2,18,6] 2.index 16 < 27 evet ise 2. index'i sola kaydır ve tekrar et. EVET. 16 < 22 evet. 
      AŞAMA 3  : [16,22,27,2,18,6] 3.İndex 2 < 27 .... 
      AŞAMA N-1  : [2,6,16,18,22,27]

-> Big-O gösterimini yazınız.

      Worst case : n^2
      Average case : n^2
      Best case : n (Zaten sıralıdır.)

-> Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  
      Cevap: Average case'dir.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
