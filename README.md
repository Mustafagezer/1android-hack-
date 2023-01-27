# 
Tlfn hack.. PhoneSploit-Pro
  

AzeemIdrisi
/
PhoneSploit-Pro
Halk
Bir Meterpreter oturumu almak için ADB ve Metasploit-Framework kullanarak Android cihazlardan uzaktan yararlanmaya yönelik hepsi bir arada bilgisayar korsanlığı aracı.

azeemidrisi.github.io/phonesploit-pro/
Lisans
 GPL-3.0 lisansı
 334 yıldız 59 çatal 
kod
Sorunlar
1
Çekme istekleri
Tartışmalar
Hareketler
Projeler
wiki
Güvenlik
içgörüler
AzeemIdrisi/PhoneSploit-Pro
En son taahhüt
@AzeemIdrisi
AzeemIdrisi
…
10 saat önce
Git istatistikleri
Dosyalar
BENİOKU.md
PhoneSploit Pro
Metasploit Entegrasyonu ile PhoneSploit.
GitHub sürümü (tarihe göre en son sürüm) Kod Faktörü Piton GitHub Yayın Tarihi GitHub son işlemi GitHub Repo yıldızları GitHub çatalları

Python( Android Debug ADBBridge) ve Metasploit-Framework.

Tek Tıklamayla bir Meterpreter oturumu almak için Tam Otomasyon
Bu araç , Android Cihazını tek bir tıklamayla tamamen hacklemek için Metasploit-Framework ve ADB'yi kullanarak hedef cihazda yükü otomatik olarak Oluşturabilir , Yükleyebilir ve Çalıştırabilir .

Bu projenin amacı, Android cihazlarda penetrasyon testini kolaylaştırmaktır. Artık komutları ve bağımsız değişkenleri öğrenmek zorunda değilsiniz, PhoneSploit Pro bunu sizin için yapıyor. Bu aracı kullanarak Android cihazlarınızın güvenliğini kolayca test edebilirsiniz.

Özellikler
v1.0
ADB'yi uzaktan kullanarak cihazı bağlayın.
Bağlı cihazları listeleyin.
Tüm cihazların bağlantısını kesin.
Bağlı cihaz kabuğuna erişin.
ADB Sunucusunu durdurun.
Ekran görüntüsünü alın ve otomatik olarak bilgisayara çekin.
Ekran Hedef cihaz ekranını belirli bir süre için kaydedin ve otomatik olarak bilgisayara çekin.
Hedef cihazdan dosya/klasör indirin.
Bilgisayardan hedef cihaza dosya/klasör gönderin.
Bir uygulama çalıştırın.
Bilgisayardan hedef cihaza bir APK dosyası yükleyin.
Bir uygulamayı kaldırın.
Hedef cihazdaki tüm yüklü uygulamaları listeleyin.
SystemHedef cihazı , Recovery, Bootloader, olarak yeniden başlatın/yeniden başlatın Fastboot.
Cihazı Tamamen Hackleyin :
IP AddressAyarlamak için otomatik olarak getirin LHOST.
kullanarak otomatik olarak bir yük oluşturun msfvenom, kurun ve hedef cihazda çalıştırın.
Ardından, bir oturum almak için Metasploit-Framework'ü otomatik olarak başlatın ve kurun.meterpreter
Oturum almak meterpreter, cihazın Metasploit-Framework kullanılarak tamamen saldırıya uğradığı ve onunla her şeyi yapabileceğiniz anlamına gelir.
v1.1
Hedef cihazların tüm dosya ve klasörlerini listeleyin.
Tüm WhatsApp Verilerini bilgisayara kopyalayın.
Tüm Ekran Görüntülerini bilgisayara kopyalayın.
Tüm Kamera Fotoğraflarını bilgisayara kopyalayın.
Anonim olarak ekran görüntüsü alın ve ekran kaydı yapın (Dosyayı hedef cihazdan otomatik olarak silin).
Hedef cihazda bir bağlantı açın.
Hedef cihazda bir görüntü/fotoğraf görüntüleyin.
Hedef cihazda bir ses çalın.
Hedef cihazda bir video oynatın.
Cihaz bilgilerini alın.
Pil bilgilerini alın.
Cihazı uzaktan kontrol etmek için Anahtar Kodları kullanın.
v1.2
Hedef cihaz üzerinden SMS gönderin.
Cihazın kilidini açın (Otomatik ekran açık, yukarı kaydırın ve şifre girişi).
Cihazı kilitle.
Cihazdan bilgisayara tüm SMS'leri boşaltın.
Tüm Kişileri cihazdan bilgisayara aktarın.
Tüm Arama Günlüklerini cihazdan bilgisayara aktarın.
Yüklü bir uygulamadan APK'yı çıkarın.
v1.3
Hedef cihazı Yansıtın ve Kontrol Edin.
Gereksinimler
python3: Python 3.10 veya Daha Yenisi
adb: Android Hata Ayıklama Köprüsü (ADB)Android SDK Platform Tools
metasploit-framework: Metasploit Çerçevesi ( msfvenomve msfconsole)
scrcpy: Scrcpy (Ekran Kopyası)
PhoneSploit Pro'yu çalıştırın
PhoneSploit Pro'nun herhangi bir kuruluma ihtiyacı yoktur ve doğrudanpython3

