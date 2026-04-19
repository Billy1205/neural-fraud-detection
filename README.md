# 🧠 Neural Network Transaction Fraud Detection
An advanced classification system utilizing **Artificial Neural Networks (ANN)** to detect fraudulent financial transactions. This project compares the effectiveness of Deep Learning models in recognizing complex anomaly patterns within high-dimensional transaction data.

*This project implements Deep Learning for financial security, focusing on neural network architecture optimization and managing the trade-off between precision and recall.*

## 📝 Project Description
Unlike traditional machine learning models, this project leverages the power of *hidden layers* within Neural Networks to extract non-linear features from transaction data. The primary focus is on **Precision-Recall Curve** analysis to determine the optimal security threshold that balances blocking accuracy with user experience.

## ✨ Key Features
- **Multi-layer Perceptron (MLP) Architecture**: Building optimized neural network layers specifically for tabular transaction data.
- **Advanced Loss Function Analysis**: Utilizing specialized evaluation metrics to monitor model performance on highly imbalanced datasets.
- **Security Trade-off Analysis**: Implementing Precision-Recall curve visualizations to determine the best detection thresholds.
- **Deep Evaluation Metrics**: Calculating **PR AUC** and peak **F1-Score** to ensure the model is sensitive to fraud cases.
- **Automated Data Retrieval**: Direct integration with Kaggle API for efficient dataset management.

## 🛠️ Tech Stack & Implementation
- **Deep Learning Framework**: TensorFlow / Keras.
- **Programming Language**: Python 3.x.
- **Evaluation Tools**: Scikit-Learn (for `precision_recall_curve` and `auc`).
- **Visualization**: Matplotlib & Seaborn.

## ⚙️ Installation & Usage

### 1. Prerequisites (Kaggle API)

This project requires access to the Kaggle dataset via API.

  - Download your `kaggle.json` from your Kaggle account.
  - **Google Colab**: Add your credentials to the **Secrets** tab as `KAGGLE_USERNAME` and `KAGGLE_KEY`.
  - **Local**: Store `kaggle.json` in your `~/.kaggle/` directory.

### 2. Environment Setup

```bash
# Clone this repository
git clone https://github.com/Billy1205/neural-fraud-detection.git
cd neural-fraud-detection

# Install deep learning dependencies
pip install -r requirements.txt
```

### 3. Execution

Open `notebooks/neural-fraud-detection.ipynb` and run the cells. The notebook will automatically:

  - Download the dataset from Kaggle.
  - Preprocess the data using **RobustScaler**.
  - Train the **Artificial Neural Network (ANN)**.
  - Perform **Threshold Optimization** based on the F1-Score.

***

# 🧠 Neural Network Transaction Fraud Detection
Sistem klasifikasi tingkat lanjut menggunakan arsitektur **Artificial Neural Networks (ANN)** untuk mendeteksi penipuan transaksi keuangan. Proyek ini membandingkan efektivitas model *Deep Learning* dalam mengenali pola anomali kompleks pada data transaksi yang memiliki dimensi tinggi.

*Proyek ini merupakan implementasi Deep Learning untuk keamanan finansial, fokus pada optimalisasi arsitektur jaringan saraf dan manajemen trade-off antara precision dan recall.*

## 📝 Project Description
Berbeda dengan model machine learning tradisional, proyek ini memanfaatkan daya tangkap *hidden layers* pada Neural Network untuk mengekstraksi fitur-fitur non-linear dari data transaksi. Fokus utama adalah pada analisis **Precision-Recall Curve** untuk menentukan *threshold* keamanan optimal yang menyeimbangkan antara akurasi pemblokiran dan kenyamanan pengguna.

## ✨ Key Features
- **Multi-layer Perceptron (MLP) Architecture**: Membangun arsitektur jaringan saraf dengan lapisan tersembunyi yang dioptimalkan untuk data tabular.
- **Advanced Loss Function Analysis**: Menggunakan metrik evaluasi khusus untuk memantau performa model pada data yang sangat tidak seimbang.
- **Security Trade-off Analysis**: Implementasi visualisasi kurva Precision-Recall untuk menentukan titik ambang batas (*threshold*) deteksi terbaik.
- **Deep Evaluation Metrics**: Menghitung **PR AUC** dan **F1-Score** tertinggi untuk memastikan model tidak hanya akurat secara global, tapi juga sensitif terhadap kasus fraud.
- **Automated Data Retrieval**: Integrasi langsung dengan Kaggle API untuk manajemen dataset yang efisien.

## 🛠️ Tech Stack & Implementation
- **Deep Learning Framework**: TensorFlow / Keras.
- **Programming Language**: Python 3.x.
- **Mathematical Computation**: NumPy & Pandas.
- **Evaluation Tools**: Scikit-Learn (untuk `precision_recall_curve` dan `auc`).
- **Visualization**: Matplotlib & Seaborn.

## 📊 Methodology
- **Neural Architecture**: Penggunaan *Dense layers* dengan fungsi aktivasi yang sesuai untuk menangani data transaksi yang sudah ditransformasi (PCA).
- **Optimal Threshold Search**: Algoritma pencarian otomatis untuk menemukan F1-Score tertinggi guna meminimalkan *False Positives*.
- **Performance Evaluation**: Analisis kurva PR (Precision-Recall) sebagai indikator utama keberhasilan model dalam skenario keamanan dunia nyata.

## ⚙️ Instalasi & Penggunaan

### 1. Prasyarat (Kaggle API)

Proyek ini membutuhkan akses ke dataset Kaggle melalui API.

  - Unduh `kaggle.json` dari akun Kaggle Anda.
  - **Google Colab**: Tambahkan kredensial ke tab **Secrets** dengan nama `KAGGLE_USERNAME` dan `KAGGLE_KEY`.
  - **Lokal**: Simpan file `kaggle.json` di folder `~/.kaggle/`.

### 2. Persiapan Lingkungan

```bash
# Klon repositori
git clone https://github.com/Billy1205/neural-fraud-detection.git
cd neural-fraud-detection

# Instal dependensi deep learning
pip install -r requirements.txt
```

### 3. Cara Menjalankan

Buka file `notebooks/neural-fraud-detection.ipynb` dan jalankan semua sel kode. Notebook akan secara otomatis:

  - Mengunduh dataset dari Kaggle.
  - Melakukan preprocessing data dengan **RobustScaler**.
  - Melatih **Artificial Neural Network (ANN)**.
  - Mencari **Threshold Optimal** berdasarkan F1-Score tertinggi.
