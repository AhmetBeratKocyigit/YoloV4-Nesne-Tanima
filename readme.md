# Nesne Tanıma ve YOLOv4 Kullanarak Nesne Algılama

Bu Python projesi, OpenCV ve YOLOv4 kullanılarak nesne tanıma için bir örnek sunmaktadır.

## Kurulum

1. Bu projeyi klonlayın:

    ```
    git clone https://github.com/AhmetBeratKocyigit/YoloV4-Nesne-Tanima.git
    ```

2. Gerekli Python kütüphanelerini yükleyin:

    ```
    pip install opencv-python
    ```

## Kullanım

1. `dnn_model` klasöründe bulunan `yolov4-tiny.weights`, `yolov4-tiny.cfg` ve `classes.txt` dosyalarını sağladığınızdan emin olun.

2. Kodu çalıştırın:

    ```
    python object_detection.py
    ```

3. Kameranızdan nesneleri tanıyın ve algılanan nesneleri ekranda görün.

## Kullanılan Kütüphaneler ve Teknolojiler

Bu proje, nesne tanıma işlemi için Python programlama dilinde geliştirilmiştir ve aşağıdaki kütüphaneleri kullanmaktadır:

### OpenCV (Open Source Computer Vision Library)

OpenCV, bilgisayarla görme ve görüntü işleme uygulamaları geliştirmek için kullanılan açık kaynaklı bir kütüphanedir. Bu projede, nesne algılama ve görsel işleme için OpenCV'nin DNN (Deep Neural Networks) modülü kullanılmıştır.

Daha fazla bilgi için: [OpenCV Ana Sayfa](https://opencv.org/)

### YOLO (You Only Look Once)

YOLO, gerçek zamanlı nesne tanıma algoritmasıdır. YOLOv4, en son versiyonu olup yüksek doğruluk ve hız sunar. Bu projede, YOLOv4 modeli kullanılarak nesne tanıma işlemi gerçekleştirilmektedir.

Daha fazla bilgi için: [YOLO Ana Sayfa](https://pjreddie.com/darknet/yolo/)

### Python

Python, basit ve okunabilir sözdizimiyle popüler bir programlama dilidir. Nesne tanıma işlemi ve proje yönetimi için Python kullanılmıştır.

Daha fazla bilgi için: [Python Ana Sayfa](https://www.python.org/)

## Kaynaklar

- [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- [OpenCV: DNN Module](https://docs.opencv.org/4.x/d6/d0f/group__dnn.html)

