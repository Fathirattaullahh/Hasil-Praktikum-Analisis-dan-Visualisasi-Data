# Analisis Performa Penjualan E-commerce 2023

## Business Question
Bagaimana performa penjualan e-commerce 2023 dan strategi apa yang bisa dioptimalkan?

## Data Wrangling
- Dataset: 150 transaksi, 5 kategori produk, 49 pelanggan unik
- 7 nilai Total_Sales kosong → diimputasi dengan Quantity × Price_Per_Unit
- Tidak ditemukan harga negatif

## Insights
- **Tren Bulanan**: Penjualan tertinggi di bulan Agustus
- **Korelasi**: Ad_Budget hampir tidak berkorelasi dengan Total_Sales
- **Underperformer**: Produk harga tinggi dengan quantity rendah ditemukan di semua kategori
- **RFM**: 14 pelanggan Champion, 10 pelanggan At Risk perlu win-back campaign
- **Efisiensi**: Electronics paling efisien (1.44x ROI), Gadget tidak menguntungkan (0.95x)
- **Hipotesis**: p-value = 0.71 → iklan tidak terbukti signifikan meningkatkan penjualan

## Recommendation
1. Fokus anggaran iklan ke kategori Electronics
2. Kurangi / evaluasi iklan untuk kategori Gadget
3. Kirim voucher loyalitas ke 14 pelanggan Champion
4. Buat kampanye re-engagement untuk 10 pelanggan At Risk
5. Review strategi harga produk underperformer
