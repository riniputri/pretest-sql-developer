# Soal Test SQL Developer

Berikut adalah soal/pertanyaan yang perlu dijawab oleh kandidat SQL Developer

## knowledge base

1.  Tuliskan perintah untuk membuat tabel dengan nama tabel1, dengan column sbb:
    - id , dengan tipe data berupa bilangan bulat
    - fullname , dengan tipe data karakter sebanyak 100 karakter
    - email , dengan tipe data karakter sebanyak 50 karakter

2.  Jelaskan mengenai fungsi PrimaryKey, ForeignKey, Index dan Unique Constraint dalam suatu tabel


3.  Jelaskan mengenai perbedaan output yang dihasilkan dari 2 query dibawah ini:
    
    SELECT * FROM tabel1 INNER JOIN tabel2 ON tabel1.id = tabel2.id;
    
    dan
    
    SELECT * FROM tabel1 LEFT JOIN tabel2 ON tabel1.id = tabel2.id;

    
4.  Dari soal nomor 1 (tabel1), buat sebuah perintah query dengan menggunakan sub-query, untuk menampilkan data email yang menggunakan gmail
 
 
5.  Jelaskan perbedaan output dari procedure dan function di Postgres  

## Test Case

 a.  Buat tabel-tabel di Postgresql untuk suatu aplikasi pembelian, yang melibatkan 3 informasi sbb:
        - Data customer/pembeli
        - Data product/barang yang dijual
        - Data order/pembelian barang

b.  Buat query dengan Postgresql untuk informasi sebagai berikut:
        - Daftar seluruh pembelian/order beserta produk yang dibelinya, customer yang membelinya, nilai total & jumlah product yang dibelinya, waktu pembeliannya
        - Total nilai pembelian per customer per bulan
        - Data produk dengan 3 penjualan terbesar per bulan

