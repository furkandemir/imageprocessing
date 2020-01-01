
 KNN ALGORİTMASI NEDİR?
 
 Sınıflandırmada (classification) kullanılan bu algoritmaya göre sınıflandırma sırasında çıkarılan özelliklerden , sınıflandırılmak istenen yeni bireyin daha önceki bireylerden k tanesine yakınlığına bakılmasıdır.

Örneğin k = 3 için yeni bir eleman sınıflandırılmak istensin. bu durumda eski sınıflandırılmış elemanlardan en yakın 3 tanesi alınır. Bu elamanlar hangi sınıfa dahilse, yeni eleman da o sınıfa dahil edilir. Mesafe hesabından genelde öklit mesafesi (euclid distance) kullanılabilir.

![Yerlestirme](https://i.hizliresim.com/1p5kV1.jpg)

örneğin yukarıda verilen ve özelliklerine göre 2 boyutlu koordinat sistemine yerleştirilmiş olan örnekleri ele alalım. Bu örneklerin birbirinden ayrılması doğrusal ayrıştırma (linear discrimination) problemidir ve buradaki yöntemlerle çözülür.

KNN yöntemine göre aşağıdaki şekilde yeni bir üyenin geldiğini düşünelim:

![Yeniuye](https://i.hizliresim.com/DOZRB1.jpg)




Yukarıdaki bu yeni gelen üyenin en yakın olduğu 3 üyeyi (3 nearest neighbors) tespit edelim.

![Yeniuyemesafe](https://i.hizliresim.com/odvZj2.jpg)





En yakın 3 üyenin iki tanesi kırmızı yuvarlak üyeler olduğuna göre yeni üyemizi bu şekilde sınıflandırabiliriz:

![Yeniuyemesafesiniflandırma](https://i.hizliresim.com/7Bzbqv.jpg)

