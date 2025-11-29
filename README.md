# 🏥 Medical Insurance Cost Prediction (Sağlık Sigortası Maliyet Tahmini)

Bu proje, kişisel özelliklere (yaş, vki, sigara kullanımı vb.) dayanarak sağlık sigortası maliyetlerini tahmin eden bir Makine Öğrenmesi (Machine Learning) modellemesidir.

## 🎯 Proje Amacı
- Veri bilimi ve istatistiksel analiz yöntemlerini kullanarak veriyi anlamlandırmak.
- Keşifçi Veri Analizi (EDA) ile değişkenler arasındaki ilişkileri (özellikle sigara kullanımının maliyete etkisini) ortaya çıkarmak.
- Linear Regression modeli ile maliyet tahmini yapmak.

## 🛠️ Kullanılan Teknolojiler
- **Python**
- **Pandas & Numpy:** Veri manipülasyonu
- **Matplotlib & Seaborn:** Veri görselleştirme
- **Scikit-learn:** Modelleme ve veri ön işleme (One-Hot Encoding, Label Encoding)

## 📊 Öne Çıkan Bulgular
- **Sigara Kullanımı:** Sigara içenlerin sigorta masrafları, içmeyenlere göre belirgin şekilde (yaklaşık 20.000 - 30.000 birim) daha yüksektir.
- **Yaş Etkisi:** Yaş arttıkça maliyet doğrusal olarak artmaktadır.
- **Model Başarısı:** İlk kurulan Linear Regression modeli, sigara içen ve içmeyen ayrımını net bir şekilde yapabilmiştir.

