# YOLO ile Özel Nesne Tespiti — Saat Dedektörü

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv5-FF6B35?style=for-the-badge&logo=ultralytics&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</p>

---

## Genel Bakış

YOLO (You Only Look Once) algoritmasıyla **4 farklı saat türünü** gerçek zamanlı olarak tespit eden özel nesne tespiti projesi. Görüntüler özel olarak toplanmış ve etiketlenmiş; model Google Colab üzerinde eğitilmiştir.

---

## Teknoloji Yığını

```
Model      → YOLOv5 (özel eğitilmiş)
Platform   → Google Colab · Darknet
Görüntü    → OpenCV
Etiketleme → LabelImg
```

---

## Proje Detayları

| Özellik | Detay |
|---------|-------|
| Tespit Edilen Sınıf | 4 farklı saat türü |
| Eğitim Platformu | Google Colab |
| Model | YOLOv5 (özel ağırlıklar) |
| Veri | Özel toplanmış ve etiketlenmiş görüntüler |

---

## Yapı

```
my_model/            # Eğitilmiş model ağırlıkları
watch_images/        # Eğitim ve test görüntüleri
data.zip             # Ham veri seti
```

---

## Sonuçlar

![Tespit Örneği](https://github.com/user-attachments/assets/0b9e6063-0433-4402-8db8-0af9262610ea)

---

## Özellikler

- 4 farklı saat sınıfı için özel eğitilmiş model
- Yüksek doğruluk oranlı gerçek zamanlı tespit
- Özel veri seti toplama ve etiketleme süreci
- Transfer learning ile hızlı model eğitimi
