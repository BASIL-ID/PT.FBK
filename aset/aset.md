# Asset 
`Asset` adalah daftar aset yang digunakan

![](/assets/aset01.PNG)

1. isikan `company`, kemudian pilih `item code` (dari proses PO yg sebelumnya sudah di input), masukkan `asset owner` dan `Asset Owner Company` sebagai pemilik asset.
2. isikan `asset name` untuk identifikasi asset, asset name harus unik per aset.
3. isikan `location` adalah dimana aset berada, Anda dapat menambahkan lokasi bari dengan klik `create a new location`
4. pada section `Accounting Dimensions`, seharusnya `cost center` akan otomatis terisi, apabila belum, bisa dipilih pada pilihan `cost center` yg tersedia.
5. pada section `Purchase Details`, masukkan `Purchase Receipt` dan `Available-for-use Date` (tanggal mulaipenggunaan aset) 
6. pada section `Depreciation`, centang `Calculate Depreciation` untuk menghitung penyusutan aset.
7. tekan save untuk menyimpan


# Asset - DIbuat otomatis dari purchase order
1. Buat `Purchase Order` baru (lihat tautan dibawah)
2. pada pembuatan `item` baru, centang pilihan `Auto Create Assets on Purchase` untuk otomatis mendaftarkan aset baru
   ![](/assets/asset-auto-create.png)
4. pada saat pembuatan `purchase receipt`, masukkan location aset. yakni lokasi dimana asset dipakai/disimpan.

------------------
## Tautan
1. [PO](./../purchasing/po.md)
2. [purchase receipt](./../purchasing/do.md)

------------------
versi 1.0.0
