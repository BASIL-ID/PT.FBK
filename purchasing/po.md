# PO
Purchase order (PO) atau disebut juga dengan pesanan pembelian adalah dokumen yang dibuat untuk menunjukkan barang yang ingin dibeli.  PO digunakan sebagai kontrak yang membentuk kesepakatan antara pembeli dan penjual mengenai barang yang ingin dibeli oleh pihak pembeli.

![](/assets/buying_flow_po..PNG)

1. Buka menu `purchase order` di `Buying > Purchase Order`, kemudian klik tombol `add purchase order`
![](/assets/po1.PNG)

2. Isi inputan `supplier` pilih supplier jika sebelumnya sudah ditambahkan data supplier, atau klik `create e new supplier` untuk menambahkan supplier baru (lihat tautan supplier dibawah untuk pembahasan supplier)

3. inputan `Required By` tidak wajib di-isi. Inputan ini bertujuan untuk menyimpan tanggal pembelian dibutuhakn paling lambat pada tanggal tertentu 

4. Pada section `Accounting Dimensions`, isi `cost center` dengan outlet/pelaku pembelian. Misal jika pembelian di lakukan di holding, maka pilih Holding
   ![](/assets/po2.PNG)

5. Pada section `Supplier Invoice Details`, apabila dari PO belum menerima dokumen dari supplier, maka tidak perlu diinput
   
6. Pada Section `Address and Contact` data akan dimuat dari informasi supplier yang sudah di input sebelumnya. 
   ![](/assets/po5.PNG)

7. Pada inputan item, masukkan informasi item yang akan dibeli. `Item` adalah produk yang akan dibeli. `Accepted Qty` adalah jumlah qty produk yang akan dibeli. `Rate` adalah nominal harga produk per 1 satuan. Klik tombol `Add Row` untuk menambahkan beberapa produk 

8. Pada inputan `Purchase Taxes and Charges` pastikan akun pajak dan nilainya sudah sesuai
   ![](/assets/po3.PNG)

9. Pada section `Additional Discount` anda dapat mengaplikasikan potonga/diskon pembelian.
   Pada inputan `Apply Additional Discount On` Anda dapat memilih `Grand Total` untuk mengaplikasikan diskon dengan menghitung ulang pajak. Pilih `Net Total` apabila diskon tidak menghitung pajak.
   ![](/assets/po6.PNG)
   ![](/assets/po7.PNG)

10. Tekan tombol `Save` untuk menyimpan PO.

11. Sistem akan membawa Anda ke tampilan review dokumen dengan menginformasikan bahwa dokumen yang sebelumnya Anda simpan masih bersifat `draft`. Pada saat ini, pengeditan dokumen masih dilakukan. Apabila dokumen sudah sesuai, tekan `submit` untuk mengkonfirmasi dokumen sudah sesuai. Dengan melakukan tersebut, dokumen PO akan dapat dilanjutkan pada proses penjualan berikutnya (lihat bagan pembelian pada awal halaman ini)

# Membatalkan/Memperbarui PO
Tutrial ini hanya berlaku untuk `Purchase Order` yang telah di `Submit`.

1. Buka dokumen PO yang akan dibatalkan `Buying > Purchase Order`
2. Tekan tombol `cancel` untuk membatalkan
   ![](/assets/po_cancel_00.png)
3. Apabila dokumen telah dibuatkan `invoice` maka akan ada konfirmasi untuk membatalkan `invoice`.  Tekan `Cancel All` untuk membatalkan `invoice` juga.
   ![](/assets/po_cancel_01.png)
4. Apabila Anda ingin memperbarui `purchase order`, tekan `amend` untuk memperbarui dokumen. Seperti pembuatan `purchase order`, tekan tombol `save` untuk menyimpan dan kemudian setelah tersimpan tekan tombol `submit` apabila dokumen sudah sesuai. Dokumen baru akan diterbitkan dengan mereferensikan dokumen `purchase order` yang sebelumnya (amandemen).
   ![](/assets/po_amend_01.png)

------------------
## Tautan
1. [Supplier](./supplier.md)
1. [Item](./item.md)

------------------
versi 1.0.0
