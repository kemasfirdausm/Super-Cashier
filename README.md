# Super-Cashier-Background
Andi adalah seorang pemilik supermarket besar di salah satu kota di Indonesia. Andi memiliki rencana untuk melakukan perbaikan proses bisnis, yaitu Andi akan membuat sistem kasir yang self-service di supermarket miliknya. Sehingga customer bisa langsung memasukkan item yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli dan fitur yang lain.
Sehingga customer yang tidak berada di kota tersebut bisa membeli barang dari supermarket tersebut. Setelah Andi melakukan riset, ternyata Andi memiliki masalah, yaitu Andi membutuhkan Programmer untuk membuatkan fitur - fitur agar bisa sistem kasir self-service di supermarket itu bisa berjalan dengan lancar.

## Objective & Feature Requirements
Objective: 
Membuat sistem kasir self-service di supermarket milik Andi

Requirements: 
- Customer bisa membuat transaksi sendiri
- Customer bisa memasukkan nama item, jumlah item, dan harga per item
- Customer memiliki opsi untuk update nama, jumlah, atau harga per item ketika melakukan kesalahan input
- Customer memiliki opsi untuk membatalkan item belanja
- Customer bisa menghapus seluruh order dengan reset transaksi
- Bisa melakukan check order untuk memastikan tidak ada salah input
- Total belanja bisa mendapatkan diskon jika memenuhi syarat syarat tertentu
     -  Jika total belanja diatas Rp 200.000 maka akan mendapatkan diskon 5%
     - Jika total belanja diatas Rp 300.000 maka akan mendapatkan diskon 8%
     - Jika total belanja diatas Rp 500.000 maka akan mendapatkan diskon 10%


## Flowchart
![Cashier flowchart pacmann](https://user-images.githubusercontent.com/130051156/231973794-7872bfff-efa9-4892-aa27-cd544e876acf.png)

## Code Description
1. Tabulate 
import tabulate untuk menyajikan beberapa kode berikutnya dalam bentuk tabel

![image](https://user-images.githubusercontent.com/130051156/232235369-7d61b417-4ebd-4478-b4e9-304de1ac1344.png)


2. Transaction Class
Inisialisasi class transaksi sebagai parent class
![image](https://user-images.githubusercontent.com/130051156/232237886-e06394e3-4a7d-4b8d-949f-00134a78f162.png)


3. Fungsi add_item untuk menambahkan item berdasarkan nama item, jumlah item, dan harga item
![image](https://user-images.githubusercontent.com/130051156/232237923-ed6358f1-6311-4dfc-8c42-8856973deb2d.png)


4. Memastikan item_qty dan item_price dalam bentuk integer dan menunjukkan error kedua variabel harus dalam 
bentuk angka
![image](https://user-images.githubusercontent.com/130051156/232238043-acadb13b-2010-41fa-91f1-7321a7b0ed9e.png)


5. update_item_name untuk update nama dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238345-94617d76-a41f-499a-aeec-96b59ee3e825.png)


6. update_item_qty untuk update jumlah dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238369-0a1bc84b-be11-4030-975e-0b90afe03d05.png)


7. update_item_price untuk update jumlah dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238386-7b2ac646-22b4-4452-95e9-3776a23bdda1.png)


8. show_order untuk melihat order yang sudah di input dalam bentuk tabel
![image](https://user-images.githubusercontent.com/130051156/232238671-070e72bc-be78-43d3-9686-6489e5bd195f.png)


9. delete_item untuk menghapus barang yang tidak jadi dibeli
![image](https://user-images.githubusercontent.com/130051156/232239082-e1e1edc8-9c0f-4d9a-bb6c-a8f8bc6f177b.png)


10. reset_transaction untuk menghapus seluruh inputan transaksi yang telah di input
![image](https://user-images.githubusercontent.com/130051156/232239102-f2af40b0-3010-447b-9e6b-3ac9b96011c4.png)


11. check_order untuk memastikan item sudah di input secara lengkap dan benar
![image](https://user-images.githubusercontent.com/130051156/232239249-37e2852a-63b9-4b34-8a25-7c9705beb9e0.png)


12. discount_eligible fungsi untuk melihat apakah pembelian sudah memenuhi syarat diskon
![image](https://user-images.githubusercontent.com/130051156/232239300-160a077e-2ad3-4af8-b601-46ebf5fa8bad.png)


13. total_price untuk menghitung total belanjaan customer setelah diskon jika mendapatkan diskon
![image](https://user-images.githubusercontent.com/130051156/232239324-90e33c30-6ac1-4efe-8f3a-eb914ec47562.png)



## Future Work
1. Membuat loyalty program bagi customer yang memenuhi syarat tertentu seperti selama berapa bulan berturut - turut menjadi customer atau lainnya. Untuk customer yang dapat loyalty program, bisa mendapatkan diskon yang lebih besar dari normal.
2. Bundling program untuk item - item tertentu dimana jika item digabung pembelian dengan beberapa item lainnya, customer bisa mendapatkan harga yang lebih murah
