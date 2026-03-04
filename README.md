# 🌍 Comprehensive Earthquake Data Analysis & Predictive Modeling

## 📌 Project Overview
Bu proje, Türkiye’deki tarihsel deprem verileri üzerinde kapsamlı veri analizi, zaman serisi modelleme ve makine öğrenmesi uygulamaları içermektedir.

**Temel Amaçlar:**
* Deprem dağılımını istatistiksel olarak incelemek.
* Günlük deprem sayısını tahmin etmek.
* Deprem büyüklüklerini modellemek ve olağandışı sismik örüntüleri tespit etmektir.

---

## 📊 Data Understanding & Preprocessing
Uçtan uca analitik süreç için veri şu adımlardan geçirilmiştir:
* **Feature Engineering:** Tarih ve saat değişkenleri birleştirilerek zaman serisi formatına dönüştürüldü.
* **Cleaning:** Eksik ve tutarsız gözlemler temizlendi.
* **Transformation:** Günlük deprem sayısı türetilerek analiz için veri sadeleştirildi.

---

## 📈 Exploratory Data Analysis (EDA)

* Deprem büyüklüğü ve derinlik dağılımı incelendi.
* Günlük deprem sayısının zaman içindeki değişimi analiz edildi.
* Bölgesel yoğunluk ve coğrafi dağılım görselleştirildi.

---

## ⏳ Time Series Modeling
Günlük deprem sayısı üzerinden sismik aktivitenin zamansal örüntüsünü anlamak için şu modeller kullanıldı:
* **ARIMA:** Kısa vadeli tahminler üretildi.
* **SARIMA:** Mevsimsel etkiler modele dahil edildi.
* **Evaluation:** Model performansı geçmiş veriler üzerinden değerlendirildi.

---

## 🤖 Predictive Modeling – Magnitude Estimation
Latitude, Longitude ve Depth değişkenleri kullanılarak büyüklük tahmini yapılmıştır:
* **Algorithm:** Gradient Boosting Regressor.
* **Metrics:** Performans $RMSE$ ve $R^2$ metrikleri ile ölçülmüştür.

---

## 🗺️ Geospatial Visualization

* **GeoPandas** kullanılarak deprem lokasyonları harita üzerinde görselleştirildi.
* Yoğunluk bölgeleri analiz edilerek mekânsal örüntüler yorumlandı.

---

## 🛠 Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow / Keras
* **Visualization:** Matplotlib, Seaborn, GeoPandas

---

## 🎯 Conclusion
Bu proje, deprem verileri üzerinde istatistiksel analiz ve makine öğrenmesi tekniklerini entegre eden kapsamlı bir çalışmadır. Amaç yalnızca tahmin üretmek değil; sismik verinin yapısını anlamak ve örüntüleri ortaya çıkarmaktır.
