# Discord RPC Maker

# Destek & Yardım sunucusu:
https://discord.gg/3AMZuA8

# Gerekli Programlar
- Node
https://nodejs.org/en/

- Git
https://git-scm.com/download/win

- NotePad++
https://notepad-plus-plus.org/download/


# Kurulum
1- İndirdikten sonra dosyaları zipten çıkarın.

2- Arama yerine cmd yazın ve açılan yere "cd <dosyanızın konumu>" yazın.

3- "npm install discord-rpc" yazın ve indirmesini bekleyin.

4- Ardından https://discordapp.com/developers/applications/me sitesine girin.

5- Bir "Application" yani "App" oluşturun. (Discordda "<app adı> Oynuyor" şeklinde gözükür.)

6- Rich Presence kısmına gelin ve Art Assets kısmına girin.

7- Rich Presence Assets kısmında "Add Image" butonuna basıp logonuzu yükleyin.

8- Tekrar Rich Presence kısmına tıklayıp Small Image Key ve Large Image Key kısmından yüklediğiniz logoyu seçin.

9- General Information kısmından ClientID'yi alın ve config.json dosyasında bulunan "appid" kısmının önüne koyun.

10- Yazıları düzenlemek için "config.json" dosyasını açın.

10 - Son olarak onları değiştirip kaydettikten sonra "run.bat" dosyasına çift tıklayın ve çalıştırın.

# config.json'da Bulunan Yazıların Anlamları
- "AppID": oluşturduğumuz application'un ID'si.
 - "durum": ilk satırda yazacak olan mesaj.
 - "aciklama": ikinci satırda yazacak olan mesaj.
 - "buyukResimAd": large (büyük) olarak yüklediğimiz fotoğrafa koyduğumuz ad.
 - "kucukResimAd": small (küçük) olarak yüklediğimiz fotoğrafa koyduğumuz ad.
 - "buyukResimYazi": large (büyük) resime imleç geldiğinde yazacak olan mesaj.
 - "kucukResimYazi": small (küçük) resime imleç geldiğinde yazacak olan mesaj.
 
