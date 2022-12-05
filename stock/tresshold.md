# Tresshold
Adalah batasan jumlah stok yang ditentukan untuk melakukan pemesanan item demi menjaga stok tetap ideal.

   ![](/assets/tresshold02.PNG)


## Item yang sudah dibuat
1. Buka item yang akan ditambahkan informasi barcodenya, kemudian pada section `inventory > barcodes` klik tombol `add row` untuk menambahkan data barcode
   ![](/assets/barcode01.PNG)

2. Pada tab `Purchasing` masukkan `Safety Stock` dengan rumus sebagai berikut:

    Safety Stock = Jumlah Pembelian Awal * 33 / 100

   ![](/assets/tresshold01.PNG)

3. Pada tab `Inventory` anda dapat mengisikan konfigurasi untuk notifikasi stok apabila stok menyentuh level tertentu. 

   ![](/assets/tresshold03.PNG)


    -.Check in (group) : adalah gudang yang di-cek apa stoknya masih di atas stok level yang diatur sebelumnya.

    -. Request for : adalah gudang tujuan yang akan menerima notifikasi dan barang yang akan dibeli.
    
    -. Re-order Level: adalah reorder point. Gunakan rumus 75% dari pemebelian pertama.
    
    -. Re-order Qty : adalah jumlah yang harus dipesan untuk mengembalikan stok ke level 100%
    
    -. Material Request Type: isikan dengan tipe aksi yang akan dilakukan sistem apabila `Re-order Level` sudah tercapai

4. Tekan tombol `save` untuk menyimpan item 

------------------
## Tautan

------------------
versi 1.0.0
