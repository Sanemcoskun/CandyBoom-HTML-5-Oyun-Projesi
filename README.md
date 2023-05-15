# HTML 5 Tabanlı Şeker ve Meyve Toplama Oyunu
Oyunumuz bir şeker ve meyve toplama oyunudur. Öncelikle karakter seçimi yapılır. Oyunda 3 farklı karakter bulunmaktadır. Her saniye rastgele bir konumda bir nesne oluşur ve onları toplarız. Her nesne 7 saniye boyunca toplanabilir. Oyunda 2 farklı seviye ve her seviyede farklı nesneler bulunmaktadır.

**Test Edin:** https://sanemcoskun.com/candy-boom/

**Youtube Tanıtımı:** https://www.youtube.com/watch?v=0la0LIq_6PU

## Oyuna Giriş Ekranı
Oyuna ilk girildiğinde rekor tablosu ve oyunun nasıl oynandığına dair bilgiler yer almaktadır. Rekor tablomuzdaki veriler çerez olarak tutulmaktadır. Seçtiğimiz karakterin rekor puanı için bir çerez oluşturulur ve o çerezdeki veriler çekilerek tabloya işlenir.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/2156615a-173e-46d6-83e5-89d8fe5233a7)

## Seviyeler
Seviyelere göre toplayacağımız nesneler değişiklik gösterir. 1. Seviyede meyveler toplarken 2. seviyede şekerler toplarız. Seviye sayısı rahatlıkla arttırılabilir. Oyuna başlandığında seviyemiz 1 olur ve 1000 puan topladığımızda seviyemiz 2 olacaktır.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/0850a909-b651-498b-8369-b308afdfd5f9)

## Bombalar ve Canlar
Oyunu zorlaştırmak için oyuna bombalar ekledik. Bombalar 6 saniyede bir rastgele bir konumda ortaya çıkar. Bombalar çarpılmadığı sürece yok olmaz. Bir bombaya çarparsak o bomba yok olacaktır. Bu bombalara çarptığımızda canlarımız azalıyor. Can sayımızı 3 olarak belirledik dilersek arttırabiliriz. Canımız bittiğinde oyunda bitmiş olur. Ayrıca topladığımız puan rekorumuzdan fazlaysa çerez değerimizde güncellenir.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/592fc134-1833-4b95-a269-5acbb9107d5b)

## Oynanış Şekli
Klavyemizin yön tuşlarını kullanarak karakterimizi hareket ettirebiliriz.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/7068fbc5-4afe-41c6-a095-80e45622c173)

## Karakter Seçme
Oyna düğmesine tıkladığımızda karakter seçim ekranımız açılacaktır. Bu ekrandan istediğimiz karakteri seçelim. Karakterlerin herhangi bir özelliği, bonusu veya gücü yoktur. Tüm karakterler eşittir.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/80f9c35b-35e8-4809-9d8c-ba9f9c5a5fc8)

## Oynama
Seçtiğimiz karakteri yön tuşlarıyla hareket ettirebiliriz. Ekranda rastgele meyveler ve şekerler belirecektir. Her saniye 1 nesne ortaya çıkar. Bu nesneler toplanana kadar 7 saniye boyunca bekleyecektir. Eğer 7 saniye içinde nesne toplanmazsa yok olur. Ayrıca her 6 saniyede bir ekranda bombalar ortaya çıkar. Bu bombalara çarpmamaya dikkat edelim.

Sağ üst köşede can sayımızı görüyoruz. Kalp simgesiyle belirtilmiştir.

Sol üst köşede ise karakterimizin adı, puanımız, seviyemiz ve karakterimizin rekoru gözükür.

Topladığımız nesneye göre puan değerimiz artar.

_1. Seviye Oyun Ekranı:_

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/f3372237-2915-4326-a235-a1e0acaeded7)

_2. Seviye Oyun Ekranı:_

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/5e6c3330-90f0-4d38-83df-5ebf2c5be39e)

## Yanma
Eğer 3 canınızıda kaybederseniz yanarsınız ve oyun biter. Oyun bittiğinde aşağıdaki gibi bir uyarı alırsınız.

![image](https://github.com/Sanemcoskun/CandyBoom-HTML-5-Oyun-Projesi/assets/92624533/5f610b9d-62f0-45d5-914c-97a0e8cfa427)

