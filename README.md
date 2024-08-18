Dataset yang digunakan merupakan data dari DQLab Mart. Terdapat 4 tabel di dalam database tersebut.

1. Tabel `ms_pelanggan` berisi tentang identitas pelanggan, dengan detail atribut/kolom sebagai berikut:
   * `no_urut` : row pada tabel
   * `kode_pelanggan` : kode setiap pelanggan yang bertransaksi
   * `nama_pelanggan` : nama dari pelanggan yang bertransaksi
   * `alamat` : tempat pelanggan tinggal
    
2. Tabel `ms_products` berisi tentang detail pada produk, dengan detail atribut/kolom sebagai berikut:
   * `no_urut` : row pada tabel
   * `kode_produk` : kode yang tertera pada produk
   * `nama_produk` : nama produk yang diperjualbelikan
   * `harga` : harga pada produk yang diperjualbelikan
    
3. Tabel `tr_penjualan` berisi tentang transaksi penjualan, dengan detail atribut/kolom sebagai berikut:
   * `kode_transaksi` : kode transaksi yang dilakukan oleh pelanggan/customer
   * `kode_pelanggan` : kode setiap pelanggan yang bertransaksi
   * `tanggal_transaksi` : waktu dimana transaksi dilakukan
    
4. Tabel `tr_penjualan_detail` berisi tentang transaksi penjualan secara detail, dengan detail atribut/kolom sebagai berikut:
   * `kode_transaksi` : kode transaksi yang dilakukan oleh pelanggan/customer
   * `kode_produk` : kode yang tertera pada produk
   * `qty` :  jumlah kuantitas produk yang tersedia
   * `harga_satuan` : harga per produk/kuantitas
