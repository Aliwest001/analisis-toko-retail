		Analisis Penjualan Toko Retail (MySQL dan Power BI)



Proyek analisis data end-to-end: dari menyiapkan basis data relasional, menganalisisnya dengan SQL, sampai menyajikan hasilnya dalam dashboard Power BI.
Proyek ini dibuat sebagai latihan pribadi untuk membangun alur kerja seorang data analyst.

Catatan: dataset yang digunakan dibuat oleh Claude untuk keperluan project analisis data mandiri, jadi seluruh data bersifat sintetis, bukan data perusahaan sungguhan.


PERTANYAAN BISNIS

  1. Berapa revenue, profit, dan margin toko. Dan bagaimana perubahannya dari 2024 ke 2025?
  2. Kategori, produk, dan cabang mana yang paling menentukan performa penjualan?
  3. Apakah produk yang paling laris juga yang paling menguntungkan?
  4. Bagaimana tren penjualan bulanan, dan siapa pelanggan dengan belanja terbesar?


ALUR ANALISIS

  1. Data cleansing	: pengecekan jumlah baris, duplikat, dan missing value
  2. KPI		: total revenue, jumlah transaksi, rata-rata nilai transaksi (AOV), growth revenue rate YoY, dan margin
  3. EDA		: tren revenue bulanan, peringkat pelanggan menurut total belanja, kinerja kategori, kinerja produk, kinerja cabang, perubahan harga jual
  4. Visualisasi	: View diimpor ke Power BI, lalu dibuat dashboard.


TEMUAN UTAMA

  1. Revenue tumbuh 16,04% dari 2024 ke 2025, didorong kenaikan jumlah transaksi (+15%) dengan nilai transaksi rata-rata yang relatif stabil.
  2. Kenaikan margin hampir seluruhnya berasal dari harga jual yang naik sekitar 4%, sementara modal produk dalam data bersifat tetap. Jadi kenaikan ini
     bukan bukti perbaikan efisiensi.
  3. Revenue terbesar tidak sama dengan margin terbesar. Elektronik menyumbang sekitar 33% revenue dengan margin 29–32%, sedangkan Fashion menyumbang
     sekitar 24% revenue dengan margin tertinggi (43–45%)
  4. Produk terlaris belum tentu paling menguntungkan. Makanan & Minuman paling banyak terjual menurut unit, tetapi marginnya paling rendah (21–23%).
     Printer Inkjet berada di peringkat ke-31 menurut jumlah unit, tetapi ke-1 menurut revenue dan profit.
  5. Toko Pusat Jakarta menyumbang sekitar 44% revenue, sebagian karena melayani pelanggan dari empat kota (Jakarta, Bekasi, Tangerang, Depok),
     bukan semata karena performanya.
  6. 275 dari 300 pelanggan terdaftar pernah melakukan transaksi yang selesai. Pola musiman terlihat jelas: revenue memuncak di bulan Desember dan
     meningkat di sekitar Maret dan April.


Terimakasih, salam hangat.
