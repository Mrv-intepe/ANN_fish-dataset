# ANN_fish-dataset
"A Large-Scale Fish Dataset" veri seti ve yapay sinir ağı (ANN) kullanılarak balık türlerinin sınıflandırma yaptım.

Modeli daha iyi eğitebilmek için Data augmatin kısmında  zoom_range, rotation_range, height sfitting gibi teknikler kullanmaya çalıştım. Model eğitme kısmında çok yavaş ilerledi ve accuracy değeri (0.1 ve 0.2 arası) çok düşük oldu. Bu yüzden bu teknikleri kullanmadım.

Model kısmında modelin sonuçlarını iyileştirek şekilde Dense ve Dropout ekleyip çıkardım. 
Modeli eğitirken Early Stopping kullanarak overfitting'in önüne geçmek ve gereksiz yere uzun eğitim süresini engellemek için kullandım.
Test accuracy:0.9 
Değerlendirme sonucumda örnek görüntü vererek modelime tahmin yaptırdım

https://www.kaggle.com/code/merveintepe/ann-fish-dataset 
