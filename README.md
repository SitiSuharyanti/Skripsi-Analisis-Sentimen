# Perbandingan Algoritma Naïve Bayes dan Support Vector Machine (SVM) Pada Analisis Sentimen Pengguna Media Sosial Twitter Terhadap PT Esteh Indonesia Makmur

### Latar Belakang
Pada 25 September 2022 media social twitter diramaikan dengan kasus pengguna twitter dengan username @gandhoyy yang mendapatkan surat somasi dari PT Esteh Indonesia Makmur. PT Esteh Indonesia Makmur merupakan perusahaan food & beverages yang didirikan oleh Haidhar Hibatullah Wurjanto pada tahun 2018. Perusahaan ini menjual minuman berbahan dasar teh yang dikombinasikan dengan susu, coklat, taro, red velvet, dan varian lainnya [4].
Gandhoyy diberi somasi oleh PT Esteh Indonesia Makmur karena tweetnya yang mengkritik salah satu minuman dari perusahaan tersebut. Dalam tweetnya, Gandhoyy mengkritik bahwa minuman chizu red velvet memiliki rasa yang terlalu manis, tidak lupa ia menambahkan kata-kata kasar pada tweetnya. Tweet tersebut mengundang banyak reaksi dari warganet, baik masyarakat biasa, public figure, 2 tenaga kesehatan, maupun kompetitor. Namun karena banyaknya reaksi dari warganet, sulit untuk mendeteksi kecenderungan sentimen dari kasus tersebut. Oleh karena itu, dibutuhkan analisis sentimen untuk mengetahui sentimen dari pengguna twitter.

### Tujuan
Penelitian ini bertujuan untuk mengetahui algoritma yang memiliki performa paling baik diantara Naïve Bayes dan Support Vector Machine dalam melakukan analisis sentimen pengguna twitter terhadap PT Esteh Indonesia Makmur.

### Metode
Algoritma yang digunakan pada penelitian ini adalah Naïve Bayes dan Support Vector Machine.

### Data
Data yang digunakan dalam penelitian ini diperoleh dari X (Twitter) menggunakan metode scraping dengan library snscrape. Data terdiri dari tweet yang mengandung kata kunci “es teh Indonesia” dan “somasi” yang diambil dalam rentang waktu 24-30 September 2022. Data yang didapat diklasifikasikan menjadi 2 kelas, yaitu positif dan negatif.

### Hasil
Algoritma Support Vector Machine tanpa hyperparameter tuning memiliki performa yang lebih baik dibandingkan algoritma Naïve Bayes, dengan akurasi 90,39%, presisi 78,91%, recall 59,17%, f1- score 62,51%, AUC-ROC 0,85, dan AUC-PR 0,42.

### Library
pandas, numpy, re, string, demoji, requests, nltk, sklearn, matplotlib, seaborn, wordcloud, sastrawi, imblearn.

