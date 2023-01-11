# Moka Sales
Data penjualan dari moka akan secara otomatis diposting kedalam sistem setiap hari. Untuk melihat data penjualan moka, Anda dapat mengakses menu `Accounting > Sales Invoice`, kemudian pasang beberapa filter seperti pada gambar dibawah ini.

![](/assets/moka1.PNG)

Apabila data di-import dari moka, akan muncul tab `MOKA` dimana disini berisi informasi dokumen tersebut telah di-import dari moka, dan juga apabila ada permasalhan sewaktu proses import data akan muncul pesan errornya juga
![](/assets/moka5.PNG)


## Transaksi yang dibatalkan
Pada aplikasi moka, pembatalan transaksi hanya dapat dilakukan menggunakan metode refund, oelh karena itu apabila ada transaksi yang dibatalkan di moka, dashboard akan mencatat pembatalan transaksi tersebut dengan menggunakan metode retur.

Untuk memfilter data sales invoice yang diretur, gunakan filter dibawah ini
![](/assets/moka2.PNG)


Untuk memfilter data dokumen retur sales invoice, gunakan filter dibawah ini
![](/assets/moka3.PNG)


## Transaksi yang bermasalah
Pada beberapa kasus, akan dijumpai bahwa data transaksi yang di-import dari moka bermasalah. Saat proses import data, sistem terlebih dahulu memvalidasi datayang diterima dengan moka, dan apabila ada data yang tidak sinkron, maka sistem akan memberikan tanda pada data transaksi yang bermasalah tersebut. 

Penyebab tranaksi bermasalah:
1. Data Item (pesan error: item data error)
    Umumnya permasalahan ini terjadi karena perbedaan harga antara moka dengan `item price list` yang ada di dashboard. Selain itu, permasalahan juga dapat timbul apabila data item yang dimaksud ditransaksi moka tidak ditemukan di dashboard.

    Apabila Anda menemui pesan error ini, silahkan cek item Anda dengan klik tombol `edit`.
   ![](/assets/moka6.PNG)

    Pada item yang Anda pilih, apabila item tersebut memiliki error, maka pada section `Moka`, akan tampil pesan errornya.
   ![](/assets/moka7.PNG)

2. Permasalahan Lainnya (pesan error: Unable submit data, please submit manually)
    Umumnya permasalhan ini terjadi apabila data item yang ditransaksikan tidak lagi mempunyai stok


Untuk mencari data transaksi yang bermasalah, dapat menggunakan filter sebagai berikut

![](/assets/moka4.PNG)


Setelah Anda menemukan permasalahannya, silahkan melakukan perbaikan data yang bermasalah, dan kemudian tekan tombol `Save` untuk menyimpan. Dan setelah semua perubahan telah dipastikan benar, Anda dapat memproses data Sales Invoice tersebut dengan klik tombol `Submit`


------------------
## Tautan

------------------
versi 1.0.0
