# Borsa_Proje
· User Story-1

a. Sisteme Kayıt (Kullanıcılar aşağıdaki bilgileri yazılıma girerek sisteme kayıt olacaklardır.)

b. (Kullanıcı Bilgilerinin sisteme eklenmesi [Ad, Soyad, Kullanıcı Adı, Password, TC Kimlik No, Telefon, Email, Adres,KullanıcıType] )

· User Story-2

c. Satıcının sahip oldukları ürünleri Admin onayı ile sisteme eklemesi (ürün tipleri [buğday,arpa,yulaf,petrol,pamuk,…] ve miktar (100 kg, 50 kg,vb) bilgilerinin sisteme eklenmesi.)

· User Story-3

d. Alıcının sahip olduğu paranın Admin onayı ile sisteme eklenmesi (para tipi TL)

· User Story-4

e. Fiyatın oluşması ile alıcının hesabına parasının olması ve satıcının hesabına ise ürünün olması lazım. Eğer alıcının almak istediği ürün var ise otomatik olarak alım işleminin gerçekleşmesi lazım.

Satıcı

Ahmet 100 kilo buğday sahibi Sahip olduğu malın satış fiyatı 2tl

Mehmet 50 kilo buğday sahibi Sahip olduğu malın satış fiyatı 3tl

Hasan 75 kilo buğday sahibi Sahip olduğu malın satış fiyatı 4tl

Alıcı

Hüseyin 200tl

Kemal 300tl

Bayram 400tl

Fiyat Oluşma Kısmı Sizin Yazılım Tarafından Otomatik Olarak Gerçekleşecek

İşlem Zamanı Yapılan İşlem Detayı Harcanan Tutar Alıcının Kalan Parası Satılan Malın Birim Fiyatı

12.34 / 26.03.2021 Hüseyin 50 kilo buğday almak ister ise 2 tl’den alım işlemi gerçekleşti Hüseyin Ahmet’in hesabına 100tl gönderdi. Hüseyin 100 tl parası kaldı 2 tl

12.35 / 26.03.2021 Kemal 100 kilo buğday almak ister ise 50 birimi 2 tl’den alır geri kalan 50 birimi ise 3tl’den alır. Kemal, Ahmet’in hesabına 100tl gönderdi ve Mehmet’in hesabına ise 150tl gönderdi. Kemal 50 tl parası kaldı 3tl

12.36 / 26.03.2021 Bayram 50 kilo buğday mal almak istesin 50 birim çarpı 4 Bayram, Hasan’ın hesabına 200tl gönderdi. Bayram 200 tl parası kaldı 4tl

Ekranlar

1.Login Ekranı

2.Alıcı ve Satıcının Bilgi Giriş Ekranı

3.Adminin ürün ve para onayı kısmı

4.Fiyatın Belirlenmesi kısmı


· UserStory-5 (Alıcı bir fiyat belirleyebilecek eğer istediği fiyattan satan kişi olmaz ise işlem gerçekleşmeyecek. İşlem ancak alıcının verdiği fiyattan ürün satan bir kişi olana kadar bekleyecek.)

Örnek: Alıcı 100kg pamuğu 5tl’den almak istiyor. Alım yapmak istediği tarihteki pamuk fiyatı 5.50tl olsun. Bu nedenden dolayı alıcının alım isteği o anda gerçekleşmiyor. Ancak bir satıcı sisteme girip de pamuk satım fiyatı 5tl’den ben 100kg ya da üstü satarım diyene kadar.

· UserStory-6 (Kullanıcı seçtiği tarih aralığında yaptığı alış ve/veya satışlara ilişkin bir rapor oluşturabilecek (Oluşturulan rapor [.csv yada .xlsx yada .dat yada.pdf] uzantılı bir formatta dönüştürülecek.)

Örnek: 01.01.2021 ile 21.05.2021 arasında alım yapılan pamukların bilgilerini listele ve Excel’e yada yukarıda yazan formatlardan birine dönüştür.

· UserStory-7 (Alıcı sisteme sadece TL değil farklı para tiplerinden de yükleme yapabilecek. Yüklenen bu tutar adminin onay verdiği tarihteki döviz kuru üzerinden Tl’ye çevrilerek sisteme aktarılacak.) (.Json/.Xml/vb bir yerden veri seçilebilir.) En az 3 para birimi sistem tarafından kabul edilsin (Örnek sterlin, İsviçre frank, Euro). http://www.tcmb.gov.tr/kurlar/today.xml yada başka bir web sayfasından yada servisinden anlık döviz kuru bilgisi çekilecektir.

· UserStory-8 (Muhasebe_kullanıcısı aracılık ücreti yüzde 1 olsun ve bu tutar alıcıdan tahsil edilsin.)
