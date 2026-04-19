# 🧺 Analisis Penjualan Ritel dan Segmentasi Pelanggan 📊

---

## 🗂 Dataset

Dataset yang digunakan merupakan data **Retail Sales** yang mencakup penjualan **Furniture dan Office Supplies** serta informasi demografi pelanggan. Dataset ini diperoleh dari Kaggle dan terdiri dari dua tabel utama, yaitu:

- Tabel **Sales**: 29.999 baris dan 14 kolom  
- Tabel **Customer**: 18.804 baris dan 7 kolom  

Project ini melakukan **Exploratory Data Analysis (EDA)** dan **analisis RFM (Recency, Frequency, Monetary)** untuk memperoleh insight terkait pola penjualan, memahami perilaku pelanggan, serta mendukung pengambilan keputusan bisnis berbasis data.

Dataset yang digunakan tersedia di repositori:  
[🔗 Dataset](https://github.com/Arfi3/Furniture-Office-Supplies-Customer-Segmentation/tree/main/Dataset)

---

## 🧾 Atribut

### Sales:
- SalesOrderNumber  
- OrderDate  
- DeliveryDate  
- ShipMode  
- CustomerKey  
- ProductKey  
- CategoryName  
- SubcategoryName  
- ProductName  
- UnitPrice  
- OrderQuantity  
- Discount %  
- ShippingCost  
- OrderPriority  

### Customer:
- CustomerKey  
- Customer  
- StateName  
- Country  
- Region  
- Market  
- BusinessType  

---

## 🛠 Tools & Libraries

- **Power BI** (data visualization & dashboard development)  
- **Python**:
  - Pandas (data cleaning, processing, and customer segmentation)  

---

## 📌 Exploratory Data Analysis (EDA)

1. Menganalisis tren penjualan dari waktu ke waktu  
2. Mengeksplorasi penjualan berdasarkan kategori dan subkategori produk  
3. Mengidentifikasi kategori dengan kontribusi penjualan tertinggi  
4. Menganalisis aspek pengiriman (mode, prioritas, dan biaya)  
5. Mengeksplorasi karakteristik pelanggan (market, negara, dan tipe bisnis)  

---

## 🙌 Segmentasi Customer 

Berdasarkan hasil analisis, diperoleh **10 pelanggan teratas** dengan kontribusi tertinggi berdasarkan total order, jumlah barang dibeli, dan total nilai pembelian. Informasi ini dapat dimanfaatkan untuk menyusun strategi seperti program membership guna meningkatkan **retensi pelanggan** dan **penjualan**.

Segmentasi pelanggan dilakukan dengan dua pendekatan:

### 🔹 1. Metode Statistik (qcut)
Klasifikasi dilakukan berdasarkan:
- Frekuensi pembelian  
- Volume pembelian  
- Nilai pembelian  

Hasil segmentasi:
- **Order Segment**: Silver, Gold, Platinum  
- **Quantity Segment**: Regular, Champion, King  
- **Sales Segment**: Prime, Elite, Diamond  

---

### 🔹 2. Metode RFM (Recency, Frequency, Monetary)

Metode RFM digunakan untuk mengelompokkan pelanggan berdasarkan perilaku pembelian:

- **Recency (R)** → waktu sejak transaksi terakhir  
- **Frequency (F)** → jumlah transaksi  
- **Monetary (M)** → total nilai pembelian  

Segmentasi akhir:
- **Low** → pelanggan kurang aktif  
- **Medium** → pelanggan cukup aktif  
- **High** → pelanggan paling bernilai  

---

## 🚀 Let’s Connect!

If you’re interested in data science and analytics, feel free to connect or reach out:  
[LinkedIn](https://www.linkedin.com/in/arfinadhifahananti/)
