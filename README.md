🌍 Comprehensive Earthquake Data Analysis & Predictive Modeling
📌 Project Overview

Bu proje, Türkiye’deki tarihsel deprem verileri üzerinde kapsamlı veri analizi, zaman serisi modelleme ve makine öğrenmesi uygulamaları içermektedir.

Amaç; deprem dağılımını istatistiksel olarak incelemek, günlük deprem sayısını tahmin etmek, deprem büyüklüklerini modellemek ve olağandışı sismik örüntüleri tespit etmektir.

Proje; veri ön işleme, keşifsel analiz, zaman serisi modelleme, regresyon ve anomali tespiti adımlarını kapsayan uçtan uca bir analitik süreç sunmaktadır.

📊 Data Understanding & Preprocessing

Tarih ve saat değişkenleri birleştirilerek zaman serisi formatına dönüştürüldü

Eksik ve tutarsız gözlemler temizlendi

Günlük deprem sayısı türetildi

Analiz için gerekli değişkenler seçilerek veri sadeleştirildi

📈 Exploratory Data Analysis (EDA)

Deprem büyüklüğü ve derinlik dağılımı incelendi

Günlük deprem sayısının zaman içindeki değişimi analiz edildi

Bölgesel yoğunluk ve coğrafi dağılım görselleştirildi

Bu aşama, modelleme öncesi veri davranışının anlaşılmasını sağlamıştır.

⏳ Time Series Modeling

Günlük deprem sayısı üzerinden zaman serisi analizi gerçekleştirildi.

ARIMA modeli ile kısa vadeli tahminler üretildi

SARIMA modeli ile mevsimsel etkiler modele dahil edildi

Model performansı geçmiş veriler üzerinden değerlendirildi

Amaç; sismik aktivitenin zamansal örüntüsünü anlamak ve tahmin edilebilirliğini test etmektir.

🤖 Predictive Modeling – Magnitude Estimation

Latitude, Longitude ve Depth değişkenleri kullanılarak büyüklük tahmini yapılmıştır.

Gradient Boosting Regressor ile model geliştirilmiş, performans RMSE ve R² metrikleri ile ölçülmüştür.

Tahmin sonuçları, depremlerin büyüklüğünü anlamada belirli bir açıklayıcılık sağlamaktadır.

🌍 Geospatial Visualization

GeoPandas kullanılarak deprem lokasyonları harita üzerinde görselleştirildi

Yoğunluk bölgeleri analiz edildi

Bu adım, mekânsal örüntülerin daha net yorumlanmasını sağladı.

🛠 Technologies Used

Python

Pandas, NumPy

Scikit-Learn

TensorFlow / Keras

Matplotlib, Seaborn

Folium, GeoPandas

📌 Key Insights

Depremler belirli bölgelerde yoğunlaşma göstermektedir.

Zaman serisi modelleri kısa vadeli tahminlerde tutarlı sonuçlar üretmiştir.

Autoencoder yöntemi olağandışı sismik olayları ayırt edebilmiştir.

🎯 Conclusion

Bu proje, deprem verileri üzerinde istatistiksel analiz, zaman serisi modelleme, ve coğrafi görselleştirme tekniklerini entegre eden kapsamlı bir analitik çalışma sunmaktadır.

Amaç yalnızca tahmin üretmek değil; sismik verinin yapısını anlamak, örüntüleri ortaya çıkarmak ve farklı analitik yaklaşımları karşılaştırmalı olarak değerlendirmektir.
