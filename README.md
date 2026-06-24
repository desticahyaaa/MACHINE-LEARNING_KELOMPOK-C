# MACHINE-LEARNING_KELOMPOK-C
# Project Machine Learning

## PREDIKSI HARGA RUMAH MENGGUNAKAN PENDEKATAN MACHINE LEARNING: PERBANDINGAN ALGORITMA RIDGE REGRESSION, LASSO REGRESSION, RANDOM FOREST, DAN XGBOOST 

## Deskripsi Project
Project ini merupakan tugas akhir mata kuliah Machine Learning Kelas A yang bertujuan untuk menerapkan seluruh tahapan machine learning workflow pada studi kasus nyata, mulai dari eksplorasi data hingga evaluasi model.

Pada project ini dilakukan analisis data dan pembangunan model machine learning untuk memprediksi data menggunakan beberapa algoritma serta membandingkan performa model.

## Anggota Kelompok
1. Desti Cahya Utami			K1D024009
2. Mukti Toifatul Istiqomah	  	K1D024021
3. Muflihah Qurrota Ain Az’zahra	K1D024024
4. Arya Daffa Pratama			K1D024033
5. Chindy Renita Listiyana		K1D024039

---

## Tujuan Project
- Melakukan Exploratory Data Analysis (EDA)
- Melakukan preprocessing data
- Melakukan feature engineering
- Melatih beberapa model machine learning
- Melakukan hyperparameter tuning
- Mengevaluasi performa model
- Menentukan model terbaik

---


## Dataset

Sumber Dataset:

[https://www.kaggle.com/](https://www.kaggle.com/datasets/chershi/house-price-prediction-dataset-2000-rows)

Informasi dataset:

- Jumlah data: 2000 baris
- Jumlah fitur: 16
- Target: Price
- Jenis masalah: Regresi

---

## Tahapan Project

### 1. Data Collection
- Mengumpulkan dataset
- Memahami struktur data

### 2. Exploratory Data Analysis (EDA)
- Statistik deskriptif
- Histogram
- Boxplot
- Heatmap korelasi
- Analisis missing value
- Analisis outlier

### 3. Data Preprocessing
- Missing value handling
- Encoding
- Feature selection
- Feature engineering
- Data scaling

### 4. Modeling

Model yang digunakan:

1. Ridge Regression
2. Lasso Regression
3. Random Forest
4. XGBoost

### 5. Hyperparameter Tuning
Menggunakan:

- GridSearchCV
atau
- RandomizedSearchCV

### 6. Evaluasi Model

Metrik yang digunakan:

Untuk regresi:
- MAE
- RMSE
- R² Score


## Struktur Repository

```text
PROJECT-ML/
│
├── dataset/
│   └── data.csv
│
├── notebook/
│   └── PROJECT_ML_FIX.ipynb
│
├── laporan/
│   └── laporan.pdf
│
├── slide/
│   └── presentasi.pdf
│
├── requirements.txt
│
├── README.md
│
└── images/
```

## Hasil Analisis & Kesimpulan Data

Berdasarkan tahap eksplorasi dan penelaahan data (Data Understanding) pada proyek Prediksi Harga Rumah ini, berikut adalah beberapa poin penting yang berhasil disimpulkan:

Kualitas Dataset: Dataset ini bersih dari data kosong (no missing values) dengan total 2.000 baris data dan 16 fitur campuran (numerik dan kategorikal)[cite: 1].

Karakteristik Data:
> Rata-rata luas area properti berada di angka 3.238 sqft [cite: 1].
> Distribusi data didominasi oleh properti dengan status Semi-Furnished yang berlokasi di kota Mumbai [cite: 1].
> Korelasi Fitur:
 Melalui visualisasi pairplot, ditemukan indikasi awal adanya korelasi positif yang cukup kuat antara fitur `Area` dan `Locality Rating` terhadap variabel target (`Price`)[cite: 1].

Insight:
 Tahap perumusan tujuan dan penelaahan data ini memberikan fondasi yang kuat mengenai struktur data, sehingga sangat membantu untuk menentukan strategi feature engineering dan pemodelan prediktif pada tahap selanjutnya.

## Catatan

Project ini dibuat untuk memenuhi tugas akhir mata kuliah Machine Learning Kelas A.
