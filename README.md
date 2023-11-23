# Control
Buraya dersi kaynatmak için ihtiyacınız olabilecek belli başlı programlar atacağım,kullanım kılavuzları ile birlikte.


# Block Control Application (blockctrl)
Bu program kullanımı en basit programlardan biridir. Basitçe bir listeye yazılan program isimlerinden herhangi birinin çalışır duruma geçtiği tespit edilirse o programı kapatır. Çok kapsamlı ve kullanım alanı geniş bir programdır. Örneğin pdf dosyalarının açılmaması için pdf dosyalarını açan ve okumaya yarayan, Pdf Reader adı verilen uygulamaların isimleri alınıp listeye yazılırsa pdf dosyaları açılmamaya başlar. Ya da ZKitap yazarsanız artık ZKitap ismindeki bir exe dosyası açılmaz. 


Önemli Not : Eğer amacınız kötü değilse "svchost" gibi kritik sistem programlarının yazılmaması önerilir. Bunların bir kısmında izinlerin eksikliği gereği bir şey yapamasa da bazı kritik işlemlerin kapatılması mavi ekran verilmesine ve hatta başlangıca atıldıysa bilgisayarın açılmamasına veya hemen mavi ekran vermesine yol açabilir.

Kullanım Kılavuzu : 


1 - Kapatmak istediğiniz şeyin bir program olduğundan emin olun. Örneğin bir kısayol ise sağ tıklayın ve dosya konumuna gidin,dosya konumunda ise sağ tıklayarak özelliklerine girin,eğer dosya türü Uygulama ise Block Control çalışabilir demektir. Bunu anlamak için bir diğer yol dosya uzantılarını göstermeyi aktif hale getirerek aradığınız kısayol olmayan dosyanın sonu .exe ile bitiyor mu kontrol etmektir.

2 - Dosyanın ismini alın. Örneğin uzantılarla birlikte "blockctrl.exe"  adındaki bir dosyanın ismi "blockctrl" olacaktır. 

3 - Önce masaüstünde sağ tıklayın ve Yeni > Yeni Metin Belgesi'ni sırasıyla seçin. Sonra metin belgesinin ismini "block" olarak belirleyin (Uzantısı dahil olmadan).

4 - Sonra metin dosyasını düzenleyin ve içerisine kullanılmasını istemediğiniz dosyaların ismini satır satır yazın. Aşağıda bir örnek bırakıyorum.

//Kapatılmasını istediğim programlar ZKitap,Blockctrl,Regedit,Taskmgr ve son olarak da Chrome olsun.

ZKitap

Blockctrl

Regedit

Taskmgr

Chrome
5 - Son olarak blockctrl.exe adındaki programı isteğinize göre Sağ Tık > Yönetici Olarak Çalıştır ile ya da Sağ Tık > Aç olarak çalıştırın. Eğer program doğru çalışıyorsa diğer programları kapatmaya ve masaüstünde oluşturduğunuz block isimli metin belgesini gizlemeye başlayacaktır. Gizlenmiş dosyaya erişim için Dosya Gezgini kullanarak Gizli Dosyaları Göster'i açık hale getirin.(Uyarı : Yönetici olarak çalıştırmak izin olmadan kapanmayan bazı programlar için önerilir.)


Son uyarı : Bu program farkedildiğinde güçsüzleşebilir,çünkü kişi programın ismini değiştirip açılabilecek bir hale sokabilir. Dikkatli kullanmaya ve şüphe çekmemeye dikkat edin.

