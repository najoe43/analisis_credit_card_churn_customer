# analisis_credit_card_churn_customer
Laporan proyek machine learning untuk prediksi churn pelanggan kartu kredit.

## Daftar Isi
- [Domain Proyek: Keuangan](#domain-proyek-keuangan)
  - [Referensi](#referensi)
- [Business Understanding](#business-understanding)
  - [Problem Statements](#problem-statements)
  - [Goals](#goals)
- [Data Understanding](#data-understanding)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)

---

## Domain Proyek: Keuangan
Proyek ini berfokus pada prediksi pelanggan churn pada pengguna kartu kredit.

### Referensi
Dataset: [BankChurners.csv](datasets/BankChurners.csv)

## Business Understanding
### Problem Statements
Tingkat keluar-masuk karyawan (attrition) merupakan salah satu permasalahan penting bagi perusahaan karena dapat menimbulkan kerugian, baik dari segi biaya rekrutmen, pelatihan, maupun penurunan produktivitas kerja. Ketika banyak karyawan yang keluar, proses adaptasi dan efisiensi tim jadi terganggu. Oleh karena itu, perusahaan perlu memahami faktor-faktor yang memengaruhi keputusan karyawan untuk keluar dan memprediksi kemungkinan tersebut sedini mungkin agar dapat dicegah sedini mungkin.
### Goals
- Membuat model untuk memprediksi apakah seorang karyawan akan keluar dari perusahaan atau tidak.
- Mengetahui faktor-faktor apa saja yang paling berpengaruh terhadap keputusan karyawan keluar.
- Menghasilkan model dengan performa optimal menggunakan pendekatan hyperparameter tuning (GridSearchCV) dan evaluasi berbasis metrik AUC, akurasi, presisi, recall, serta F1-score.

## Data Understanding
### Sumber Data
Dataset yang digunakan pada proyek ini diperoleh dari situs kaggle (?). Dataset ini terdiri dari 1170 data karyawan yang berisi 31 variabel seperti demografis dan pekerjaan seperti usia, jenis kelamin, jabatan, tingkat pendidikan, pendapatan, kepuasan kerja, serta lama bekerja di perusahaan. Kolom target bernama Attrition menunjukkan apakah seorang karyawan keluar dari perusahaan atau tidak. Data ini digunakan untuk membangun model klasifikasi yang mampu memprediksi potensi karyawan mengalami attrition berdasarkan karakteristiknya.

