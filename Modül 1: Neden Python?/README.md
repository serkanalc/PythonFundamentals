# Neden Python?

Bir işe **Neden** sorusunu sorarak başlamak atabileceğiniz en sağlam temellerden birini atarak başlamakla eşdeğerdir. Eğer işe yanlış sorular sorarak başlarsak, öğreneceğimiz kavramı veya öğrenim aşamasında karşılaşacağımız problem yaratan şeyin ne olduğunun farkına varamazsak, o zaman elde edeceğimiz sonuçta başarısızlık olur.

Bu yazıda **Python programlama dilinin tarihçesini**, **programlamanın ne olduğunu** ve **Neden Python öğrenilmesinin yararlı olacağını** anlatıyor olacağım. Eğer bu yazıdaki bilgiler dikkatinizi çektiyse veya işinize yarayabileceğinizi düşündüyseniz Python programlama dilini öğrenmeye çalışmak sizin için zaman kaybı olmayacaktır.

<br>


## Programlama Nedir?

<br>

Programlama, bilgisayarın donanıma nasıl davranacağını anlatan, bilgisayara yön veren komutlar, kelimeler, aritmetik işlemlerdir. Diğer bir tanımla programlama, bilgisayar programlarının yazılması, test edilmesi ve bakımının yapılması sürecine verilen isimdir.

Daha somut bir örnek vermek gerekirse, günlük yaşamınıza şöyle bir bakın. Yaşamınızda birçok işi tekrar ettiğinizi ve ciddi anlamda zaman kaybettiğinizi farkedeceksiniz. Programlama bu tekrar eden faliyetleri sizin yerinize yapabilen harika bir yardımcı olabilir. Programlama böyle bir durumda devreye girer. Her gün saatler boyunca uğraştığınız işlerinizi, yalnızca birkaç satır kod yardımıyla birkaç saniye içinde tamamlayabilirsiniz.

Programcılar genelde programlamayı gerçek hayata benzetirler. Bir program yazmak veya bir problemi çözmek için öncelikle komutları unutmak ve çözümü gerçek hayatta yapıyormuş gibi düşünmek gerekir. Onlara göre komutlar sadece araçtır.

Programlama dili ise, yazılımcının bir algoritmayı ifade etmek amacıyla, bir bilgisayara ne yapmasını istediğini anlatmasının tektipleştirilmiş yoludur. Programlama dilleri, yazılımcının bilgisayara hangi veri üzerinde işlem yapacağını, verinin nasıl depolanıp iletileceğini, hangi koşullarda hangi işlemlerin yapılacağını tam olarak anlatmasını sağlar. 

Günlük hayatta kullandığımız dile **Doğal dil** denir. Bilgisayarlarda program süreçlerinde bir dil kullanır, bu dile **Makine dili** denir. Doğal dil ile Makine dili arasında iletişim kurulması gerekir, iletişim kurulmasını sağlayan bu dillere **Yüksek Seviyeli Dil** denir. Yazılımcılar bu programlama dillerini kullanır.

Yüksek seviyeli dilleri makine diline çevirmek için iki yaklaşım kullanılır: Derleme ve yorumlama. Herhangi bir tekniği kullanarak bir programlama dili uygulamak mümkündür.

> **Derleme**, insanlar tarafından anlaşılabilir ve yazılan yüksek düzeyli programlama dilinde yazılmış programları, yalnızca bilgisayar tarafından anlaşılan düşük düzeyli bir ikili dile dönüştürme eylemidir. Kaynak kod her değişiklikte içinde makina dili bulunan bir dosyaya dönüştürülür. Bu dosya üzerinden program dağıtılır ve yürütülür. Bu dönüşümü yapan programa derleyici(compiler) denir.<br><br>**Yorumlama**, Kaynak kod her çalıştırıldığında makina diline dönüştürülür. Bu dönüşü yapan programa yorumlayıcı (interpreter) adı verilir. Bu yöntemin kullanıldığı programlarda bilgisayar üzerinde yorumlayıcının da yüklü olması gerekmektedir.

<br>


## Python Tarihçesi

