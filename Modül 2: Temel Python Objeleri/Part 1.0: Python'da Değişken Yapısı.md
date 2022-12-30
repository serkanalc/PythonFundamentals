# Python'da Değişkenler

Python programlarımızda geçici olarak veri saklamak için oluşturduğumuz alanlara `Değişken` denir. İşlem yapmak istediğimizde de veriyi hafızadan çağırıp gerekli işlemleri yerine getirir. Hafızadaki verirleri ifade etmek için programlama dillerinde değişkenleri kullanırız Başlangıç için anlaması zor bir tanım olabilir, böyle durumlarda süreç boyunca yapmanız gereken en doğru şey gerçek hayattan örneklar arayarak kavramaya çalışmaktır.


## Gerçek Hayattan Örnek:

Odanızı düzenlemek istediğinizi ve bunun için bir arkadaşınızdan yardım aldığınızı düşünün. Belli eşyaların daha düzenli durması için kutular aldınız ve içine eşya koydukça bu kutuların üzerine o eşyaları size hatırlatacak adlar yazmasını istediniz. İlk kutuya renkli kalemlerin koyulması, ikinci kutuya ise kurşun kalemlerin konulması gerekiyor. Son olarak bu 2 kutuyuda içine alacak genişlikte bir kutunuz daha olduğunu ve 2 kutuyuda içerisinde tuttuğunuzu düşünün. 5 Renkli kalem 7 kurşun kaleminiz olduğunu varsayarsak Burda size yardımcı olacak arkadaşınız için adım adım yapılacakları anlatmanız gerekmektedir.

**Adım 1:** Renkli kalemleri içine koyacağın kutu için bir sonrasında baktığında sana içinde ne olduğunu anımsatacak bir isim belirle ve kutunun üstüne yaz. Şimdilik `renkliKalemler` diyelim <br>

**Adım 2:** `renkliKalemler` yazılı kutuya elinde bulunan 5 adet renkli kalemi koy <br>

**Adım 3:** Kurşun kalemler içine konacağı kutu için bir sonrasında baktığında sana içinde ne olduğunu anımsatacak bir isim belirle ve kutunun üstüne yaz. Şimdilik `kurşunKalemler` diyelim <br>

**Adım 4:** `kurşunKalemler` yazılı kutuya elinde bulunan 7 adet renkli kalemi koy <br>

**Adım 5:** Bu 2 kutuyu `kalemler` adındaki daha büyük başka bir kutuya koy <br>

Burda dikkat etmeniz gereken yegane şey kutulara içine koyacağınız şeylere göre, okuyana sonrasında içinde olanı anımsatıp işinizi kolaylaştıracak isimler vermektir. Değişkenlerde böyle çalışır içinde tutacağı veriyi sonrasında size hatırlatacak isimler vermeniz sizin için önemli olacaktır. Hadi yükardeki işlemleri Python ile yapalım:

```python

# Adım 1 & Adım 2
renkiKalemler = 5

# Adım 3 & Adım 4
kurşunKalemler = 7

# Adım 5
kalemler = renkliKalemler + kurşunKalemler

```

Yukardaki kod satırları ile değişkenlerinizi tanımlamış oldunuz. Kutu örneğinden gitmeye devam edersek, programlamada "=" ifadesinin sol tarafındaki değişkeniniz(kutunuz), sağ tarafındaki ise kutunun içine konulacak verileriniz olacaktır. İşte bu kadar basit!

## Değişken Adlandırma Kuralları

Gerçek hayatta eşyalarınızı koyacağınız kutu üstüne isim yazarken istediğiniz ismi seçebilirsiniz ama programlamada işler böyle yürümez. Kullanacağınız programlama dillerinin belli kuralları vardır ve bu kurallara dikkat etmezseniz ilginç hatalarla karşılaşabilirsiniz. Bu kuralların yanı sıra kullanmasanızda programınızın çalışacağı ama kullanmanız halinde kodlarınızı takibi kolay ve daha okunaklı hale getirecek değişken adlandırma yöntemleride vardır. Gelin birlikte inceleyelim:

### Kurallar:

1. Değişkenler bir sayı ile başlayamaz

```python

# Kullanım halinde program hata verecektir!

7taneKalem = 7 

```
  
2. Değişkenler aritmatik sembollerle başlayamaz


```python

# Kullanım halinde program hata verecektir!

+kalemKutusu = 7   

```

3. Python'da özel anlam ifade eden kelimeler ve fonksiyonlar değişken olarak kullanılamaz, kullanılma durumunda değişken ismini kabul edecektir ancak sonrasında fonksiyonlarınız çalışmayacaktır.

```python

# Kullanım halinde program hata verecektir!

false = 7
print = 10  
```

4. Değişkenler adlandırılırken boşluk bırakılamaz


```python

# Kullanım halinde program hata verecektir!

kalem kutusu = 7

```


### Değişken Adlandırma Yöntemleri:

1. Pytnon, türkçe harfleri değişkenlerinizde kabul eder ancak ilerleyen aşamalarda uyum problemleri çıkabileceği için türkçe harf kullanımlarından kaçınmanız yararınıza olabilir.

```python

sayı = 10 # Programınız kullanım halinde çalışır

number = 10 # Programınız kullanım halinde çalışır
```

2. Değişkenleri adlandırırken boşluk bırakma durumunda `_` veya Deve kemeri metodu kullanılabilir.

```python

kalem_kutusu = 7 # Programınız kullanım halinde çalışır

kalemKutusu = 7 # Programınız kullanım halinde çalışır
```

3. Değişkenleri adlandırırken içinde tutulacak değeri en iyi betimleyecek isimleri kullanmanız işinize yarayacaktır

```python

sayı = 3,14 # Programınız kullanım halinde çalışır

pi_sayısı = 3,14 # Programınız için daha doğru bir kullanımdır!
```

## Değişken Türleri
