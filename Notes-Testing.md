

Test; hata bulma amaçlı planlı bir şekilde gerçekleştirilebilen eylemler dizisi, bir doğrulama

metodudur.

Planning

Care and Support

Defining

Testing

Building

Planning: “Bu porje ile ne başarmak istiyoruz?” sorusuna cevap aranır.

Analiz: Bu porje ile istediğimiz noktaya “nasıl” geliriz?

Geliştirme: Kod yazımı gerçekleşir.

Test: İstediğimiz sonuca varabildik mi?

Bakım ve Destek: Kullanıcıdan geri bildirim alınarak uygulama geliştirilir.

Bir Testçinin Görevleri

Test Plan

Test Tasarım (case tasarım, test adımları yazılır)

Test Koşulması( beklenen sonucu veriyor mu kontrol eder)

Test Tamamlama(yüksek öncelikli hata kayıtları çözüldü, ürün kullanıcıya sunulmaya hazır)

**Test Sürecindeki Faaliyetler**

Test analizi: “ne” sorusu

Hatalar ne kadar erken(analiz aşamasında) fark edilirse maliyet düşük olur. Test edilecek ve

edilmeyecek özellikleri belirle, her özellik test edilmeyi gerektirmez.

Test tasarımı:”nasıl” sorusu

senaryo tasarlama

test verilerinin belirlenmesi

test ortamı tasarlanması

izlenebilirlik kurulması(hangi gereksinime hangi test senaryosu)

test tasarlama

Test oluşturma(implementation):

test ve prosedürleri geliştirme

otomasyon test komut dosyası oluşturma

test takımı oluşturma

test verisi hazırla ve ortama yerleştir

test ortamında çift yönlü izlenebilirlik





Test koşturma(execution):

manuel ya da otomasyon aracı kullanılarak çalıştırma

elde edilen ve beklenen sonuç karşılaştırma

karşılaştırma sonucunda çıkan hataların bildirilmesi

çıkan hataya sebep olan sorunu belirle

Testi tamamlama(completion):

Test log ve raporu incele

Bunları planlamada belirlenen sonlandırma kriterine yakalanıp yakalanmadığına bak.

Test daha yapılmalı mı sonlandırılmalı mı karar ver.

Test proje özetini üst birime raporla.

Yazılım Test Seviyeleri

Birim Test (ilk adımdır, kod yazan yazılımcı yapar,beyaz kutu)

Entegrasyon Testi(birim-sistem arasındaki etkileşime bakılır)

Otomatize Kullanıcı Arayüz Testi(test uygulamada önyüzü dğru şekilde çalıştığını kontrol eder,

masraflıdır, bakım gerektirir)

Sistem ve Kabul Testleri(bütün systemin davranış ve yeteneklerine odaklanır. Amaç proje riskini

azaltmaktır, system kalitesine güven oluşturmak önemlidir. Güven oluşturmak, systemin güven

oluşturduğu ve beklendiği gibi çalıştığının sağlaması yapılır)

Manual Session Based Testing

Automated GUI Tests

Automated API Tests

Automated Integration Tests

Automated Component Tests

Automated Unit Tests

BlackBox testte kullanıcıyı etkileyebilecek hatalar test edilir.

Fonksiyonel Testler:

1)Test uzmanı systemin nasıl çalıştığını kontrol eder.

2)Kullanıcı gereksinimlerini baz alır.

3)Sistem testi

4)Uygulamanın davranışsal akışlarını içerir(işlevsellik)

5)Örn:Duman Testi-Regresyon Testi

Fonksiyonel Olmayan Tesler:





1)Sistemin nasıl cevap verdiğini(response) kontrol eder.

2)Kullanıcı beklentisini baz alır.

3)Sistem testi

4)Uygulamanın performansını kontrollerini içerir.

5)Örn: Yük Testi-Güvenlik Testi

Test senaryosu için kaç senaryo gerekir? 2n

3 koşul varsa = 23=8

