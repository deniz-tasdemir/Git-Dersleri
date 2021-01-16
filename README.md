<<<<<<< HEAD


### GIT’in Hikayesi
Linus Torvalds, 2002 yılında, kernel’i geliştirirken BitKeeper adlı revizyon kontrol sistemini kullanıyor. 2005 yılında Linux kernel geliştirici topluluğu ile BitKeeper arasında bir sıkıntı oluyor. BitKeeper’ın ücretsiz kullanım lisansı iptal oluyor ve Linus’un sigorta bu noktada atıyor.

İzlediğim Git Under the Hood eğitiminde Jeffrey Haemer, Linus’un GIT’i geliştirmeye bir pazartesi başlayıp, çarşamba gününden itibaren GIT’i GIT ile versiyonlamaya başladığını söyledi. Bu kadar hızlı geliştirmesinin sebebi olarak da zaten çok iyi bildiği kernel’i kopyalaması olduğunu söyledi.

Hatta Ken Thompson’ın da Unix’i tam 1 ayda yazdığını, Linus’un da Unix’i örnek aldığını söyledi...

Sonuç Olarak...
Neticede GIT aslında bir veritabanıdır. Tanımlandığı dizin altında çalışan, ilgili bilgilerini, ayarlarını ve benzeri bilgilerini .git/ dizini altında tutan, o dizindeki tüm dosyaların (eğer izole edilmemişse) versiyonlarını yani dosyalardaki değişikliklerin tarihçesini, bu kendi şahsına özel veritabanı mekanizması içinde saklar.


## GİT NOTLARIM
=======
### GİT DERLERİ
### Git’in Hikayesi
 İlk sürümü Linux çekirdeği'nin geliştirilmesinde kullanılmak üzere 2005 yılında bizzat Linus Torvalds tarafından tasarlanıp geliştirilmiş, son Eclipse kullanıcı topluluğu anketi verilerine göre 2013 yılı itibarıyla %30 pazar payına ulaşmıştır.
Linus Torvalds, 2002 yılında, kernel’i geliştirirken BitKeeper adlı revizyon kontrol sistemini kullanıyor. 2005 yılında Linux kernel geliştirici topluluğu ile BitKeeper arasında bir sıkıntı oluyor. BitKeeper’ın ücretsiz kullanım lisansı iptal oluyor ve Linus’un sigortaları bu noktada atıyor.Sonrasında git ortaya çıkıyor.

### Git Ne İşe Yarar?
 Geliştiriciler yeni bir proje yaptıklarında, kodlarına daima güncelleme yaparak devam ederler. Projelerini yayınladıklarından sonra bile versiyon güncelleme, hata düzeltme, yeni özellikler ekleme gibi işlemleri yapmaları gerekmektedir.

Versiyon kontrol sistemi, kod temeline yapılan değişikliklerin izini sürmeye yardımcı olur. Dahası, değişiklikleri kimin yaptığının kaydını tutar ve silinmiş veya değiştirilmiş kodları geri getirebilir.Şimdi diyeceksiniz ki bunun  yerine klasörü kopyalarak yedek alsaydık bu kadar şeyle neden uğraşıyoruz. Örneğin bir projeye başladınız ve bu projeye birşey ekleyeceksiniz ve bu kodların çalışıp çalışmadığından emin değilsiniz, işte git burada devreye giriyor. git de yeni bir branch oluşturup test edip, daha sonra bu branchleri birleştirebilirsiniz. Yada bir den fazla yazılımcı branch oluşturarak aynı projede çalışıp sonra ana branch olan masterde bu branchleri birleştirebilir. Ayrıca siz her branch oluşturduğunuzda o dosyanın tamamını kopyalamış olmazsınız, sadece değişiklik yaptığınız satır kadar bilgisayarında yer kaplar. Sürekli aynı klasörü kopyaladığınızda değişik yapmadığınız dosya ve klasörü de boşuna kopyalayarak hem yer hemde zamandan kaybınız olur.
>>>>>>> githubv1


