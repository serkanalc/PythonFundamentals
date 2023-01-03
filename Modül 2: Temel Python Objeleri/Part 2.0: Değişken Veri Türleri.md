# Değişken Veri Türleri

Bellekte saklanan veriler farklı türde olabilir. Bu işlem gerçek hayattakine oldukça benzemektedir, örneiğin yaşınızın bir sayı olduğunu, isminizin harflerden oluşmuş bir kelime olduğunu, yaşadığınız yerin adresini kelimelerden oluşmuş bir cümle olduğunu veya pi sayısının ondalıklı bir sayı olduğunu bilirsiniz. Programlamada değişkenlerinizin tuttuğu verilerin türleri vardır ve kullanacağınız veri tipini doğru seçmek çoğu zaman ciddi anlamda önem arzetmektedir. Örnek olarak kur farkı hesaplayan bir program yazdığınızı düşünün bu durumda ondalık sayılar yerine tam sayılar kullanırsanız büyük sorunlarla karşılaşabilirsiniz. Programlamada değişkenlerinizin tuttuğu verilerin türleri vardır. Gelin bu dokümanda basit veri tiplerini inceleyelim.

## Sayı tipleri

Matematikte birçok sayı kümesine raslayabiliriz, Doğal Sayılar, Tam Sayılar, Rasyonel Sayılar, İrrasyonel Sayılar, Reel Sayılar, Karmaşık Sayılar bu sayı kümeleri için güzel örneklerdir. Programlamada ki kullanacaklarımız ise `Integer`, `Float`, ve `Complex` veri tipleridir. Bu dokümanda temel değişken türlerini inceleyeceğimiz için sadece `Integer`ve `Float` değişken tiplerini örnekliyor olacağız.

### Integer Veri Tipi

Python'da **integer** veri tipi, tam sayı değerlerini temsil eden bir veri tipidir. Örneğin, 1, 0, -1 gibi sayılar integer veri tipine aittir. Python'da integer veri tipi, sonlu bir aralıkta değerler alabilir, Integer veri tipine ait değerler, Python programlarında sayısal işlemlerde kullanılır. Örneğin, aşağıdaki gibi bir kod parçacığında integer veri tipine ait değerler kullanılmıştır ve kontrol etmek için "[Python'da Tanımlanmış Temel Fonksiyonlar](https://github.com/serkanalc/PythonFundamentals/blob/main/Mod%C3%BCl%202:%20Temel%20Python%20Objeleri/Part%201.2:%20Python'da%20Tan%C4%B1mlanm%C4%B1%C5%9F%20Temel%20Fonksiyonlar.md)" dokümanında da incelediğimiz `type()` fonksiyonunu kullanabilirsiniz:

```python
# Örnek

x = 11
y = 9
toplam= x + y

print(toplam) Çıktı 20
type(toplam) Çıktı int
```

### Float Veri Tipi

Python'da **float** veri tipi, ondalıklı sayı değerlerini temsil eden bir veri tipidir. Örneğin, 3.14, -2.718, 0.0 gibi sayılar float veri tipine aittir. Python'da float veri tipi, çok geniş bir değer aralığında değerler alabilir, ancak bu aralık platform ve sistem özelliklerine göre değişebilir. Float veri tipine ait değerler, Python programlarında sayısal işlemlerde kullanılabilir. Ancak, float veri tipinin değerlerinin tam sayı değerlerine göre daha az hassas olduğu unutulmamalıdır. Örneğin, aşağıdaki gibi bir kod parçacığında float veri tipine ait değerler kullanılabilir:

```python
# Örnek

x = 3.14
y = 2.718
çıktı= x - y

print(çıktı) # Çıktı: 0.4220000000000002
type(çıktı) #Çıktı float
```

## Metin Tipleri

Pythonda bir veri tipi olan Stringler veya Türkçe ismiyle metin dizeleri gerçek hayatta kullandığımız cümle yapısına oldukça benzer. Cümlelerin harflerden oluştuğu gibi Bu veri tipide  aslında her biri bir karakter olan bir dizidir. "python" kelimesini örnek alalım, sırasıyla p,y,t,h,o,n karakterlerden oluşmaktadır. Bu zaman kadar dikkat ederseniz string türünde değişkenler tanımlarken hep başlarına `" "` sembolü koyduk, bu bir kuraldır ama string değişkenler tanımlamanızın tek yolu değildir.

```python

# Yöntem 1
x = "Değişken Veri Türleri"
type(x) # str çıktısı alıyor olacaksınız

# Yöntem 2
y = """ Değişken Veri Türleri """
type(y) # str çıktısı alıyor olacaksınız

# Yöntem 3
z = `Değişken Veri Türleri`
type(z) # str çıktısı alıyor olacaksınız


```

Bu kullanımlarda dikkat etmeniz gereken bir diğer kural, hangi sembol ile değişken tanımlamaya başladıysanız o sembol ile bitirmeniz gerektiğidir. Eğer `"` sembolü ile değişken tanımlamaya başladıysanız sonunda başka bir sembolünü kullanmanız durumunda hata ile karşılaşacaksınız.

```python

a = "Değişken Veri Türleri`
# String değişken tanımlaması hata verecektir

b = `Değişken Veri Türleri"""
# String değişken tanımlaması hata verecektir

```
