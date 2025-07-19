# Prediksi Pengunjung Berpotensi Membeli atau Tidak

## Repository Outline
```
1. README.md - Penjelasan gambaran umum project
2. app.py - File utama untuk menjalankan aplikasi Streamlit dan mengatur navigasi halaman
3. eda.py - Visualisasi eksplorasi data (EDA)
4. home.py - Tampilan halaman awal dashboard (berisi deskripsi, tujuan, dan informasi model)
5. prediction.py – Halaman input prediksi pembelian
6. model_terbaik.pkl – Model machine learning terbaik yang sudah dilatih
7. ecommerce_purchasing_intention.csv – Dataset utama
8. P1M2_arvin_wibowo.ipynb – Notebook eksplorasi dan pelatihan model
9. P1M2_arvin_wibowo_inf.ipynb – Notebook untuk inference/deployment
10. url.txt - Informasi link dataset dan streamlit
11. tipe_data.png – Deskripsi dataset

```

## Problem Background
Salah satu tantangan utama yang dihadapi oleh e-commerce adalah rendahnya konversi dari kunjungan pengguna menjadi transaksi pembelian. Meskipun situs mendapatkan banyak pengunjung setiap harinya, namun sebagian besar kunjungan tidak berakhir dengan pembelian. Oleh karena itu tim management ingin mengembangkan model machine learning prediksi purchasing intention untuk memprediksi apakah seorang pengguna cenderung akan melakukan pembelian atau tidak sehingga pengguna yang diprediksi akan membeli akan diperlakukan secara berbeda dalam strategi pemasaran

## Project Output
Project ini menghasilkan sebuah model machine learning yang dapat memprediksi apakah pengunjung website akan melakukan pembelian atau tidak. Selain itu, dibangun pula dashboard interaktif menggunakan streamlit yang menampilkan hasil eksplorasi data (EDA) serta fitur input prediksi secara real-time.

## Data
Data yang digunakan adalah Online Shoppers Purchasing Intention Dataset dari UCI Machine Learning Repository Dataset terdiri dari 10 data bertipe numerical dan 8 data bertipe categorical. Dataset ini tidak memiliki missing value

## Method
Proyek ini menggunakan pendekatan supervised learning untuk menyelesaikan masalah klasifikasi. Beberapa algoritma machine learning yang diuji antara lain KNN, SVM, Decision Tree, Random Forest, dan XGBoost. Model terbaik dipilih berdasarkan performa recall tertinggi karena fokus proyek adalah mengidentifikasi sebanyak mungkin pengunjung yang benar-benar membeli

## Stacks
- **Bahasa Pemrograman**: Python
- **Tools**: Jupyter Notebook, Visual Studio Code, Streamlit
- **Library**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, streamlit, scipy, pillow



## Reference
- **Dataset:** [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset)  
- **Deployment :** [Predict Purchase Intention](https://predict-purchase-intention.streamlit.app/)
