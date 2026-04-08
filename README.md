# Sephora Skincare Data Analysis: Uncovering Customer Preferences & Chemical Ingredient Trends

## Project Overview
Proyek ini menganalisis data produk perawatan kulit dan kosmetik dari Sephora untuk melihat lebih dalam bagaimana hubungan antara harga, rating pengguna, merek, dan komposisi bahan kimia dalam produk. Fokus utamanya adalah menggali wawasan yang relavan bagi pengembang produk kosmetik dan pelaku bisnis kecantikan, mulai dari strategi harga, positioning merek, sampai tren fprmulasi bahan aktif yang sebenarnya disukai konsumen.

## Tools & Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation & Cleaning), Matplotlib & Seaborn (Data Visualization)
* **Environment:** Jupyter Notebook / Google Colab

## Business Questions
1. Apakah produk kosmetik dengan harga yang lebih mahal cenderung memiliki *rating* yang lebih baik?
2. *Brand* apa saja yang konsisten menghasilkan produk dengan *rating* tinggi (>= 4.5)?
3. Bahan aktif kimia apa yang paling banyak muncul pada produk dengan *rating* tertinggi, khususnya untuk kategori *skincare*?

## Key Insights
BRingkasa temuan dari *Exploratory Data Analysis (EDA)*:

* **1. Harga mahal tidak selalu berbanding lurus dengan kepuasan pelanggan**
*   Sebagian besar produk dengan *rating* tinggi justru berda di bawah harga 100 USD. Korelasi antara harga dan rating terlihat lemah, ada beberapa produk dengan harga di atas 300 USD tetapi memiliki tingkat kepuasan yang relatif rendah.

* **2. In-House brand kuat di volume, sementara luxury brand kuat di persepsi kualitas**
* SEPHORA COLLECTION sebagai *in-house brand* mendominasi jumlah produk dengan *rating* tinggi berkat variasi produk yang luas dan harga yang lebih terjangkau. Di sisi lain, merek-merek *luxury* seperti Dior, Yves Saint Laurent, dan Armani Beauty tetap mempertahankan citra kualitas tinggi dan loyalitas pelanggan meskipun berada di segmen harga premium.

* **3. Produk dengan formulasi fokus hidrasi dan skin barrier cenderung lebih disukai**
* Dari sisi komposisi kimia, bahan aktif yang paling sering muncul pada produk *skincare* berating tinggi bukanlah eksfoliator "keras", melainkan agen hidrasi dan penenang kulit seperti **glycerin, penthenol (vitamin B5), dan squalane**. Ini mengindikasikan preferensi konsumen terhadap produk dengan formulasi yang lembut, menenangkan, dan mendukung *skin barrier*.


## Repository Structure
* `Sephora_Skincare_EDA.ipynb`: notebook utama berisi alur analisis, mulai hari data cleaning hingga visualisasi.
* `product_info.csv`:dataset berisi informasi harga, *rating*, merek, dan komposisi bahan produk.

## About the Author
**Nazwa** 
*Undergraduate Chemistry Student – Institut Teknologi Bandung (ITB) | Aspiring Data Analyst* 
Latar belakang kimia membantu dalam membaca komposisi bahan dan memahami peran masing-masing senyawa, sedangkan analisis data digunakan untuk mengubah kumpulan angka dan teks menjadi insight yang bisa dipakai dalam konteks bisnis maupun pengembangan produk. Tertarik pada persilangan antara sains, data, dan industri kecantikan.

