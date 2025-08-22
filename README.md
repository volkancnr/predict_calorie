# predict_calorie

Kaggle üzerinden aldığpımız veri ile (https://www.kaggle.com/datasets/adilshamim8/predict-calorie-expenditure) HistGradientBoostingRegressor kullanılarak regresyon modeli kurarak regresyonun açıklanabilirliğini test ederek tahminler yapma. aynı zamanda veri görselleştirme ve analiz teknikleriyle veriyi incelemek hedeflenmiştir.
train veriseti ilk 5 satırı:

<img width="623" height="168" alt="image" src="https://github.com/user-attachments/assets/559fcd3d-4cc5-4c91-8ed4-ea17833b7f2e" />

test veriseti ilk 5 satırı:

 <img width="592" height="168" alt="image" src="https://github.com/user-attachments/assets/b6be690a-3437-4870-846e-b75ff5b68a17" />

verisetinin çeşitli görselleştirmeleri: 

<img width="600" height="578" alt="image" src="https://github.com/user-attachments/assets/080851bd-58a1-4877-8b24-d2b2adf98074" />

<img width="584" height="574" alt="image" src="https://github.com/user-attachments/assets/7729cb7e-ac1a-4287-8f62-22da84653c8c" />

<img width="587" height="578" alt="image" src="https://github.com/user-attachments/assets/ffff1fbb-e060-4a8e-ab10-4cec8236f5fb" />

<img width="840" height="738" alt="image" src="https://github.com/user-attachments/assets/f71a28e3-837c-43da-9145-8ff4d3d88a81" />


# Önemli Çıkarımlar:

Kalori yakımını en çok etkileyen faktör aktivite süresi

İkinci en önemli faktör kalp atış hızı

Cinsiyet, kalori yakımında çok belirleyici bir faktör değil

# Most Important Findings:

The most important factor affecting calorie burn is activity duration

The second most important factor is heart rate

Gender is not a very determinant factor in calorie burn

 Model değerlendirme sonuçları:
  - R²: 0.9963
  - RMSE: 3.8098
  - MAE: 2.3716
