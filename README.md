Prediksi Churn Pelanggan Perusahaan Telekomunikasi Menggunakan Machine Learning

Nama : Muhammad Syafan Midhad

NIM : A11.2023.14923

Ringkasan dan Permasalahan

Perusahaan telekomunikasi sering mengalami masalah churn pelanggan (pelanggan berhenti berlangganan layanan).
Untuk meningkatkan retensi pelanggan, penting untuk mengidentifikasi pelanggan yang berpotensi churn.
Project ini menggunakan algoritma Machine Learning untuk memprediksi kemungkinan pelanggan akan churn berdasarkan data pelanggan.

Tujuan Project
- Memprediksi apakah pelanggan akan churn atau tidak.
- Menghasilkan model prediksi churn yang akurat untuk membantu perusahaan mengambil keputusan.

Alur Penyelesaian Project

```plaintext
+-----------------------------+
|      Data Pelanggan         |
|   (Dataset Churn Pelanggan) |
+-----------------------------+
              |
              v
+-----------------------------+
|   Exploratory Data Analysis |
|            (EDA)            |
+-----------------------------+
              |
              v
+-----------------------------+
|     Preprocessing Data      |
| - Cleaning                  |
| - Feature Engineering       |
+-----------------------------+
              |
              v
+-----------------------------+
|     Modeling Machine        |
|        Learning             |
| - Training                  |
| - Evaluation                |
+-----------------------------+
              |
              v
+-----------------------------+
|       Evaluasi Model        |
| - Akurasi                   |
| - Precision, Recall, F1     |
+-----------------------------+
              |
              v
+-----------------------------+
|  Prediksi & Insight Bisnis  |
| - Prediksi Churn Pelanggan  |
| - Insight untuk Perusahaan  |
+-----------------------------+
```
Dataset

Dataset berisi informasi pelanggan perusahaan telekomunikasi, seperti :

-Informasi demografi (jenis kelamin, usia, status pernikahan)

-Lama berlangganan

-Layanan yang digunakan (internet, telepon, streaming)

-Tagihan dan biaya bulanan

-Status churn (target prediksi)

Exploratory Data Analysis (EDA) :

-Pengecekan missing value

-Statistik deskriptif untuk melihat distribusi data

-Visualisasi data seperti:

-Distribusi pelanggan churn vs tidak churn
  
-Korelasi antar fitur

Beberapa insight EDA:

-Pelanggan dengan tagihan bulanan tinggi cenderung lebih sering churn.

-Lama berlangganan yang pendek lebih berpotensi churn.

Feature Engineering dan Preprocessing :

-Encoding data kategorikal (Label Encoding / One-Hot Encoding)

-Normalisasi / Standarisasi fitur numerik

-Pembuangan data yang tidak relevan atau duplikat

Pembagian data:

  -Train set: untuk training model
  
  -Test set: untuk evaluasi model

Proses Learning / Modeling

Algoritma Machine Learning yang Digunakan:

-Logistic Regression

-Decision Tree

-Random Forest

-Support Vector Machine (SVM)

-K-Nearest Neighbor (KNN)

Langkah-langkah Modeling:

-Splitting data (train-test)

-Melatih model dengan data training

-Menyimpan hasil prediksi

-Mengukur performa model pada data testing

Hasil Evaluasi Model :
| Model               | Akurasi | Precision | Recall | F1-Score |
| ------------------- | ------- | --------- | ------ | -------- |
| Logistic Regression | 80%     | 78%       | 75%    | 76%      |
| Decision Tree       | 77%     | 74%       | 73%    | 73%      |
| Random Forest       | 82%     | 80%       | 78%    | 79%      |
| SVM                 | 79%     | 76%       | 74%    | 75%      |
| KNN                 | 75%     | 72%       | 70%    | 71%      |

Diskusi Hasil :

-Model Random Forest menghasilkan performa terbaik pada dataset ini, dengan akurasi tertinggi serta keseimbangan precision, recall, dan F1-score.

-Pelanggan dengan tagihan tinggi, lama berlangganan singkat, serta layanan tambahan tertentu lebih berisiko mengalami churn.

-Model ini dapat digunakan untuk mendeteksi pelanggan berpotensi churn dan mengambil tindakan preventif seperti promo atau layanan khusus.

Kesimpulan :

-Machine Learning efektif untuk memprediksi churn pelanggan di industri telekomunikasi.

-Model Random Forest paling optimal dalam kasus ini.

-Hasil prediksi dapat digunakan untuk strategi bisnis perusahaan seperti customer retention dan personalized marketing.
