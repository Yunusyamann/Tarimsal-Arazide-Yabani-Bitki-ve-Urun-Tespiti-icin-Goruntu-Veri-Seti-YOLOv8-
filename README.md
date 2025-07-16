# Tarımsal Arazide Yabani Bitki ve Ürün Tespiti için Görüntü Veri Seti (YOLOv8)

Bu depo, **"Tarımsal Arazide Yabani Bitki Tespiti: Tekli ve Çoklu Sınıf Eğitimlerinin Karşılaştırılması ve Model Çıktılarının Analizi"** başlıklı makalemizde kullanılan görüntü veri setini içermektedir. Veri seti, YOLOv8 modeli kullanılarak tarımsal ürünlerin ve yabani bitkilerin tespiti amacıyla oluşturulmuş ve etiketlenmiştir.

## 📖 Proje Hakkında

Bu çalışmanın temel amacı, derin öğrenme tabanlı bir nesne algılama modeli olan YOLOv8 kullanarak tarımsal alanlardaki yabani bitkileri tespit etmek için yapay zekâ tabanlı bir çözüm sunmaktır. Yabani bitkiler, ekinlerle su, besin ve güneş ışığı gibi kaynaklar için rekabet ederek ürün verimini ve kalitesini önemli ölçüde azaltmaktadır. Geliştirilen bu sistem, tarımsal üretimde verimliliği artırmayı, maliyetleri düşürmeyi ve sürdürülebilir uygulamaları desteklemeyi hedeflemektedir.

## 📊 Veri Seti Detayları

Veri seti, 4 farklı tarımsal ürün ve 2 farklı yabani bitki sınıfını içermektedir.

* **Toplam Görüntü Sayısı:** Yaklaşık 200 orijinal görüntü, veri artırma (data augmentation) teknikleriyle ~1200 görüntüye çıkarılmıştır.
* **Etiketleme Formatı:** Tüm görseller, YOLO (Darknet TXT) formatında `LabelImg` programı kullanılarak etiketlenmiştir.
* **Veri Seti Dağılımı:**
    * Eğitim (Train): %80 
    * Doğrulama (Validation): %10 
    * Test: %10 

### Sınıflar (Classes)

Veri seti aşağıdaki 6 sınıftan oluşmaktadır:
1.  `elma`
2.  `havuc`
3.  `kabak`
4.  `marul`
5.  `yabani_ot_1`
6.  `yabani_ot_2`

## 📥 Veri Setini İndirme

Veri setinin tamamına aşağıdaki Google Drive bağlantısından erişebilirsiniz. Dosyalar, standart YOLO eğitim yapısına uygun olarak `train/`, `valid/` ve `test/` klasörleri altında düzenlenmiştir. Her bir klasörün içinde `images/` ve `labels/` alt klasörleri bulunmaktadır.

➡️ **Veri Seti İndirme Bağlantısı için** **yunusyaman0110@gmail.com adresine mail atınız**

## 📜 İlişkili Yayın ve Alıntı Yapma

Bu veri setini çalışmanızda kullanırsanız, lütfen aşağıdaki makalemize atıfta bulunun:

**Makale Başlığı:** Tarımsal Arazide Yabani Bitki Tespiti: Tekli ve Çoklu Sınıf Eğitimlerinin Karşılaştırılması ve Model Çıktılarının Analizi 
**Yazarlar:** Yunus YAMAN, Yusuf DEMİR 


## 📄 Lisans

Bu veri seti, [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.tr) altında lisanslanmıştır. Bu, veri setini ticari olmayan amaçlarla paylaşabileceğiniz ve uyarlayabileceğiniz anlamına gelir, ancak orijinal çalışmaya uygun şekilde atıfta bulunmanız ve kendi katkılarınızı aynı lisans altında dağıtmanız gerekir.
