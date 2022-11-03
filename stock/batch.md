# Batch

## Menambahkan Batch Pada Item Baru
1. Pada saat pembuatan `purchase receipt`, pada section `items` klik edit.
   ![](/assets/batch04.PNG)

2. Isikan informasi batch pada section `warehouse and reference` pada kolom `batch no`, apabila informasi batch blm dibuat sebelumnya, klik untuk membuat baru.
   ![](/assets/batch05.PNG)

3. Isikan informasi batch. Masukkan kode batch dengan format pengisian kode batch (lihat dibawah) pada `batch id`, isikan `item` dengan produk yang akan diberikan informasi batch, masukkan informasi tanggal manufaktur produk (bila ada) pada kolom `Manufacturing date`, kemudian masukkan satuan produk pada `UOMS`, dan terakhir masukkan informasi kadaluarsa produk pada `expiry date`   
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

3. Tekan `save` untuk menyimpan batch baru
4. Untuk menambahkan informasi batch pada item stock, dapat dilakukan mealui membuat `purchase order` baru apabila item belum pernah memilik transaksi stok sebelumnya

**PENTING** 
Item yang sudah memiliki transaksi stok (seperti purchase receipt) tidak dapat lagi diedit informasi batch nya. Jadi pastikan untuk melakukan pengaturan batch sebelum memproses transaksi item

Apabila transaksi sudah terlanjur dibuat maka yang dapat dilakukan:

1. Batalkan semua transaksi stock terkait item yang bermasalah.
   
   Pertama cek semua transaksi stok dari item yang dipilih. Buka menu `Stock > Stock Ledger`, kemudian pada kolom pencarian `item` masukkan item yang bermasalah. 
      ![](/assets/batch_replace01.PNG)

   Tabel akan menampilkan data transaksi stok yang pernah terjadi pada item yang dipilih. Anda perlu membatalkan semua transaksi dalam daftar agar item dapat diedit sehingga mempunyai informasi `batch no`. Klik nomor transaksi untuk melihat detail transaksi pada kolom `voucher` . 

      ![](/assets/batch_replace02.PNG)

      **PENTING! Anda perlu mencatat semua transaksi yang tampil pada tabel untuk mempermudah Anda dalam mengembalikan data transaksi yang Anda akan batalkan (Note1).**
   
   Pada dokumen detail, klik `cancel` untuk membatalkan transaksi. 

      ![](/assets/batch_replace03.PNG)

   Pada beberapa transaksi, akan ada kemungkinan muncul konfirmasi bahwa dokumen telah digunakan dalam sebagai referensi dokumen transaksi lain. 

      ![](/assets/batch_replace04.PNG)

     **PENTING! Catat dokumen yang memeiliki relasi dengan dokumen yang akan dibatalkan. Anda akan butuh untuk mengedit dokumen yang terhubung tersebut. Klik nomor dokumen untuk melihat detail dokumen (Note2).**

   Apabila Anda telah mencatat dokumen yang terhubung, tekan `cancel all`. Proses ini akan membatalkan semua dokumen baik dokumen transaksi yang dipilih, maupun dokumen-dokumen lain yang terhubung dengan dokumen yang Anda pilih sebelumnya.

      ![](/assets/batch_replace05.PNG)
   
   Ulangi proses untuk semua transaksi stok yang ada dalam `stock ledger`, hingga tidak ada transaksi tersisa.

      ![](/assets/batch_replace06.PNG)

2. Perbarui Item 
   Buka item yang akan diperbarui, dan pastikan `Maintain Stock` dicentang. Anda mungkin perlu melakukan `hard reload` dengan cara menekan `ctrl` + `shift` + `R`, untuk memperbarui data yang tertampil pada browser (pada beberapa kasus, item tidak dapat diedit dan anda perlu melakukan `hard reload`).

    ![](/assets/batch_replace07.PNG)

   Pada section `Serial Nos and Batches`, centang `Has Batch No` dan `Has Expiry Date`. Tekan `Save` untuk memperbarui item.

    ![](/assets/batch_replace08.PNG)

3. Perbarui transaksi stok item yang sebelumnya dibatalkan.
   Buka catatan Anda **(NOTE1)**, kemudian buka dokumen transaksi yang ada dalam daftar catatan Anda. Kemudian, klik `Amend` dan transaksi baru akan dibuat dari data transaksi yang sudah dibatalkan sebelumnya (adendum). Klik tombol `Save` untuk menyimpan dokumen dan tekan `Submit` untuk meneruskan proses transaksi.

    ![](/assets/batch_replace09.PNG)

   Jika Anda perhatikan, sistem akan membuat dokumen baru dengan nomor transaksi seperti transaksi sebelumnya ditambah revisi adendum dibelakang nomor transaksi.

    ![](/assets/batch_replace10.PNG)

   Ulangi proses untuk semua transaksi yang ada dalam catatan Anda.

4. Perbarui transaksi yang terhubung dengan dokumen transaksi stok
   Buka catatan Anda **(NOTE2)**, kemudian buka dokumen transaksi yang ada dalam daftar catatan Anda.klik `Amend` dan transaksi baru akan dibuat dari data transaksi yang sudah dibatalkan sebelumnya (adendum). 

   Masukkan informasi nomor batch. Pada section `Items`, klik tombol `edit` pada item yang sebelumnya telah diperbarui untuk dapat menyimpan informasi nomor batch.
    ![](/assets/batch_replace11.PNG)

   Isikan informasi batch. Masukkan kode batch dengan format pengisian kode batch (lihat dibawah) pada `batch id`, isikan `item` dengan produk yang akan diberikan informasi batch, masukkan informasi tanggal manufaktur produk (bila ada) pada kolom `Manufacturing date`, kemudian masukkan satuan produk pada `UOMS`, dan terakhir masukkan informasi kadaluarsa produk pada `expiry date`   
   ![](/assets/batch03.PNG)


   Tekan `save` untuk menyimpan batch baru
   
   Klik tombol `Save` untuk menyimpan dokumen dan tekan `Submit` untuk meneruskan proses transaksi.

   Ulangi proses untuk semua transaksi yang ada dalam catatan Anda.

- Periksa `General Ledger` dan `Stock Ledger` untuk memastikan stok dan valuasi item sudah sesuai. Apabila ada selisih, pastikan semua transaksi yang Anda batalkan sebelumnya telah Anda perbarui (amandemen).

## Format Penomoran Batch
KODE PRODUCT - TANGGAL EXPIRED

*Penting*  untuk format tanggal gunakan format sebagai berikut : TAHUN kemudian BULAN dan TANGGAL. Contoh: 1 desember 2022 -> 20221201

contoh
    nama produk: Alamii Cheesy Tomato Puffs
    Kode: ACTP
    expired date: 9 Desember 2022

    maka Kode batch adalah ACTP-221209 

------------------
## Tautan
1. [PO](./po.md)

------------------
versi 1.0.1
