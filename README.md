Sisli Sancaklar — oynanabilir ilk sürüm

Bu, Kül Geçidi'nden ayrı bir strateji oyunudur.

## Hemen oyna

1. `INTERNETSiZ_OYNA.html` dosyasına çift tıkla.
2. Bir medeniyet seç. İstersen üstteki **Ses kapalı** düğmesine dokunup müziği aç.
3. **İnternetsiz sefere çık** düğmesine bas.
4. Bir köylüye, sonra ağaca veya madene dokun. Köylü kaynağı merkeze taşır.
5. Köylü seçiliyken alttan bina seç, boş yere dokun.
6. Oba merkezine dokunarak köylü; kışla, okçu ocağı ve ahırdan asker eğit.
7. Ordunu seçip düşmana dokun. Rakip oba merkezlerini yıkarak kazan.

Haritayı sürükle. İki parmakla yakınlaştır veya + / − kullan. Telefonu yatay tutmak daha fazla alan gösterir.
Evlere odun harcayarak nüfus sınırını artır. Depoyu kaynaklara yakın kurmak taşıma süresini kısaltır.
Tarlalar yiyecek verir; sonsuz değildir. Okçu mızraklıya, süvari okçuya, mızraklı süvariye güçlüdür.
Medeniyetlerin bonusları seçim ekranında açıklanır; hepsi açıktır, satın alma yoktur.

## Kayıt

İnternetsiz sefer her 10 saniyede ve duraklatınca bu tarayıcıya kaydolur.
**Kayıtlı sefere devam et** ile dönersin.
Dosyayı taşımak, başka tarayıcı kullanmak veya tarayıcı verilerini silmek kayda erişimi etkileyebilir.
Kayıt farklı cihazlar arasında aktarılmaz. Wi-Fi maçları bu sürümde diske kaydedilmez.

## Aynı Wi-Fi'de 4 telefon

Bu ilk sürümde bilgisayar oda sunucusudur. Bilgisayar oyuna katılmak zorunda değildir.
Dört oyuncu telefonlardan bağlanabilir.

1. Bütün dosyaları aynı klasörde tut. ZIP aldıysan önce tümünü çıkar.
2. Bilgisayarda `ODAYI_AC.cmd` dosyasını çalıştır.
3. Açılan pencerede `http://192.168...:8787` benzeri adresler görünür.
4. Telefonları bilgisayarla **aynı Wi-Fi ağına** bağla.
5. Telefonların Chrome adres çubuğuna uygun yerel adresi yaz.
6. Herkes adını ve medeniyetini seçsin.
7. Bir kişi **Aynı Wi-Fi → Oda kur** desin. Diğerleri kodu yazıp **Katıl** desin.
8. Oda sahibi **Maçı başlat** desin. Boş koltuklar bilgisayar oyuncularıyla dolar.

Pencereyi kapatırsan oda kapanır. Oyuncu ayrılırsa yerini bilgisayar alır.
Geçici bağlantı kopmasında sayfa yeniden bağlanmayı dener; 30 saniye haber alınamayan oyuncuyu yapay zekâ devralır.

Bilgisayarda Node.js gerekir. Başlatıcı önce normal Node.js kurulumunu, sonra bu bilgisayardaki Codex çalışma ortamını arar.
Node.js bulunamazsa [resmî Node.js sitesi](https://nodejs.org/) üzerinden LTS kurulumu gerekir.
Telefon bağlantısı engellenirse Windows Güvenlik Duvarında Node.js'in **özel ağ** erişimini kontrol et.
Güvenlik duvarını tamamen kapatma. Misafir Wi-Fi ağlarında cihazların birbirine erişimi kapalı olabilir.
Bu adres internette herkese açık bir site değildir. Modem portu açmak gerekmez.

## Telefona ana ekran oyunu olarak eklemek

1. Yeni ve ayrı bir GitHub deposu oluştur. Kül Geçidi deposunun üzerine yazma.
2. Aşağıdaki web dosyalarını depo köküne yükle:
   `index.html`, `engine.js`, `app.js`, `style.css`, `sw.js`, `manifest.webmanifest`,
   `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-maskable.png`.
3. Ayarlar → Pages → main → / (root) → Save.
4. Yayınlanan HTTPS adresini telefonda aç, dosyaların hazır mesajını bekle.
5. Android Chrome'da sunulursa **Telefona / ana ekrana ekle** düğmesini kullan;
   tarayıcı menüsünde **Uygulamayı yükle / Ana ekrana ekle** de bulunabilir.
6. İlk yükleme tamamlandıktan sonra internetsiz seferi açabilirsin.

HTTPS üzerinden ilk açılış internet gerektirir. Tarayıcı önbelleği silinirse dosyaları tekrar indirmek gerekir.
Yerel `http://192.168...` adresinde ana ekrana uygulama kurulumu bekleme; bu adres Wi-Fi maçları içindir.
GitHub Pages oda sunucusunu çalıştırmaz. Wi-Fi oynamak için bilgisayarın gösterdiği yerel oda adresini ayrıca açmalısın.

## Bu sürümde neler var?

- 10 özgün hayalî medeniyet; ekonomi, can, menzil, hız ve eğitim bonusları.
- 4 arazi teması ve sayı tohumu değiştikçe farklı kaynak yerleşimleri.
- 4 oyuncu; herkes tek veya 2'ye 2. İnternetsiz modda sen + 3 yapay zekâ.
- Köylü, mızraklı, okçu, süvari; 8 bina türü (merkez başlangıç binasıdır).
- Kaynak taşıma, inşa, eğitim kuyruğu, nüfus, 3 gelişim dönemi.
- Görüş alanı, küçük harita, dokunmatik seçme, sürükleme ve yakınlaştırma.
- Özgün Canvas çizimleri, sentezlenen müzik ve işlem/savaş sesleri.
- Yerel kayıt, web uygulaması önbelleği ve ücretsiz yerel oda sunucusu.

## Sınırlar

Bu bir ilk prototiptir; bitmiş mağaza ürünü değildir.
APK/AAB üretilmedi; Play Store yayını yapılmadı.
Telefonun kendisi oda sunucusu olamaz; Wi-Fi için bilgisayar açık kalır.
Farklı ağlardan internet maçı, hesap, sohbet, sıralama, ücretli içerik yoktur.
Haritalar açık arazidir; engeller etrafında gelişmiş yol bulma, surlar, gemiler ve kuşatma sistemleri yoktur.
Askerlerin temel görselleri paylaşılır; medeniyet renkleri ve gerçek sayısal bonusları farklıdır.
Sunucu komut sahipliğini kontrol eder; ancak istemcilere tüm dünya durumu gönderildiği için rekabetçi anti-hile ürünü değildir.

## Testler

`node --test tests.cjs` komutu temel ekonomi, inşa, savaş, kayıt ve dört istemcili yerel ağ testlerini çalıştırır.
`node build.cjs` tek dosyalı internetsiz sürümü yeniden üretir.
Testler gerçek dört telefonda yapılan oyun testinin yerine geçmez.

## Varlık ve hak notu

Grafikler, arayüz çizimleri ve müzik bu proje için kodla üretildi; başka oyundan ses, sprite, harita, logo veya yazı tipi dosyası alınmadı.
Müzik, Web Audio ile yerel olarak sentezlenir; haricî kayıt/ses örneği kullanılmaz.
Sistem yazı tipleri kullanılır. Çalışma adı için marka araştırması tamamlanmadı.
Sıfır telif/marka şikâyeti garantisi verilmez. Ticari yayın öncesinde ad, görsel kimlik ve kullanılan araçların hak koşulları ayrıca kontrol edilmelidir.