**Negative Testing**

Bileşen veya systemin çalışıp çalışmadığı noktaları göstermeyi amaçlayan testler.

Negatif sonuç verecek verilerle de test gerçekleştirilmeli.

➔ Şifre için sadece pozitif tam sayı kabul ediyor diyelim. -1000 gibi bir değer

de dene.

Pozitif testler→ Happy path

**Smoke and Sanity Testing**

Smoke: Uygulama önemli. Uygulamanın yeni sürümü yayınlandıktan sonra fonksiyonların çalışıp

çalışmadığını kontrol etmek için kullanılır, detaya girmez.

Sanity: Yeni uygulama sürümünde hata çözümü sonrası fonksiyonda hataların çözülüp çözülmediğini

kontrol etmek. Sadece kod değişimi olan yer kontrol edilir.

Risk Bazlı Testler

Gelecekte olumsuz sonuçlara yol açacak bir olayın gerçekleşme olasılığını içerir.

Risk hesaplanırken etki ve olma olasılığı göz önüne alınır.

Risk; son kullanıcının karşılaşmaması gereken bir durumla karşılaşmasıdır.

Risk = Etki x Olma olasılığı

Risk düşükse test başarısız olsa bile canlıya alınabilir.

Statik

Dinamik

İş gereksinimi ve analiz

Tasarım(üst)

x

x

x

x

x

Tasarım(detaylı)

Geliştirme

x

x

Kullanıcı Kabul testi





Statik→ yazılım çalışırken hataların neden olduğu arızaları bulmak yerine doğrudan çalışma

ürünlerindeki hataları çalıştırmadan bulur.

Statik, çalışma ürünlerinin tutarlılığı ve iç kalitesini iyileştirmek için

Dinamik, dışarıdan görülebilen davranışlara odaklanır.

**Test Çeşitleri**

**1)Dinamik Testler**

Yazılımın fiziksel olarak çalıştırılarak davranışı gözlemlenir. Genelde test mühendisleri yapar.

Işlevsel testler

İşlevler test edilir. Belirli girdiler ne yapar sorusuna cevap aranır.

Kara kutu test yöntemiyle yapılır. İzlenebilirdir.

Gereksinim temelli test, iş-süeç temelli test

Alan bilgisi

İşlevsel olmayan test

Sistem ne kadar iyi sorusuna cevap arar.

Sistem testleri(sisteme girdi oranı)

Performans testleri(zaman dilimi)

Konfigürasyon uyum(farklı platformlarda nasıl çalışır)

Güvenlik testi(sisteme izinsiz girildiğinde yazılım nasıl çalışıyor)

kullanılabilirlik testi(kullanıcı system ilişkisine bakar örn:atm cihazı- yaş tepkisi farkı)

geri alma(recovery) testi – hata durumunda systemin kendiliğinden beklediğinde düzelmesi

kullanıcı arayüz testi- hata mesajı evrensel olarak kırmızı gösterilir, bunun test edilmesi gibi.

Regresyon Testleri

Yazılım üzerinde yapılan değişiklik sonrası bu değişikliğin yazılım diğer alanlarını etkileyip

etkilemediğini anlamak için kullanılır.

Öncelikli amaç uygulama kritik alanlarının hala beklendiği gibi çalıştığını kontrol etmek için kullanılır.

Kullanıcının yoğun kullandığı alanlar, genelde hata çıkan uygulama alanları, ana fonksiyonlar, yüksek

karmaşık fonksiyonlar, son değişiklik yapılan alan, önemli entegrasyonlar test edilmeli çünkü

zaman=maliyet

**2)Statik Testler**

Yazılım çalıştırılmadan test edilir.

Sadece kod üzerinden değil yazılım iş ürünü üzerinden de olur.

İki türlü yapılır;

-gözden geçirme: yazılım ürünü hatalarını ortaya koyduğu için bunu sunmak ve toplantı yapmak

-statik kod analizi





