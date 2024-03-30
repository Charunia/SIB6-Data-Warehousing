# SIB6-Data-Warehousing
Data Warehousing at Dibimbing.id currently work in OOP Python
# Task 1
BASIC OPP Buatlah class MarketingDataETL yang memiliki tiga metode:
extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv)
transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)
store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFramet.
# Answer Task 1
extract data csv menghasikan output extract file.
transform data csv menghasilkan output data yang telah dibersihkan (cleaning) formatnya yaitu tanggal dan nilai kosong.
store data csv menghasilkan output data yang telah di transform akan disimpan dalam store.
# Task 2
INHERITANCE & POLYMORPHISM Gunakan inheritance untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL.
Tambahkan metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli).
Demonstrasi polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.
# Answer Task 2
Inheritance memberikan output tambahan kolom berupa segment_customers yang mengatur kelas dari para konsumen dalam hal ini berdasarkan kriteria pengeluaran total.
-Jika pengeluaran total > 500 maka dikategorikan dalam kelas A.
-Jika pengeluaran total > 200 dan pengeluaran total < 500 maka dikategorikan dalam kelas B.
-Jika pengeluaran total > 0 dan pengeluaran total < 200 maka dikategorikan dalam kelas C.
-Seebihnya dikategorikan tidak diketahui.
Polymorphism memberikan output berupa cara etl yang berbeda dengan nama yang sama dalam menambahkan logika segmentasi_pelanggan.