<br>

Python Programlama dili, **Guido Van Rossum** adlı Hollandalı bir programcı tarafından 90’lı yılların başında geliştirilmeye başlanmıştır. Çoğu insan adını piton yılanından aldığını düşünür, ancak düşünülenin aksine Guido Van Rossum bu programlama dilinin adını **The Monty Python** adlı bir İngiliz komedi grubunun, Monty Python’s Flying Circus adlı gösterisinden esinlenerek adlandırmıştır. Günümüzde **Python Software Foundation** çevresinde toplanan gönüllülerin çabalarıyla geliştirilmesi ve açık kaynak kod olarak özür kullanılması sürdürülmektedir.

Guido Van Rossum bu dili geliştirirken koyduğu temel hedefler:

- Mümkün olduğunca okunabilir 
- Ücretsiz ve herkesin kullanımına açık 
- Çok yönlü geliştirmeye açık

Geliştiricisi Hollandalı olsa da python İngilizce bir kelimedir. Dolayısıyla bu kelimenin telaffuzunda İngilizcenin kuralları geçerlidir. Ancak bu kelimeyi hakkıyla telaffuz etmek, ana dili Türkçe olanlar için pek kolay değil. Çünkü bu kelime içinde, Türkçede yer almayan ve telaffuzu peltek s’yi andıran [th] sesi vardır. İngilizce bilenler bu sesi think (düşünmek) kelimesinden hatırlayacaklardır. Ana dili Türkçe olanlar think kelimesini genellikle [tink] şeklinde telaffuz eder. Dolayısıyla python kelimesini de [payton] şeklinde telaffuz edebilirsiniz.

<br>


## Neden Python Öğrenilmeli?

<br>

Guido Van Rossum'un hedeflediği gibi, python yazımı basit, öğrenmesi kolay, anlaşılabilir bir dildir. Python Syntax'ının temiz ve basit olması sayesinde hem program yazmak, hem de başkası tarafından yazılmış bir programı okumak, başka dillere kıyasla çok kolaydır. Aynı görevi gerçekleştirmek için C/C++ ve Java gibi diğer ana dillere kıyasla daha az kod satırına ihtiyac vardır.

Python ile programlarının en büyük özelliklerinden birisi, C ve C++ gibi dillerin aksine, derlenmeye gerek olmadan çalıştırılabilmeleridir. Python’da derleme işlemi ortadan kaldırıldığı için, bu dille oldukça hızlı bir şekilde program geliştirilebilir.

Programlama Nedir? kısmında bahsettiğimiz üzere derlemeye ihtiyaç duymama nedeni yorumlanmış bir dil olmasıdır; bu, python'un kodu satır satır doğrudan yürüttüğü anlamına gelir . Herhangi bir hata durumunda daha fazla çalışmayı durdurur ve oluşan hatayı geri bildirir. Python, programın birden fazla hatası olsa bile yalnızca bir hata gösterir. Bu, hata ayıklamayı ve hatayı bulmayı kolaylaştırır.

Bir diğer hedefte olduğu gibi python ücretsiz ve herkesin kullanımına açıktır. Açık kaynak kodlu ve OSI onaylı açık kaynak lisansına sahip olması yazılım geliştiricilerine özgür içerikler ve Python’a ait kaynak kodları indirip düzenleme şansı verir.

> **Open Source Initiative (OSI)**, 1998 yılında kurulan, ticari dünyada açık kaynak yazılım kullanımına teşvik eden ve kar amacı gütmeyen bir Kaliforniya kamu yararı şirketidir.

Python programlama dilini öğrenmek için daha birçok neden olsada temel anlamda bu nedenleri başta bilmek, sizin için iyi bir başlangıç olacaktır. 
<br>


## Özet

<br>

Kullanıcılar için **Hızlı**, **Güçlü**, **Güvenli** ve **Tamamıyla ücretsiz** olması Python'u öğrenmek için mükemmel nedenler olsada, öğrenmeye başladıkça daha birçok harika neden keşfedeceğinize emin olabilirsiniz. Umarım öğrenme süreciniz güzel geçer. 



