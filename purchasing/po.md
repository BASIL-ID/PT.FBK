# PO
Purchase order (PO) atau disebut juga dengan pesanan pembelian adalah dokumen yang dibuat untuk menunjukkan barang yang ingin dibeli.  PO digunakan sebagai kontrak yang membentuk kesepakatan antara pembeli dan penjual mengenai barang yang ingin dibeli oleh pihak pembeli.

![](/assets/buying_flow_po.png)



1. Buka menu `purchase order` di `Buying > Purchase Order`, kemudian klik tombol `add purchase order`
![](/assets/po1.PNG)

2. Isi inputan `supplier` pilih supplier jika sebelumnya sudah ditambahkan data supplier, atau klik `create e new supplier` untuk menambahkan supplier baru (lihat tautan supplier dibawah untuk pembahasan supplier)

3. inputan `Required By` tidak wajib di-isi. Inputan ini bertujuan untuk menyimpan tanggal pembelian dibutuhakn paling lambat pada tanggal tertentu 

4. Pada section `Accounting Dimensions`, isi `cost center` dengan outlet/pelaku pembelian. Misal jika pembelian di lakukan di holding, maka pilih Holding

![](/assets/po2.png)

5. Pada section `Supplier Invoice Details`, apabila dari PO belum menerima dokumen dari supplier, maka tidak perlu diinput
   
6. Pada Section `Address and Contact` masukkan informasi mengenai supplier melalui inputan `Supplier Address` dan `Supplier Contact`. Pilihan inputan akan dimuat dari data kontak `supplier` yg telah terdaftar. Anda juga dapat menambahkan data baru, apabila diperlukan.

7. Pada inputan item, masukkan informasi item yang akan dibeli. `Item` adalah produk yang akan dibeli. `Accepted Qty` adalah jumlah qty produk yang akan dibeli. `Rate` adalah nominal harga produk per 1 satuan. Klik tombol `Add Row` untuk menambahkan beberapa produk 

8. Pada inputan `Purchase Taxes and Charges` pastikan akun pajak dan nilainya sudah sesuai
![](/assets/po3.png)

9. Tekan tombol `Save` untuk menyimpan PO.

10. Sistem akan membawa Anda ke tampilan review dokumen dengan menginformasikan bahwa dokumen yang sebelumnya Anda simpan masih bersifat `draft`. Pada saat ini, pengeditan dokumen masih dilakukan. Apabila dokumen sudah sesuai, tekan `submit` untuk mengkonfirmasi dokumen sudah sesuai. Dengan melakukan tersebut, dokumen PO akan dapat dilanjutkan pada proses penjualan berikutnya (lihat bagan pembelian pada awal halaman ini)

------------------
## Tautan
1. [Supplier](./supplier.md)
1. [Item](./item.md)

------------------
versi 1.0.0
