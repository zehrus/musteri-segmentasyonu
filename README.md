# Müşteri Segmentasyonu Projesi

## Proje Açıklaması
Bu proje, müşteri davranışlarını analiz ederek müşterileri benzer özelliklerine göre segmentlere ayırmayı amaçlamaktadır. Amaç, pazarlama stratejilerini daha hedefli ve verimli hale getirmektir.

## Problem Tanımı
Şirketler tüm müşterilere aynı yaklaşımı uyguladığında verimsizlik oluşur. Bu proje ile:
- Müşteri grupları belirlenir
- Hedefli pazarlama yapılabilir
- Sadık ve riskli müşteriler ayrıştırılır

## Kullanılan Veri
Proje kapsamında müşteri satın alma davranışlarını içeren veri seti kullanılmıştır. Veri setinde:
- Satın alma sıklığı
- Harcama miktarı
- Müşteri davranış metrikleri bulunmaktadır

## Kullanılan Yöntemler
- Veri temizleme (Data Cleaning)
- Özellik ölçeklendirme (Feature Scaling)
- K-Means Clustering algoritması
- Elbow Method ile optimal küme sayısı belirleme

## Analiz Adımları
1. Veri keşfi (Exploratory Data Analysis)
2. Aykırı değer analizi
3. K-Means modeli kurulumu
4. Optimal cluster sayısının belirlenmesi
5. Müşteri segmentlerinin oluşturulması

## Müşteri Segmentleri
Model sonucunda müşteriler şu gruplara ayrılmıştır:

- **VIP Müşteriler**: Yüksek harcama yapan ve sadık müşteriler  
- **Düzenli Müşteriler**: Orta seviyede alışveriş yapan kullanıcılar  
- **Riskli Müşteriler**: Aktivitesi düşen ve kaybedilme riski olan grup  

## Görselleştirmeler
- Elbow Method grafiği ile optimal cluster sayısı belirlenmiştir  
- Cluster dağılımları scatter plot ile görselleştirilmiştir  

## Kullanılan Teknolojiler
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## İş Etkisi
Bu segmentasyon çalışması sayesinde:
- Pazarlama kampanyaları daha hedefli hale getirilebilir  
- Müşteri kaybı (churn) azaltılabilir  
- Yüksek değerli müşteriler daha iyi analiz edilebilir  

## Sonuç
Bu proje, müşteri segmentasyonu problemini makine öğrenmesi ile çözerek iş kararlarını destekleyen bir analiz ortaya koymaktadır.