### GİT AYARLAR
### `git –version  :`gitin versionu öğrenmiş oluruz.
 
### ;`git –config list :`ile yapılandırılımış ayarlarmızı görebiliriz. 

### `git config –global user.name` “github kullanıcı adımızı yazıyoruz.”  :buradaki global anlamda yapılandırma yaptığımızı gösterir.

### `git config –global user.email ` “email adresinizi yazıyoruz”  mail adresimizi tanımlıyoruz. Bu şekilde ayarları bitirmiş oluyoruz.

### İPUCU

Git'in komutları ve bu komutların seçenek ve parametreleri ile ilgili yardım almak istediğinizde aşağıdaki komutları kullanabilirsiniz.
## git [komut adı] --help (örneğin: git init --help)
## git help [komut adı] (örneğin: git help init) komutlarını kullanabilirsiniz. 


### TERMİNAL KOMUTLARI
### `pwd: `Terminal üzerinde bulunduğumuz  tam adresini verir.
### `ls:`Mevcut bulunduğumuz dosyaları ve dizileri listeler.### Ls -a : Mevcut bulunduğumuz gizli dosyaları ve dizileri listeler.###  cd : Dizin değiştirme k için kullanılır örnek cd desktop gibi.. Normal Windows den Myproject diye bir klasör oluşturup,  içine cd komutu ile girebiliriz.
### `cd.. :`Bu komut ile bir önceki dizine geri gelebiliriz.
### `Clear:` Terminali temizler. Yada kısayol tuşu CTRL+L tuşu ile temizleyebiliriz.
### `Touch :` touch  dosya.txt (dediğimizde bulunduğumuz klasörün içine dosya.txt adında dosya oluştururuz.)
### `mkdir dosyaadı`  bu şekilde bulunduğumuz dizine dosya oluştururuz.
### `vi dosyaadı.uzantısı :` yazıp o dosyayı terminal üzerinden açabiliriz.
### Terminalden dosya içine bir şey yazmak için;
1-Önce i tuşuna basınıyoruz be yazmak istediklerimizi yazıyoruz.
2-Daha sonra önce “Esc” Tuşuna basıp “:wq” bır w write yani yazmak kelimesinden geliyor q da quit yani çıkmakdan geliyor.
3-Subl dosya.uzantısı yazarakda o dosya içindeki yaptığımız değişiklikleri görebiliriz.
### `git log :` Versiyon değişikliklerini detaylı bir şekilde görebiliriz.
### `git log –oneline :` versiyon değişikliklerini kısa özet olarak gösterir.
### `rm dosyaadı.uzantısı:` (Dosya silme)yazarsak o klasör içindeki dosyayı silmiş oluruz.
### `rm –r klasöradı`  : (Klasör silme) Klasör silmek için o klasör dizinin içinde olmamız gerekir.Yoksa o klasörü silemeyiz.

### Git Dersleri & Commit & Log
1- `git init :` cd ile proje dosyasına  gelip, git init yaparakgit projesi haline getirip, proje dosyalarını yükleriz.
2-	git add . add eklemek anlamında . nokta ise şuanki bulunduğumuz dizin demek  bu kod çalıştığı zaman git tüm dosyaları deposuna ekler.Fakat bu komut tek başına yeterli değildir. Aslında bu dosyalar şu anda git deposunda değil, git geçiş deposundadır.
3-	git commit –m “ilk commit” : Geçiş deposundan, git deposuna eklemek  için bu komut kulanılır.
NOT: Eğer geçiş bölgesindeki bir dosyanın içinde değişiklik yaptıysak tekrar
O dosyayı git add dosya.txt  yani dosya adı ve uzantısını yazarak tekrar geçiş bölgesine göndermeliyiz.

### GİT STATUS
 git status: Projenizde herhangi değişiklik olup olmadığını gösterir .Eğer Herhangi bir değişiklik yok ise 
