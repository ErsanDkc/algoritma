# İnsertion Sort olarak incelenmesi; <br>
[22,27,16,2,18,6] <br>
(en küçük olan sayı seçilir ve en baştakiyle yeri değiştirilir) <br>
-[2,27,16,22,18,6] <br>
-(ikinci en küçük sayıda seçilir ve 2. sırayla yer değiştirir) <br>
-[2,6,16,22,18,27] <br>
-(diğerleride aynı şekilde küçükten büyüğe doğru yer değiştirirler) <br>
-[2,6,16,18,22,27] <br>

-Big-O gösterimi : n+(n-1)+(n-2)+..+.= n*(n+1)/2 (Matematik bilgisi) <br>
                                    =n^2+n/2 <br>
                                Big O(n^2)  <br>

# Selection Sort olarak inceleme; <br>
-[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı ; <br>
-[2,3,5,8,7,9,4,15,6] 1.adım <br>
-[2,3,4,8,7,9,5,15,6] 2.adım <br>
-[2,3,4,5,7,9,8,15,6] 3.adım <br>
-[2,3,4,5,6,9,8,15,7] 4.adım <br>
