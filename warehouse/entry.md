# Stock Entry
Stock Entry adalah proses mencatat pergerakan stok antar gudang.

## Membuat Stock Entry
1. Buka menu `Stock > Stock Entry` kemudian klik tombol `Add Stock ENtry` untuk membuat stock entry baru.
   ![](/assets/stockentry_01.PNG)

2. Isikan `Stock Entry Type` dengan tipe mutasi stok. (lihat detail dibawah).
3. Jika tanggal posting bukan saat ini, centang `Edit Posting Date and Time` dan kemudan isikan `Posting Date` dan `Posting Time` sesuai dengan waktu mutasi.
   ![](/assets/stockentry_02.PNG)
4. Pada section items, masukkan item yang akan dimutasikan. Anda dapat mengakses menu ini melalui smartphone, dan melakukan scan barcode product (klik tombol barcode pada ipputan `scan barcode`). Jika anda melakukan input melalui komputer, untuk menambahkan item, klik inputan `item code` dan ketikkan nama/kode item yang akan dipilih.
   ![](/assets/stockentry_03.PNG)
5. Apabila produk yang anda pilih diatur untuk memiliki nomor batch, maka setelah anda memilih produk, akan muncul tampilan seperti dibawah. Masukkan gudang tujuan pada kolom `source warehouse`, beserta informasi batch produk pada kolom `batch entries`.
   ![](/assets/stockentry_04.PNG)
6. Masukkan jumlah barang yang akan dimutasi pada kolom `qty`
7. Tekan `save` untuk menyimpan stock entry. Pada tahap ini dokumen masih dapat diedit.
8. Tekan `Submit` untuk memproses dokumen. Setelah dokumen disubmit, maka dokumen tidak dapat diedit kembali.

## Stock Entry Type
1. Material Issue
      
      Tipe ini akan mengurangi jumlah item didalam gudang asal (megngeluarkan item dari gudang) untuk pihak didalam/diluar perusahaan. Item ini juga dapat digunakan untuk membuang item (waste/disposal)

2. Material Receipt

      Tipe ini akan menambah jumlah item didalam gudang asal (menerima item). Tipe ini juga dapat digunakan untuk menerima item ke gudang jika `purchase receipt` tidak dibuat.

3. Material Transfer

      Tipe ini digunakan untuk memindahkan stok antar gudang.

4. Material Transfer for Manufacture
   
      Tipe ini akan mengeluarkan item dari gudang dan memindahkan kedalam proses produksi. Jika tipe ini dipilih, sistem akan membuat dokumen `work order`. `Item` yang dipilih pada tipe ini berdasarkan `BOM` yang akan diproduksi.

5. Manufacture 

      Tipe ini digunakan untuk menerima produk hasil `Manufacture` (produksi)

6. Repack 

      Tipe ini digunakan untuk melakukan proses pengemasan ulang (repack)

7. Subcontract 

      Tipe ini digunakan untuk mengirimkan item ke gudang subkontraktor.

------------------
## Tautan
BOM
WORKORDER

------------------
versi 1.0.1
