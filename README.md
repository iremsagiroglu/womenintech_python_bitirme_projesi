### Herkese merhaba! ⚡

SistersLab’in Toplum Gönüllüleri Vakfı tarafından desteklenen Women in Tech Academy proje katılımcılarından biriyim. 

Proje, 20–28 yaş aralığındaki 25 kadını 3 ay boyunca yazılım eğitimleriyle güçlendirerek sektörde iş gücüne katılımını hedefliyor. 

Projeyle ilgili daha fazla bilgiye https://sisterslab.co/women-in-tech-academy/ adresinden ulaşabilirsiniz.

Women in Tech Academy bitirme projesi kapsamında Brezilya tabanlı bir online alışveriş sitesinin 9 adet csv dosyası analiz edilmiş ve görselleştirilmiştir. 


![image](https://user-images.githubusercontent.com/111069609/202862182-b192e3c2-65ff-4196-80a9-032d974804e4.png)


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



## Yapılan Analiz ve Görselleştirmeler; 🧠
---

* **Siparişler ortalama ne kadar tuttu?**


* **E-ticaret sitesinin müşterileri ve satıcıları çoğunlukla hangi şehirde yaşıyor?**


* **Ödeme türlerinin birbirlerine oranı.**


![odemetipi](https://user-images.githubusercontent.com/111069609/202861607-5a921737-1e72-42fd-852f-dda4a566fc18.png)


* **Fiyat arttıkça müşterilerin taksit yapma eğilimi artıyor mu?**


![taksitOdeme](https://user-images.githubusercontent.com/111069609/202861636-c2e83a70-2eb1-438a-8aa2-64a25af6146a.png)


* **Aylara göre sipariş sayısı.**


![aylaraGoreSiparis](https://user-images.githubusercontent.com/111069609/202861650-4b4cc407-92c1-49fd-976d-86e3524c7a59.png)


* **Hangi satıcı ne kadar ürün sattı?** 


* **Yüksek satış miktarı ile yüksek değerlendirme puanı arasında bir ilişki var mı?**


![topSiparisOrtDegerlendirme](https://user-images.githubusercontent.com/111069609/202861666-d1c68785-fb41-4b50-a777-921fd4a0ec48.png)


* **Hangi kategoriden ne kadar ürün satıldı?**


* **Kategorilere göre ortalama fiyat değişimi.**


* **Satıcıların siparişlerini kargoya verme hızı ortalamaları.**


* **Ürünlerin müşteriye ortalama ulaştığı süre.**


* **Müşteriler kötü değerlendirmeleri mi yoksa iyi değerlendirmeleri mi daha hızlı bir şekilde yapmaya meyilli?** 


![degerlendirmeZamanPuanİlişkisi](https://user-images.githubusercontent.com/111069609/202861684-1d0c4896-a135-4bbc-9751-f7886772f3fa.png)


* **Müşteriler daha çok kötü olarak değerlendirdikleri ürünlere mi yoksa iyi olarak değerlendirdikleri ürünlere mi yorum yapıyorlar?** 


![yorumsuzanaliz](https://user-images.githubusercontent.com/111069609/202861688-8e9e0fe2-ffdc-47d0-a435-77d0d0cd7801.png)

![yorumluanaliz](https://user-images.githubusercontent.com/111069609/202861697-e9596584-856a-4afe-a97e-534501124261.png)


* **En yüksek ve en düşük puan alan yorumlardaki en sık kullanılan 10 kelime ve 5 cümle. (1 puan ve 5 puan)** 

