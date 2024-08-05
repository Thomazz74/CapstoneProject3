## E-Commerce Customer Churn Predictive Model with Random Forest

Perusahaan e-commerce terkemuka menghadapi tantangan untuk mengidentifikasi pelanggan yang kemungkinan besar akan churn (berhenti berbelanja) dalam waktu dekat. Kehilangan pelanggan memiliki dampak signifikan terhadap pendapatan perusahaan, mengingat biaya yang lebih tinggi untuk menarik pelanggan baru dibandingkan mempertahankan pelanggan yang sudah ada. Oleh karena itu, perusahaan ingin mengembangkan model prediktif yang dapat mendeteksi pelanggan berisiko churn sehingga dapat diambil langkah-langkah preventif seperti menawarkan promosi atau program loyalitas yang tepat untuk mempertahankan mereka.

### Penggunaan Model 
Model Prediksi ini ditujukan untuk :
- Tim Marketing
- Data Analyst
- Product Development
  
### Dataset
__[data_ecommerce_customer_churn.csv](https://drive.google.com/drive/folders/1PITb78NtK9Ra6wOkQdXCIgItZkj29Ves)__

### <b>Tujuan:</b>
- Memprediksi pelanggan yang akan churn dalam waktu dekat.
- Mengidentifikasi faktor-faktor utama yang menyebabkan churn.
- Mengembangkan strategi retensi berbasis data.

### <b>Data Understanding</b>
Data yang diberikan mencakup berbagai fitur yang dapat membantu dalam memprediksi churn pelanggan. Berikut adalah deskripsi masing-masing fitur:

1. <b>Tenure:</b> Lama waktu pelanggan bergabung dengan perusahaan.
2. <b>WarehouseToHome:</b> Jarak antara gudang dan rumah pelanggan.
3. <b>NumberOfDeviceRegistered:</b> Total perangkat yang terdaftar pada pelanggan tertentu.
4. <b>PreferedOrderCat:</b> Kategori pesanan yang paling sering dipesan pelanggan dalam bulan terakhir.
5. <b>SatisfactionScore:</b> Skor Kepuasan pelanggan terhadap layanan.
6. <b>MaritalStatus:</b> Status pernikahan pelanggan.
7. <b>NumberOfAddress:</b> Total alamat yang terdaftar pada pelanggan tertentu.
8. <b>Complaint:</b> Apakah ada keluhan yang diajukan dalam bulan terakhir.
9. <b>DaySinceLastOrder:</b> Jumlah hari sejak pesanan terakhir oleh pelanggan.
10. <b>CashbackAmount:</b> Rata-rata jumlah cashback yang diterima dalam bulan terakhir.
11. <b>Churn:</b> Indikator apakah pelanggan churn atau tidak.
