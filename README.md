# Prediksi Kelulusan Mahasiswa Menggunakan Algoritma Support Vector Machine (SVM)
## Deskripsi Dataset
Dataset yang digunakan berisi data akademik mahasiswa yang mencakup beberapa variabel seperti:
- IPK
- Total SKS
- Presentase Kehadiran
- Lama Studi
- Status Keaktifan Organisasi
- Dan variabel pendukung lainnya

Dataset memiliki label berupa **Lulus** atau **Belum Lulus**, yang digunakan sebagai target model klasifikasi.

## Langkah Pengerjaan

1. **Load Dataset**
   - Menggunakan Pandas untuk membaca file CSV
   - Mengecek informasi umum dataset dan missing values

2. **Exploratory Data Analysis (EDA)**
   - Statistik deskriptif
   - Visualisasi (Histogram IPK, Countplot Status Kelulusan)
   - Analisis hubungan data terhadap label target

3. **Preprocessing Data**
   - Handling missing values
   - Encoding data kategorikal
   - Normalisasi fitur menggunakan StandardScaler
   - Split data latih dan data uji dengan beberapa rasio: 60:40, 75:25, 80:20, dan 90:10

4. **Training Model**
   - Melatih dua model SVM:
     - SVM Linear
     - SVM RBF Kernel
   - Melakukan tuning parameter (C dan gamma)

5. **Evaluasi Model**
   - Confusion matrix
   - Accuracy, precision, recall, dan f1-score
   - Perbandingan hasil model untuk menentukan model terbaik

6. **Deployment Sederhana**
   - Membuat fungsi `predict_status()` untuk melakukan prediksi terhadap data baru

## Cara Menjalankan Notebook

1. Download repository ini
2. Buka file `SVM_kelulusan_NurLydyaAzizah_2457201002379.ipynb` menggunakan:
   - Jupyter Notebook, atau
   - Google Colab
3. Jalankan cell secara berurutan dari atas hingga bawah.

- Nama: **Nur Lydya Azizah**
- NIM: **245720102379**
- Program Studi: **Sistem Informasi**
- Mata Kuliah: **Machine Learning**
- Dosen Pengampu: **Dr. DWI WAHYU PRABOWO, S.Si., M.Eng.**
