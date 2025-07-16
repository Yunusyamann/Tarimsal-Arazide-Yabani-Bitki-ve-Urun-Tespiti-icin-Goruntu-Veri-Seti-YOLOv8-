# Tarımsal Arazide Yabani Bitki ve Ürün Tespiti için Görüntü Veri Seti (YOLOv8)

Bu depo, **"Tarımsal Arazide Yabani Bitki Tespiti: Tekli ve Çoklu Sınıf Eğitimlerinin Karşılaştırılması ve Model Çıktılarının Analizi"** başlıklı makalemizde kullanılan görüntü veri setini içermektedir. Veri seti, YOLOv8 modeli kullanılarak tarımsal ürünlerin ve yabani bitkilerin tespiti amacıyla oluşturulmuş ve etiketlenmiştir.

## 📖 Proje Hakkında

[cite_start]Bu çalışmanın temel amacı, derin öğrenme tabanlı bir nesne algılama modeli olan YOLOv8 kullanarak tarımsal alanlardaki yabani bitkileri tespit etmek için yapay zekâ tabanlı bir çözüm sunmaktır[cite: 7, 8, 40]. [cite_start]Yabani bitkiler, ekinlerle su, besin ve güneş ışığı gibi kaynaklar için rekabet ederek ürün verimini ve kalitesini önemli ölçüde azaltmaktadır[cite: 6]. [cite_start]Geliştirilen bu sistem, tarımsal üretimde verimliliği artırmayı, maliyetleri düşürmeyi ve sürdürülebilir uygulamaları desteklemeyi hedeflemektedir[cite: 50].

## 📊 Veri Seti Detayları

Veri seti, 4 farklı tarımsal ürün ve 2 farklı yabani bitki sınıfını içermektedir.

* [cite_start]**Toplam Görüntü Sayısı:** Yaklaşık 200 orijinal görüntü, veri artırma (data augmentation) teknikleriyle ~1200 görüntüye çıkarılmıştır[cite: 11, 12, 213].
* [cite_start]**Etiketleme Formatı:** Tüm görseller, YOLO (Darknet TXT) formatında `LabelImg` programı kullanılarak etiketlenmiştir[cite: 152, 210].
* **Veri Seti Dağılımı:**
    * [cite_start]Eğitim (Train): %80 [cite: 155, 214]
    * [cite_start]Doğrulama (Validation): %10 [cite: 155, 214]
    * [cite_start]Test: %10 [cite: 155, 214]

### Sınıflar (Classes)

[cite_start]Veri seti aşağıdaki 6 sınıftan oluşmaktadır[cite: 146]:
1.  `elma`
2.  `havuc`
3.  `kabak`
4.  `marul`
5.  `yabani_ot_1`
6.  `yabani_ot_2`

## 📥 Veri Setini İndirme

Veri setinin tamamına aşağıdaki Google Drive bağlantısından erişebilirsiniz. Dosyalar, standart YOLO eğitim yapısına uygun olarak `train/`, `valid/` ve `test/` klasörleri altında düzenlenmiştir. Her bir klasörün içinde `images/` ve `labels/` alt klasörleri bulunmaktadır.

➡️ **Veri Seti İndirme Bağlantısı:** **[DRIVE_LINKINIZI_BURAYA_EKLEYIN]**

## 📜 İlişkili Yayın ve Alıntı Yapma

Bu veri setini çalışmanızda kullanırsanız, lütfen aşağıdaki makalemize atıfta bulunun:

[cite_start]**Makale Başlığı:** Tarımsal Arazide Yabani Bitki Tespiti: Tekli ve Çoklu Sınıf Eğitimlerinin Karşılaştırılması ve Model Çıktılarının Analizi [cite: 1]
[cite_start]**Yazarlar:** Yunus YAMAN, Yusuf DEMİR [cite: 2, 3]

### BibTeX Formatında Atıf:
```bibtex
@article{yaman2025tarimsal,
  title={Tarımsal Arazide Yabani Bitki Tespiti: Tekli ve Çoklu Sınıf Eğitimlerinin Karşılaştırılması ve Model Çıktılarının Analizi},
  author={Yaman, Yunus and Demir, Yusuf},
  year={2025},
  journal={Makalenin Yayınlandığı Dergi/Konferans Adı}
}
```
*(Not: `journal` ve `year` alanlarını makalenizin yayın bilgilerine göre güncelleyebilirsiniz.)*

## 📄 Lisans

Bu veri seti, [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.tr) altında lisanslanmıştır. Bu, veri setini ticari olmayan amaçlarla paylaşabileceğiniz ve uyarlayabileceğiniz anlamına gelir, ancak orijinal çalışmaya uygun şekilde atıfta bulunmanız ve kendi katkılarınızı aynı lisans altında dağıtmanız gerekir.
