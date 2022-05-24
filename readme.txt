insert : levela göre karşılaştırma yapıyorum ve ona göre ekliyorum.
search : roottan başalayarak point değerine göre sağ, sol çocuk diye araştırıyorum. Her cocuğa gitmiyoruz. X ya da y yegöre karşılaştırıp gidilmesi gereken yeri buluruz.
findMin: için ise 0 ise X,1 için Y parametrelerine göre karşılaştırma yaptım. 
findMax: için ise 0 ise X,1 için Y parametrelerine göre karşılaştırma yaptım. 
nearestNeighbour: bu kısımda aslında insert fonksiyonuna benziyor. pointin insert edilecek yerinekadar gidilip insert edilmeden insert edilecek kdTree2D öğesini dönmesine sistematiğini içeren bir fonksiyondur.
toString: Bir global string tutariz ve buna treedeki elemanları import ederiz.
remove: remove edilen kdTree2Dnin seviyesine bakılarak X ya da Y ye göre karşılştırma yapılır. remove işleminden sonra ise sağ subtreedeki en küçük ya da sol subtreedeki en büyük ifadeyi bu remove edilen kısma yazarız. 
inRectange: kısmında ise her bir kdTree2D dosyaına index string tutturuyoruz. Bu sayede sağa ya da sola gideceğimizi anlıyoruz. Bu aşamadan sonra ise nearestNeighbour
ile en yakın kdTree2D'yi buluruz.  Bulunan iki kdTree2D arasındaki kdTree2D'leri arrayliste ekleriz ve bu arraylisti döneriz. Ancak bu kısımda hatam olduğundan dolayı fonksiyonu
çalıştıramadım. :)