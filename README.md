
# Fast Food Machine Learning

## 1. Deskripsi Proyek

Proyek ini merupakan analisis data makanan cepat saji
menggunakan algoritma Random Forest Classification.

Tujuan proyek adalah membangun model yang memprediksi
kategori workout_shock_tier berdasarkan kandungan gizi,
kategori makanan, restoran, dan karakteristik konsumen.

## 2. Dataset

Nama file:
fast_food_cheat_meal_workout_burn.csv

Jumlah data:
8.000 baris dan 23 kolom.

Dataset mencakup informasi makanan cepat saji,
kandungan nutrisi, karakteristik konsumen, dan estimasi
aktivitas olahraga.

Catatan: asal-usul dan metode pembuatan dataset perlu
diverifikasi sebelum hasil digunakan untuk penelitian.

## 3. Metode

Algoritma yang digunakan adalah Random Forest Classification.

Target:
workout_shock_tier

Fitur yang digunakan mencakup:
- fast_food_chain
- meal_category
- item_count
- total_calories
- fat_grams
- saturated_fat_grams
- carb_grams
- sugar_grams
- protein_grams
- sodium_mg
- consumer_gender
- consumer_age
- consumer_weight_kg
- fitness_level

Kolom ID transaksi dan sejumlah kolom turunan dikeluarkan
untuk mengurangi risiko data leakage.

## 4. Tools dan Library

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Instalasi

Jalankan perintah berikut di terminal:

python -m pip install pandas numpy matplotlib seaborn scikit-learn

## 6. Cara Menjalankan

1. Siapkan Python dan Jupyter Notebook.
2. Letakkan file CSV di folder proyek.
3. Buka Jupyter Notebook.
4. Buka fast_food_analysis.ipynb.
5. Jalankan setiap cell secara berurutan.
6. Periksa hasil preprocessing, prediksi, dan evaluasi.

## 7. Tahapan Analisis

1. Import library.
2. Membaca dataset.
3. Memeriksa struktur dan kualitas data.
4. Visualisasi distribusi target.
5. Menentukan fitur dan target.
6. Membagi data training dan testing.
7. Melakukan preprocessing.
8. Melatih model Random Forest.
9. Melakukan prediksi.
10. Mengevaluasi model.
11. Membuat confusion matrix.
12. Menganalisis feature importance.
13. Menyusun kesimpulan.

## 8. Evaluasi

Model dievaluasi menggunakan:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Nilai evaluasi dicatat setelah seluruh cell berhasil
dijalankan. Tidak ada nilai akurasi yang ditetapkan
sebelum pengujian dilakukan.

## 9. Batasan

Hasil model bergantung pada kualitas dan karakteristik
dataset. Prediksi tidak dapat langsung dianggap sebagai
rekomendasi medis atau ukuran kebutuhan olahraga yang
akurat bagi individu.

## 10. Kesimpulan

Proyek ini menerapkan Machine Learning untuk mempelajari
pola data makanan cepat saji dan memprediksi kategori
target menggunakan Random Forest Classification.