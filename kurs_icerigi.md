# Java ile Nesne Yönelimli Programlama

## Temel kavramlar
+ Java ortamı
+ _JDK_ ve _JVM_
+ Çevirici programlar, derleyiciler yorumlayıcılar
+ İşletim Sistemleri
+ IDE _(Integrated Development Environment)_ programları
+ Temel sayı sistemleri
+ JDK kurulumu
+ Merhaba Java program
+ Metot bildirimi
+ Metotların çağrılması

## Tür kavramı
+ Java’da temel türler
+ Tamsayı türleri, gerçek sayı türleri, _char_ türü ve _boolean_ türü 
+ Değişkenler ve faaliyet alanı
+ Yerel değişkenler

## Metotlar
+ Metotların geri dönüş değerleri
+ _return_ deyimi
+ Metotların parametre değişkenleri
+ Matematiksel işlem yapan yararlı metotlar: _Math_ sınıfı

## Temel Operatörler
+ Operatörlerin sınıflandırılması
+ Operatör önceliği
+ Aritmetik Operatörler
+ Karşılaştırma operatörleri
+ Mantıksal operatörler
+ Mantıksal operatörlerin kısa devre davranışları
+ Atama operatörü
+ İşlemli atama operatörleri

## Kontrol deyimleri
+ _if_ deyimi
+ while döngü deyimi
+ _do while_ döngü deyimi
+ _for_ döngü deyimi
+ _break_ ve _continue_ deyimleri
+ Etiketli _break_ ve etiketli _continue_ deyimleri
+ _switch_ deyimi
+ Örnek programlar

## Tür dönüştürmeleri
+ Farklı türlerin birbirine atanması
+ İşlem öncesi otomatik tür dönüşümleri
+ Tür dönüştürme operatörü

## Koşul operatörü
+ Koşul operatörünün özellikleri
+ Koşul operatörünün kullanıldığı durumlar

## Aynı isimde metotlar _(method overloading)_
+ Bir sınıf içerisinde aynı isimde metotlar
+ Bir metodun imzası
+ Çağırma sırasında hangi metodun çağrılacağının belirlenme süreci _(overload resolution)_
+ Tam uyum _(best match)_
+ Tam uyum olmadığında hangi metodun çağrılacağının belirlenme süreci

## Nesne Yönelimli Programlama Tekniği
+ Nesne yönelimli programlama tekniğine ilişkin temel kavramlar

## Adres kavramı
+ Adres kavramı
+ Stack ve heap alanları
+ Ömür _(storage duration)_ kavramı: yerel ve parametre değişkenlerinin ömürleri

## Temel sınıf kavramları
+ Sınıf ve nesne kavramları
+ Referans türleri ve değer türleri
+ Referans kavramı
+ _new_ operatörü
+ Sınıfın _static_ olmayan veri elemanlarına erişim ve nokta operatörü
+ Sınıfın _static_ olmayan veri elemanlarının varsayılan değerleri
+ Referans parametreli metotlar
+ Referans geri dönüş değerli metotlar
+ Sınıfın _static_ veri elemanları
+ Sınıfın _non-static_ ve _static_ metotları
+ Sınıfın _non-static_ metotları içerisinde _non-static_ ve _static_ elemanlara doğrudan erişim durumu
+ Sınıfın _static_ metotları içerisinde _non-static_ ve _static_ elemanlara doğrudan erişim durumu
+ Örnek yararlı sınıflar

## Sınıfların başlangıç metotları _(constructors)_
+ Nesne yaratılması adımları
+ Sınıfın varsayılan _(default)_ başlangıç metodu
+ Başlangıç metotlarının _overload_ edilmesi
+ Örnek yararlı sınıflar

## Rasgele sayı üretimi _(Random sınıfı)_
+ Rasgele sayı üretimi
+ Random sınfının metotları
+ Tohum değeri _(seed value)_ kavramı 
+ Random sınıfının tohum değeri parametreli başlangıç metodu ve _setSeed_ metodu
+ Örnek programlar

## String sınıfı
+ _Immutable_ sınıf kavramı
+ String nesnesinin bellekteki durumu
+ String sabitleri _(String literals)_
+ String sınıfının metotları
+ String işlemlerine yönelik yararlı metotların yazılması
+ Örnek programlar

