# Stock Repack
Stock Repack adalah proses mengkonversi/mengemas ulang barang dari satuan besar, ke satuan stok yang lebih kecil.

**CATATAN**
Anda perlu memastikan item yang akan direpack dan item hasil repack telah terdaftar di sistem. Pastikan juga, untuk penamaan item, dan juga satuan (UOM) yang digunakan.

## Membuat Stock Entry
1. Buka menu `Stock > Stock Entry` kemudian klik tombol `Add Stock Entry` untuk membuat stock entry baru.
   ![](/assets/stockentry_01.PNG)

2. Isikan `Stock Entry Type` dengan tipe `Repack`
3. Jika tanggal posting bukan saat ini, centang `Edit Posting Date and Time` dan kemudan isikan `Posting Date` dan `Posting Time` sesuai dengan waktu mutasi.
   ![](/assets/stockentry_02.PNG)
4. Pada section items, masukkan item yang akan direpack. Anda dapat mengakses menu ini melalui smartphone, dan melakukan scan barcode product (klik tombol barcode pada ipputan `scan barcode`). Jika anda melakukan input melalui komputer, untuk menambahkan item, klik inputan `item code` dan ketikkan nama/kode item yang akan dipilih.
   ![](/assets/stockentry_03.PNG)
5. Apabila produk yang anda pilih diatur untuk memiliki nomor batch, maka setelah anda memilih produk, akan muncul tampilan seperti dibawah. Masukkan gudang tujuan pada kolom `source warehouse`, beserta informasi batch produk pada kolom `batch entries`.
   ![](/assets/stockentry_04.PNG)
6. Pada section `items` masukkan juga warehouse asal `source warehouse`, yakni gudang dimana item diambil. kemudian tambahkan kolom baru, masukkan item hasil repack pada `item code`, kemudian pada input `target warehouse`, masukkan target dimana gudang akan menyimpan hasil item repack.
   ![](/assets/stockentry_05.PNG)
6. Masukkan jumlah barang yang akan dimutasi pada kolom `qty`
7. Tekan `save` untuk menyimpan stock entry. Pada tahap ini dokumen masih dapat diedit.
8. Tekan `Submit` untuk memproses dokumen. Setelah dokumen disubmit, maka dokumen tidak dapat diedit kembali.

------------------
## Tautan
BOM
WORKORDER

------------------
versi 1.0.0
