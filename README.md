# Customer Invoices Cohort Retention Analysis

![image](https://github.com/user-attachments/assets/4e2cb00c-5028-4724-8281-0e423ca34e5c)


## Latar Belakang

Pengelolaan pembayaran invoice merupakan bagian penting dari operasional keuangan perusahaan. Dalam bisnis, pemahaman tentang pola pembayaran pelanggan sangat penting untuk memastikan kelancaran operasi dan kesehatan keuangan perusahaan. Analisis retensi cohort adalah salah satu cara untuk memahami perilaku pelanggan dari waktu ke waktu, sehingga perusahaan dapat mengidentifikasi tren, mengoptimalkan strategi penagihan, dan meningkatkan retensi pelanggan.

## Stakeholder

**Tim Eksekutif Bisnis:** Tim ini bertanggung jawab untuk pengambilan keputusan strategis dalam perusahaan. Mereka memerlukan informasi mengenai perilaku pelanggan untuk mengidentifikasi segmen pelanggan yang setia dan memahami faktor-faktor yang mempengaruhi retensi pelanggan. Dengan wawasan dari analisis cohort, tim ini dapat menentukan strategi pemasaran yang tepat, kebijakan penagihan yang efektif, dan inisiatif loyalitas untuk meningkatkan retensi pelanggan dan memaksimalkan pendapatan.

## Rumusan Masalah

Perusahaan kesulitan untuk memahami pola pembayaran pelanggan dari waktu ke waktu. Ketidakpastian dalam retensi pelanggan ini dapat mempengaruhi perencanaan keuangan dan operasional perusahaan, serta menghambat pengambilan keputusan strategis terkait pengelolaan hubungan pelanggan.

## Tujuan

Tujuan perusahaan adalah untuk menganalisis tingkat retensi cohort pelanggan dan mengidentifikasi pola retensi dari waktu ke waktu. Dengan analisis ini, perusahaan dapat:

1. Memahami tingkat retensi pelanggan pada setiap cohort bulan ke bulan.
2. Mengembangkan strategi yang lebih efektif untuk mempertahankan pelanggan berdasarkan wawasan dari analisis retensi ini.


## Analisis

Analisis retensi cohort dilakukan dengan beberapa langkah berikut:

1. **Pembuatan Cohort:** Mengelompokkan pelanggan berdasarkan bulan pertama mereka melakukan transaksi. Contoh: semua pelanggan yang pertama kali melakukan transaksi pada Januari 2020 dimasukkan ke dalam cohort Januari 2020.
2. **Analisis Retensi:** Menghitung jumlah pelanggan dari setiap cohort yang melakukan transaksi pada bulan-bulan berikutnya. Misalnya, berapa banyak pelanggan cohort Januari 2020 yang melakukan pembayaran kembali pada Februari 2020, Maret 2020, dan seterusnya.
3. **Visualisasi dengan Heatmap:** Membuat pivot table untuk visualisasi retensi cohort dalam bentuk heatmap. Ini akan menunjukkan proporsi pelanggan yang tetap aktif dari setiap cohort pada bulan-bulan berikutnya.
4. **Analisis Tren:** Menganalisis tren retensi dari waktu ke waktu dan mengidentifikasi pola atau anomali. Misalnya, melihat apakah ada penurunan signifikan pada retensi setelah beberapa bulan, atau apakah ada pola retensi yang konsisten di beberapa cohort.

## Kesimpulan

1. **Cohort Januari 2019 (Cohort 2019-01)**:  
   - Cohort ini menunjukkan performa retensi tertinggi, dengan **72% retensi pada bulan pertama**. Pada bulan ke-10, angka ini masih bertahan di **59.1%**, menjadikannya cohort dengan retensi terbaik. Kesuksesan ini dapat disebabkan oleh strategi pemasaran yang sangat efektif pada awal tahun 2019, mungkin melalui peluncuran promosi besar atau produk yang sangat diminati.

2. **Cohort Februari 2019 (Cohort 2019-02)**:  
   - Cohort ini menunjukkan penurunan yang signifikan, dengan hanya **36.44% retensi pada bulan pertama** dan **35.2% pada bulan kedua**. Penurunan ini lebih drastis dibandingkan Januari 2019, menunjukkan adanya kemungkinan perubahan strategi pemasaran atau penurunan efektivitas layanan yang mempengaruhi ketertarikan pelanggan pada produk di bulan ini.

3. **Cohort Maret 2019 (Cohort 2019-03)**:  
   - Cohort ini memulai dengan **39.5% retensi di bulan pertama** tetapi mengalami penurunan yang stabil, dengan **9.2% retensi di bulan ke-10**. Ini menunjukkan adanya kehilangan pelanggan yang lebih cepat dibanding cohort Januari, yang bisa dikaitkan dengan perubahan pola permintaan atau penurunan kualitas pengalaman pelanggan.

4. **Cohort dengan Penurunan Drastis (2019-04 hingga 2020-04)**:  
   - Cohort ini secara konsisten menunjukkan retensi yang rendah setelah bulan kedua, dengan beberapa cohort bahkan mencapai **0% retensi** pada bulan ke-3 dan ke-4. Misalnya, **Cohort April 2019 (Cohort 2019-04)** hanya mempertahankan **9.0% pelanggan di bulan ke-5**. Kemungkinan besar, faktor seperti perubahan musiman dalam permintaan atau promosi yang kurang menarik mempengaruhi cohort-cohort ini.

## Rekomendasi

1. **Pelajari Keberhasilan Cohort Januari 2019:**
   - Cohort Januari 2019 memiliki tingkat retensi yang sangat tinggi. Penting untuk melakukan analisis mendalam terhadap elemen-elemen spesifik yang membuat cohort ini berhasil, seperti promosi, kampanye, atau produk yang ditawarkan pada periode tersebut. Data ini bisa membantu untuk mereplikasi kesuksesan ini di cohort-cohort berikutnya.

2. **Evaluasi Cohort Februari dan Maret 2019:**
   - Retensi menurun signifikan pada cohort Februari dan Maret 2019. Perusahaan perlu menganalisis apakah ada perubahan dalam strategi pemasaran atau produk pada periode tersebut yang mungkin mengakibatkan penurunan retensi. Analisis lebih lanjut dapat membantu memperbaiki kelemahan dalam strategi pemasaran.

3. **Perbaikan Strategi untuk Cohort dengan Penurunan Cepat (2019-04 hingga 2020-04):**
   - Cohort ini menunjukkan penurunan yang sangat cepat. Perusahaan harus mengidentifikasi penyebab utama dari penurunan ini, seperti kurangnya follow-up setelah pembelian pertama, atau tidak adanya penawaran yang menarik di bulan-bulan berikutnya. Mengimplementasikan program loyalitas atau penawaran diskon yang lebih relevan dapat membantu memperpanjang retensi pelanggan di cohort-cohort ini.

4. **Pemantauan dan Penyesuaian Berkelanjutan:**
   - Retensi pelanggan adalah metrik yang dinamis dan memerlukan pemantauan serta penyesuaian terus-menerus. Dengan pemantauan berkelanjutan dan penyesuaian strategi berdasarkan data terbaru, perusahaan dapat terus meningkatkan loyalitas pelanggan dan profitabilitas jangka panjang.

Dengan analisis mendalam dan rekomendasi yang spesifik, perusahaan dapat memahami faktor-faktor yang menyebabkan penurunan atau peningkatan retensi di berbagai cohort. Dengan menggunakan data ini, perusahaan dapat menyesuaikan strategi pemasaran dan retensi yang lebih efektif, serta menerapkan pelajaran dari cohort sukses untuk meningkatkan kinerja cohort-cohort lainnya.

## Dashboard Looker

[Cohort Retention Dashboard](https://lookerstudio.google.com/reporting/1196afe5-79a0-49f3-aed1-78ad9f7f04f2) untuk visualisasi menggunakan Lookerstudio
