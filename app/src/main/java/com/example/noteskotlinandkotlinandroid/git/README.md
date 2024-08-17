#  GIT GENEL KULLANIMI 

## git init nedir ? 
-> git init komutu, yeni bir Git deposu oluşturmak için kullanılan temel bir Git komutudur. 
Mevcut bir dizini Git deposuna dönüştürür veya boş bir dizinde yeni bir depo başlatır.

-> git Dizini Oluşturulur: Komut, mevcut dizinin kök dizininde .git adında gizli bir dizin oluşturur.
Bu dizin, Git deposunun tüm meta verilerini, geçmişini, konfigürasyonunu ve 
diğer önemli bilgilerini içerir.

-> Çalışma Dizini Hazırlanır: Mevcut dizin, artık bir Git çalışma dizini haline gelir.
Bu, Git tarafından izlenen ve değişikliklerin kaydedildiği dizindir.

## git config  nedir ? 
git config komutu, Git'in yapılandırma ayarlarını yönetmek için kullanılan bir komuttur. 
Bu komut ile Git'in nasıl davranacağını, kullanıcı bilgilerini, uzak depoları ve 
diğer ayarları yapılandırabilirsiniz.

## git config --global user.name  ve git config --global user.name "Fatih Dengiz"
-> user.name : kullanıcı adını öğrenmek için kullanılır ve aynı zamanda kullanıcı adını değiştirmek
içinde kullanılır .
-> ismi değiştirme için "" lar kullanılmazsa ilk kelime parçacığı alır. ilk boşluğa kadar olan kısmı.


## git config --global user.email ve git config --global user.email "dengizfth@gmail.com"
-> user.email : kullanıcı emailini öğrenmek için kullanılır ve aynı zamanda kullanıcı emailini değiştirmek
içinde kullanılır .

## git clone <uzak_depo_url>
-> git clone komutu, belirtilen uzak deponun tüm dosyalarını, geçmişini, dallarını ve 
diğer meta verilerini yerel makinenize indirir. Bu, uzak deponun tam bir kopyasını oluşturur ve 
yerel olarak üzerinde çalışmanıza olanak tanır.
-> git clone https://github.com/username/repository.git

## git clone --branch branchName <uzak_depo_url>
-> git clone branch branchName <uzak_depo_url> komutu, belirtilen bir Git deposunu kopyalarken direkt
 olarak main branch'ini (dalını) çekmenizi sağlar. Normalde git clone komutu varsayılan olarak uzak
 deponun main branch'ini kopyalar, ancak bazı durumlarda farklı bir varsayılan branch kullanılıyor 
 olabilir. Bu komut ise, hangi branch'in varsayılan olarak kullanıldığına bakmaksızın, 
 main branch'ini kopyalamanızı garanti eder.
 * git clone: Git deposunu kopyalamak için kullanılan temel komut.
 * branch main: main branch'ini kopyalamak istediğinizi belirtir.
 * <repo link>: Kopyalamak istediğiniz Git deposunun URL'si.
### git clone --single-branch branchName <uzak_depo_url>
-> sadece belirtilen branch'in geçmişini alarak yukarıdaki işlemleri gerçekleştirir.
* Not: Diğer brach'lerinde geçmişini ve erişimi istemek için direk "git clone" yeterli olucaktır



