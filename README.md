# Patika İlk Repo
Bu repoda ilk hafta verilen Git eğitimine ilişkin ödevler bulunmaktadır. 

## Git Nedir?
Git, dağıtık bir sürüm (versiyon) kontrol sistemi ve kaynak kod yönetim aracıdır. Git, projelerin geçmiş versiyonlarını takip etmek, değişiklikleri yönetmek, farklı geliştiriciler arasında işbirliği yapmak ve projeleri güvenli bir şekilde paylaşmak için kullanılır.

### Git'in sağladığı faydalar:
* Dağınık Yapı
* Hızlı ve verimli olması
* Branching / Merging
* Ekip halinde çalışma
* Güvenlik / İşlemi geri alma

## Git Temel Komutları

- **git init:** Bir Git deposu oluşturur. Bu komutu, bir projeyi Git ile izlemeye başlamak için proje dizininde çalıştırabilirsiniz.

- **git clone *repo-url* :** Bir uzak Git deposunu yerel makinenize kopyalar. 'repo-url', kopyalamak istediğiniz reposunun URL'sini temsil eder.

- **git add *dosya-adı* :** Bir dosyayı Git tarafından izlenen dosyalara ekler. Değişiklikleri Git'in takip etmesini istediğiniz dosyaları bu komutla belirtmelisiniz. Örneğin, git add dosya.txt dosyasını izlemeye alır.

- **git commit -m *<açıklama>* :** Yapılan değişiklikleri bir commit olarak kaydeder. <açıklama>, commit için açıklayıcı bir mesajdır ve yapılan değişikliği tanımlar.

- **git push :** Yereldeki değişiklikleri uzak bir Git sunucusuna gönderir. Bu komut, yerel deponuzdaki commit'leri uzak sunucuya yükler ve paylaşmanızı sağlar.

- **git pull :** Uzaktaki bir Git deposundan değişiklikleri alır ve yerel projenize birleştirir. Bu komut, başka bir geliştiricinin yaptığı değişiklikleri güncellemenizi sağlar.

- **git branch :** Mevcut dalları listeler. Bu komutu çalıştırarak mevcut dalları görüntüleyebilir ve hangi dalda olduğunuzu öğrenebilirsiniz.

- **git checkout -b *yeni-dal* :** Yeni bir dal oluşturur ve üzerine geçer. "yeni-dal", oluşturmak istediğiniz yeni dalın adını temsil eder.

- **git checkout *dal* :** Mevcut dalı değiştirir. 'dal', üzerine geçmek istediğiniz dalı temsil eder.

- **git merge *dal* :** İlgili dali mevcut dala birleştirir. Bu komut, farklı dallardaki değişiklikleri birleştirerek kodu entegre etmenizi sağlar.

- **git status :** Değişiklikleri ve depo durumunu kontrol eder. Bu komutu çalıştırarak hangi dosyaların değiştiğini, hangi dosyaların staged (hazır) olduğunu ve hangi dosyaların commit edilmesi gerektiğini görebilirsiniz.

- **git log :** Commit geçmişini görüntüler. Bu komut, yapılan commit'leri, commit kimliklerini, tarihleri ve commit mesajlarını görüntüler.

- **git diff :** Değişiklikleri gösterir. Bu komut, çalışma dizinindeki değişiklikleri ve henüz staged (hazır) olmayan değişiklikleri gösterir. Kullanımı git diff veya git diff dosya.txt şeklindedir. İkinci kullanım, belirli bir dosyadaki değişiklikleri görüntüler.

- **git rm :** Bir dosyayı Git deposundan ve dosya sisteminizden kaldırır. Kullanımı git rm dosya.txt şeklindedir. Bu komutla dosyayı silip, bir sonraki commit'te silinmiş olarak işaretleyebilirsiniz. Staged ortamına eklenmiş bir dosyanın takibinin bırakılması yani untracked (izlenmeyen) hale getirilmesi sağlayan komuttur.

[Git hakkında daha fazla bilgi için tıklayınız](https://git-scm.com/docs)

---------------------

![Git Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png)
