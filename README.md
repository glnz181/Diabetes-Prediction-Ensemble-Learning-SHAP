# Topluluk Öğrenme Modelleri ile Diyabet Tahmini

Bu proje, diyabet hastalığının erken teşhisinde modern makine öğrenmesi algoritmalarının performansını ve model açıklanabilirliğini incelemek amacıyla geliştirilmiştir. Pima Indian veri seti üzerinde yürütülen çalışmada, veri ön işleme ve özellik mühendisliği teknikleri ön planda tutulmuştur.

## 📊 Proje Özeti
Bu çalışma, Sivas Cumhuriyet Üniversitesi Bilgisayar Mühendisliği bölümü bünyesinde hazırlanmıştır. Proje kapsamında eksik verilerin yönetimi, medyan tamamlama ve ileri seviye özellik mühendisliği (Feature Engineering) teknikleri uygulanarak model başarımı artırılmıştır.

## 🚀 Öne Çıkan Sonuçlar
* **En İyi Model:** CatBoost
* **Doğruluk (Accuracy):** %89,58
* **F1-Skoru:** %87,93
* **Optimizasyon:** GridSearchCV ve Bayesian Optimizasyon yöntemleri kıyaslanmıştır.

## 🛠️ Metodoloji ve Teknik Detaylar
* **Veri Seti:** Pima Indian Diabetes Dataset.
* **Kullanılan Algoritmalar:** * CatBoost (En yüksek performans)
    * Extra Trees Classifier
* **Özellik Mühendisliği:** Glikoz seviyesi ve "Yaş-Kan Basıncı Etkileşimi" gibi yeni değişkenler türetilerek modelin tahmin gücü desteklenmiştir.
* **Açıklanabilirlik:** Modellerin karar verme süreçleri **SHAP (SHapley Additive exPlanations)** analizi ile şeffaflaştırılmıştır.

## 📈 Performans Karşılaştırması
| Model | Doğruluk (Accuracy) | F1-Skoru |
| :--- | :--- | :--- |
| **CatBoost** | **%89,58** | **%87,93** |
| Extra Trees | %86,45 | %84,20 |

## 💻 Kullanılan Teknolojiler
* Python
* CatBoost & Scikit-Learn
* Pandas & NumPy
* SHAP (Model Interpretability)
* Gradio (Kullanıcı arayüzü için)

## 📂 Dosya Yapısı
* `Kod.ipynb`: Veri analizi, model eğitimi ve test aşamalarını içeren Jupyter Notebook.
* `Bildiri.docx`: Projenin akademik detaylarını içeren rapor dosyası.
* `diabetes.csv`: Eğitimde kullanılan veri seti.

## 📝 Yazarlar
Bu çalışma; Kayra Belinay Kınaş, Ecenur Işık ve Gülnaz Şeker tarafından gerçekleştirilmiştir.