Linux / macOS'ta:
Gerekli tüm yazılımların yüklendiğinden emin olun .

Terminali açın ve aşağıdaki komutları yapıştırın:

git clone https://github.com/AzeemIdrisi/PhoneSploit-Pro.git
cd PhoneSploit-Pro/
python3 phonesploitpro.py
Windows'ta:
Gerekli tüm yazılımların yüklendiğinden emin olun .

Terminali açın ve aşağıdaki komutları yapıştırın:

git clone https://github.com/AzeemIdrisi/PhoneSploit-Pro.git
cd PhoneSploit-Pro/
platform-toolsEn son buradan indirin ve çıkarın .

platform-toolsAyıklanan veya adbdizindeki tüm dosyaları PhoneSploit-Pro dizinine kopyalayın ve ardından şunu çalıştırın:

python phonesploitpro.py
Ekran görüntüleri
Ekran Görüntüsü Sayfa 1 Ekran Görüntüsü Sayfa 2 Ekran Görüntüsü Sayfa 3

ADB'yi yükleme
Linux'ta ADB:
Terminali açın ve aşağıdaki komutları yapıştırın:

Debian / Ubuntu
sudo apt install adb
Fötr şapka
sudo dnf install adb
Arch Linux / Manjaro
sudo pacman -Sy android-tools
macOS'ta ADB:
Terminali açın ve aşağıdaki komutu yapıştırın:

brew install android-platform-tools
veya Bu bağlantıyı ziyaret edin: Buraya Tıklayın

Windows'ta ADB:
Bu bağlantıyı ziyaret edin: Buraya tıklayın

Termux'ta ADB:
pkg install android-tools
Metasploit-Framework Kurulumu
Linux / macOS'ta:
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
veya Bu bağlantıyı takip edin: Buraya Tıklayın

veya Bu bağlantıyı ziyaret edin: Buraya Tıklayın

Windows'ta:
Bu bağlantıyı ziyaret edin: Buraya tıklayın

veya Bu bağlantıyı takip edin: Buraya Tıklayın

scrcpy'yi yükleme
scrcpyEn son kurulum talimatları için GitHub sayfasını ziyaret edin : Buraya Tıklayın

Windows'ta : Ayıklanan scrcpy klasöründeki tüm dosyaları PhoneSploit-Pro klasörüne kopyalayın.

Öğretici
Android Telefonu ilk kez kurma
Geliştirici Seçeneklerini Etkinleştirme
aç Settings_
About Phone. _
bul Build Number_
Build Number7 kez üzerine dokunun .
Developer optionsMenüyü etkinleştirmek için deseninizi, PIN'inizi veya şifrenizi girin .
Menü Developer optionsşimdi Ayarlar menünüzde görünecektir.
USB Hata Ayıklamayı Etkinleştirme
aç Settings_
System> öğesine gidin Developer options.
Aşağı kaydırın ve Etkinleştir USB debugging.
Bilgisayarla Bağlanma
Android cihazınızı ve adbana bilgisayarınızı ortak bir Wi-Fi ağına bağlayın.
Cihazı bir USB kablosuyla ana bilgisayara bağlayın.
Bilgisayarda terminali açın ve aşağıdaki komutu girin:
adb devices
Telefonunuzu yeni bir PC'ye ilk kez bağladığınızda Android telefonda bir açılır pencere belirecektir : Allow USB debugging?.
Always allow from this computerOnay kutusuna tıklayın ve ardından öğesine tıklayın Allow.
Ardından aşağıdaki komutu girin:
adb tcpip 5555
Artık Android Telefonu Wi-Fi üzerinden bağlayabilirsiniz.
USB kablosunu çıkarın.
Settings> About Phone> Status> öğesine gidin IP addressve telefonun IP Address.
PhoneSploit Pro'yu çalıştırın ve Wi-Fi üzerinden bağlanmak Connect a deviceiçin hedefi seçip girin.IP Address
Android telefonu bir dahaki sefere bağlamak
Android cihazınızı ve ana bilgisayarınızı ortak bir Wi-Fi ağına bağlayın.
PhoneSploit Pro'yu çalıştırın ve Wi-Fi üzerinden bağlanmak Connect a deviceiçin hedefi seçip girin.IP Address
Bu araç üzerinde test edilmiştir
✅ubuntu
✅Linux Nane
✅Kali Linux
✅Fötr şapka
✅Arch Linux
✅Papağan Güvenlik İşletim Sistemi
✅Windows 11
✅Termux (Android)
Tüm yeni özellikler öncelikle Linux'ta test edilmiştir , bu nedenle PhoneSploit Pro'yu çalıştırmak için Linux önerilir. Bazı özellikler Windows'ta düzgün çalışmayabilir.

Feragatname
Ne proje ne de geliştiricisi herhangi bir yasa dışı faaliyeti teşvik etmez ve bu projenin neden olduğu herhangi bir yanlış kullanım veya zarardan sorumlu değildir.
Bu proje sadece penetrasyon testi amaçlıdır.
Lütfen bu aracı başkalarının cihazlarında onların izni olmadan kullanmayın.
Bu aracı başkalarına zarar vermek için kullanmayın.
Bu projeyi yalnızca kendi cihazlarınızda sorumlu bir şekilde kullanın.
Geçerli tüm yerel, eyalet, federal ve uluslararası yasalara uymak son kullanıcının sorumluluğundadır.
