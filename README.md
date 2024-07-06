1. Latar belakang
Diabetes merupakan salah satu penyakit yang berbahaya juga penyakit yang 
kompleks dan rumit. Tingkat diagnosa diabetes memberikan kontribusi yang signifikan 
terhadap komorbiditas, atau penyakit lain yang dapat menyertai penyakit utama, dan 
tingkat komplikasi diabetes [1]. Pada diabetes mellitus, komorbiditas tersebut dapat berupa 
serangan jantung, stroke, gagal ginjal bahkan kebutaan. Pemicu diabetes mellitus ini terdiri 
dari 2 faktor, yaitu faktor internal seseorang dan faktor external. Faktor internal meliputi 
keturunan atau genetika, di mana tubuh tidak menghasilkan insulin atau mengalami 
kelainan atau kerusakan pankreas sejak kecil. Sedangkan faktor external adalah pola hidup 
yang tidak sehat seperti terlalu banyak mengkonsumsi gula, obesitas, dan jarang 
berolahraga. Di Indonesia sendiri, jumlah penderita diabetes mellitus naik setiap tahunnya 
[2]. 
Oleh karena itu deteksi dan diagnosis diabetes pada tahap awal dibutuhkan. 
Diagnosis medis merupakan sebuah proses klasifikasi. Seorang dokter harus menganalisis 
banyak faktor terlebih dahulu sebelum dapat memulai diagnosis diabetes, yang mana 
membuat pekerjaan dokter sulit [3]. Berdasarkan data histori penderita penyakit diabetes, 
penyakit diabetes ini dapat diklasifikasikan. Tujuan dari klasifikasi data adalah untuk 
mengelompokkan suatu objek menjadi sejumlah kategori atau kelas. Sehingga dapat dibuat 
suatu sistem yang dapat melakukan klasifikasi atau prediksi dalam mendiagnosa penyakit 
diabetes pada seseorang. Untuk melakukan klasifikasi data, dapat digunakan metode 
pembelajaran mesin atau machine learning. Dengan adanya pembelajaran mesin tersebut, 
dapat dilakukan deteksi penyakit dengan pengukuran klinis yang lebih cepat. Sehingga, 
diharapkan dapat membantu masyarakat terutama tenaga medis dalam melakukan 
diagnosis. 
Pada saat ini sudah terdapat beberapa penelitian mengenai prediksi diabetes, dataset 
yang digunakan pun beragam. Seperti data hasil observasi peneliti terhadap penduduk di 
Indonesia, mulai dari random sampling Rumah Tangga (RT) oleh Wahyuni [4], dan data 
salah satu Rumah Sakit oleh Anggraeni [5]. Ada pula yang menggunakan dataset 
internasional “Pima Indian Diabetes Database” dari The John Hopkins University. Dalam 
mengolah dataset internasional tersebut, sudah banyak metode machine learning yang 
digunakan. Pada salah satu penelitian sebelumnya, metode machine learning yang 
digunakan adalah KNN, Naive Bayes, dan Random Forest [2]. Pada penelitian yang lain, 
digunakan metode Artificial Neural Network (ANN) atau jaringan saraf tiruan [6], dan ada 
pula metode Support Vector Machine (SVM) [3][7].
Penelitian ini bertujuan untuk menguji performa dari metode Logistic regression, 
KNN, Random Forest dan Naive Bayes.
 
2. Datasheet 
Kami menggunakan dataset diabetes dari Mehmet Akturk yang diupdate 3 tahun 
lalu tepatnya di 2021. (https://www.kaggle.com/datasets/mathchi/diabetes-data-set) 
Kumpulan data ini berasal dari Institut Nasional Diabetes dan Penyakit Pencernaan dan 
Ginjal. Tujuannya adalah untuk memprediksi berdasarkan pengukuran diagnostik apakah 
seorang pasien menderita diabetes.
Datasheet tersebut memiliki 9 feature yang ada di dalam dataset diantara sebagai berikut:
● Pregnancies: Number of times pregnant
● Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
● BloodPressure: Diastolic blood pressure (mm Hg)
● SkinThickness: Triceps skin fold thickness (mm)
● Insulin: 2-Hour serum insulin (mu U/ml)
● BMI: Body mass index (weight in kg/(height in m)^2)
● DiabetesPedigreeFunction: Diabetes pedigree function
● Age: Age (years)
● Outcome: Class variable (0 or 1)
