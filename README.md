# JavaPokemonCardGame
Pokemon Kart Oyunu bir oyuncunun, otomatik oyuncuyla (bilgisayar) savaşabileceği bir kart oyunu ve GUI sinden oluşmaktadır

Projenin Gerçekleştirilmesi:

1.	Bir oyuncu otomatik oyuncuyla (bilgisayar) savaşabileceği gibi aynı zamanda bilgisayar, bilgisayar ile de oynayabilecek.
2.	Tasarlanan oyunda,toplamda 10 pokemon kartı olacaktır ve her bir kullanıcıya ilk başta random olarak 3 er pokemon kartı dağıtılacaktır.
3.	Dağıtımdan sonra ortada 4 tane pokemon kartı kalacaktır. Kullanıcı ve bilgisayar kendilerine dağıtılan 3 pokemon karttan birini seçerek ortaya koyacaktır.
4.	İki taraf kartları ortaya kapalı bir şekilde koyacak ve kartlar aynı anda çevrilerek yüksek hasar puanına sahip olan pokemon kartına sahip olan kişi ya da bilgisayar 5 puan kazanacaktır.
5.	Daha sonra kullanıcı ve bilgisayar ortada kalan kartlardan birer tane (kartların ne olduğunu bilmeden) alacaklardır.
6.	Ortadaki ve eldeki kartlar bitene kadar oyun devam edecektir. En yüksek puana sahip oyuncu, oyunu kazanacaktır.

JFrame sınıfı açılarak design kısmından, JFrame’e buton ve arkaplan resmi eklendi.JFrame ‘in source kısmına geçildiğinde design da sürükle bırak ile oluşturulan giriş ekranının kodları otomatik şekilde yazıldı.’PRESS’ butonu aktif edildi.

![prolab1 2](https://user-images.githubusercontent.com/34886354/73479651-6ae2bd80-43a9-11ea-953f-1b529ca82907.PNG)

Pokemon kart oyununun oynanacağı tahta JFrame ile butonlar,arkaplan resmi,skor sonucunun yazılacağı TextField’lar oluşturuldu.10 adet pokemon kartının görselleri Resimler klasörü olarak projeye dahil edildi.
PcPc ve KullaniciPc sınıflarında kartUret metodu,kartUret2 metodu,kontrolYap ve skorYaz metotları tanımlandı.

Pokemon Kart Oyununun oynandığı oyun tahtası
![prolab1 2 4](https://user-images.githubusercontent.com/34886354/73479643-674f3680-43a9-11ea-9455-050b1b520431.PNG)