nothing to commit yani kayıt edilecek herhangi bir şey yok demek.
Eğer var ise kırmızı renkte dosyanın adını gösterir.
### `git add dosyaismi.html:` Yazıp direk dosya eklebiliriz. (git add . şeklinde yazsaydık tüm dosyaları ekleyecekti. Daha önce yaptığımız için böyle birşeye ihtiyaç yok.)
### `git commit –m “ikinci dosya eklendi.” :` Geçiş deposundan, git deposuna eklemek  için bu komut kulanılır. 

### GİT AKIŞI 
## Git Dersleri & Diff  Değişiklikler
 ### `git status :` Dediğimizde ; Dosyanın içinde  herhangi bir değişiklik olup olmadığını söyler.
### `Git diff : `Dosyanın içindeki değişiklikleri satır satır  listeler.
### `git add .  :`Diyerek git’in geçiş deposuna gönderiyoruz.
### `git commit –m “ekleme yapıldı” :`Geçiş deposundan, git deposuna eklemek  için  bu komut kullanılır.
### `git diff  dosyaadı.uzantısı  :` yazdığımızda dosyanın içindeki değişiklikleri  görebiliriz. Kırmızı ile yazılanlar çıkarılanlardır.Yeşil ile yazılanlar eklenenlerdir.
### `Eğer  git add.`: Yazıp daha sonra git  diff yazarsanız  hiçbir değişiklik göstermez.Çünkü 
### Dosyaları git add . İle geçiş  dosyasına attığımız için herhangi bir  farklılık göstermiyor.

### GİT BRANCH OLUŞTURMA
### `it branch ne işe yarar:` Proje üzerinde dal oluşturulmak anlamında. Bu dalı bir proje üzerinde bir değişiklik yaparak, yaptığımız değişikliklerin işe yarar olup olmadığını kontrol ederiz ve daha sonra da yaptığımız değişikleri master branch ile birleştiririz. Yada iki farklı yazılımcı front-end ve Backend gibi iki farklı yazılımcının çalışıyorsa projenin backend ve font-end için iki farklı dal oluşturulur.Font-end ve backend kişi istediği değişiklikleri yaptıktan sonra master branch ile birleştirir. git status :dediğimizde hangi branch de olduğumuzu görürüz.Örnek master branch deyiz.

### `git branch dal-1: `  dediğimizde dal-1 isimli bir branch oluşturmuş oluruz.(Klasörün içinde en az bir dosya olmalı.Dosya olmadan bu komut çalışmaz)

### `git branch –a: ` oluşturulan branchleri listemek için kullanılır.

### `Örnek: ` master ve dal-1 adında iki branch miz olduğu görülüyor.Master branch yeşil Durumda bu şuanda master branch üstünde olduğumuzu gösteriyor.

### `git checkout dal-1 :` bu komutla gitmek istediğimiz branch gidiyoruz.

### ` touch dal-1.js :` yazarak dal-1 içinde bir dosya oluşturuyoruz. Ve sırasıyla geçiş bölgesi ve git deposuna gönderiyoruz. Sonra da  git log ile inceliyoruz.Dal-1 de (HEAD) kısm bizim şuanda hangi branchde olduğumuzu gösteriyor. İncelediğimizde dal-1 ve master branch lerinde yaptığımız değişlikleri görebiliyoruz.

### `git checkout master :` dediğimizde master branch ine gitmiş oluruz. sadece o klasörün içinde master branch ine ait dosyalar gözükür. dal-1 branch içindeki dosyalarımız gözükmez.
### Hızlı Branch oluşturulma:
### `git checkout –b dal-2 :` dediğimizde hem branch oluşturmuş hemde dal-2 branch e gitmiş oluyoruz.

### Branch silme :
### `git branch –d dal-1 :` dal 1 isimli dosyayı silmek istediğimizi söyledik fakat hata aldık diyelim.Branchler birleştirilmediği için  hata aldıyorsak . Böyle durumlarda git branch –D dal-1 yazıyoruz. Yani küçük d yerine büyük D kullanıyoruz.

 



