# EnergyEfficientDataset
- Energy Efficient Veriseti kullanılarak ısınma ve soğutma yükünün tahmin edilmesi
- Bu notebook'ta bir regression problemi olan ısıtma ve soğutma yükü tahmini 'Energy Efficient' veriseti için uygulanmıştır.

- Makine Öğrenmesi yöntemi olarak RandomForestRegressor kullanılmıştır.

- Değerlendirme yöntemi olarak MAE, RMSLE ve R^2 metrikleri tahmin edilen değerler ve gerçek değerler arasındaki hatayı hesaplamak için kullanılmıştır.

### Veriseti
Veriseti aşağıdaki linkten bulunabilir. https://www.kaggle.com/elikplim/eergy-efficiency-dataset?select=ENB2012_data.csv

Verisetinde 768 satır veri ve 10 sütun bulunmaktadır. Sütunların özellikleri kısaca aşağıdaki gibidir. 
X1 Relative Compactness
X2 Surface Area
X3 Wall Area
X4 Roof Area
X5 Overall Height
X6 Orientation
X7 Glazing Area
X8 Glazing Area Distribution
y1 Heating Load
y2 Cooling Load

Veri ile ilgili detaylı açıklamaya da yukarıdaki linkten ulaşabilirsiniz.

Veri Seti %60 eğitim %20 doğrulama ve %20 test verisi olarak ayrılmıştır.

### Kullanılan Kütüphaneler
Pandas veri analizi için kullanılmıştır
Numpy nümerik işlemler için kullanılmıştır.
Matplotlib ve seaborn veri görselleştirme için kullanılmıştır.
Scikit-learn makine öğrenmesi modelleme ve değerlendirmesi için kullanılmıştır.
