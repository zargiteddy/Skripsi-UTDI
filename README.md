# My Bachelor's Thesis

Fenomena pernikahan di usia muda banyak terjadi di Indonesia. Pada tahun 2021, Komnas Perempuan mencatat ada 59.709 kasus pernikahan dini yang mendapat dispensasi. Hal itu membuktikan bahwa masih banyak masyarakat Indonesia yang tidak mengetahui atau tidak mengikuti aturan UU No. 1 tahun 1974 yang mengatur tentang umur minimal menikah yaitu 19 tahun. Topik ini pun selalu menjadi perbincangan hangat di Twitter. Ada netizen yang beropini baik, ada yang beropini jelek, dan ada pula yang netral. Hal tersebut dapat dianalisis menggunakan analisis sentimen.

Analisis sentimen dapat digunakan untuk menganalisis pendapat netizen dan mengelompokkannya menjadi tiga kategori yaitu positif, netral, dan negatif. Penelitian ini menggunakan metode Support Vector Machine (SVM) untuk melakukan klasifikasi yang dilakukan dengan garis pembatas (hyperplane) yang memisahkan kelas-kelas yang ada pada kumpulan data netizen Twitter yang memiliki opini tentang nikah muda.

Jumlah data yang digunakan sebanyak 4000 data yang diambil selama bulan Maret dan April 2023. Data dibagi dengan rasio 80:20 dimana 3200 data digunakan untuk data latih dan 800 data digunakan sebagai data uji. Penelitian ini menghasilkan akurasi Linear Support Vector Machine sebesar 87,375% dengan nilai presisi 82% untuk sentimen negatif, 40% untuk sentimen netral, dan 91% untuk sentimen positif. Selain itu juga dihasilkan nilai recall 64% untuk sentimen negatif, 44% untuk sentimen netral, dan 95% untuk sentimen positif. Terakhir, f1-score untuk sentimen negatif adalah 72%, lalu 42% untuk sentimen netral, kemudian 93% untuk sentimen positif.

Penelitian ini juga menghasilkan sebuah aplikasi web yang memiliki model machine learning Linear SVM di dalam backend yang dapat mengklasifikasikan teks yang dimasukkan oleh pengguna ke dalam kelas positif, netral, atau negatif.

# Tampilan sekilas web app

## Halaman beranda:
![image](https://github.com/zargiteddy/Skripsi-UTDI/assets/72479466/e61aadbd-5864-47fe-8e8d-c7778555c0e7)

## Input teks dengan hasil klasifikasi negatif:
![image](https://github.com/zargiteddy/Skripsi-UTDI/assets/72479466/49de1d0a-8720-41e7-962f-4e205a740f16)

## Input teks dengan hasil klasifikasi netral:
![image](https://github.com/zargiteddy/Skripsi-UTDI/assets/72479466/cf011842-243c-4402-a2c1-0949d228a535)

## Input teks dengan hasil klasifikasi positif:
![image](https://github.com/zargiteddy/Skripsi-UTDI/assets/72479466/788a21c4-12e8-4593-85a1-a77a401f6ca4)