## Diziler (Arrays) ve uygulamalar
+ Dizi referansları
+ Diziye ilişkin nesnelerin bellekteki durumu
+ Dizi elemanlarına erişim
+ Dizilere ilk değer verilmesi
+ Dizilerin metotlara geçirilmesi: dizi referansı parametreli metotlar
+ Dizi referansı döndüren metotlar
+ Dizilere ilişkin temel algoritmaların yazımı
+ Dizilere ilişkin yararlı metotların yazımı
+ Dizilerde bazı sıralama algoritmaları: kabarcık sıralaması _(bubble sort)_ ve _seçerek sıralama _(selection sort)_ algoritmaları
+ _char_ türden diziler
+ _char_ türden diziler ve _String_ sınıfı
+ Referans dizileri
+ Referans dizilerine ilkdeğer verilmesi
+ _String_ türden diziler
+ Dizi dizileri
+ Dizi dizilerinin çok boyutlu dizi gibi kullanılması
+ Dizi dizilerine ilk değer verilmesi
+ Matrisler ve matrislerlere ilişkin algoritmalar
+ Örnek programlar

## Paketler
+ Paket kavramı
+ Farklı paketlerdeki sınıflara erişim
+ İçiçe paket bildirimleri
+ Paketler ve dizinlerin ilişkisi
+ Paket isimlendirmesine ilişkin teknikler
+ Kaynak dizin _(source folder)_
+ Yazılmış olan yararlı sınıflara ilişki uygun paketler

## İsim arama
+ Niteliksiz _(unqualified)_ isim arama
+ Nitelikli _(qualified)_ isim arama
+ import bildirimleri _(import on demand declaration, import single type declaration)_
+ import static bildirimleri _(import static on demand declaration, import static single type declaration)_

## Sınıflarda temel erişim kuralları
+ _public_ erişimcisi
+ _private_ erişimcisi
+ Erişim belirleyicilerin paketlerle ilişkisi
+ _no-modifier_ erişimcisi
+ _protected_ erişimcisi
+ Başlangıç metodunun _private_ olması durumu
+ Singleton sınıf tasarımı: _lazy implementation_
+ Örnek sınıflar

## Sınıflar arası ilişkiler
+ _Composition_
+ _Aggregation_
+ _Association_
+ _Inheritance_
+ Sınıflar arası ilişkilerin modellenmesi

## Türetme (inheritance)
+ _Super class_ (taban sınıf) ve _sub class_ (türemiş sınıf) kavramları
+ Türetme sentaksı
+ Başlangıç metodu içerisinde taban sınıfın başlangıç metodunun çağrılması
+ Başlangıç metodu içerisinde taban sınfın istenilen başlangıç metodunun çağrılması: super sentaksı
+ Başlangıç metodu içerisinde başka bir başlangıç metodunun çağrılması: _this_ sentaksı
+ _protected_ bölümün anlamı
+ Object sınıfı
+ Örnek sınıflar

## Taban sınıf ve türemiş sınıf arasındaki dönüşümler
+ Yukarıya doğru dönüşüm _(upcasting)_
+ Yukarıya doğru dönüşümün anlamı
+ Referansların statik ve dinamik türleri
+ Aşağıya doğru dönüşüm _(down-casting)_
+ Haklı ve haksız dönüşüm kavramı
+ _instanceof_ opetörü
+ Sarmalayan _(wrapper)_ sınıflar
+ Number sınıfı ve metotlarının anlamı
+ Otomatik kutulama _(auto-boxing)_ ve otomatik kutuyu açma _(auto-unboxing)_
+ _final_ sınıflar
+ Örnek programlar

## Sınıflar içerisinde bloklar
+ Sınıfların _static_ blokları _(static initializers)_
+ Sınıfların _static_ olmayan blokları _(non-static initializers)_

## this referansı
+ _this_ referansının anlamı
+ _non-static_ metotlar içerisinde _this_ kullanmı
+ _this_ referansının kullanıldığı örnek durumlar: _fluent_ kalıbı
+ Örnek sınıflar

## null referans
+ null adres kavramı ve null sabiti
+ null referansın kullanıldığı durumlar

## Temel algoritma analizi
+ Algoritmanın karmaşıklığı
+ Karmaşıklığın ölçütü
+ Karmaşıklığın gösterimine ilişkin notasyonlar
+ Big O notasyonu ile çeşitli karmaşıklık durumlarının incelenmesi
+ O(1), O(logn), O(n), O(n * Logn), O(n ^ 2), O(n ^ 3), ... , O(n ^ k) karmaşıklıkları
+ O(k ^ n), O(n!) gibi özel karmaşıklıklar

