# Steam Game Sales Prediction

Bu proje Steam oyunlarının satış tahminini yapmayı amaçlamaktadır.  
Veri analizi, makine öğrenimi modelleri (Random Forest ve XGBoost) ile tahmin yapılmıştır.

## Veri Seti

- Oyunların fiyatı, pozitif/negatif değerlendirmeleri, ortalama oynama süresi gibi özellikler içerir.
- `owners` değişkeni logaritmik olarak dönüştürülerek hedef değişken olarak kullanılmıştır.

## Kullanılan Teknolojiler

- Python 3.x
- pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn

## Kurulum

```bash
pip install -r requirements.txt
Sonuçlar
Random Forest ve XGBoost modelleri kullanıldı.

RMSE değerleri:

Random Forest (tuned): 0.4588

XGBoost (tuned): 0.4538

SHAP ile Özellik Önemi
Model açıklanabilirliği için SHAP değerleri hesaplandı ve görselleştirildi.
