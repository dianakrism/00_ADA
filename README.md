# ADA RETAIL-SUPERMARKET ANALYSIS 2019 Q1
[Kaggle Dataset Source](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data)

## Project Description
Proyek ini bertujuan untuk menganalisis penjualan pada tiga cabang supermarket ADA Retail selama kuartal pertama tahun 2019. Analisis ini digunakan untuk menentukan cabang yang berpotensi diperluas dengan target peningkatan pendapatan penjualan sebesar 25%. Strategi ini didukung dengan identifikasi produk terlaris, yang akan membantu dalam merancang promosi yang tepat dan menarik.

## Dataset Description
Berikut adalah deskripsi dari kolom-kolom yang terdapat dalam dataset:

| Column Name             | Description                                                                                      |
|-------------------------|--------------------------------------------------------------------------------------------------|
| `Invoice id`             | Nomor identifikasi faktur penjualan yang dihasilkan oleh komputer.                               |
| `Branch`                 | Cabang supermarket (tersedia 3 cabang, diidentifikasi sebagai A, B, dan C).                      |
| `City`                   | Lokasi cabang supermarket.                                                                       |
| `Customer type`          | Jenis pelanggan, dicatat sebagai `Members` (anggota kartu) dan `Normal` (non-anggota).           |
| `Gender`                 | Jenis kelamin pelanggan.                                                                         |
| `Product line`           | Kategori produk (misal: Electronic accessories, Fashion accessories, dll.).                      |
| `Unit price`             | Harga per unit produk dalam USD.                                                                 |
| `Quantity`               | Jumlah produk yang dibeli pelanggan.                                                             |
| `Tax`                    | Pajak sebesar 5% yang dibebankan kepada pelanggan.                                               |
| `Total`                  | Total harga yang termasuk pajak.                                                                 |
| `Date`                   | Tanggal pembelian (data tersedia dari Januari hingga Maret 2019).                                |
| `Time`                   | Waktu pembelian (antara pukul 10:00 hingga 21:00).                                               |
| `Payment`                | Metode pembayaran yang digunakan (Cash, Credit card, atau Ewallet).                              |
| `COGS`                   | Cost of Goods Sold (Harga pokok penjualan).                                                      |
| `Gross margin percentage`| Persentase margin kotor.                                                                         |
| `Gross income`           | Pendapatan kotor dari penjualan.                                                                 |
| `Rating`                 | Peringkat kepuasan pelanggan terhadap pengalaman berbelanja (skala 1 hingga 10).                 |

## Fitur Utama
- **Exploratory Data Analysis (EDA):** Menganalisis pola data untuk mendapatkan insight mengenai penjualan.
- **Statistik Deskriptif:** Menghitung nilai-nilai seperti mean, median, modus, dan distribusi data.
- **Statistik Inferensial:** Melakukan uji hipotesis dan analisis korelasi untuk memahami hubungan antar variabel.
- **Visualisasi Data:** Membuat berbagai grafik seperti pie chart, trend line, bar chart, dan box plot untuk mempermudah pemahaman data.

## Teknologi yang Digunakan
- **Python**: Bahasa pemrograman utama yang digunakan.
- **Pandas**: Untuk manipulasi dan analisis data.
- **Scipy**: Untuk pengujian statistik dan analisis inferensial.
- **Matplotlib**: Untuk visualisasi data dasar.
- **Plotly Express**: Untuk visualisasi data yang interaktif.
-- **Tableau**: Untuk penyajian visualisasi dalam bentuk dashboard.
