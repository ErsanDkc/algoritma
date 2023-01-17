# Merge Sort olarak inceleme ;
[16,21,11,8,12,22] <br><br>
 
[16,21] [11]  ve  [8,12] [22] olarak ayırdım. <br>
[11,16,21] olarak ve   [8,12,22] olarak birleştirdim <br>
 Şimdi bu iki grubu birleştiricem; <br>
 Öncelikle 8, 11'den küçük olduğu  için önce o yazılır. 8 den sonra kendi grubunda gelen sayı 12 ve 11 den büyük olduğu için, 8'in yanına 11 yazılır. <br>
 [8,11] <br>
 16 ve 12 kıyaslanır ve 12 küçük olduğu için ilk o yazılır. 12 den sonra kendi grubunda gelen sayı 22 ve 16 dan büyük olduğu için, 12 den sonra 16 yazılır; <br>
 [8,11,12,16] <br>
 son olarak kalan 21 ve 22 de sırasıyla eklenir; <br>
 [8,11,12,16,21,22] <br><br>

 Big O(nlogn) <br>
