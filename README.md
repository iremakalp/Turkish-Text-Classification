# Turkish-Text-Classification
Bu projede getir play store yorumlarından duygu analizi yapılmıştır.

## Dataset
[Veri kümesinde](https://github.com/iremakalp/Turkish-Text-Classification/tree/main/Dataset)
getir uygulaması için playstoredan toplanan 74.500 etiketlenmiş veri bulunmaktadır. Bu verilerin 54.000'i olumlu (1) 20.000'i ise olumsuz(0) olarak etiketlenmiştir.
Veri toplama ön işlem aşamaları için  [bu dosyaya](https://github.com/iremakalp/Turkish-Text-Classification/blob/main/Veri%20Toplama-On%20Isleme-Etiketleme/veriToplamaOnIsleme.ipynb) bakabilirsiniz.
Veri etiketleme için [Bert](https://huggingface.co/savasy/bert-base-turkish-sentiment-cased) kullanımıştır. 
Veri etiketleme aşamaları için [bu belgeye](https://github.com/iremakalp/Turkish-Text-Classification/blob/main/Veri%20Toplama-On%20Isleme-Etiketleme/veriEtiketleme.ipynb) bakabilirsiniz.

## Makine Öğrenmesi Algoritmaları
 Projede duygu analizi için SVM,Naive Bayes,MLP ve RNN makine öğrenmesi algoritmaları kullanılmıştır.