Yazılım Test Tasarım Teknikleri

\*Kara Kutu Test Tekniği

\*Beyaz Kutu Test Tekniği

\*Deneyim Temelli Test Tekniği

*Test Tekniklerini Etkileyen Faktörler*

*-sistem türü*

*-düzenleyici standartlar(BDDK, EPDK)*

*-müşteri veya sözleşmeden doğan şartlar*

*-risk seviyeleri-türleri*

*-test hedefleri*

*-mevcut belgeler*

*-zaman, bütçe, mevcut araç..*

**Kara Kutu Test Tekniği (Black Box Testing)**

Sadece yazılımın ne iş yapacağı bilinir. Yazılımın yapısı, kod vs bilinmez. Test senaryoları buna göre

oluşturulur, her seviye testte kullanılır. İşlevler tanımlı olmalı.

a)Eşdeğer Aralık Testi(Equivalence Partitioning): Aynı sonucu veren girdi kümeleri(örn:0-100 arasında

değer verdiğin şeyin geçerli yazması)

b)Sınır Değer Analizi(Boundary Value Analysis): 3lü ve 2li kombinasyonları vardır. Eşit aralık testindeki

değerlerin sınırlarında bulunan değerleri test edilir. Yani değişim noktalarında yazılımın davranışı test

edilir.

C)Karar Tablosu(Decision Table Testing): if else then mantığını test etmek için kullanılır.

Koşul

Kural1

Kural2

Eylem

d)Durum Geçiş Testi(State Transition):belli kurallara bağlı şartların oluşmasında göre systemin bir

durumdan diğerine geçerek bir noktada sonlanması durumunu test etmesi. Atm cihazında hatalı şifre

yetersiz bakiye gibi seçeneklerin olması..

e)Kullanım Senaryosu(Use-Case Testing): Kullanıcı ile system arasındaki etkileşimi gösterir.

ATM

Para çekme

Şifre Değişikliği

Havale

X

y

Birincil aktör

banka sistemi

Ikincil aktör

Bakiye sorgulama

**Beyaz Kutu Test Tasarım Tekniği(White Box)**





Yapısal bazlı testler. Kod çalıştırılı, satır satır kod incelenir. İki amacı vardır; ifade kapsamının

ölçülmesi ve test tasarımı kaliteli olsun.

**Tecrübeye Dayalı Test T.**

İşlevler belli değilse ve gereksinimler yeterince kayıt altına alınmadıysa kullanılır.

Error Guessing: ilk test olarak kullanılmamalı. Med yok, otomasyon yok.

Exploratory Testing:amaç öğrenme

Kontrol listesi temelli test: test koşulları kontrol listesine göre uygulanır.

Statik Testler için Araç Desteği

Review

Crucible(kod inceleme)

CodeScene

Checkstyle

