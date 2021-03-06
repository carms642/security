### VirtualBox nedir ?

* VirtualBox bir sanallaştırma yazılımıdır.
* İştetim sistemlerini fiziksel makinelere kurmak yerine, VirtualBox aracılığı ile sanal olarak kurulabilir ve sanal network oluşturabilirsiniz.
* İndirme linki:
    * [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### Virutal Box Kurulumu

İlk önce VirtualBox sitesine gidip proğramı indirdiyseniz ve sonrasında da bilgisayarınıza kurduysanız, ayarlamalarına devam edebiliriz.

1. __New__ tıklayarak yeni bir sanal makine oluşturalım. Sonradan sıkıntı olmaması için isimlendirmeyi benimkiyle aynı devam edebilirsiniz.
![][vb1]

2. Makinemizin kullanacağı RAM ı belirledikten sonra __Continue__
![][vb2]

3. __Create a virtual hard drive now__ seçerek __Create__
![][vb3]

4. __VDI__ seçerek __Continue__
![][vb4]

5. __Dynamically allocated__ seçerek __Continue__
![][vb5]

6. Şimdi Linux'un belleğimizde kullanacağı alanı belirliyoruz, ben 10 GB seçtim __Create__
![][vb6]

7. Oluşturduğumuz _Kali Linux_ seçerek __Settings__ den ayarlarını yapalım. __System > Processor > Enable PAE/NX__ işaretleyelim.
![][vb7]

8. __Storage__ gelelim ve CD ikonu üstüne tıklayarak, indirdiğimiz _Kali Linux .iso_ dosyasına yönlendirelim ve __OK__ tıklayarak ayarlamalarımızı tamamlayabiliriz.
![][vb8]

[vb1]: ../resim/kurulum/vb1.png
[vb2]: ../resim/kurulum/vb2.png
[vb3]: ../resim/kurulum/vb3.png
[vb4]: ../resim/kurulum/vb4.png
[vb5]: ../resim/kurulum/vb5.png
[vb6]: ../resim/kurulum/vb6.png
[vb7]: ../resim/kurulum/vb7.png
[vb8]: ../resim/kurulum/vb8.png