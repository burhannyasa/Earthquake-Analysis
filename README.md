Earthquake Analysis

Proje Amacı
Bu proje, Türkiye'deki depremlere ait verileri analiz etmek, anomalileri tespit etmek ve deprem büyüklüklerini tahmin etmek amacıyla geliştirilmiştir. Deprem verileri üzerinde yapılan çeşitli görselleştirmeler, istatistiksel analizler ve makine öğrenimi teknikleri ile depremlerin dağılımını ve olası anormallikleri inceleyerek, gelecekteki depremlerin büyüklükleri hakkında tahminler yapılmaya çalışılmıştır.

Projenin Kapsamı
Deprem verilerinin analizi ve tahmin süreci, şu adımlardan oluşmaktadır:

1. Veri Yükleme ve Ön İşleme
Veri seti, Türkiye'deki geçmiş deprem verilerini içermektedir. Veriler, farklı kodlamalarla başarıyla yüklendikten sonra tarih ve saat sütunları birleştirilerek datetime formatına dönüştürülmüş, eksik ve hatalı veriler temizlenmiştir. Ayrıca, verinin boyutu küçültülerek gerekli sütunlar seçilmiş ve okunabilir hale getirilmiştir.

2. Görselleştirme (Visualization)
Verilerin analizi için çeşitli grafikler ve görselleştirmeler yapılmıştır:

Deprem Büyüklüğü Dağılımı: Depremlerin büyüklük dağılımını incelemek için histogram ve yoğunluk grafikleri kullanılmıştır.
Günlük Deprem Sayısı: Deprem verilerinin zaman içindeki değişimlerini görmek amacıyla günlük deprem sayıları zaman serisi grafiği ile görselleştirilmiştir.
Derinlik ve Büyüklük Histogramları: Depremlerin derinlik ve büyüklük dağılımları ayrıca histogramlar kullanılarak incelenmiştir.
3. Zaman Serisi Analizi
ARIMA Modeli: Günlük deprem sayısı verisi üzerinde ARIMA modeli oluşturularak, geçmiş verilerden yola çıkarak gelecekteki deprem sayıları tahmin edilmiştir. Modelin performansı geçmiş verilere göre değerlendirilmiştir.
SARIMA Modeli: Mevsimsel etkileri de göz önünde bulundurmak için SARIMA modeli kullanılarak, günlük deprem sayılarının tahmini gerçekleştirilmiştir.
4. Anomali Tespiti
Otomatik kodlayıcı (autoencoder) modeli kullanılarak deprem verilerinde anomaliler tespit edilmiştir. Bu anomaliler, coğrafi konumlarına göre harita üzerinde işaretlenmiş ve anomalilerin hangi bölgelerde yoğunlaştığı analiz edilmiştir.

5. Deprem Tahmin Modelleri
Makine öğrenimi modelleri kullanılarak deprem büyüklüklerinin tahmin edilmesi hedeflenmiştir:

Random Forest Regresyon: Bu model, deprem büyüklüklerini tahmin etmek için kullanılmış ve modelin performansı değerlendirilmiştir.
Lineer Regresyon: Deprem büyüklüğünü etkileyen faktörleri anlamak amacıyla lineer regresyon modeli uygulanmıştır. Modelin performansı RMSE ve R^2 skorları ile değerlendirilmiştir.
LSTM (Long Short-Term Memory): Derin öğrenme tabanlı bir model kullanılarak, geçmiş verilerle deprem sayıları tahmin edilmiştir.
SVM (Support Vector Machine): 5 ve üzeri büyüklükteki depremleri sınıflandırmak amacıyla destek vektör makineleri kullanılmıştır. Modelin başarısı, karmaşıklık ve sınıflandırma raporu ile ölçülmüştür.
6. Kümelenme Analizi (Clustering Analysis)
K-means kümeleme algoritması kullanılarak deprem büyüklükleri ve derinlikleri arasındaki ilişkiler incelenmiş ve veri kümeleri oluşturulmuştur. Bu kümeleme, deprem verilerinin daha iyi anlaşılmasına yardımcı olmuştur.

7. Coğrafi Görselleştirme ve Haritalama
Folium ile Harita Üzerinde Görselleştirme: Deprem verileri, Folium kütüphanesi kullanılarak Türkiye haritası üzerinde görselleştirilmiştir. Harita üzerinde, anomaliler ve deprem lokasyonları işaretlenmiş, deprem yoğunluk bölgeleri analiz edilmiştir.
(GIS) Analiz: Coğrafi bilgi sistemleri (GIS) kullanılarak deprem verileri, Türkiye haritası üzerinde gösterilmiş ve deprem lokasyonları ile ilgili coğrafi analizler gerçekleştirilmiştir.
Kullanılan Teknolojiler
Python: Veri analizi, görselleştirme ve modelleme süreçlerinde ana dil olarak kullanılmıştır.
Pandas ve NumPy: Veri işleme ve analiz için kullanılmıştır.
Matplotlib ve Seaborn: Verilerin görselleştirilmesi için kullanılmıştır.
Scikit-learn: Makine öğrenimi modellerinin oluşturulması ve değerlendirilmesi için kullanılmıştır.
TensorFlow ve Keras: Derin öğrenme modelleri (LSTM ve autoencoder) için kullanılmıştır.
Folium: Depremlerin coğrafi dağılımlarını görselleştirmek için kullanılmıştır.
Geopandas: Coğrafi veri görselleştirmelerinde kullanılmıştır.




















