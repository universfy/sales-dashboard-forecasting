1. Tujuan Project

Tujuan project ini adalah untuk menganalisis performa penjualan e-commerce dan membuat prediksi penjualan beberapa bulan ke depan menggunakan forecasting. Project ini membantu bisnis memahami tren penjualan, performa produk, wilayah terbaik, serta membantu pengambilan keputusan bisnis berdasarkan data.

2. Source Dataset : https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/

Dataset yang digunakan adalah dataset Superstore Sales yang berisi data:
- penjualan
- profit
- customer segment
- region
- category
- produk
- tanggal order

3. Problemnya Apa

Permasalahan utama dalam project ini adalah:
perusahaan ingin mengetahui performa penjualan dan memprediksi tren sales di masa depan agar dapat membantu strategi bisnis dan pengambilan keputusan.

Selain itu, perusahaan juga ingin mengetahui:
- wilayah dengan penjualan tertinggi
- kategori produk terbaik
- produk paling laku
- segment customer terbaik
- pola penjualan bulanan

4. Langkah Pengerjaan

Data Loading
Load dataset menggunakan: Pandas

Data Cleaning & Preparation
Melakukan:
- convert tipe data tanggal
- membuat kolom tambahan seperti year dan month
- mengecek missing value
- melihat struktur data menggunakan info()

Exploratory Data Analysis (EDA)
Melakukan analisis:
- total sales
- total profit
- total order
- sales trend per bulan
- sales by region
- sales by category
- top product
- sales by segment
- top state

Visualisasi menggunakan:
- Plotly
- Matplotlib
- Forecasting

Membuat prediksi penjualan menggunakan: Prophet
Langkahnya:
- mengubah format data menjadi ds dan y
- training model Prophet
- membuat prediksi 12 bulan ke depan
- visualisasi hasil forecasting

5. Model yang Dipakai

Model yang digunakan adalah: Prophet
Karena:
- cocok untuk time series forecasting
- mudah digunakan
- cukup baik dalam membaca tren dan seasonality
- dapat memprediksi data penjualan bulanan

6. Hasil

Hasil analisis menunjukkan:
- adanya pola tren penjualan bulanan
- beberapa region memiliki sales lebih tinggi dibanding region lain
- terdapat kategori dan produk tertentu yang mendominasi penjualan
- segment customer tertentu memberikan kontribusi sales lebih besar
Hasil forecasting juga memberikan estimasi penjualan untuk 12 bulan berikutnya sehingga perusahaan dapat memperkirakan performa bisnis di masa depan.

7. Insight Bisnisnya

Beberapa insight bisnis yang didapat:
- Penjualan memiliki pola tren tertentu setiap bulannya.
- Beberapa produk dan kategori memberikan kontribusi sales paling besar.
- Region tertentu memiliki performa penjualan lebih tinggi sehingga dapat menjadi fokus bisnis.
- Forecasting membantu perusahaan mempersiapkan strategi stok dan target penjualan untuk periode berikutnya.

Berdasarkan hasil analisis, perusahaan dapat:
- fokus meningkatkan penjualan produk dengan performa terbaik
- membuat strategi promosi di region dengan potensi tinggi
- mempersiapkan stok berdasarkan hasil forecasting
- mengevaluasi kategori dengan penjualan rendah agar performanya meningkat.
