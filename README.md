# Pengolahan Data dengan Decision Tree untuk Data Tabular
-----
## 1. Data Tabular
* Definisi Data Tabular:
Data tabular adalah jenis data terstruktur yang disusun dalam bentuk tabel, dengan baris dan kolom yang terorganisir secara jelas. Format umumnya seperti CSV (Comma-Separated Values) atau Excel, di mana setiap baris data dipisahkan dengan koma atau diatur dalam sel-sel yang berbeda.

* Penggunaan Data Tabular:
Data tabular sering digunakan untuk analisis dan pemodelan statistik. Algoritma pembelajaran mesin seperti regresi, klasifikasi, atau pengelompokan sering diterapkan pada data tabular untuk mengungkap pola atau membuat prediksi berdasarkan atribut-atribut yang diberikan.

## 2. E - Commerce Shipping data 
* E-commerce shipping data adalah data yang terkait dengan proses pengiriman barang dalam industri e-commerce. Ini mencakup informasi tentang bagaimana produk diproses, dikemas, dan dikirim kepada pelanggan setelah pembelian online. Data ini dapat memberikan wawasan tentang efisiensi operasional, kualitas layanan pengiriman, dan kepuasan pelanggan.

## 3. Penggunaan Dataset Kaggle
* Dataset yang Digunakan:
Saya menggunakan dataset dari Kaggle yang terkait dengan E-Commerce Shipping data. Dataset ini memuat informasi tentang pengiriman barang dalam industri e-commerce, dengan fokus pada waktu pengiriman dan kepuasan pelanggan. Dataset dapat diakses di [dataset E-commerce Shipping Data ](https://www.kaggle.com/datasets/prachi13/customer-analytics)

## 4. Langkah-Langkah Pengolahan Data
* Persiapan Dataset dan EDA
  - Menggunakan Google Colab untuk analisis data.
  - Mengunduh dataset dan menyimpannya di Google Drive.
  - Melakukan Exploratory Data Analysis (EDA) untuk memahami karakteristik dasar, pola, dan hubungan dalam data.
  - Menggunakan Pandas, untuk memeriksa informasi dasar tentang dataset seperti deskripsi statistik dan informasi kolom.
* Data Preprocessing
   - Proses Label Encoding, Label encoding digunakan untuk mengubah variabel kategorikal menjadi nilai numerik. Ini diperlukan untuk proses selanjutnya, seperti feature selection.
* Feature Selection
  - Pemilihan Fitur, Pemilihan fitur dilakukan untuk mengurangi dimensi data, meningkatkan kinerja model, dan memudahkan interpretasi.
* Train-Test Split
  - Pembagian Dataset, Train-test split dilakukan untuk membagi dataset menjadi dua subset: data latih (train set) dan data uji (test set).
* Decision Tree Model
  - Membangun Model Decision Tree, Model Decision Tree dibangun menggunakan DecisionTreeClassifier dari scikit-learn. Model ini digunakan untuk memprediksi mode pengiriman berdasarkan fitur-fitur yang dipilih.
* Evaluasi Model
  - Mengukur Akurasi Model, Akurasi model diukur menggunakan metrik accuracy, yang menggambarkan sejauh mana model dapat memprediksi dengan benar kelas target pada data uji.
  
