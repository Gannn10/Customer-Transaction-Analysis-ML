Customer-Transaction-Analysis-ML


📌 Project Overview
Proyek ini bertujuan untuk menganalisis data transaksi perbankan menggunakan dua pendekatan utama Machine Learning:

Customer Segmentation (Clustering): Mengelompokkan nasabah berdasarkan perilaku transaksi menggunakan algoritma K-Means dan reduksi dimensi PCA.

Transaction Classification: Memprediksi kategori atau target transaksi menggunakan algoritma Decision Tree yang telah dioptimasi (Hyperparameter Tuning).

📁 Repository Structure
[Klasifikasi]_Submission_Akhir_BMLP_...ipynb: Notebook proses klasifikasi (EDA, Preprocessing, Modeling, Evaluasi).

[Clustering]_Submission_Akhir_BMLP_...ipynb: Notebook proses segmentasi/clustering.

decision_tree_model.h5: Model klasifikasi yang sudah dilatih.

model_clustering.h5: Model clustering K-Means.

PCA_model_clustering.h5: Model PCA untuk reduksi dimensi.

data_clustering_inverse.csv: Hasil akhir pelabelan cluster pada data asli.

📊 Dataset Features
Dataset mencakup informasi kunci seperti:

TransactionAmount: Jumlah transaksi.

CustomerAge & AgeGroup: Profil umur nasabah.

AccountBalance: Saldo rekening.

TransactionDuration & LoginAttempts: Metrik aktivitas akun.

Location & Channel: Informasi geografis dan metode transaksi.

🛠️ Workflow & Methodology
1. Unsupervised Learning (Clustering)
Preprocessing: Scaling data dan penanganan outliers.

Dimensionality Reduction: Menggunakan PCA untuk memvisualisasikan data multidimensi ke dalam komponen utama.

Clustering: Implementasi K-Means untuk menentukan segmen nasabah yang optimal.

2. Supervised Learning (Classification)
Model: Base model menggunakan Decision Tree Classifier.

Optimization: Melakukan Hyperparameter Tuning (Grid Search/Random Search) untuk meningkatkan performa model.

Evaluation: Diukur menggunakan Accuracy, Precision, Recall, dan F1-Score.

🚀 How to Use
Clone repositori ini:

Bash

git clone https://github.com/gannn10/Customer-Transaction-Analysis-ML.git

Install library yang dibutuhkan:

Bash

pip install pandas numpy scikit-learn matplotlib seaborn joblib
Jalankan notebook .ipynb melalui Jupyter atau Google Colab.
