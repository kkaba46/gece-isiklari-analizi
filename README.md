# gece-isiklari-analizi

# Türkiye Ulusal Gözlemevleri Bünyesindeki Erzurum DAG Yerleşkesi ve Antalya TUG Yerleşkesi için Gece Işıklarının Analizi
## TÜBİTAK 3501 Kariyer Geliştirme Programı (Proje No: 124F297)

Bu depo, **TÜBİTAK 3501** projesi kapsamında geliştirilen, uydu uzaktan algılama verileri ve yer tabanlı gözlemlerle ışık kirliliğini inceleyen açık kaynaklı bir eğitim ve uygulama serisidir.

---

## 👥 Proje Ekibi & Dokümanı Hazırlayanlar
- **Dr. Kazım Kaba** (Yürütücü)
- **Dr. Funda Aksoy** (Araştırmacı)
- **Doç. Dr. İlham Nasıroğlu** (Araştırmacı)
- **Fethullah Polat** (Bursiyer)
- **Sima Aydın** (Bursiyer)
- **Rabia Beyza Türkmen**  (Bursiyer)
- **Yusuf Sağlam** (Bursiyer)
- **Prof.Dr. Cahit Yeşilyaprak** (Danışman)
- **Prof.Dr. H. Mustafa Kandırmaz** (Danışman)

---

## 📂 Depo Yapısı
* `notebooks/`: Eğitim amaçlı hazırlanan adım adım Jupyter Notebook (`.ipynb`) dosyaları.
* `veri/`: Analizlerde kullanılan verilerin (`.txt`, `.tif`) bir kısmı bu dizinde paylaşılmaktadır.

---

## 🚀 İçerik ve Eğitim Serisi
Bu seride işlenen temel modüller şunlardır:
1. **Yer Tabanlı SQM Ölçümleri:** SQM cihazı veri standardizasyonu, Bortle skalasına göre sınıflandırma ve TİKE değişim analizi.
2. **VIIRS NTL Veri Temini ve İşleme:** NASA LAADS DAAC üzerinden VNP46A1/A2 günlük ürünlerinin temin edilmesi ve işlenmesi.
3. **Veri dönüşümleri, Mekânsal ve İstatistiksel Modelleme:** Logaritmik transfer fonksiyonlarının uygulanması, interpolasyon modellerinin geliştirilmesi.
4. **Hibrit  Modelleme:** Makine öğrenme algoritmaları ile hibrit interpolasyon modellerinin geliştirilmesi.
5. **Zamansal Analizler:** VIIRS NTL verilerinden zaman serisi analizleri.
6. **Konumsal Analizler:**  VIIRS NTL verilerinden değişim tespiti analizleri.
7. **Gece Işıklarının Spektral Analizleri:** Yapay gece ışıklarının SDGSAT-1 Glimmer görüntülerinden çok bantlı analizleri.
8. **Atmosferik Aerosol ve Işık Kirliliği:** Aerosol parametrelerinin hesaplanması ve ışık kirliliği ile etkileşimleri.

---

## 🛠️ Kurulum ve Gereksinimler
Kodların yerel bilgisayarınızda çalışabilmesi için Python standart modüllerine ek olarak gerekli olan Python kütüphaneleri:
* `pandas`, `numpy`, `scipy`, `matplotlib`
* `gdal`, `rasterio`, `xarray`,  `rioxarray`, `pyproj`, `cartopy`, `geopandas`
* `pykrige`, `scikit-learn`, `xgboost`

---

## 📜 Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Özgürce inceleyebilir, paylaşabilir ve akademik çalışmalarınızda referans verebilirsiniz.