PMD(koddaki sorunları bildirir(

İşlevsel Test Araçları(dinamik)

Selenium(web uyg. Test etmek, tüm test tarayıcılarında çalışır)

Ranorex (düşük maliyetli ve kapsamlı)

IBM

HP Quick Test Professional

Performans Test Araçları

Jmeter

HP LoadRunner(uyg testi, system davranışlarını ölçer)

Test Yönetim Araçları

Kualitee(manual ve otomatik, bulut tabanlı)

TestRail

Resmi gözden geçirme adımları

-Planlama

-Gözden geçirmenin başlatılması

-Bireysel gözden geçirme

-Bulguların iletilmesi ve analiz

-Hataların giderimesi ve raporlama

Test stratejisi→testin o proje ya da firmada nasıl ele alındığını ve koşulduğunu belirten dökümana

denir.

**Test stratejisi şablonu**

-kalite nerede başlar

-Neden test

-test piramidi

-test tipleri

-birim test

-arayüz testi





-kabul testi

-regresyon testi

-keşif

-Giriş ve çıkış kriterleri

Geliştirme→Test→Pre-production→Canlı

API: Uygulama arayüz, önyüz ile veritabanı arasındaki iletişimi sağlayan katmana denir.

HTTP: very transferi metodu

APL URL: hangi arayüze çağrı yapılacağını belirler.

HTTP metodları

-Payload (gönderilen veri)

Response code: önyüzde yapılan işlemin başarılı olduğunu belirlemek için kod geri döner. 200lü kod.

Eğer 400-500lü kod gelirse hata vardır. Response message döner.

Response result(cevap sonucu)

Get/read: serverdaki bilgiyi okumak

Post/create: servera oluştur komutu verir.(uygulama veritabanı üzerinde kaynak oluşturmak için

çağrıyı gerçekleştirir)

Put/update:güncelleme

delete: veritabanı üzerinde kayıtlı veriyi siler

\*Kullanıcıyı tanı

\*Uygulamaya geniş perspektiften bak

\*Çapraz tarayıcı testleri(cross browser testing)

\*Keşfet

\*Kullanılabilirlik kontrolleri

Mobil uygulama testleri

Gerçek cihaz üstünde test et.

Cihaz seçimini,işletim sistemini test başlamadan önce seç.

Her zaman oluşabilecek olumsuz durumları düşün.

Uygulama pil gereksinimini test et.

Mobil cihazı yatay olarak da test et.(ekran)

Mobil uygulama türleri

Native-spesifik işletim sistemi için üretilmiştir

Web uygulaması- mobil cihazın tümm fonksiyonlarını kullanamaz

Hbirid- native ve web kombinasyonu. Hızı nativeden daha yavaş.

PgAdmin: Çağru yapabileceğin kullanıcı arayüzü

PostgreSQL: verileri depolayan sql veritabanı





**Waterfall model**

Analiz, tasarım, kodlama, test, sürüm ve bakım gibi safhalardan oluşur. Her safha, başlangıç

noktasında bir önceki safhanın ürettiklerini bulur. Kendi bünyesindeki değişikler doğrultusunda teslim

aldıklarını bir sonraki safhanın kullanabileceği şekilde değiştirir.

**V-model**

[waterfall](https://tr.wikipedia.org/wiki/Waterfall_model)[ ](https://tr.wikipedia.org/wiki/Waterfall_model)modelinin gelişmiş hali olarak düşünülebilecek bir [yazılım](https://tr.wikipedia.org/wiki/Yaz%C4%B1l%C4%B1m_geli%C5%9Ftirme_s%C3%BCreci)[ ](https://tr.wikipedia.org/wiki/Yaz%C4%B1l%C4%B1m_geli%C5%9Ftirme_s%C3%BCreci)[geliştirme](https://tr.wikipedia.org/wiki/Yaz%C4%B1l%C4%B1m_geli%C5%9Ftirme_s%C3%BCreci)

[süreci](https://tr.wikipedia.org/wiki/Yaz%C4%B1l%C4%B1m_geli%C5%9Ftirme_s%C3%BCreci)[ ](https://tr.wikipedia.org/wiki/Yaz%C4%B1l%C4%B1m_geli%C5%9Ftirme_s%C3%BCreci)sunar. [Doğrusal](https://tr.wikipedia.org/wiki/Do%C4%9Frusal_programlama)[ ](https://tr.wikipedia.org/wiki/Do%C4%9Frusal_programlama)bir yönde ilerlemek yerine, süreç adımları kodlama evresinden sonra yukarıya

doğru eğim alır ve tipik V şeklini oluşturur. V-Model geliştirme yaşam çevriminin her bir evresi

arasındaki ilişkileri gösterir. Yatay ve dikey açılar zaman veya projenin tamamlanabilirliğini ve soyut

seviyeyi gösterir.

**Döngüsel ve Artırımlı SDLC**

Artırımlı→Parçalar halinde gereksinim belirler, yazılım özellikleri adım adım artar.

Döngüsel→ Artırımlı fakat süre sabit.

