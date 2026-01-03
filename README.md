# Automatic-ticket-classification-RNN-LSTM-Bert-Roberta
📌 Proje Tanımı

Bu proje, müşteri destek taleplerinin (ticket) doğal dil işleme (NLP) teknikleri kullanılarak otomatik olarak sınıflandırılmasını amaçlamaktadır.
Amaç; gelen destek taleplerini içeriklerine göre ilgili kategoriye ayırarak müşteri destek süreçlerini hızlandırmak ve manuel iş yükünü azaltmaktır.

🧠 Kullanılan Yöntemler

Proje kapsamında aşağıdaki adımlar uygulanmıştır:

Metin temizleme (lowercase, noktalama temizleme vb.)

Stopword kaldırma

Metin vektörleştirme

CountVectorizer

TF-IDF

Makine öğrenmesi modelleri:

Logistic Regression

Naive Bayes

Decision Tree

Random Forest

📊 Veri Seti

Müşteri destek taleplerinden oluşan metin tabanlı bir veri seti

Her kayıt:

Ticket metni

Ticket kategorisi (etiket)

⚙️ Modelleme ve Değerlendirme

Eğitim / test bölünmesi

Model karşılaştırmaları

Performans metrikleri:

Accuracy

Precision

Recall

F1-score

Confusion Matrix analizi

📈 Çıktılar

En iyi performans gösteren modelin belirlenmesi

Ticket kategorilerinin otomatik tahmini

Model sonuçlarının görselleştirilmesi

🛠️ Kullanılan Teknolojiler

Python

Pandas

NumPy

Scikit-learn

NLTK / SpaCy (varsa)

Jupyter Notebook

🚀 Gelecek Çalışmalar

BERT / Transformer tabanlı modellerin denenmesi

Çok sınıflı dengesiz veri için gelişmiş yöntemler

Gerçek zamanlı ticket sınıflandırma sistemi

📁 Dosya
Automatic_Ticket_Classification.ipynb

📄 README — filtered_automaticticketclassification.ipynb
📌 Proje Tanımı

Bu notebook, Automatic Ticket Classification projesinin ön işlenmiş ve filtrelenmiş veri seti ile yeniden ele alındığı bir versiyonudur.
Amaç; daha temiz ve dengeli bir veri seti ile model performansını artırmaktır.

🔍 Yapılan Filtreleme İşlemleri

Az sayıda örneğe sahip sınıfların çıkarılması

Gürültülü ve anlamsız kayıtların temizlenmesi

Veri setinin sınıf bazında dengelenmesi

🧠 NLP ve Makine Öğrenmesi Süreci

Geliştirilmiş metin ön işleme

TF-IDF ağırlıklı vektörleştirme

Model eğitimi ve test süreçleri

Önceki notebook ile performans karşılaştırması

📊 Değerlendirme

Daha dengeli sınıflar ile:

Daha stabil accuracy

Daha yüksek macro-F1 skorları

Sınıf bazlı performans analizi

📈 Sonuçlar

Filtrelenmiş veri ile daha güvenilir sonuçlar

Overfitting riskinin azaltılması

Gerçek dünyaya daha uygun modelleme

🛠️ Kullanılan Teknolojiler

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

📁 Dosya
filtered_automaticticketclassification.ipynb

📌 Not

Bu iki notebook birlikte değerlendirildiğinde:

İlki: Ham veri ile temel modelleme

İkincisi: Filtrelenmiş veri ile optimize edilmiş modelleme
yaklaşımını göstermektedir.
