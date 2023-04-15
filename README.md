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
a. Tabulate 
import tabulate untuk menyajikan beberapa kode berikutnya dalam bentuk tabel

![image](https://user-images.githubusercontent.com/130051156/232235369-7d61b417-4ebd-4478-b4e9-304de1ac1344.png)


b. Transaction Class
Inisialisasi class transaksi sebagai parent class
![image](https://user-images.githubusercontent.com/130051156/232237886-e06394e3-4a7d-4b8d-949f-00134a78f162.png)


c. Fungsi add_item untuk menambahkan item berdasarkan nama item, jumlah item, dan harga item
![image](https://user-images.githubusercontent.com/130051156/232237923-ed6358f1-6311-4dfc-8c42-8856973deb2d.png)


d. Memastikan item_qty dan item_price dalam bentuk integer dan menunjukkan error kedua variabel harus dalam bentuk angka
![image](https://user-images.githubusercontent.com/130051156/232238043-acadb13b-2010-41fa-91f1-7321a7b0ed9e.png)


e. update_item_name untuk update nama dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238345-94617d76-a41f-499a-aeec-96b59ee3e825.png)


f. update_item_qty untuk update jumlah dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238369-0a1bc84b-be11-4030-975e-0b90afe03d05.png)


g. update_item_price untuk update jumlah dari item yang sudah dimasukkan
![image](https://user-images.githubusercontent.com/130051156/232238386-7b2ac646-22b4-4452-95e9-3776a23bdda1.png)


