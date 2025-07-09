# 🚨 Klasifikasi Aktivitas Berdasarkan Kualitas Udara (Air Quality & ADL)

Proyek ini menggunakan **machine learning (Random Forest)** untuk mengklasifikasikan aktivitas dalam ruangan (Normal, Memasak, Asap, Pembersihan) berdasarkan data dari sensor gas. Fokusnya adalah deteksi aktivitas berisiko seperti asap — penting untuk pemantauan pasien dengan gangguan pernapasan di lingkungan medis.

---

## 📊 Dataset

- **Sumber**: Mendeley (DOI: 10.17632/kn3x9rz3kd.1)

- **Fitur**: 6 sensor gas (MQ2, MQ9, MQ135, MQ137, MQ138, MG_811)

- **Label**: 4 aktivitas (Normal situation, Preparing meals, Presence of smoke, Cleaning)

- **Ukuran**: 1845 sampel

---

## 🎯 Tujuan

- Menganalisis dan memvisualisasi data kualitas udara

- Membangun model klasifikasi aktivitas

- Membandingkan performa model dengan **semua fitur vs fitur tereduksi**

---

## ⚙️ Metode

- **Model**: Random Forest

- **Preprocessing**: StandardScaler, train-test split 80:20

- **Evaluasi**: Accuracy, F1-score, Confusion Matrix

---

## 🧪 Hasil

### ✅ Semua Fitur

- Akurasi: **96%**

- Recall kelas Asap: **0.94**

- F1-score rata-rata: **0.96**

### ⚠️ Fitur Tereduksi (MQ2 & MG_811)

- Akurasi: **83%**

- Recall kelas Asap: **0.75**

🔎 **Kesimpulan**: Random Forest tetap efektif meski fitur berkorelasi. Semua fitur memberikan hasil terbaik dan direkomendasikan untuk aplikasi medis.

---

## 💡 Relevansi Medis

- **Deteksi Asap**: Melindungi pasien asma dan gangguan pernapasan

- **Identifikasi Aktivitas**: Mendeteksi paparan berbahaya (asap, pembersih, dll.)

- **Solusi AI hemat biaya** tanpa kalibrasi manual sensor

---

## ▶️ Cara Menjalankan

1. Clone repo ini

2. Unduh dataset dari Kaggle atau Mendeley

3. Jalankan notebook di Google Colab

4. Unggah file dataset saat diminta

5. Jalankan semua sel untuk melihat hasil

📦 Prasyarat:\
`pip install pandas numpy matplotlib seaborn scikit-learn`

---

## 🙋 Kontak

**Muhammad Naufal Aqil**\
📧 muhammadnaufalaqil20@gmail.com\
🔗 https://github.com/Naufal22 | https://www.linkedin.com/in/muhammad-naufal-aqil-b6114424a/

---

## 🙏 Acknowledgements

Dataset oleh: Gambi, E. (2020). *Air Quality dataset for ADL classification*, Mendeley Data V1.
Kaggle : https://www.kaggle.com/datasets/saurabhshahane/adl-classification/data

---
