## Python'da Kaçış Karakterleri

Python'da kaçış karakterleri, string dizisi içerisinde bulunan ve özel anlam ifade eden karakterleri kullanmanıza yarar. Örnek vermek gerekirse `"` sembolü string'leri belirtirken kullanırız ama aynı zamanda kuracağınız cümlede tırnak içinde bir cümle kullanılacağınız zaman hatalarla karşılaşabilirsiniz. 

``` python

print("Bu dokümanın adı "Python Kaçış Karakterleri"dir")
# Böyle bir kullanımda hata alacaksınız! 

```
```python
# Karşılaşacağınız hata:

Cell In[4], line 1
    print("Bu dokümanın adı "Python Kaçış Karakterleri"dir")
          ^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
```

Hata ile karşılaşma nedeniniz Python'dan önceki `"` sembolü ile stringin bittiğini varsayacaktır ve geri kalanı için hata verecektir. Bu gibi durumlarda kaçış karakteri kullanmanız gerekecektir. Sorunu çözmek için `"` sembolünün öncesine `\`(ters slash) işareti koymanız yeterlidir.


``` python

print("Bu dokümanın adı \"Python Kaçış Karakterleri\"dir")
# Başarılı bir şekilde çıktı alabileceksiniz. 

```

İşte diğer kaçış karakterleri ve kullanımları:

`\n` Bir satır aşağıya inmek için kullanılır. Karakteri kullandığımız yerden sonraki kelimeleri bir alt satıra indirerek ekran çıktısını verdirir. <br>
`\t` Kelimeler arası 1 tab boşluk bırakmak için kullanılır. <br>
`\r` Bu kaçış dizisi, bir karakter dizisinde aynı satırın en başına dönülmesini sağlar. <br>
`\b` kaçış dizisinin görevi, imleci o anki konumundan sola kaydırmaktır. <br>


```python

# \n Kullanımı:
print("Hello\nWorld") # Çıktı:

-> Hello
World

```
```python

# \t Kullanımı:
print("Hello\tWorld") # Çıktı:

-> Hello     World

```
```python

# \r Kullanımı:
print("Hello\rWorld") # Çıktı:

-> World

```
```python

# \b Kullanımı:
print("Hello\bWorld") # Çıktı:

-> HellWorld

```






