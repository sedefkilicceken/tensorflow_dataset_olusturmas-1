# TENSORFLOW KULLANARAK  DATASET OLUŞTURMA

Tensorflow teknolojisi kullanarak kendi datasetimizi oluşturma
Öncelikle gerekli olan platformların kurulumunun yapılması 
## KURULUMLAR

### Anaconda
- https://www.anaconda.com/download/
- İsterseniz yukarıdaki linkten son Anaconda'nın son sürümünü kurmak yerine aşağıdaki linkle 5.1 sürümünü kurabilirsiniz. Anaconda 5.1 daha stabil çalışıyor. 5.1 ile pek hata almazsınız.
- 64-bit Anaconda indirip kurun. Ayrıca Python kurulumu yapmanıza gerek yok. Python Anaconda'yla birlikte gelecek.
- Son güncellemeyle beraber Anaconda Python 3.7 ile beraber gelecektir. Kurstaki kütüphanelerin sorunsuz çalışması için aşağıdaki komutu komut penceresinde çalıştırarak Python 3.6'ya geçin.
 
    conda install python=3.6
 ### TENSORFLOW
 
 - Tensorflow kurarken iki seçeneğiniz var. CPU veya GPU. Eğer uygun ekran kartınız varsa kesinlikle GPU için kurulum yapın, CPU'ya göre daha hızlı eğitim gerçekleşecek. Nvidia'dan farklı bir ekran kartınız varsa CPU için kurulum yapmanız gerekiyor. Sadece Nvidia ekran kartları destekleniyor. Ekran kartınızda CUDA compute capability 3.5'den büyükse Tensorflow'u GPU için kurabilirsiniz. Aşağıdaki linkten ekran kartınız uygun mu kontrol edebilirsiniz.
    
 #### 1. Tensorflow CPU
 
 #### pip install --upgrade tensorflow
 
 ### Diğer Kütüphaneler
 
- Ne zaman eksik bir kütüphane varsa Tensorflow kurarken yaptığımız gibi pip install ile kurabilirsiniz. Kursta kullanacağımız aşağıdaki iki kütüphanenin kurulu olduğuna emin olun.
 
    pip install opencv-python
    
    pip install imageio
    
 ### Tensorflow Object Detection Kurulumu 

- TensorFlow Object Detection API'ı indirin. https://github.com/tensorflow/models

- Masaüstünde tensorflow1 isminde klasör oluşturup indirdiğiniz models klasörünü bu klasörün içine atın. models-master ismini basitleştirmek için models yapabilirsiniz.Benim bilgisayarımda dosya yolu  "home\sedefkilicceken\Desktop\tensorflow1\models\research\object_detection" ve object_detection klasörü içerisinde işlem yapılacaktır.

 - Eğitim yapabilmek için bilgisayarınızın özelliklerine en uygun olan modeli
 https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md den indilebilirsiniz.Bize uygun olan model olarak  Faster-RCNN-Inception-V2-COCO'yu indirin. tar.gz dosyasını object detection klasörüne çıkartın.  
 
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
