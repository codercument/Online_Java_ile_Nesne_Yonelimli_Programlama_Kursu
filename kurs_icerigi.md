# Java ile Nesne Yönelimli Programlama

## Temel kavramlar
+ Java ortamı
+ JDK ve JVM
+ Sayı sistemleri
+ Çevirici programlar, derleyiciler yorumlayıcılar
+ İşletim Sistemleri
+ IDE (Integrated Development Environment) programlar
+ Temel sayı sistemleri
+ JDK kurulumu
+ Merhaba Java program
+ Metot bildirimi
+ Metotların çağrılması

## Tür kavramı
+ Java’da temel türler
+ Tamsayı türleri, gerçek sayı türleri, char türü ve boolean türü 
+ Değişkenler ve faaliyet alanı
+ Yerel değişkenler

## Metotlar
+ Metotların geri dönüş değerleri
+ return deyimi
+ Metotların parametre değişkenleri
+ Matematiksel işlem yapan yararlı metotlar: Math sınıfı

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
+ while döngü deyimleri (while ve do-while döngüleri)
+ for döngü deyimi
+ break ve continue deyimleri
+ Etiketli break ve etiketli continue deyimleri
+ switch deyimi
+ Örnek programlar

## Tür dönüştürmeleri
+ Farklı  türlerin birbirine atanması
+ İşlem öncesi otomatik tür dönüşümleri
+ Tür dönüştürme operatörü

## Koşul operatörü
+ Koşul operatörünün özellikleri
+ Koşul operatörünün kullanıldığı durumlar

## Aynı isimde metotlar (method overloading)
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
+ Sınıfın non-static metotları içerisinde non-static ve static elemanlara doğrudan erişim durumu
+ Sınıfın static metotları içerisinde non-static ve static elemanlara doğrudan erişim durumu
+ Örnek yararlı sınıflar

## Sınıfların başlangıç metotları (constructor)
+ Nesne yaratılması adımları
+ Sınıfın varsayılan _(default)_ başlangıç metodu
+ Başlangıç metotlarının overload edilmesi
+ Örnek yararlı sınıflar

## Rasgele sayı üretimi (Random sınıfı)
+ Rasgele sayı üretimi
+ Random sınfının metotları
+ Tohum değeri _(seed value)_ kavramı 
+ Random sınıfının tohum değeri parametreli başlangıç metodu ve setSeed metodu
+ Örnek programlar

## String sınıfı
+ Immutable sınıf kavramı
+ String nesnesinin bellekteki durumu
+ String sabitleri (String literals)
+ String sınıfının metotları
+ String işlemlerine yönelik yararlı metotların yazılması
+ Örnek programlar

## Diziler (Arrays) ve uygulamalar
+ Dizi referansları
+ Dizi'ye ilişkin nesnelerin bellekteki durumu
+ Dizi elemanlarına erişim
+ Dizilere ilkdeğer verilmesi
+ Dizilerin metotlara geçirilmesi: dizi referansı parametreli metotlar
+ Dizi referansı döndüren metotlar
+ Dizilere ilişkin temel algoritmaların yazımı
+ Dizilere ilişkin yararlı metotların yazımı
+ Dizilerde bazı sıralama algoritmaları: kabarcık (bubble) ve seçerek sıralama algoritmaları
+ char türden diziler
+ char türden diziler ve String sınıfı
+ Referans dizileri
+ Referans dizilerine ilkdeğer verilmesi
+ String türden diziler
+ Dizi dizileri
+ Dizi dizilerinin çok boyutlu dizi gibi kullanılması
+ Dizi dizilerine ilkdeğer verilmesi
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
+ Nitelikli (qualified) isim arama
+ import bildirimleri (import on demand declaration, import single type declaration)
+ import static bildirimleri (import static on demand declaration, import static single type declaration)

## Sınıflarda temel erişim kuralları
+ public erişimcisi
+ private erişimcisi
+ Erişim belirleyicilerin paketlerle ilişkisi
+ no-modifier erişimcisi
+ protected erişimcisi
+ Başlangıç metodunun private olması durumu
+ Singleton sınıf tasarımı: lazy implementation
+ Örnek sınıflar

## Sınıflar arası ilişkiler
+ Composition
+ Aggregation
+ Association
+ Inheritance
+ Sınıflar arası ilişkilerin modellenmesi

## Türetme (inheritance)
+ super class (taban sınıf) ve sub class (türemiş sınıf) kavramları
+ Türetme sentaksı
+ Başlangıç metodu içerisinde taban sınıfın başlangıç metodunun çağrılması
+ Başlangıç metodu içerisinde taban sınfın istenilen başlangıç metodunun çağrılması: super sentaksı
+ Başlangıç metodu içerisinde başka bir başlangıç metodunun çağrılması: this sentaksı
+ protected bölümüm anlamı
+ Object sınıfı
+ Örnek sınıflar

## Taban sınıf ve türemiş sınıf arasındaki dönüşümler
+ Yukarıya doğru dönüşüm (upcasting)
+ Yukarıya doğru dönüşümün anlamı
+ Referansların statik ve dinamik türleri
+ Aşağıya doğru dönüşüm (downcasting)
+ Haklı ve haksız dönüşüm kavramı
+ instanceof opetörü
+ Sarmalayan (wrapper) sınıflar
+ Number sınıfı ve metotlarının anlamı
+ Otomatik kutulama (auto-boxing) ve otomatik kutuyu açma (auto-unboxing)
+ final sınıflar
+ Örnek programlar

## Sınıflar içerisinde bloklar
+ Sınıfların static blokları (static initializers)
+ Sınıfların static olmayan blokları (non-static initializers)

## this referansı
+ this referansının anlamı
+ non-static metotlar içerisinde this kullanmı
+ this referansının kullanıldığı örnek durumlar: fluent kalıbı
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
+ Exception kavramı kullanımı
+ Exception sınıf hiyerarşisi: Throwable, Exception, Error ve RuntimeException sınıfları
+ throw anahtar sözcüğü ve bir exception nesnesinin fırlatılması
+ try blokları
+ catch blokları
+ catch blokları parametrelerine ilişkin sınıflar ve uygun catch bloğunun bulunması
+ Yeniden fırlatma (rethrow)
+ İçiçe try bloklarının bulunması durumu
+ finally bloğu
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
	
