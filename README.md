# Dini_metin_yorum_benzerligi

Bu proje, Python ve Jupyter Notebook kullanılarak hazırlanmış bir veri analizi / makine öğrenmesi çalışmasıdır. Proje, veri seti üzerinde analiz yaparak kuran ve incil metinlerini işlemeyi ve ayetler ve sözler arasında benzerlik hesaplaması yapmayı amaçlamaktadır.

# Kullanılan Teknolojiler ve Kütüphaneler
Bu projede çeşitli doğal dil işleme (NLP), veri analizi ve görselleştirme kütüphaneleri kullanılmıştır:
Python 3.x: Projenin geliştirildiği programlama dili.
Jupyter Notebook: Kodun hücresel biçimde yazılıp çalıştırılabildiği, interaktif bir geliştirme ortamı.
NumPy (numpy): Sayısal işlemler ve çok boyutlu diziler üzerinde işlem yapma.
Pandas (pandas): Veri manipülasyonu ve analiz için güçlü veri yapıları.
Matplotlib (matplotlib.pyplot): Veri görselleştirme için grafik ve çizim araçları.
scikit-learn:
TfidfVectorizer: Metin verisini sayısal vektörlere dönüştürmek için.
cosine_similarity: Metinler arasında benzerlik ölçümü için.
Gensim (gensim.models.Word2Vec): Kelime gömme (word embedding) modeli ile sözcükleri vektörel temsillere dönüştürmek için.
Stanza: Stanford NLP tarafından sağlanan güçlü bir doğal dil işleme kütüphanesi.
re (Regular Expressions): Metin temizleme ve desen eşleme işlemleri için.
os: Dosya ve klasör işlemleri için Python’un yerleşik modülü.
collections.Counter: Kelime sıklığı gibi sayımlama işlemleri için.
TurkishStemmer (TurkishStemmer): Türkçe metinlerde kök bulma (stemleme) işlemi yapmak için özel bir kütüphane.

# Projeyi Çalıştırma Adımları
Bu repoyu bilgisayarınıza klonlayın:
git clone https://github.com/veysellklc/Dini_metin_yorum_benzerligi/tree/main
cd proje-adi

Gerekli kütüphaneleri yüklemek için bir sanal ortam oluşturun ve bağımlılıkları yükleyin:
python -m venv venv
source venv\Scripts\activate  
numpy
pandas
matplotlib
scikit-learn
gensim
stanza
TurkishStemmer


Jupyter Notebook'u başlatın:
jupyter notebook

Kod-dosyası.ipynb dosyasını açın ve hücreleri sırayla çalıştırın.
