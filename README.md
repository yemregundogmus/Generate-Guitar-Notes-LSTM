# Generate-Guitar-Notes-LSTM


Yunus Emre Gündoğmuş - Mayıs 2019

# Özet 
Projedeki amacımız, çok sevdiğimiz Nirvana'nın parçalarındaki gitar notalarını alarak, bunları LSTM Ağları ile eğitip next character prediction yaparak yeni bir Nirvana Şarkısı Oluşturmak.

# Nasıl Çalıştırabilirim?
Öncelikle Şu Kütüphaneleri Yüklemeniz Gerekiyor.
```
pip install keras
pip install tensorflow
pip install selenium
pip install pynput
pip install keyboard
```

Ardından **LSTM - Develop Model -1.ipynb** Dosyasını Jupyter Notebook ile açıp modeli kurabilirsin. Veya Hazır Modeli Kullanmak İstiyorsan, **LSTM - Selenium Testing -2.ipynb** Dosyasını Açarak Direkt Hazır Modelden Şarkı Ürettirebilir ve Bunu Çaldırabilirsin.

# Dosya Açıklamaları
Model Dosyaları :
- stacked-weights-improvement-90-0.2360.hdf5
- stacked-weights-improvement-80-0.2467.hdf5

Verisetleri :
- nirvananota.txt

Selenium için chromedriver.exe :
- chromedriver.exe


### Proje Sahipleri:
- Yunus Emre Gündoğmuş

### Katkı sağlayanlar:
- Feyza Zeynep Salam
