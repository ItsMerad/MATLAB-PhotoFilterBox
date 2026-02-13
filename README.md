# 📸 PhotoFilterer: MATLAB Image Processing Studio

![MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-orange.svg?style=for-the-badge&logo=mathworks)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

**PhotoFilterer**, MATLAB App Designer kullanılarak geliştirilmiş, görüntü işleme algoritmalarını görselleştiren ve uygulayan kapsamlı bir masaüstü uygulamasıdır. Akademik ve pratik görüntü işleme çalışmalarında kullanılan temel tekniklerin çoğunu tek bir arayüzde sunar.

## 🖼️ Uygulama Arayüzü

<p align="center">
  <img src="Ekran Resmi 2026-02-13 14.13.39.png" alt="PhotoFilterer GUI" width="700">
</p>

## 🚀 Teknik Özellikler

Uygulama, görsel üzerinde aşağıdaki işlemleri eşzamanlı veya ardışık olarak gerçekleştirebilir:

### ⚡ Intensity Transformation Functions
* **Negative:** Görüntü renklerini tersine çevirme.
* **Log / Reverse Log:** Düşük veya yüksek yoğunluklu değerleri genişletme.
* **n'th Power/Root:** Gamma düzeltmesi için özel kuvvet ve kök fonksiyonları.

### 🔊 Noise Generation
* **Gaussian Noise:** İstatistiki normal dağılımlı gürültü ekleme.
* **Impulse / Salt & Pepper:** Görüntüye rastgele beyaz ve siyah pikseller ekleme.

### 🔍 Spatial Filters
* **Smoothing:** Average (Ortalama), Weighted (Ağırlıklı), Median, Max, Min filtreleri.
* **Sharpening:** Derivative (Türevsel) ve High-Boost filtreleme teknikleri.

### 🧬 Morphology & Segmentation
* **Morphology:** Erosion (Aşındırma) ve Dilation (Genleşme) işlemleri.
* **OTSU Segmentation:** Otomatik eşikleme (thresholding) yöntemiyle nesne ve arka plan ayırma.

### 📐 Edge & Corner Detection
* **Kenar Belirleme:** Prewitt, Sobel, Roberts ve Canny operatörleri.
* **Köşe Belirleme:** Harris Corner Detection algoritması desteği.

## 🛠️ Kurulum ve Çalıştırma

1. **Gereksinimler:** Bilgisayarınızda **MATLAB** ve **Image Processing Toolbox** yüklü olmalıdır.
2. **Projeyi İndirin:**
   ```bash
   git clone [https://github.com/ItsMerad/PhotoFilterer.git](https://github.com/ItsMerad/PhotoFilterer.git)
