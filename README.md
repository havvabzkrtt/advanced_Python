# İleri Python Terimleri

## Args

- Fonksiyonun parametresi *args olarak tanımladığında : Input olarak list/tuple gibi yapılar vermeden de değişken sayılı input'u sıralı olarak fonksiyona verebilebilmesini sağlar.

## Kwargs

- Fonksiyonun parametresi **kwargs olarak verildiğinde : Değişken sayıda keyword argument verebilebilmesini sağlar.

## Closure

- İç içe fonksiyonlarda outer(dış) fonksiyonu çağırdıktan sonra bile inner(iç) fonksiyonun, outer fonksiyon scope'una erişebilmesidir.

## Decorator

- Bir fonksiyon gibi düşünülebilir. Decorator'lar başka fonksiyonları input (parametre) olarak kabul edip yeni bir fonksiyonalite ile yeni bir fonksiyon döndüren yapılardır. Orjinal olarak verdiğimiz input fonksiyonu değiştirmeyecek.

## Class

- Class mantığı hem fonksiyonalite hem de veriyi bir arada tutma yoludur.

- Attribute: Class içerisinde tanımlanan variable'lar.

- Method: Class içerisinde tanımlanan fonksiyonlar.

Araba taralamak istiyoruz: 

    class     : arabanın planı class olur (özellikleri, yapacağı şeyler) 
    
    obje      : plandan oluşturulan arabalar objeler olur 
    
    instance  : o an hali hazırda incelenen araba objesi olur 
    
 
## Class Variable

- Class Variable'lar class'tan yaratılan tüm objelerde aynı olarak paylaşılan variable'lardır, Instance Variable'lar instance'a özeldir.


## Class & Static Method

- Class Method

İlk input'u, oyomatik olarak class referansı aktarılan methodlardır.

- Static Method

Class'ların içerisinde otomatik olarak hiçbir input almayan methodlar'dır.