# gece-isiklari-analizi

# Türkiye Ulusal Gözlemevleri Bünyesindeki Erzurum DAG Yerleşkesi ve Antalya TUG Yerleşkesi için Gece Işıklarının Analizi
## TÜBİTAK 3501 Kariyer Geliştirme Programı (Proje No: 124F297)

Bu depo, **TÜBİTAK 3501** projesi kapsamında geliştirilen, uydu uzaktan algılama verileri ve yer tabanlı gözlemlerle ışık kirliliğini inceleyen açık kaynaklı bir eğitim ve uygulama serisidir.

---

## 👥 Proje Ekibi & Dökümanı Hazırlayanlar
- **Dr. Kazım Kaba** (Yürütücü)
- **Dr. Funda Aksoy** (Araştırmacı)
- **Doç. Dr. İlham Nasıroğlu** (Araştırmacı)
- **Fethullah Polat** (Bursiyer)
- **Sima Aydın** (Bursiyer)
- **Rabia Beyza Türkmen**  (Bursiyer)
- **Prof.Dr. H. Mustafa Kandırmaz** (Danışman)

---

## 📂 Depo Yapısı
* `notebooks/`: Eğitim amaçlı hazırlanan adım adım Jupyter Notebook (`.ipynb`) dosyaları.
* `scripts/`: Veri işleme, kesme, mozaikleme ve istatistiksel analizleri yürüten Python betikleri (`.py`).

---

## 🚀 İçerik ve Eğitim Serisi
Bu seride işlenen temel modüller şunlardır:
1. **Yer Tabanlı SQM Ölçümleri:** SQM cihazı veri standardizasyonu, Bortle skalasına göre sınıflandırma ve TİKE değişim analizi.
2. **VIIRS NTL Veri Temini ve İşleme:** NASA LAADS DAAC üzerinden VNP46A1/A2 günlük ürünlerinin GDAL ile WGS84 projeksiyonuna dönüştürülmesi ve Türkiye sınırlarına göre maskelenmesi.
3. **Mekânsal ve İstatistiki Modelleme:** Logaritmik transfer fonksiyonlarının uygulanması, Hibrit interpolasyon modellerinin geliştirilmesi
4. **VIIRS NTL Zamansal ve Konumsal Analizler:** Zaman serisi ve değişim tespiti analizleri
5. **Gece Işıklarının Spektral Analizleri**

---

## 🛠️ Kurulum ve Gereksinimler
Kodların yerel bilgisayarınızda çalışabilmesi için gerekli olan temel Python kütüphaneleri:
* `gdal` (OSGeo)
* `xarray`
* `pandas`
* `numpy`
* `matplotlib`
* `rasterio`
* `geopandas`

---

## 📜 Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Özgürce inceleyebilir, paylaşabilir ve akademik çalışmalarınızda referans verebilirsiniz.
