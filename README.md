# Sephora Skincare Data Analysis: Uncovering Customer Preferences & Chemical Ingredient Trends 💄🧪

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis data produk perawatan kecantikan dari Sephora guna menemukan wawasan bisnis (*business insights*) terkait preferensi pelanggan, strategi penetapan harga, dan tren formulasi bahan kimia (*ingredients*). Analisis ini menggunakan pustaka data terkemuka di Python untuk mengeksplorasi ribuan produk dan memberikan rekomendasi berbasis data bagi pengembang produk kosmetik.

## 🛠️ Tools & Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation & Cleaning), Matplotlib & Seaborn (Data Visualization)
* **Environment:** Jupyter Notebook / Google Colab

## ❓ Business Questions Addressed
1. Apakah produk kosmetik dengan harga yang lebih mahal selalu mendapatkan *rating* yang lebih tinggi dari pengguna?
2. *Brand* apa saja yang mendominasi pasar dalam memproduksi produk berkualitas tinggi (*rating* >= 4.5)?
3. **[Advanced]** Bahan aktif kimia (*active ingredients*) apa yang paling banyak diformulasikan di dalam produk-produk berating tertinggi?

## 💡 Key Business Insights
Berdasarkan *Exploratory Data Analysis* (EDA) yang telah dilakukan, ditemukan beberapa wawasan krusial:

* **Insight 1: Harga Mahal Bukan Jaminan Kepuasan Pelanggan** Mayoritas produk kosmetik dan *skincare* berada di rentang harga di bawah $100 dan berhasil memperoleh *rating* sangat tinggi (di atas 4.0). Tidak ditemukan korelasi positif yang kuat antara tingginya harga produk dengan tingginya *rating* pelanggan. Beberapa produk di atas $300 bahkan memiliki metrik kepuasan yang rendah.

* **Insight 2: Dominasi *In-House Brand* dan Kekuatan Merek *Luxury*** Merek *in-house* (**SEPHORA COLLECTION**) memimpin jumlah produk dengan *rating* tertinggi berkat variasi katalog yang masif dan harga yang kompetitif. Namun, merek *luxury* konvensional seperti **Dior**, **Yves Saint Laurent**, dan **Armani Beauty** tetap menunjukkan dominasi kualitas yang sangat kuat dan mempertahankan loyalitas konsumen.

* **Insight 3: Kunci Kepuasan Pelanggan Ada pada Hidrasi dan *Skin Barrier*** Analisis komponen kimia menunjukkan bahwa bahan aktif yang paling mendominasi produk *skincare* berating tinggi bukanlah agen eksfoliator keras, melainkan agen hidrasi dan penenang kulit seperti **Glycerin** (humektan), **Panthenol** (Vitamin B5), dan **Squalane**. Hal ini membuktikan bahwa konsumen Sephora sangat menghargai produk dengan formulasi dasar yang aman, melembapkan, dan minim iritasi (*gentle formulation*).

## 📂 Repository Files
* `Sephora_Skincare_EDA.ipynb`: File utama Jupyter Notebook yang berisi kode Python untuk proses pembersihan data hingga visualisasi.
* `product_info.csv`: Dataset utama yang berisi informasi harga, *rating*, merek, dan komposisi bahan produk.

## 👩‍🔬 About the Author
**Nazwa** *Chemistry Undergraduate Student at Institut Teknologi Bandung (ITB) | Aspiring Data Analyst* Menggabungkan pemahaman sains presisi dengan teknik analisis data untuk memecahkan masalah bisnis yang kompleks. Sangat antusias dalam mengeksplorasi data, membangun visualisasi, dan menarik wawasan yang dapat ditindaklanjuti.

*Let's connect and discuss data!*
