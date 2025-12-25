# SQL Portfolio: Customer Transactions Analysis

## Deskripsi
Project ini bertujuan untuk menganalisis data transaksi pelanggan menggunakan SQL.  
Analisis dilakukan untuk memahami pola pembelian, perilaku pelanggan, dampak diskon, serta segmentasi pelanggan berdasarkan karakteristik tertentu.

Project ini dibuat sebagai bagian dari **portfolio SQL** untuk menunjukkan kemampuan analisis data menggunakan query SQL dasar hingga menengah.

---

## About the Data
Dataset berisi data transaksi pelanggan dengan struktur tabel sebagai berikut:

**Table Name:** customer_transactions_final  

Kolom utama:
- customer_id : ID unik pelanggan  
- age, age_group : usia dan kelompok usia pelanggan  
- gender : jenis kelamin pelanggan  
- item_purchased : barang yang dibeli  
- category : kategori barang  
- purchase_amount : nilai pembelian  
- location : lokasi pelanggan  
- season : musim pembelian  
- review_rating : rating pelanggan  
- subscription_status : status berlangganan  
- discount_applied : status diskon  
- previous_purchases : jumlah pembelian sebelumnya  
- payment_method : metode pembayaran  
- frequency_of_purchases_days : jarak hari antar pembelian  

---

## Use Case / Business Questions
Analisis dalam project ini menjawab beberapa pertanyaan bisnis, antara lain:
1. Berapa total transaksi dan total pendapatan?
2. Kategori dan produk apa yang paling laris?
3. Apakah pelanggan berlangganan berbelanja lebih banyak?
4. Bagaimana perilaku pelanggan terhadap diskon?
5. Segmentasi pelanggan berdasarkan usia dan status langganan
6. Identifikasi pelanggan bernilai tinggi dan risiko churn

---

## Analysis Overview
Analisis dibagi menjadi beberapa bagian:
- Revenue & Transaction Overview  
- Product & Category Analysis  
- Customer & Segment Analysis  
- Discount & Behavior Analysis  
- Advanced Analysis (CLV sederhana, churn risk, customer satisfaction)

---

## Key Insights (Contoh)
- Kategori tertentu memberikan kontribusi pendapatan terbesar
- Pelanggan berlangganan memiliki rata-rata pembelian lebih tinggi
- Diskon meningkatkan frekuensi pembelian, namun tidak selalu meningkatkan nilai transaksi
- Terdapat pelanggan bernilai tinggi dengan tingkat kepuasan rendah

---

## Tools
- SQL (Window Function, CTE, Aggregation)
- Database: SQLite / PostgreSQL (opsional, sesuaikan)

---

## Notes
Project ini fokus pada eksplorasi data menggunakan SQL tanpa visualisasi lanjutan.  
Hasil query dapat digunakan sebagai dasar untuk dashboard atau analisis lanjutan.

---
