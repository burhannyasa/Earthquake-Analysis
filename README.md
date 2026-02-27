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

Deprem büyüklüğünü tahmin etmek amacıyla regresyon modelleri geliştirildi:

Random Forest Regressor

Linear Regression

Model performansı RMSE ve R² metrikleri ile değerlendirildi ve karşılaştırıldı.

🚨 Anomaly Detection

Deprem verilerindeki olağandışı örüntüleri tespit etmek amacıyla:

Autoencoder tabanlı anomali tespiti modeli uygulandı

Bu yöntem, ekstrem büyüklükteki veya sıra dışı özelliklere sahip depremlerin belirlenmesini sağladı.

🌍 Geospatial Visualization

Folium ve GeoPandas kullanılarak deprem lokasyonları harita üzerinde görselleştirildi

Yoğunluk bölgeleri analiz edildi

Anomaliler coğrafi olarak işaretlendi

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

Makine öğrenmesi modelleri büyüklük tahmininde anlamlı performans göstermiştir.

Autoencoder yöntemi olağandışı sismik olayları ayırt edebilmiştir.

🎯 Conclusion

Bu proje, deprem verileri üzerinde istatistiksel analiz, zaman serisi modelleme, makine öğrenmesi ve coğrafi görselleştirme tekniklerini entegre eden kapsamlı bir analitik çalışma sunmaktadır.

Amaç yalnızca tahmin üretmek değil; sismik verinin yapısını anlamak, örüntüleri ortaya çıkarmak ve farklı analitik yaklaşımları karşılaştırmalı olarak değerlendirmektir.
