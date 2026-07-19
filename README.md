# Laporan Analisis dan Prediksi Churn Pelanggan Telco

1. Proyek ini disusun dengan tujuan untuk menganalisis dan memprediksi churn pelanggan (pelanggan yang berhenti berlangganan) pada perusahaan telekomunikasi fiktif. Dengan memahami faktor-faktor yang menyebabkan pelanggan churn, perusahaan dapat mengambil tindakan proaktif untuk mempertahankan pelanggan dan mengurangi kerugian. Proyek ini mencakup tahapan eksplorasi data, pra-pemrosesan, pembangunan model prediktif, dan evaluasi model.

2. Sumber Data
Dataset yang digunakan dalam proyek ini adalah Telco Customer Churn yang disediakan oleh IBM. Dataset ini berisi informasi demografi pelanggan, layanan yang mereka gunakan, dan status churn mereka. Dataset ini dapat diakses secara publik melalui repositori GitHub IBM.

3. Metodologi
Proyek ini mengikuti standar alur analisis data:
a) Pemuatan dan Pembersihan Data: Memuat dataset dan menangani nilai yang hilang atau tidak konsisten.
b) Eksplorasi Data (EDA): Menganalisis distribusi variabel dan hubungan antar variabel untuk mendapatkan wawasan awal.
c) Pra-pemrosesan Data: Mengubah variabel kategorikal menjadi numerik dan melakukan scaling pada fitur numerik.
d) Pembangunan Model Prediktif: Menggunakan algoritma Random Forest Classifier untuk memprediksi churn.
e) Evaluasi Model: Menilai kinerja model menggunakan metrik seperti akurasi, presisi, recall, dan f1-score, serta menganalisis confusion matrix dan feature importance.

4. Kesimpulan dan Rekomendasi Bisnis
Proyek ini berhasil membangun model prediksi churn dengan akurasi yang cukup baik dan mengidentifikasi faktor-faktor kunci yang berkontribusi terhadap churn. Pelanggan dengan biaya bulanan tinggi, total biaya yang lebih rendah (mungkin karena baru berlangganan), tenure yang singkat, dan kontrak bulanan memiliki kemungkinan churn yang lebih tinggi. Rekomendasi Bisnis: a) Program Retensi untuk Pelanggan Baru/Jangka Pendek: Fokus pada pelanggan dengan tenure singkat dan kontrak bulanan. Tawarkan insentif untuk beralih ke kontrak jangka panjang. b) Evaluasi Struktur Harga: Tinjau kembali paket layanan dengan biaya bulanan tinggi, terutama jika ada keluhan pelanggan atau penawaran kompetitor yang lebih menarik. c) Analisis Metode Pembayaran: Selidiki lebih lanjut mengapa metode pembayaran tertentu berkorelasi dengan churn yang lebih tinggi. Mungkin ada masalah dalam proses pembayaran atau preferensi pelanggan. d) Peningkatan Layanan Pelanggan: Karena faktor-faktor seperti OnlineSecurity dan TechSupport juga muncul sebagai faktor penting (meskipun tidak di top 5), peningkatan kualitas layanan dan dukungan teknis dapat membantu mengurangi churn.
Dengan menerapkan rekomendasi ini, perusahaan telekomunikasi dapat meningkatkan strategi retensi pelanggan dan mengurangi tingkat churn.
