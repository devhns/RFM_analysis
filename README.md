# RFM Analizi

Daha fazla yeni müşteri hedefi yerine mevcut müşteriyi elde tutmanın yolları ile müşteri ilişkilerinde daha güçlü bir bağ oluşturmayı sağlar. Elde edilen veri üzerinden belli kriterler ve incelemelerle ilerleyerek o zamana kadar ki mevcut müşteri kitlesinin analiz edilmesi ve analize göre müşteri segmentasyonu gerçekleştirmede en sık kullanılan tekniklerden biri RFM Analizi’dir.

***RFM,mantığını kısaltması içinde saklar. Yani her bir harf bir faktörü temsil eder.<br/>***

**R – Recency (Yenilik):** Müşterinin son alışverişinden bu yana geçen süre olarak tanımlansada yapılan analize göre son ziyareti şeklinde de değerlendirilebilir.<br/>
**F – Frequency (Sıklık):** Müşterinin analiz edilen aralıkta ne sıklıkla alım yaptığı ya da analize göre ziyarette bulunduğu bilgisidir.<br/>
**M – Monetary  (Parasal Durum):** Müşterinin analiz edilen aralıkta ne kadar harcama yaptığı bilgisidir. <br/>

![In-content-screen-shot-1](https://user-images.githubusercontent.com/66906729/123497536-acc37200-d636-11eb-8db1-f6402fc52a90.png)

Görüntü kaynak: https://clevertap.com/blog/automate-user-segmentation-with-rfm-analysis/

***Veri Kümesi Hakkında;***

**InvoiceNo:** Yapılan alışverişin faturası için eşsiz olarak üretilen 6 basamaklı fatura numarasını içeren sütundur.<br/>
**StockCode:** Ürünün stoktaki mevcut durumunun incelenebilmesini sağlayan 5 basamaklı ve her ürün için eşsiz olan stok kodlarını içeren sütundur.<br/>
**Description:** Ürüne ait isim/açıklama bilgisini saklayan sütundur.<br/>
**Quantity:** Alışveriş başına olan ürün miktarıdır.<br/>
**InvoiceDate:** Tarih ve saat cinsinden fatura kesim zamanını saklayan sütundur.<br/>
**UnitPrice:** Birim başına ürün fiyatıdır.<br/>
**CustomerID:** Her müşteriye eşsiz olarak verilen müşteri ID bilgisini saklayan sütundur.<br/>
**Country:** Alışverişi yapan müşterinin hangi ülkeden olduğu bilgisini veren sütundur.<br/>

*Bu reponun içerisindeki .ipynb uzantılı Jupyter Notebook dosyasında Online Retail verisi üzerine RFM analizi uygulanmıştır. Dosya içerisinden kodlama aşamaları ve diğer bilgilere ulaşabilirsiniz.*
