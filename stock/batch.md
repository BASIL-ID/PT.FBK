# Batch
**PENTING** 
Item yang sudah memiliki transaksi stok (seperti purchase receipt) tidak dapat lagi diedit informasi batch nya. Jadi pastikan untuk melakukan pengaturan batch sebelum memproses transaksi item

Apabila transaksi sudah terlanjur dibuat maka yang dapat dilakukan:
- batalkan semua transaksi stock terkait item yang bermasalah
- hapus item yang bermasalah
- buat item baru dan atur dengan pengaturan batch yang sesuai
- buat kembali transaksi stock yang sudah dibatalkan sebelumnya


## Menambahkan Batch Pada Item Baru
1. Pada saat pembuatan `purchase receipt`, pada section `items` klik edit.
   ![](/assets/batch04.PNG)

2. Isikan informasi batch pada section `warehouse and reference` pada kolom `batch no`, apabila informasi batch blm dibuat sebelumnya, klik untuk membuat baru.
   ![](/assets/batch05.PNG)

3. Isikan informasi batch. Masukkan kode batch dengan format `KODE-TANGGAL` pada `batch id`, isikan `item` dengan produk yang akan diberikan informasi batch, masukkan informasi tanggal manufaktur produk (bila ada) pada kolom `Manufacturing date`, kemudian masukkan satuan produk pada `UOMS`, dan terakhir masukkan informasi kadaluarsa produk pada `expiry date`   
   ![](/assets/batch03.PNG)

   *Penting*  untuk format tanggal gunakan format sebagai berikut : TAHUN kemudian BULAN dan TANGGAL. Contoh: 1 desember 2022 -> 20221201

4. Tekan `save` untuk menyimpan batch baru

5. Pada halaman `Purchase receipt` tekan tombol `save` untuk menyimpan, kemudian tekan `submit` apabila sudah sesuai

## Menambahkan Batch Pada Item Yang Sudah Ada
Untuk item yang sudah ada, perlu di update dahulu pengaturan item terkait `batch no`.

1. Buka item yang akan diedit, kemudian pada section `inventory > Serial Nos and Batches` centang opsi berikut

   ![](/assets/batch02.PNG)

2. Tekan `save` untuk menyimpan

Buat informasi Batch dari item
1. Buka menu batch `stock > batch > add batch`
2. Isikan informasi batch. Masukkan kode batch dengan format `KODE-TANGGAL` pada `batch id`, isikan `item` dengan produk yang akan diberikan informasi batch, masukkan informasi tanggal manufaktur produk (bila ada) pada kolom `Manufacturing date`, kemudian masukkan satuan produk pada `UOMS`, dan terakhir masukkan informasi kadaluarsa produk pada `expiry date`   
   ![](/assets/batch03.PNG)

      *Penting*  untuk format tanggal gunakan format sebagai berikut : TAHUN kemudian BULAN dan TANGGAL. Contoh: 1 desember 2022 -> 20221201
3. Tekan `save` untuk menyimpan batch baru

Untuk menambahkan informasi batch pada item stock, dapat dilakukan mealui membuat `purchase order` baru 

------------------
## Tautan
1. [PO](./po.md)

------------------
versi 1.0.0
