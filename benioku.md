Edited by Berkay Kotan
# SOLIDWORKS 2020
0 Yüklemeden önce, Windows aracılığıyla giden İnternet erişimini engelleyin
    Güvenlik duvarı veya fiş fişi. .NET Framework 3.5 ve 4.0'ın kurulu olup olmadığını kontrol edin. Eğer
    .NET Framework 3.5 (2.0 dahil) kurulu değil, şu adrese gidin:
    "Denetim Masası" -> "Programlar ve Özellikler" -> "Windows özelliklerini aç veya kapat" ->
    -> ".NET Framework 3.5 (2.0 dahil)" seçeneğini seçin

00. SolidWorks_Flexnet_Server'ı (varsa) SW2019 SSQ sürümünden kaldırın!
     Bunu yapmak için Yönetici SolidWorks_Flexnet_Server\server_remove.bat olarak çalıştırın
     ve "SolidWorks Flexnet Sunucusu" hizmeti kaldırılana kadar bekleyin
     Bundan sonra bilgisayardan SolidWorks_Flexnet_Server klasörünü silin

1. "sw2020_network_serials_licensing.reg" dosyasını çalıştırın ve bilgi eklemek için onaylayın
    Windows Kayıt Defterine

2. "SolidWorks_Flexnet_Server" klasörünü C:'ye kopyalayın, Yönetici olarak çalıştırın
    "SolidWorks_Flexnet_Server\server_install.bat" ve yeni hizmete kadar bekleyin
    "SolidWorks Flexnet Sunucusu" kurulacak ve başlatılacak

3. SolidWorks 2020'yi kurun (gerekirse PDM İstemcisi dahil).
    SolidNetwork Lisans Sunucusunu (SNL) KURMAYIN!
    Lisans Sunucusu tanım girişi sorulduğunda: 25734@localhost

    3.1 Sistem Kontrolü Uyarısı penceresi görünürse, yok sayın (devam etmek için İleri'ye tıklayın)

    3.2 "SolidWorks Seri numarası etkinleştirme veritabanında bulunamadı" uyarısı
        görünür, yok sayın (devam etmek için Tamam'ı tıklayın)

    3.3 Yüklenecek SW ürünlerinin tam listesi görünmüyorsa,
        "Farklı paket seç"e tıklayın ve seçeneği işaretleyin
        "Bu pakete dahil olmayan ürünleri seçin"

    3.4 Yüklenecek yazılım ürünlerini seçin

    3.5 "Kurulum Yöneticisi geçerli aboneliği belirleyemediyse
        Son kullanma tarihi. Bu bilgileri güncellemek için lisansınızı yeniden etkinleştirmek ister misiniz?"
        görüntülendiğinde, Hayır'a basın ve "Bunu daha sonra yapmak istiyor musunuz?" seçeneğinde Evet'e basın. çabuk.

4. Kurulumun sonunda orijinal SolidWorks 2020 program klasörlerinin (varsa) üzerine yazın
    "Program Files\SOLIDWORKS Corp" ve "Program Files (x86)" klasöründeki kırık dosyalarla

    "Program Files\SOLIDWORKS Corp" konumundan değiştirilecek klasörler (varsayılan olarak kurulum sırasında):

    ```java
    C:\Program Dosyaları\SOLIDWORKS Corp\eDrawings
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS CAM
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Composer
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Electrical
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Explorer
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Flow Simulation
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Inspection
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Manage Client
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS PCB
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS PDM
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Plastics
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Visualize
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Visualize Boost
    ```

    "Program Dosyaları (x86)" içinden değiştirilecek klasörler (varsayılan olarak kurulumda):

    ```java
    C:\Program Dosyaları (x86)\SOLIDWORKS PDM
    ```

5. "SolidSQUADLoaderEnabler.reg" dosyasını çalıştırın ve bilgi eklemek için onaylayın
    Windows Kayıt Defterine

6. BİLGİSAYARI YENİDEN BAŞLATIN!

7. SolidWorks > Yardım > SolidNetWork License Manager > Lisans Siparişini çalıştırın

    Premium ürünleri konumlandırmak için "Yukarı Taşı" ve "Aşağı Taşı" düğmelerini kullanın.
    aynı isim Profesyonel ve Standart ürünlerden daha yüksek

    Ayarları kaydetmek için "Uygula"ya tıklayın

    SolidNetWork License Manager'ı kapatmak için "Tamam"a tıklayın

8. Keyfini çıkarın

NOT:

    SW2019 ağ lisanslama çatlağı, öncekinden (SW2010-2018) farklı seri numaraları kullandığından
    sürümleri, SW2020'yi SW2010-2018 ile aynı bilgisayara yüklediyseniz şunları yapmanız gerekir:
 
    SW2017-2018 için ilgili SSQ'nun SW2017-2018 Aktivatörünü çalıştırarak bunları yeniden etkinleştirin (çalıştırın
    SSQ'nun SW2017-2018 Aktivatörü, uygun SW sürümünü seçin ve "Lisansları Etkinleştir"e tıklayın)

    SW2010-2016 için orijinal SolidWorks 2010-2016 program klasörlerini (varsa) değiştirin
    "Program Files\SOLIDWORKS Corp" ve "Program Files (x86)" klasöründeki kırık dosyalarla

    "Program Files\SOLIDWORKS Corp" konumundan değiştirilecek klasörler (varsayılan olarak kurulum sırasında):
   
C:\Program Dosyaları\SOLIDWORKS Corp\eDrawings
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS CAM
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Composer
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Electrical
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Explorer
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Flow Simulation
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Inspection
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Manage Client
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS PCB
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS PDM
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Plastics
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Visualize
    C:\Program Dosyaları\SOLIDWORKS Corp\SOLIDWORKS Visualize Boost