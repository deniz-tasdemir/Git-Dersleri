# Github-Egitimi-Git-Dersleri
## GİT NOTLARIM

 ### GİT PROJESİ OLUŞTURMA

### GİT AYARLAR
### `git –version  :`gitin versionu öğrenmiş oluruz.

 
### ;`git –config list :`ile yapılandırılımış ayarlarmızı görebiliriz.
 

### `git config –global user.name` “github kullanıcı adımızı yazıyoruz.”  :buradaki global anlamda
## yapılandırma yaptığımızı gösterir.
### `git config –global user.email ` “email adresinizi yazıyoruz”  mail adresimizi tanımlıyoruz. Bu şekilde ayarları bitirmiş oluyoruz.


### TERMİNAL KOMUTLARI
### `pwd: `Terminal üzerinde bulunduğumuz  tam adresini verir.
### `ls:`Mevcut bulunduğumuz dosyaları ve dizileri listeler.### Ls -a : Mevcut bulunduğumuz gizli dosyaları ve dizileri listeler.###  cd : Dizin değiştirme k için kullanılır örnek cd desktop gibi.. Normal Windows den Myproject diye bir klasör oluşturup,  içine cd komutu ile girebiliriz.
### `cd.. :`Bu komut ile bir önceki dizine geri gelebiliriz.
### `Clear:` Terminali temizler. Yada kısayol tuşu CTRL+L tuşu ile temizleyebiliriz.
### `Touch :` touch  dosya.txt (dediğimizde bulunduğumuz klasörün içine dosya.txt adında dosya oluştururuz.)
### `mkdir dosyaadı`  bu şekilde bulunduğumuz dizine dosya oluştururuz.
### `vi dosyaadı.uzantısı :` yazıp o dosyayı terminal üzerinden açabiliriz.
# Terminalden dosya içine bir şey yazmak için;
# 1-Önce i tuşuna basınıyoruz be yazmak istediklerimizi yazıyoruz.
# 2-Daha sonra önce “Esc” Tuşuna basıp “:wq” bır w write yani yazmak kelimesinden geliyor q da quit yani çıkmakdan geliyor.
# 3-Subl dosya.uzantısı yazarakda o dosya içindeki yaptığımız değişiklikleri görebiliriz.
# git log : Versiyon değişikliklerini detaylı bir şekilde görebiliriz.
# git log –oneline : versiyon değişikliklerini kısa özet olarak gösterir.
### `rm dosyaadı.uzantısı:` (Dosya silme)yazarsak o klasör içindeki dosyayı silmiş oluruz.
### `rm –r klasöradı`  : (Klasör silme) Klasör silmek için o klasör dizinin içinde olmamız gerekir.Yoksa o klasörü silemeyiz.

### Git Dersleri – 6 – Commit & Log
# 1-	git init : cd ile proje dosyasına  gelip, git init yaparakgit projesi haline getirip, proje dosyalarını yükleriz.
# 2-	git add . add eklemek anlamında . nokta ise şuanki bulunduğumuz dizin demek  bu kod çalıştığı zaman git tüm dosyaları deposuna ekler.Fakat bu komut tek başına yeterli değildir. Aslında bu dosyalar şu anda git deposunda değil, git geçiş deposundadır.
# 3-	git commit –m “ilk commit” : Geçiş deposundan, git deposuna eklemek  için bu komut kulanılır.
## NOT: Eğer geçiş bölgesindeki bir dosyanın içinde değişiklik yaptıysak tekrar
## O dosyayı git add dosya.txt  yani dosya adı ve uzantısını yazarak tekrar
### geçiş bölgesine göndermeliyiz.

### GİT STATUS
# git status: Projenizde herhangi değişiklik olup olmadığını gösterir .Eğer Herhangi bir değişiklik yok ise 
# nothing to commit yani kayıt edilecek herhangi bir şey yok demek.
# Eğer var ise kırmızı renkte dosyanın adını gösterir.
### `git add dosyaismi.html:  Yazıp direk dosya eklebiliriz. (git add . şeklinde yazsaydık tüm dosyaları ekleyecekti. Daha önce yaptığımız için böyle birşeye ihtiyaç yok.)
# 4-	git commit –m “ikinci dosya eklendi.” : Geçiş deposundan, git deposuna eklemek  için bu komut kulanılır. Git Dersleri – 8 – Git İş Akışı 

## Git Dersleri – 9 – Diff & Değişiklikler
# git status : Dediğimizde ; Aşağıdaki örnekte dosyanın içinde bir değişiklik olduğunu söylüyor. Modified lesson-4.html Olarak hangi dosyada değişiklik yapılmışsa onu belirtiyor.
### `Git diff : `Dosyanın içindeki değişiklikleri satır satır  listeler.
### `git add .  :`Diyerek git’in geçiş deposuna gönderiyoruz.
### `git commit –m “ekleme yapıldı” :`Geçiş deposundan, git deposuna eklemek  için  bu komut kullanılır.
### `git diff  dosyaadı.uzantısı  :` yazdığımızda dosyanın içindeki değişiklikleri  görebiliriz. Kırmızı ile yazılanlar çıkarılanlardır.Yeşil ile yazılanlar eklenenlerdir.
### `Eğer  git add.`: Yazıp daha sonra git  diff yazarsanız  hiçbir değişiklik göstermez.Çünkü 
### Dosyaları git add . İle geçiş  dosyasına attığımız için herhangi bir  farklılık göstermiyor.


