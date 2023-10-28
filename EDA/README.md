# Dataset
Dataset ini menceritakan tentang campaign produk deposito yang dilakukan oleh suatu bank di portuguese, dimana strategi campaign yang dilakukan untuk _me-reach-out_ customer menggunakan Telephone, sayangnya karena keterbatasan pengetahuan bank ini melakukan campaign secara buta sehingga menyebabkan biaya campaign yang tinggi.

## Goal
Kita sebagai data scientist diminta untuk meningkatkan Efisiensi marketing dengan cara menargetkan customer yang paling potensial

# EDA
Ini merupakan tahap exploratory data analysis, kita membagi tiga tahap analisa yaitu:
- Descriptive Statistics : mencari missing value, kesesuaian tipe data, mencari nilai summary yang agak aneh
- Univariate Analysis : mencari insight berdasarkan 1 variabel, melihat apakah data terdistribusi normal, membagia data menjadi 2 category
- Multivariate Analysis : Mencari insight berdasarkan 2 atau lebih variabel, melakukan uji testing menggunakan Chi-Square

## Lampiran
1. hasil preview kelompok kami bisa di klik disini [preview](https://github.com/jundanaa/PROJECT_RAKAMIN.git)


2. untuk preview syntax hasil pengerjaan dapat di akses [disini](https://drive.google.com/drive/folders/12v_3eg92yPVeIXWiRP1pt1psMCT4Jpg3?usp=share_link)

## Insight
**Business Insight**
1. Customer yang memiliki loan dan tidak memiliki housing kebanyakan tidak deposit sedangkan customer yang tidak memiliki tanggungan apa apa (loan &housing) cukup banyak melakukan deposito dibanding orang yang memiliki tanggungan namun, meskipun begitu tetap lebih banyak orang yang tidak melakukan deposito
2. Customer yang memiliki kredit macet banyak yang tidak melakukan deposito
3. Orang yang berstatus married memiliki durasi waktu telephone yang lebih banyak tetapi orang yang melakukan deposito lebih banyak dari yang single dibandingkan married dan divorced
4. Diketahui persebaran status marital customer untuk yang Married dan Single tersebar secara merata di umur < 20 - 65 tahun dengan balance sekitar 0 - 20rb

**Rekomendasi Bisnis**
1. Mengutamakan target marketing pada  konsumen yang tidak memiliki housing dan loan
2. Perusahaan perlu melakukan evaluasi dalam memahami mengapa banyaknya jumlah campaign yang diterima tidak sukses untuk mengajak orang melakukan deposito
3. Kita dapat memberikan campaign yang berbeda untuk setiap jenjang status, misal untuk customer di umur 15 - 30 tahun dan belum menikah bisa diberikan penawaran berupa deposito rendah biaya dengan tipe deposito medium - long term deposits(5 - 10 tahun)
untuk umur 30 - 55 tahun, dapat diberikan penawaran berupa deposito biaya menengah dengan tipe deposito medium - short term deposit(<5 tahun)
