# adresbook-sunum
PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .<img width="953" alt="219572540-abd005fc-65f3-4be0-b576-0d21f0902b80" src="https://user-images.githubusercontent.com/120451838/221549749-6208cd3f-8705-4aef-b3c0-e1197d3858ee.png">
<img width="960" alt="219572552-edf5e923-5112-4529-93b3-a99fe2b277b3" src="https://user-images.githubusercontent.com/120451838/221549760-3238c4de-6b83-4094-ab94-978c21c1274f.png">
<img width="960" alt="219572558-1bc3befc-494b-498a-95ce-6ee726aa3e69" src="https://user-images.githubusercontent.com/120451838/221549765-e0984138-f56c-42da-a3d3-4db3358e297c.png">
<img width="956" alt="219574456-075c80bd-eb93-4e6e-813e-6fa4de9292f8" src="https://user-images.githubusercontent.com/120451838/221549771-7a595ebf-bd9c-460e-bd0d-8fe78ffbbd24.png">
<img width="959" alt="219574469-ec16aeee-8e9c-44ad-ac3d-0c7973c37eff" src="https://user-images.githubusercontent.com/120451838/221549778-63feb561-f50e-433b-9556-7ddc7c8d2728.png">
