# Araştırma Ödevi


1. Solid Prensiplerini Öğren.
2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)


51. İstanbul C# .NET CORE ile MVC Bootcamp HomeWork

SOLİD PRENSİPLERİ

Solid bir yazılım geliştiricinin esnek ve gelişmeye açık object oriented programlama yaparken uyması gereken kuralların bir araya getirildiği bir prensiptir. Dünya standartlarında yazılım geliştirmek için uymamız gereken bu prensipler 5 başlıkta ele alınıyor.
1- Single Responsibility Principle: Tek sorumluluk anlamına gelen bu kuralın amacı projede bir değişiklik yapılmak istendiğinde buna bağlı olarak nelerin etkileneceği düşüncesinden kurtulmak ve özgürce isteğimiz geliştirmeyi yapabilmemize olanak sağlamaktır. Her bir method sadece kendisine verilen işi yapmalıdır mantığıyla hareket edilmesi gerektiğini ifade eder.
2- Open/Closed Principle: Açık kapalı prensibi projemizdeki nesnelerin geliştirmeye açık ama değişime kapalı olmaları anlamına gelmektedir. Oluşturduğunuz nesneler zaman içerisinde ek özellikler kazanabilir genişlemeye açık olurlar bu normal bir yazılım projesinde kaçınılmaz bir durumdur. Ama temel nesne değişime kapalı tutulmalıdır.
3- Liskov ‘s Substitution Principle: Yerine geçme prensibi kalıtım alarak türeyen sınıfların kalıtım aldıkları nesnenin tüm özellikleri kullanmalı ve sonrasında kendi özelliklerini barındırmasını hedefleyen bir prensiptir eğer nesne kalıtım aldığı objenin tüm özelliklerini kullanmaz ise ortaya gereksiz kod yığınları oluşur ve sonrasında kalıtım alınan objenin diğerlerinden ayrılması için if else bloklarına ihtiyaç olur ve bu durum son derece verimsiz bir yazılıma sebep olur.
4- Interface Segregation Principle : Arayüz ayırım prensibi, bir arayüze gerektiğinden fazla yetenek eklenmemesi gerektiğini söyler. Nesnelerin ihtiyaç duymadıkları fonksiyonların Interface’lerinden münkün olduğunca ayrıştırılmasıdır.
5- Dependency Inversion Principle : Bağımlılığın ters çevirilmesi ilkesine göre üst seviye sınıflar, modüller, methodlar vs. alt seviyeli sınıflara bağımlı olmamalıdır. Alt sınıflarda yapılan değişiklikler üst sınıfları etkilememelidir. Yüksek seviyeli sınıflar, düşük seviyeli sınıflara bağlı olmamalı, her ikisi de soyut kavramlara bağlı olmalıdır.

Takip Ettiğim Kişiler

1-) İbrahim Öz : Zamanında Bilge Adam da eğitmen iken derslerinin kaydını alıp youtube platformuna .NET Yazılım Uzmanlığı ile ilgili kapsamlı bir video serisi oluşturmuştu. Videolarından çok fazla detay öğrendim.

2-) Engin Demiroğ : Udemy ve Youtube üzerinde denk gelmiştim. Şu sıralar canlı yayınlarla birçok farklı programlama dilini; “dilin ne olduğuna takılmayın mantığını kavrayın” tarzıyla gösteriyor.

3-) Sadık Turan : Yine Youtube ve Udemy üzerinden ağırlıklı olarak WEB Programlama olsa da birçok farklı dilde eğitimleri mevcut bir yazılımcı.,

4-) Gökhan Kandemir : Kendisi yazılım mühendisi. Java, JavaScript, Python, Mobil Uygulama vs. birçok dilde eğitimleri mevcuttur. 

5-) Sadi Evren Şeker : Kendisi akademisyen, ayrıca youtube ve udemy üzerinden bir çok eğitim veriyor. İşin teorik tarafına çok hakim olduğu için düşüncelerini değerli buluyorum.

Takip Ettiğim Etkinlik Grupları

1-) RPA Türkiye
2-) RPA İstanbul Community

