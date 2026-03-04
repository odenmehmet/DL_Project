# 🧠 Derin Öğrenme Eğitim Serisi

> **Bu repo eğitim amaçlıdır.** Derin öğrenmeye adım atmak isteyenler için temel konuları kapsayan Jupyter notebook koleksiyonudur.

![Eğitim](https://img.shields.io/badge/Amaç-Eğitim-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odenmehmet/DL_Project/)

---

## 📚 İçindekiler

| # | Konu | Notebook | Açıklama |
|---|------|----------|----------|
| 1 | Yapay Sinir Ağı (MLP) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odenmehmet/DL_Project/blob/main/Yapay_Sinir_A%C4%9F%C4%B1_(MLP).ipynb) | MNIST el yazısı rakam tanıma |
| 2 | Konvolüsyonel Sinir Ağları (CNN) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odenmehmet/DL_Project/blob/main/Konvol%C3%BCsyonel_Sinir_A%C4%9Flar%C4%B1_(CNN).ipynb) | CIFAR-10 görüntü sınıflandırma |
| 3 | Transfer Learning | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odenmehmet/DL_Project/blob/main/Transfer_Learning.ipynb) | Hazır model ile fine-tuning |
| 4 | Obje Tespiti (YOLO) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odenmehmet/DL_Project/blob/main/YOLO_Nesne_Tespit.ipynb) | YOLOv8 ile gerçek zamanlı nesne tespiti |

---

## 🎯 Konu Detayları

### 1. Yapay Sinir Ağı (MLP)
- **Proje:** Basit El Yazısı Rakam Tanıma (MNIST)
- **Amaç:** Sıfırdan (veya PyTorch ile) MLP kur, MNIST'te rakam tanı.
- **Kazanım:** Sinir ağı temeli, ileri/geri yayılım, optimizasyon.

### 2. Konvolüsyonel Sinir Ağları (CNN)
- **Proje:** Görüntü Sınıflandırma (CIFAR-10)
- **Amaç:** Basit bir CNN ile köpek, kedi, araba gibi resimleri ayırt et.
- **Kazanım:** Görüntü işlemede filtreler, katmanlar, dropout, augmentation.

### 3. Transfer Learning
- **Proje:** Kendi Veri Setinde (ör. Çiçek Resimleri) Eğitim
- **Amaç:** Hazır bir model (ResNet, VGG vb.) al, kendi küçük veri setine uygula.
- **Kazanım:** Feature extraction, fine-tuning, model özelleştirme.

### 4. Obje Tespiti (YOLO)
- **Proje:** YOLO ile Nesne Tespiti
- **Amaç:** YOLOv8 ile gerçek zamanlı görüntüde nesne kutuları çizdir.
- **Kazanım:** Bounding box, veri etiketi, gerçek zamanlı inference.

### 5. Doğal Dil İşleme (NLP) *(Planlanan)*
- **Proje:** Film Yorumları Duygu Analizi
- **Amaç:** Basit LSTM/GRU ile metinlerden pozitif/negatif duygu tespiti.
- **Kazanım:** Tokenization, embedding, RNN temelleri.

### 6. Sıralı Veri / Zaman Serisi (RNN) *(Planlanan)*
- **Proje:** Hisse Senedi Fiyatı Tahmini (RNN/LSTM)
- **Amaç:** Bir zaman serisi verisini (ör. borsa) tahmin et.
- **Kazanım:** Sequence modeling, LSTM, GRU, veri hazırlama.

### 7. Otomatik Kodlayıcı (Autoencoder) *(Planlanan)*
- **Proje:** Gürültülü Görüntü Temizleme (Denoising Autoencoder)
- **Amaç:** Noisy (bozuk) resimlerden temiz resim üret.
- **Kazanım:** Sıkıştırma, feature learning, encoder-decoder yapısı.

### 8. Generative Adversarial Network (GAN) *(Planlanan)*
- **Proje:** Sahte Görüntü Üretimi (MNIST ile Fake Rakam)
- **Amaç:** GAN ile sıfırdan rakam görseli üret.
- **Kazanım:** Generator, discriminator, adversarial training.

### 9. Transformer ve Attention *(Planlanan)*
- **Proje:** İngilizce-Türkçe Basit Çeviri Modeli
- **Amaç:** Küçük bir metin çeviri datası ile seq2seq transformer kur.
- **Kazanım:** Attention mekanizması, encoder-decoder mantığı.

### 10. Model Deployment *(Planlanan)*
- **Proje:** Trained Model'i Web API'ye Dönüştürme
- **Amaç:** Flask veya FastAPI ile modeli API olarak sun.
- **Kazanım:** Model kaydetme, yükleme, inference, deployment.

### 11. Explainability ve Analiz *(Planlanan)*
- **Proje:** Modelinin Neden Yanıldığını Açıkla (SHAP, LIME)
- **Amaç:** Model kararlarını açıklayan araçlar kullan.
- **Kazanım:** Explainable AI (XAI).

---

## 🚀 Nasıl Kullanılır?

Her notebook'u doğrudan **Google Colab** üzerinde açabilirsiniz — kurulum gerektirmez.

1. Yukarıdaki tabloda ilgilendiğiniz konunun Colab rozetine tıklayın.
2. Google hesabınızla giriş yapın.
3. Notebook'u kopyalayın (`Dosya > Drive'a kopyala`) ve çalıştırın.

---

## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **PyTorch**
- **Google Colab**
- **OpenCV**, **Ultralytics (YOLOv8)**
- **Matplotlib**, **NumPy**

---

## 📝 Not

Bu repo kişisel öğrenme sürecimin bir parçasıdır. İçerikler öğrenme amaçlı hazırlanmış olup zamanla güncellenmeye devam edecektir.
