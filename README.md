# Laporan Analisis dan Prediksi Churn Pelanggan Telco

1. Pendahuluan
Proyek ini bertujuan untuk menganalisis dan memprediksi churn pelanggan (pelanggan yang berhenti berlangganan) pada perusahaan telekomunikasi fiktif. Dengan memahami faktor-faktor yang menyebabkan pelanggan churn, perusahaan dapat mengambil tindakan proaktif untuk mempertahankan pelanggan dan mengurangi kerugian. Proyek ini mencakup tahapan eksplorasi data, pra-pemrosesan, pembangunan model prediktif, dan evaluasi model.

2. Sumber Data
Dataset yang digunakan dalam proyek ini adalah Telco Customer Churn yang disediakan oleh IBM. Dataset ini berisi informasi demografi pelanggan, layanan yang mereka gunakan, dan status churn mereka. Dataset ini dapat diakses secara publik melalui repositori GitHub IBM .

3. Metodologi
Proyek ini mengikuti alur analisis data standar:
a) Pemuatan dan Pembersihan Data: Memuat dataset dan menangani nilai yang hilang atau tidak konsisten.
b) Eksplorasi Data (EDA): Menganalisis distribusi variabel dan hubungan antar variabel untuk mendapatkan wawasan awal.
c) Pra-pemrosesan Data: Mengubah variabel kategorikal menjadi numerik dan melakukan scaling pada fitur numerik.
d) Pembangunan Model Prediktif: Menggunakan algoritma Random Forest Classifier untuk memprediksi churn.
e) Evaluasi Model: Menilai kinerja model menggunakan metrik seperti akurasi, presisi, recall, dan f1-score, serta menganalisis confusion matrix dan feature importance.
