# Grid-Projects

Başlamadan önce bilmemiz gereken iki yeni özellik var. Font awesome, CSS Variables. 

Font awesome web sayfası tasarlarken sıklıkla kullanılan ikonları font olarak sunan CSS kütüphanesidir.

![font-awesome](https://user-images.githubusercontent.com/102905227/167356133-41b08980-1c94-4b4f-a4f7-501337e1f6eb.png)

Font awesome kurulumu için font awesome dosyalarını https://fontawesome.com sitesinden son sürümü "fontawesome-free-6.1.1-web" indirin.

İkinci olarak CSS'de değişken tanımlamadan faydalandım. Değişken adlarının başına çift çizgi koyarak adlandırmaya başlıyorsunuz.

/* CSS */
 --color: red; 
 
Değişkene erişmek için ise var( ) keywordu kullanılır.Değişkenler tanımlandığı yerlerde geçerlidir.

:root{ } da tanımlanan bir değişken tüm html’de geçerliyken, #item{ } da tanımlanan bir değişken sadece #item’da geçerlidir. Ona dışarıdan erişilemez.

/* CSS */
:root{
  --color: red;
}
#item{
   --color: blue;
}

Setup kurulumunu tamamladıktan sonra projelerimize başlayabiliriz.

Proje 1 Navbar 

![image](https://user-images.githubusercontent.com/102905227/167357496-fc26e714-87dc-433b-acdf-d0be4d4c7582.png)

![image](https://user-images.githubusercontent.com/102905227/167357554-1a86895d-30e5-4884-ad94-e5d878a04b6f.png)

Project 2 Hero 

![image](https://user-images.githubusercontent.com/102905227/167357692-27c87777-5790-405d-bbc0-ccbadafb5ea2.png)

Project 3 Cards 

![image](https://user-images.githubusercontent.com/102905227/167357885-5706744b-8e17-4caa-846c-765d893ec3e6.png)

Project 4 Tiles 

![image](https://user-images.githubusercontent.com/102905227/167358127-03d78879-0ee7-4487-b9cc-eff128153e35.png)

Project 5 Layout

![image](https://user-images.githubusercontent.com/102905227/167358276-ab4c8c6b-218e-469b-be33-2d9027c9f7d5.png)
