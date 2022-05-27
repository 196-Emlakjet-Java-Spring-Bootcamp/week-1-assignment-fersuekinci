# JAVA 11 İLE GELEN YENİLİKLER
* Java dosyasını tek bir komut ile çalıştırma özelliği gelmiştir.
* Yeni string methodları gelmiştir.
  * isBlank() : Boolean methodtur. String'in dolu olup olmadığını kontrol eder.
  * lines() : String ifadesindeki satır sonlandırıcına göre Stream API değeri verir.
  * repeat() : İçine verilen parametre değeri kadar stringi tekrar eder.
  * stripLeading() : Bu method string objesinin içerisindeki ilk whitespace olmayan karakter öncesindeki whitespace karakterlerini kaldırırır.
  * stripTrailing() : Bu method string objesinin içerisindeki son whitespace olmayan karakter sonrasındaki whitespace karakterlerini kaldırırır.
  * strip() : Bu method string objesinin içerisindeki whitespace karakterlerini kaldırırır. trim() methodundan farkı Unicode desteği olmasıdır.
* Yeni dosya methodları eklenmiştir.
  * writeString() : Dosyaya yazma işlemi gerçekleştirir.
  * readString() : Dosyadan okuma işlemi geröekleştirir.
  * isSameFile() : Boolean methodtur. İki dosyanın aynı olup olmadığını kontrol eder.
* Java 10 ile gelen var ifadesinin kapsamı genişletilerek lambda expressions ile kullanma imkanı gelmiştir.
* Sınıf içerisinde yer alan alt sınıfların derlenmesinde değişiklik yapılarak nest olarak adlandırılan bir yapı kurulmuştur.
* Nest-based yapısına göre derlenen sınıflar ile ilgili detaylı bilgi almak için Class sınıfına getNestHost(), getNestMembers(), isNestmateOf() metotları eklenmiştir.
* Dosya/Dizin yolunu ifade etmek için kullanılan Path arayüzüne of metotları eklenmiştir.
* Koleksiyonları dizilere çevirmek için toArray(IntFunction) metodu eklenmiştir.
* Java ile Input/Output işlemlerinde kullanılan java.io paketine yeni nullInputStream(), nullOutputStream(), nullReader(), nullWriter(), readNBytes() metotları eklenmiştir.

# JAVA 17 İLE GELEN YENİLİKLER
  
