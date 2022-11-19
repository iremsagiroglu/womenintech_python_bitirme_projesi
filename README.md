
![E-Commerce](https://images.app.goo.gl/QdJM41HhZ3h5gw8v8)

Herkese merhaba! ⚡

SistersLab’in Toplum Gönüllüleri Vakfı tarafından desteklenen Women in Tech Academy proje katılımcılarından biriyim. 

Proje, 20–28 yaş aralığındaki 25 kadını 3 ay boyunca yazılım eğitimleriyle güçlendirerek sektörde iş gücüne katılımını hedefliyor. 

Projeyle ilgili daha fazla bilgiye https://sisterslab.co/women-in-tech-academy/ adresinden ulaşabilirsiniz.

Women in Tech Academy bitirme projesi kapsamında Brezilya tabanlı bir online alışveriş sitesinin 9 adet csv dosyası analiz edilmiş ve görselleştirilmiştir. 


# E- Commerce Dataset
---

* Brezilya e-ticaret sitesinin siparişleri, satıcıları, ürünleri, siparişlerin ödeme yöntemi, siparişin içinde olan ürünler gibi bilgiler bulunmaktadır. 

* Bu bilgileri içeren 9 adet veri seti vardır.


## Veri Setleri Hakkında Bilgilendirme; 💡
---

1. **Costumers Dataset:**  Müşteri bilgileri id, şehir, posta kodu ve elayet bilgilerini içermektedir. 

2. **Geolocation Dataset:** Şehir, posta kodu, elayet, enlem ve boylam bilgilerini içermektedir. 

3. **Order Items Dataset:** Sipariş numarası, ürün numarası, satıcı numarası ve fiyat bilgilerini içermektedir. 

4. **Order Payments Dataset:** Sipariş numarası, taksit miktarı, ödeme türü ve fiyat bilgilerini içermektedir. 

5. **Order Reviews Dataset:** Değerlendirme ve sipariş numarası, müşteri değerlendirme puanı, yorum vb. bilgilerini içermektedir.

6. **Orders Dataset:** Sipariş ve müşteri numarası; sipariş alınma, onaylanma, kargoya veriliş ve teslimat gün/saat bilgilerini içermektedir.

7. **Product Category Name Translation:** Portekizce kategori isimleri ve bunların İngilizceye çevrilmiş hali bilgilerini içermektedir. 

8. **Product Dataset:** Ürün numarası, kategori ismi, site içerisinde yer alan başlık, fotoğraf, açıklama, ürün ebatları gibi bilgileri içermektedir. 

9. **Sellers Dataset:** Bu veri setinde satıcı nuarası ve satıcıya ait konum bilgileri verilmiştir. 


## Analizde Kullanılan Kütüphaneler; 📚
---

* Pandas

* Matplotlib

* Seaborn


![E-Commerce Icon](https://thenounproject.com/api/private/icons/5306224/edit/?backgroundShape=SQUARE&backgroundShapeColor=%23000000&backgroundShapeOpacity=0&exportSize=752&flipX=false&flipY=false&foregroundColor=%23000000&foregroundOpacity=1&imageFormat=png&rotation=0&token=gAAAAABjeNq1SiGRRMQc6G_DtYzxJDjjttSf_QXaUPu3HZhjNVlrGH8X_qJYNaxoLQikN027uUAd1x1ykV-32u56emoCCZS19Q%3D%3D)


## Yapılan Analiz ve Görselleştirmeler; 🧠
---

* Siparişler ortalama ne kadar tuttu?

* E-ticaret sitesinin müşterileri ve satıcıları çoğunlukla hangi şehirde yaşıyor?

* Ödeme türlerinin birbirlerine oranı.

![Ödeme türü oranları](/Users/irems/Desktop/odemetipi.png)

* Fiyat arttıkça müşterilerin taksit yapma eğilimi artıyor mu?

![Taksit miktarı ve Tutar](/Users/irems/Desktop/taksitOdeme.png)

* Aylara göre sipariş sayısı.

![Aylara göre sipariş sayııs](/Users/irems/Desktop/aylaraGoreSiparis.png)

* Hangi satıcının ne kadar ürün sattığı. 

* Yüksek satış miktarı ile yüksek değerlendirme puanı arasında bir ilişki var mı?

![Yüksek Satış ve Yüksek Değerlendirme](/Users/irems/Desktop/topSiparisOrtDegerlendirme.png)

* Hangi kategoriden ne kadar ürün satıldığı.

* Kategorilere göre ortalama fiyat değişimi.

* Satıcıların siparişlerini kargoya verme hızı ortalamaları.

* Ürünlerin müşteriye ortalama ulaştığı süre.

* Müşteriler kötü değerlendirmeleri mi yoksa iyi değerlendirmeleri mi daha hızlı bir şekilde yapmaya meyilli? 

![Yorum Hızı ve Değerlendirme Puanı İlişkisi](/Users/irems/Desktop/degerlendirmeZamanPuanİlişkisi.png)

* Müşteriler daha çok kötü olarak değerlendirdikleri ürünlere mi yoksa iyi olarak değerlendirdikleri ürünlere mi yorum yapıyorlar? 

![Yorumlu Analiz](/Users/irems/Desktop/yorumluanaliz.png)

![Yorumsuz Analiz](/Users/irems/Desktop/yorumsuzanaliz.png)

* En yüksek ve en düşük puan alan yorumlardaki en sık kullanılan 10 kelime ve 5 cümle. (1 puan ve 5 puan) 

