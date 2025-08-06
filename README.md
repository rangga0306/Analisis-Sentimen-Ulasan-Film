# Proyek Data Science: Analisis Sentimen Ulasan Film IMDb

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model machine learning yang mampu mengklasifikasi sentimen (positif atau negatif) dari ulasan film. Dataset yang digunakan adalah "IMDB Dataset of 50k Movie Reviews" dari Kaggle.

## Metodologi
1.  **Pembersihan Data:** Melakukan *text preprocessing* seperti menghapus tag HTML, tanda baca, *stop words*, dan *stemming*.
2.  **Feature Engineering:** Mengubah teks bersih menjadi representasi numerik menggunakan **TF-IDF Vectorizer**.
3.  **Pemodelan:** Melatih model klasifikasi **Logistic Regression** pada 80% data latih.
4.  **Evaluasi:** Menguji performa model pada 20% data uji.

## Hasil
Model yang dibangun berhasil mencapai **akurasi sebesar 88.38%** dalam memprediksi sentimen ulasan film. Metrik evaluasi lainnya juga menunjukkan performa yang sangat baik dan seimbang.

## Tools & Library
* Python
* Pandas
* NLTK
* Scikit-learn
* Google Colab

## Konten Repositori
* `IMDB Sentiment Analysis.ipynb`: Notebook Google Colab yang berisi kode lengkap dari proyek ini.