Takip Ettiğim Sayfalar

1-) Stackoverflow
2-) IFTTT : IF This Than That. İçerisinde otomasyonlar için birçok servis bulunduran bir sayfa
3-) Medium
4-) Devnot
5-) gencayyildiz.com
6-) W3schools : Programlada syntaxları yada nasıl yapılıyordu gibi sorularım olduğun da kullandığım ve çok yararlı bulduğum bir sayfa
7-) Mockaroo : SQL için çalışma hazır çalışma dataları oluşturmamızı sağlayan bir site

#### Microsoft Build 2020 Etkinlikte Duyurulan Yenilikler

Build 2020’de operasyonel veritabanı hizmetlerini ve analitiği gerçek zamanlı olarak bir araya getiren Azure Synapse Link tanıtıldı. Maliyetleri düşüren ve zaman kazandıran Azure Synapse Link, veri hareketlerini yönetmeye gerek kalmadan müşterilerin değerli bilgiler elde etmesini sağlıyor.

Geliştiricilerin Visual Studio ve Visual Studio Code'dan Teams uygulamaları oluşturmaları ve yayınlamaları için Microsoft Teams'e, yenilikler sunuldu. Bu yeni yetenekler BT yöneticilerinin Teams’teki kullanıcıların iş kollarını ve ISV uygulamalarını değerlendirmesine ve iş dağılımı yapmasına olanak tanıyor.

Yeni güncellemeler eklenen Fluid Framework, açık kaynak platformu olarak geliştiricilere sunulmaya başlandı. Böylece Office.com ve Web için Outlook'taki Fluid bileşenleri de son kullanıcılara sağlanmış oldu.
Azure Machine Learning ve OSS araçlarına getirilen yeniliklerle müşterilerin yapay zekâ modellerini daha sorumlu bir şekilde kullanmasına yardımcı olmak için yeni Responsible ML (Sorumlu Makine Öğrenmesi) araçları sunuldu. Bu araç, model yorumlama yeteneğini geliştirerek veri güvenliğini ve kullanıcı gizliliği garanti altına alacak, yapay zeka sistemlerinin geliştirilmesinde sorumluluk anlayışını güçlendirecek.

Etkinlikte, 1 milyar Windows 10 cihazında birlikte uygulama geliştirmeye yardımcı olmak için Project Reunion girişimi de tanıtıldı. Project Reunion, Win32 ve UWP API'leri ile entegrasyonu kolaylaştırmak ve Windows 10 sürümleri kullanılan tüm cihazlarda çalışan kullanışlı uygulamalar geliştirmek üzere bir “Windows geliştirici platformu” olarak oluşturuldu.

Power Automate çözümüne kapsamlı düşük kodlu Robotik Proses Otomasyonu (RPA) teknolojisini sunmak için yatırımlarını sürdüren Microsoft, düşük kodlu ve kullanımı kolay RPA geliştirme ortamlarının lider sağlayıcısı Softomotive'i satın aldı. Softomotive’in teknolojisi, Microsoft müşterilerinin işlerini kolaylaştırmak için kullanıcı arayüzü akışlarına destek olan çözümler sunmaya başladı.

Etkinlikte, Azure'da yer alan dünyanın en güçlü süper yapay zekâ bilgisayarlarından birini de duyuruldu. OpenAI ile işbirliğiyle özel olarak geliştirilen bu süper bilgisayar gücünü Azure bulut altyapısından alıyor. Sistem, dağıtılmış devasa yapay zekâ modelleri geliştirmek için özel olarak tasarlandı.

Visual Studio ürün ailesiyle Microsoft, her geliştiriciye sınıfının en iyisi araçları sağlanmaya devam ediyor. Build 2020’de, yeni bir geliştirici kutusu kurmak, yeni bir projeye katılırken veya uzaktan çalışmaya geçerken ortak bir senaryo oluşturmak için Visual Studio Codespaces de tanıtıldı. VS Codespaces, geliştiricilerin dakikalar içinde tamamen yapılandırılmış geliştirme ortamları oluşturması için bulutun gücünden faydalanıyor.
