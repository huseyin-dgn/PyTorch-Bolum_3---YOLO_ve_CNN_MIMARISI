# PyTorch Bölüm 3 - YOLO ve CNN Mimarisi

**PyTorch Part 3 - YOLO Mimarisi ve CNN Uygulamaları**

Bu proje, **derin öğrenme ve bilgisayarla görü** konularını öğrenmek isteyenler için hazırlanmıştır.  
YOLO (You Only Look Once) ve CNN (Konvolüsyonel Sinir Ağları) mimarileri üzerinden **nesne tespiti ve görüntü sınıflandırma** uygulamaları yapılmıştır.

## 📌 Proje Hedefleri

- YOLO mimarisini detaylı olarak incelemek  
- CNN ile görüntü sınıflandırma yapmak  
- YOLO ve CNN’i birlikte kullanarak nesne tespiti örnekleri geliştirmek  
- PyTorch kullanarak model eğitimi, doğrulama ve tahmin süreçlerini göstermek
  
## ⚠️ Veri Seti Hakkında

- Veri seti **repo içerisinde bulunmamaktadır**.  
- Veri setini **uyari.txt** dosyasından bulabilirsiniz.  
- Dosya boyutu büyük olduğu için repoya eklenmemiştir.  
- Ancak, **dosya yolları ve klasör yapısı korunmuştur**, yani mevcut kod çalıştırılabilir.

## 📁 `runs/` Klasörünün Kullanımı

`runs/` klasörü, YOLO ile yapılan **model eğitimi ve tahmin çıktılarının** saklandığı klasördür.  
Repo içerisinde bu klasör **bulunmamaktadır**, kullanıcı tarafından oluşturulmalıdır.

### 1. `runs/` Klasörünü Oluşturma
Terminal veya dosya gezgini ile proje dizininde şu yolu oluşturabilirsiniz:

* mkdir -p "YOLO - CNN/YOLO/Uygulamalar/1_Yol_Tumsek/runs"

### 2. Tahmin Sonuçlarının Kaydedilmesi

YOLO modellerini çalıştırdığınızda, detect veya train komutları çıktıları otomatik olarak runs/ altına kaydeder.

### 3. Notlar

Mevcut dosya ve klasör yolları korunmuştur, bu nedenle notebook’lar çalıştırıldığında runs/ klasörü otomatik olarak dolacaktır.
Eğer runs/ klasörü yoksa, YOLO çıktıları kaydedilemez ve notebook hata verir.




### 5️⃣ Proje Yapısı

```markdown
## 📂 Proje Yapısı

PyTorch-Bolum_3---YOLO_ve_CNN_MIMARISI/
│
├── YOLO - CNN/
│   │
│   ├── PyTorch_CNN_Uygulamalar/
│   │   └── Uygulamalar/
│   │       ├── Uygulama_1/
│   │       │   └── cat_dog.ipynb
│   │       └── Uygulama_2/
│   │           └── weather.ipynb
│   │
│   └── YOLO/
│       ├── YOLO_Nedir/
│       │   └── Yolo1.ipynb
│       │
│       ├── Kendi_YOLO_Modelimizi_Egitelim/
│       │   └── yolo_train.ipynb
│       │
│       ├── RoboFlow/
│       │   └── roboflow.ipynb
│       │
│       ├── Uygulamalar/
│       │   └── 1_Yol_Tumsek/
│       │       └── (model çıktıları veya veri)
│       │
│       ├── YOLO_Mimarisinin_Isleyisi/
│       │   └── yolov8_mimarisi.ipynb
│       │
│       ├── YOLO_Modeli_CNN_e_Verelim/
│       │   └── cnn.ipynb
│       │
│       └── Yolo_v8_Kullanimi/
│           └── yolov8_demo.ipynb


### Klasör Açıklamaları

- `PyTorch_CNN_Uygulamalar/` → CNN temel uygulamalar ve örnek veri setleri  
- `YOLO/` → YOLO mimarisi, kendi model eğitimi, RoboFlow entegrasyonu ve uygulama klasörleri  
- `Uygulamalar/1_Yol_Tumsek/` → özel yol/tümsek veri ve tahmin çıktıları  
- `runs/` → model çıktı klasörü (kullanıcı ekleyecek, repo’ya dahil değil)

## 📖 Kaynaklar

- [YOLOv8 Official Documentation](https://docs.ultralytics.com/)  
- [PyTorch Tutorials](https://pytorch.org/tutorials/)  
- [Roboflow](https://roboflow.com/)

