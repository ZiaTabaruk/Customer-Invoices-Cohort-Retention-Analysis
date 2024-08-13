# Cohort Retention Analysis

![image.png](attachment:image.png)

## Latar Belakang

Pengelolaan pembayaran invoice merupakan bagian penting dari operasional keuangan perusahaan. Dalam bisnis, pengelolaan cash flow dan arus kas sangat penting untuk memastikan kelancaran operasi dan kesehatan keuangan perusahaan. Mengetahui kapan pembayaran invoice akan dilakukan dapat membantu perusahaan dalam merencanakan cash flow, mengoptimalkan proses penagihan, dan mengurangi risiko piutang tak tertagih. 

## Rumusan Masalah

Perusahaan mengalami kesulitan dalam memprediksi tanggal pembayaran invoice, yang menyebabkan ketidakpastian dalam pengelolaan arus kas. Ketidakpastian ini dapat mempengaruhi operasional bisnis dan keputusan strategis yang bergantung pada ketersediaan dana.

## Tujuan

Tujuan perusahaan adalah untuk menganalisis retensi cohort dan mengidentifikasi tren pembelian dari waktu ke waktu. Dengan analisis ini, perusahaan berharap dapat meningkatkan akurasi prediksi pembayaran invoice dan mengoptimalkan manajemen arus kas.

## Stakeholder

Pihak Terkait:
1.	Tim Keuangan: Menggunakan prediksi tanggal pembayaran untuk mengelola arus kas dan merencanakan kebutuhan keuangan perusahaan.
2.	Tim Penjualan dan Penagihan: Mengoptimalkan proses penagihan dan mengidentifikasi pelanggan yang membutuhkan perhatian khusus.
3.	Manajemen Eksekutif: Membutuhkan laporan dan analisis untuk membuat keputusan strategis terkait manajemen arus kas dan kebijakan kredit.

## Metodologi

Analisis retensi cohort dilakukan dengan beberapa langkah berikut:
1. **Pembuatan Cohort** : Mengelompokkan pelanggan berdasarkan bulan pertama mereka melakukan transaksi.
2. **Analisis Retensi** : Menghitung jumlah pelanggan yang melakukan transaksi kembali pada bulan-bulan berikutnya.
3. **Visualisasi dengan Heatmap** : Membuat pivot table untuk visualisasi retensi cohort.
4. **Analisis Tren** : Menganalisis tren retensi dari waktu ke waktu dan mengidentifikasi pola atau anomali.

## Analisis

Dari analisis cohort retensi dan visualisasi, kita bisa mendapatkan beberapa wawasan kunci:
1. **Retensi Awal**: Tingkat retensi pada bulan pertama bervariasi antar cohort. Mengidentifikasi cohort dengan retensi awal tertinggi dapat membantu memahami faktor-faktor yang menyebabkan retensi awal yang kuat. Misalnya, kampanye pemasaran tertentu, penawaran produk, atau pengalaman pengguna pertama yang positif.

2. **Tren Penurunan Retensi**: Meskipun tingkat retensi cenderung menurun seiring waktu, tingkat penurunannya berbeda-beda untuk setiap cohort. Cohort yang menunjukkan penurunan retensi yang lebih lambat mengindikasikan adanya pelanggan yang lebih loyal. Menganalisis perilaku pelanggan dalam cohort ini dapat memberikan wawasan tentang strategi retensi yang efektif.

3. **Cohort dengan Retensi Tinggi**: Beberapa cohort menunjukkan tingkat retensi yang lebih tinggi karena pengaruh musiman atau kampanye pemasaran khusus. Analisis lebih lanjut terhadap periode waktu tertentu atau kegiatan pemasaran yang dilakukan dapat membantu mengidentifikasi faktor-faktor yang berkontribusi terhadap peningkatan retensi pada cohort tersebut.

4. **Strategi Keterlibatan Pelanggan yang Berhasil**: Cohort yang mempertahankan tingkat retensi tinggi dalam jangka waktu yang panjang menunjukkan keberhasilan strategi keterlibatan pelanggan. Strategi-strategi ini, seperti program loyalitas, interaksi pelanggan yang personal, atau layanan pelanggan yang superior, dapat diterapkan pada cohort lain untuk meningkatkan retensi secara keseluruhan.

## Kesimpulan

Analisis retensi cohort menunjukkan variasi retensi bulan pertama dan penurunan retensi yang berbeda-beda antar cohort. Beberapa cohort mempertahankan retensi tinggi karena strategi keterlibatan yang sukses seperti program loyalitas. Disarankan untuk menganalisis dan mereplikasi strategi cohort dengan retensi tinggi serta menerapkan strategi proaktif untuk cohort dengan penurunan cepat. Pemantauan dan penyesuaian berkelanjutan sangat penting untuk meningkatkan loyalitas dan profitabilitas jangka panjang.

## Dashboard Looker

[Cohort Retention Dashboard](https://lookerstudio.google.com/u/0/reporting/1196afe5-79a0-49f3-aed1-78ad9f7f04f2/page/fnj7D) untuk visualisasi menggunakan Lookerstudio
