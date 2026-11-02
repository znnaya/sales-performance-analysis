# 📊 Sales Performance & Marketing Channel Analysis (2011)

## 📌 Project Overview

Proyek ini merupakan **Mini Portfolio** yang disusun sebagai bagian dari program **Mini Bootcamp Data Analytics (DSF 55.0) oleh Dibimbing.id**. 

Proyek ini bertujuan untuk menganalisis performa penjualan dan efektivitas channel periklanan (*Ads*) pada data transaksi perusahaan sepanjang tahun 2011. Dashboard interaktif ini dirancang untuk membantu tim **Sales & Marketing** dalam memantau tren penjualan, mengidentifikasi segmen pelanggan potensial (*top spenders*), serta mengoptimalkan alokasi anggaran iklan berdasarkan hasil konversi.

## 🛠️ Tools & Technologies

* **Google Looker Studio (Data Studio):** Pembuatan Dashboard Interaktif & Visualisasi Data
* **Python (Google Colab / Pandas):** Data Cleaning, Processing, & Exploratory Data Analysis (EDA)
* **Microsoft Excel:** Format Data Prep & Spreadsheet Processing

## 📁 Dataset Summary

* **Total Rows:** 198 baris transaksi
* **Total Columns:** 11 fitur (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, InvoiceMonth, UnitPrice, CustomerID, Country, CustomerDate, Source)
* **Data Quality:** 100% Complete (*Zero Missing Values*)

## 🎯 Business Problems & Questions

Dashboard ini dibangun untuk menjawab pertanyaan bisnis utama berikut:

1. **Bagaimana tren volume penjualan perusahaan sepanjang tahun 2011?**
2. **Channel iklan mana yang memberikan kontribusi penjualan terbesar?**
3. **Siapa saja pelanggan yang paling kontributif (*Top Spenders*)?**
4. **Bagaimana sebaran penjualan secara geografis dan seberapa dominan pasar utama?**

## 📈 Key Insights & Analysis Findings

### 1. Performa Channel Iklan (*Ads Performance*)
* **Instagram Ads** merupakan kontributor penjualan terbesar secara global dengan porsi **20.6%**, disusul oleh **Paid Ads (16.3%)** dan **Retargeting (14.3%)**.
* **Facebook Ads** memberikan kontribusi terendah (**8.7%**), menandakan perlunya evaluasi ulang strategi periklanan di platform tersebut.

### 2. Tren Penjualan & Musiman (*Seasonality*)
* Terjadi lonjakan penjualan drastis (*peak performance*) pada **Mei 2011**.
* Penurunan penjualan yang cukup tajam terjadi pada **Maret** dan **Juli 2011**.

### 3. Performa Pasar & Geografis (UK vs Global)
* **Pasar Utama UK:** United Kingdom (UK) mencatatkan volume penjualan tertinggi yaitu **80.1% dari total penjualan global** (2,907 dari 3,629) serta mencakup **86.9% basis pelanggan**.
* **Perilaku Iklan di UK:** Berbeda dari pasar global yang dipimpin Instagram Ads, konsumen di UK merespon hampir seimbang antara **Instagram Ads (19.9%)** dan **Paid Ads (19.8%)**, diikuti oleh **Criteo (15.8%)**.

## 💡 Strategic Business Recommendations

* **Evaluasi Lonjakan Penjualan:** Mengidentifikasi faktor pemicu utama (*campaign/promo*) pada penjualan puncak Mei 2011 untuk diterapkan kembali pada kuartal berikutnya.
* **Optimasi Marketing UK:** Memaksimalkan pasar UK sebagai sumber penjualan utama lewat *Customer Loyalty Program* berbasis kombinasi channel Instagram Ads + Paid Ads.
* **Strategi Pengembangan Pasar Baru:** Meskipun UK menjadi pasar dengan angka penjualan tertinggi saat ini, perusahaan disarankan untuk memperkuat penetrasi ke negara-negara lain yang tercatat pada peta global. Langkah ini penting untuk **menyebarkan sumber penjualan** agar performa bisnis tetap stabil dan tidak hanya bergantung pada satu negara saja.

## 📁 Repository Structure

```
.
├── sales_performance_2011.csv      # Dataset
├── Sales_Performance_Analysis.pdf  # Slide Presentasi Portofolio (PPT Export)
└── README.md                       # Dokumentasi Proyek
```

## 👩‍💻 Author

**Zainnaya Putri Diyanti**  
*Participant of Dibimbing.id - Data Analytics Mini Bootcamp (DSF 55.0)*

* ✉️ **Email:** putrizainnaya@gmail.com
* 💼 **LinkedIn:** [linkedin.com/in/zainnayaputri](https://www.linkedin.com/in/zainnayaputri/)
