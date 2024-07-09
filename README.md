Bu proje, Türkçe metinlerde küfür, argo veya şiddet içeren cümleleri tespit etmek amacıyla geliştirilmiş bir metin sınıflandırma modelini içermektedir. Proje, NLTK ve Scikit-learn kütüphanelerini kullanarak metin ön işleme, özellik çıkarımı ve model eğitimi gibi adımları gerçekleştirmektedir.
Gereksinimler

###Bu projeyi çalıştırmak için aşağıdaki yazılımlar ve kütüphaneler gereklidir:

Python 3.x
NLTK
NumPy
Pandas
Scikit-learn

###Proje Yapısı
Proje aşağıdaki dosya ve klasörlerden oluşmaktadır:

main.py: Projenin ana Python kodu.
data/test.csv: Kaggle'dan indirilen veri seti. (Veri seti yolu kullanıcıya göre değişebilir)

###Model Eğitimi ve Testi
Veri Yükleme: Kaggle veri seti Pandas DataFrame olarak yüklenir.
Metin Ön İşleme: Metinler temizlenir, küçük harfe dönüştürülür ve durak kelimeler kaldırılır.
Özellik Çıkarımı: TF-IDF yöntemi ile metinlerden özellikler çıkarılır.
Model Eğitimi: Veriler eğitim ve test setlerine ayrılır, ardından Random Forest modeli eğitilir.
Tahmin: Kullanıcıdan alınan metinler işlenir ve model tarafından sınıflandırılır.
