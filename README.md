# Klasifikasi Teks Berindikasi Toxic Mental Health Menggunakan Algoritma Gradient Boosting Tree

## Anggota Kelompok
| Nama                      | NIM        |
|---------------------------|------------|
| Abdurrahman Ridho         | 21.11.4341 |
| Mohamad Doddy Sujatmiko   | 21.11.4344 |
| Nur Fadhlur Rahman        | 21.11.4349 |
| Muhammad Zhafar Al Fathi  | 21.11.4374 |
| Oxa Defrizal Khasay       | 21.11.4388 |
| Irfan Andriyanto          | 21.11.4398 |

## Latar Belakang
Dalam beberapa tahun terakhir, ada kesadaran yang semakin meningkat akan dampak mendalam dari masalah kesehatan mental pada individu dan masyarakat luas. Di tengah kesadaran ini, platform digital telah menjadi arena yang signifikan bagi individu untuk mengekspresikan pikiran, pengalaman, dan emosi mereka terkait kesehatan mental. Kombinasi kedua hal tersebut dapat berdampak buruk dimana orang akan mengekspresikan pikiran mereka sembari terpengaruhi oleh kesehatan mental mereka. Dengan menggunakan dataset ‘Mental Health Corpus’ kita bisa men-filter pendapat mana yang layak ditampilkan ke khalayak umum dan mana yang tidak pantas.

## Analisa Data
- Dataset diambil dari web [Kaggle](https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus)
- Data Mental health Corpus memiliki 2 kolom text dan label yang berisi informasi apakah teks tersebut mencerminkan kesehatan mental yang positif atau negatif.
- Terdapat null value pada data setelah dilakukan lemmatisasi
- Fitur yang dipakai adalah kolom text

## Pre-Processing
1. Text Extraction
1. Tokenization
1. Delete Stopwords
1. Part of Speech Tagging
1. Lemmatization
1. Hashing TF-IDF

## Metode
Metode yang digunakan adalah Gradien Boosting karena cocok digunakan terhadap data yang kompleks dan memilki pola bernuansa. Dalam konteks Korpus Kesehatan Mental, di mana sentimen dan label toksisitas dapat dipengaruhi oleh nuansa kecil dan kerumitan kontekstual, model Gradient Boosting dapat memberikan akurasi prediksi yang unggul.

## Diskusi
- Kelebihan
  * Memperbaiki kata-kata yang salah seperti “Iam”, youd” dan lain-lain.
  * Menggunakan lemmatisasi
  * Menggunakan hyperparameter seperti, maxIter, maxDepth, maxBins, stepSize dan subsamplingRate
- Kekurangan
  - Proses yang dilakukan terlalu lama
  - Akurasi saat input manual kurang sesuai dengan yang diharapkan
