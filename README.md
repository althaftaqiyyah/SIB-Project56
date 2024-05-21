# SIB-Project 6

#### Project ETL sederhana melakukan migrasi Tabel dari Database Marketplace ke Data Warehouse menggunakan Hadoop 

### Background Project 

Projek ini merupakan projek lanjutan dari projek ke 3, yaitu mengenai pembuatan batch processing untuk data migrasi. Pada project ini, kita membuat tambahan task untuk membuat tabel data mart yang nantinya akan digunakan oleh data analis untuk membuat dashboard report order setiap bulannya. Proses yang dilakukan tidak boleh lebih dari 1 jam. Oleh karena itu, pada projek ini kita akan menggunakan HDFS agar proses migrasi datanya lebih cepat. 

### Goal Project

Membuat tabel data mart `total_orders_based_on_month` dengan kolom berupa `month` dan `total_orders`
