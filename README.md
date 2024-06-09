# Urkutucu-Yazar-Tespiti

Bu proje, üç farklı yazarın (Edgar Allan Poe, H.P. Lovecraft, Mary Shelley) metinlerini sınıflandırmayı amaçlamaktadır. Farklı makine öğrenimi modelleri kullanarak yazar tahmini yapılmıştır.

## İçerik

- [Proje Açıklaması](#proje-açıklaması)
- [Veri](#veri)
- [Özellik Mühendisliği](#özellik-mühendisliği)
- [Kullanılan Modeller](#kullanılan-modeller)
- [Sonuçlar](#sonuçlar)
- [Kurulum ve Çalıştırma](#kurulum-ve-çalıştırma)
- [Yazar](#yazar)

## Proje Açıklaması

Bu projede, belirli metinlerin yazarlarını tahmin etmek için çeşitli makine öğrenimi algoritmaları kullanılmıştır. Proje, metin verilerini işleyerek ve özellikler çıkararak, bu özellikler üzerinden modelleri eğitmek ve performanslarını değerlendirmek üzerine odaklanmıştır.

## Veri

Kullanılan veri seti, üç yazarın eserlerinden alınmış metinlerden oluşmaktadır. Her metin için aşağıdaki özellikler çıkarılmıştır:

- Kelime sayısı
- Benzersiz kelime sayısı
- Karakter sayısı
- Durak kelime (stopwords) sayısı
- Noktalama işareti sayısı
- Büyük harfle yazılmış kelime sayısı
- Baş harfi büyük kelime sayısı
- Kelimelerin ortalama uzunluğu

## Özellik Mühendisliği

Veri setindeki metinler üzerinde çeşitli özellik mühendisliği teknikleri uygulanmıştır:

- Lemmatizasyon
- Kelime ve karakter sayımı
- TF-IDF Vektörizasyonu
- Yukarıda belirtilen diğer metrikler

## Kullanılan Modeller

Aşağıdaki makine öğrenimi algoritmaları kullanılarak modeller eğitilmiştir:

1. Rastgele Orman (Random Forest)
2. XGBoost
3. Karar Ağacı (Decision Tree)
4. Naive Bayes
5. Lojistik Regresyon (Logistic Regression)

### Model Eğitim ve Değerlendirme

Her bir model, 5 katlı çapraz doğrulama (cross-validation) kullanılarak eğitilmiş ve değerlendirilmiştir. Modellerin performansı log-loss metriği ile ölçülmüştür.

## Sonuçlar

Modellerin performansları aşağıdaki gibi özetlenmiştir:

- **Rastgele Orman**: Performans sonucu
- **XGBoost**: Performans sonucu
- **Karar Ağacı**: Performans sonucu
- **Naive Bayes**: Performans sonucu
- **Lojistik Regresyon**: Performans sonucu

Detaylı sonuçlar ve karşılaştırmalar için lütfen kod dosyasına bakınız.

## Kurulum ve Çalıştırma

Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1. Gerekli kütüphaneleri yükleyin:

2. Proje dosyalarını klonlayın veya indirin:
    ```bash
    git clone https://github.com/berkaykalin/Urkutucu-Yazar-Tespiti.git
    cd Urkutucu-Yazar-Tespiti
    ```

3. Jupyter Notebook'u açarak projeyi inceleyin ve çalıştırın:
    ```bash
    jupyter notebook Spooky_Final.ipynb
    ```

## Yazar

- [Berkay Kalın](https://github.com/berkaykalin)

Herhangi bir soru veya geri bildirim için benimle iletişime geçmekten çekinmeyin.

