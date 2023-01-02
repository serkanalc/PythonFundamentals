# Python'da Tanımlanmış Temel Fonksiyonlar 

Öncelikle fonksiyonlar nedir birlikte bakalım. **Fonksiyonlar**, Fonksiyon, bir programda tekrar etmek istediğiniz bir işlemi yapmak için oluşturulan bir kod bloğudur. Fonksiyonlar, bir programı daha okunabilir, anlaşılır ve bakımı kolay hale getirirler. Ayrıca, bir fonksiyonu birkaç farklı yerde kullanarak kodunuzu tekrar etmek zorunda kalmazsınız.

Fonksiyonlar, bir giriş parametresi olarak bir veya daha fazla değişken alabilirler ve çıktı olarak bir değer döndürebilirler. Bu değerler, fonksiyonun içinde belirli bir işlem yaptıktan sonra hesaplanır ve fonksiyonun çağrıldığı yere döndürülür.


## Gerçek Hayattan Örnek:

Bir arkadaşınızdan su istediğinizi varsayalım, ona su istediğinizi söylerseniz size birkaç basit soru sormak haricinde yanılmadan bardağı eline alıp su doldurup size getirebilir. Programlar [Python'da Değişkenler](https://github.com/serkanalc/PythonFundamentals/blob/main/Mod%C3%BCl%202:%20Temel%20Python%20Objeleri/Part%201.0:%20Python'da%20De%C4%9Fi%C5%9Fken%20Yap%C4%B1s%C4%B1.md) bölümünde de anlatıldığı gibi bu şekilde çalışmaz. Program, suyun ne olduğu, neye konulması gerektiği, bardağın ne olduğunu, ne kadar konması gerektiğini, nasıl getirilmesi gerektiği gibi adımlarla işlemini gerçekleştirebilir. Bu durum kulağa kısa bir işlem gibi gelebilir ama her gün bu döngüyü onlarca kez yaptığınızı düşünün. İşte yukarda bahsedildiği gibi arkadaşınıza bu işlemi bir kere anlatıp bu işleve bir isim verdiğiniz zaman, örneğin `su_getirir_misin` gibi o zaman her `su_getirir_misin` dediğinizde programınız saydığımız döngüyü gerçekleştirecektir. Aslında değişken mantığına benzerdir, değişken bir data tutarken fonksiyonlar içinde bir işlev tutar gibi düşünebilirsiniz. 

## Tanımlanmış Basit Fonksiyonlar

Bir çok programlama dilinde kullanmanız için hazır fonksiyonlar vardır. Bu fonksiyonlar o programlama dilini kullanabilmeniz için öncesinde tanımlanmıştır. Bu dokümanda en temel fonksiyonlardan birkaçını inceliyor ve örneklendiriyor olacağız.

### print() Fonksiyonu

Print fonksiyonu Python'daki en temel ve ilk akla gelen foksiyondur. `print()` fonksiyonu, bir değişkenin veya bir ifadenin değerini ekrana yazdırmak için kullanılır. Temel anlamda bu işe yarasa da `print()`fonksiyonunun birçok kullanım şekli vardır:

```python

isim = Serkan
print(isim) 

# Çıktı, isim değişkeninin içinde tuttuğu değer olan "Serkan" olacaktır 

```
```python

x = 5
y = 10
print(x + y)

# Çıktı, 10 ve 5 sayısının toplamı olan 15 olacaktır

```
```python

print("Rakamlar:",0,1,2,3,4,5,6,8,9)

# Çıktı, Rakamlar: 0 1 2 3 4 5 6 8 9 olacaktır

```
### type() Fonksiyonu

type() fonksiyonu en basit açıklamasıyla içine gönderilen değerin hangi veri tipinden olduğunu söyler. Kullanımı basittir, sadece öğrenmek istediğiniz değerin türünü type() fonksiyonunun içine yazarak çağırırsınız.

```python

değer = 11
print(type(değer))

# Çıktı, integer'in kısaltması olan int olacaktır.

```