## Dinamik büyüyen dizi veri yapısı
+ Dinamik büyüyen veri yapısına ilişkin temel kavramlar: capacity, size vs.
+ Dinamik büyüyen veri yapısına ilişkin metotların karmaşıklık durumları
+ ArrayList ve Vector sınıfları
+ Örnek programlar
+ Örnek bir dinamik büyüyen dizi sınıfının yazılması

## Çok biçimlilik (polymorphism)
+ Çok biçimliliğin programlamaya yönelik tanımları
+ Çok biçimli mekanizma
+ Sanal metotlar
+ Sanal metotların override edilmesi
+ Metotların override edilmesinin anlamı
+ super referansı
+ Override edilen metot içerisinde taban sınıfın aynı metodunun çağrılması (augmentation)
+ Override edilen metodun erişim belirleyicisinin erişim anlamında yükseltilmesi
+ final metotlar
+ Çok biçimliliğe ilişkin örnek tasarımlar ve kodlanması

## Soyut sınıflar ve metotlar (abstract classes and methods)
+ Soyut sınıf ve metotların anlamı
+ Soyut metotların override edilmesi
+ Soyut metotların override edilmemesi durumu
+ Soyut sınıfların taban sınıf referansı olarak kullanılması
+ Soyut sınıfların başlangıç metotları
+ Örnek sınıflar

## Exception işlemleri
+ _Exception_ kavramı kullanımı
+ _Exception_ sınıf hiyerarşisi: _Throwable_, _Exception_, _Error_ ve _RuntimeException_ sınıfları
+ _throw_ anahtar sözcüğü ve bir exception nesnesinin fırlatılması
+ _try_ blokları
+ _catch_ blokları
+ _catch_ blokları parametrelerine ilişkin sınıflar ve uygun catch bloğunun bulunması
+ Yeniden fırlatma _(rethrow)_
+ İçiçe try bloklarının bulunması durumu
+ _finally_ bloğu
+ Yakalanamayan bir exception durumu
+ Exception sınıflarının anlamı
+ Cause exception
+ checked ve unchecked exception sınıfları
+ throws anahtar sözcüğü
+ Önemli exception sınıfları
+ Örnek sınıfların exception açısından düzenlenmesi ve genel hale getirilmesi

## Arayüzler (interfaces)
+ Arayüzlerin elemanları
+ Arayüzler içerisinde olabiliecek elemanların Java sürümlerine göre farklılıkları
+ Bir sınıfın desteklediği arayüzler ve metotların override edilmesi
+ Marker arayüzler, fonlsiyonel arayüzler
+ Java 8 ile eklenen arayüz içerisinde default metotlar ve static metotlar
+ Arayüzler ile abstract sınıflar arasındaki farklar
+ Arayüzler arası tür dönüştürme ayrıntıları
+ Çok kullanılan bazı arayüzler
+ try-with resources bloğu ve kullanımı: AutoCloseable ve Closeable arayüzleri

## Dosya işlemleri
+ Dosya ve dizin (directory) kavramları
+ Dosya yol ifadeleri: absolute and relative path
+ Processin çalışma dizini (current working directory)
+ Metin (text) ve ikili (binary) dosyalar
+ Dosya üzerinde bütünsel işlemler yapan sınıflar
+ Dosylar üzerinde ayrıntılı işlem yapan sınıflar,
+ File sınıfının dosya ve dizinler üzerinde işlem yapan metotlar
+ Path arayüzü ve Files sınıfı
+ InputStream ve OutputStream soyut sınıfları
+ FileInputStream ve FileOutputStream sınıfları
+ Dosya göstericisi (file pointer) kavramı
+ Dosya göstericisinin EOF durumu
+ Dosyadan okuma ve yazma işlemleri
+ RandomAccessFile sınıfı 
+ Dosya göstericisinin konumlandırılması
+ Örnek programlar

## Generic sınıflar ve metotlar
+ Generic sınıflar
+ Generic sınıflarda türetme işlemleri
+ Generic sınıflarda new operatörü ile <> (diamond syntax) kullanımı
+ Generic arayüzler
 + Generic türlerde kısıtlar: extends ve super anahtar sözcüğünün generic parametrelerde kullanımı
+ Generic türlerde joker karakter
+ Generic sınıflarda alt sınır ve üst sınır belirlenmesi (invariant, covariant ve contra-variant)
+ Generic metotlar
+ Generic metotlarda parametre türlerinin tespiti
+ Generic türlerin ve metotların generic parametrelerinin arakoda Object olarak aktarılması
+ Örnek sınıflar ve programlar
	
