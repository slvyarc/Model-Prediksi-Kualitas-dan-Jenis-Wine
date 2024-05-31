# Membangun Model Machine Learning dengan Multiple Output Menggunakan Keras Functional API

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun model machine learning yang mampu memprediksi multiple output menggunakan Keras Functional API. Saya menggunakan Wine Quality Dataset dari UCI Machine Learning Repository untuk memprediksi kualitas dan jenis wine. Proyek ini menyoroti pentingnya penggunaan model dengan multiple output dalam meningkatkan efisiensi dan performa prediksi.

## Dataset

Wine Quality Dataset digunakan dalam proyek ini dan dapat diunduh dari [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality).

## Langkah-langkah dalam Notebook

1. **Mengimpor Library yang Diperlukan**
2. **Memuat dan Memproses Dataset**
   - Pre-proses White Wine
   - Pre-proses Red Wine
   - Menggabungkan Dataset
   - Mengacak Data
   - Menangani Data yang Tidak Seimbang
3. **Membagi Dataset menjadi Train, Validation, dan Test Sets**
4. **Ekstraksi Label dari Data**
5. **Normalisasi Data**
6. **Mendefinisikan Model Menggunakan Keras Functional API**
   - Model Dasar
   - Lapisan Output Model
7. **Mengompilasi Model**
8. **Melatih Model**
9. **Evaluasi Model**
10. **Analisis Kinerja Model**
    - Prediksi
    - Visualisasi Metrik Model
    - Matriks Kebingungan
    - Scatter Plot

## Hasil

Proyek ini menunjukkan bahwa dengan pendekatan yang tepat, kita bisa membangun model machine learning yang efektif untuk prediksi multiple output. Keras Functional API memberikan fleksibilitas yang dibutuhkan untuk mengembangkan model seperti ini, dan dengan evaluasi yang tepat, kita bisa memastikan bahwa model yang dibangun memiliki performa yang baik dan dapat diandalkan.

### Hasil Akurasi

Model yang dikembangkan dalam proyek ini menunjukkan kinerja yang sangat baik dengan metrik-metrik sebagai berikut:
- **Overall Loss**: 0.3834
- **Wine Quality Loss**: 0.3758
- **Wine Type Loss**: 0.0076
- **Wine Quality RMSE**: 0.6130
- **Wine Type Accuracy**: 99.75%

Nilai **Overall Loss** yang rendah dan **Wine Type Accuracy** yang hampir sempurna menunjukkan bahwa model ini sangat efektif dalam memprediksi baik kualitas maupun jenis wine. **Wine Quality RMSE** yang rendah juga menunjukkan bahwa prediksi kualitas wine sangat mendekati nilai sebenarnya, menandakan model ini sangat akurat.

Untuk penjelasan lengkap tentang proses dan hasil proyek ini, kunjungi artikel Medium saya: [Membangun Model Machine Learning dengan Multiple Output Menggunakan Keras Functional API: Studi Kasus Prediksi Kualitas dan Jenis Wine](https://medium.com/@silviadharma07/membangun-model-machine-learning-dengan-multiple-output-menggunakan-keras-functional-api-studi-2a7dee9a2362)
