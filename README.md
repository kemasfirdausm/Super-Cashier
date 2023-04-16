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

![image](https://user-images.githubusercontent.com/130051156/232327018-eed05c5b-3756-4ed6-ba4d-ac34cdd22e6b.png)


3. Fungsi add_item untuk menambahkan item berdasarkan nama item, jumlah item, dan harga item

![image](https://user-images.githubusercontent.com/130051156/232327052-a24475d0-1e43-4d6d-9ef1-e032adb5e711.png)


4. Memastikan item_qty dan item_price dalam bentuk integer dan menunjukkan error kedua variabel harus dalam 
bentuk angka

![image](https://user-images.githubusercontent.com/130051156/232327065-079d0b55-5169-455f-b760-064fdcfabd1d.png)


5. update_item_name untuk update nama dari item yang sudah dimasukkan

![image](https://user-images.githubusercontent.com/130051156/232327080-b24607e3-3ab9-4d4a-95ca-7f0733c6a2f9.png)


6. update_item_qty untuk update jumlah dari item yang sudah dimasukkan

![image](https://user-images.githubusercontent.com/130051156/232327092-6fc4c67d-7d14-49fd-a1d3-fcc6f18e27f0.png)


7. update_item_price untuk update jumlah dari item yang sudah dimasukkan

![image](https://user-images.githubusercontent.com/130051156/232327102-4d8b99de-dd76-4a1a-8346-2c2fed47f743.png)


8. show_order untuk melihat order yang sudah di input dalam bentuk tabel

![image](https://user-images.githubusercontent.com/130051156/232327125-46ae8003-9bf6-46ba-b22b-71b8c3d7a86e.png)


9. delete_item untuk menghapus barang yang tidak jadi dibeli

![image](https://user-images.githubusercontent.com/130051156/232327135-0cbe4cc8-2571-4232-8541-a8c99472ec0e.png)


10. reset_transaction untuk menghapus seluruh inputan transaksi yang telah di input

![image](https://user-images.githubusercontent.com/130051156/232327145-43bc2576-bce2-42b9-b510-4e7bdc63bce8.png)


11. check_order untuk memastikan item sudah di input secara lengkap dan benar

![image](https://user-images.githubusercontent.com/130051156/232327159-67441609-cd0e-4307-9d26-8247e4387b48.png)


12. discount_eligible fungsi untuk melihat apakah pembelian sudah memenuhi syarat diskon

![image](https://user-images.githubusercontent.com/130051156/232327173-0f521cfd-bdbb-4588-990a-ee6fa89c77d3.png)


13. total_price untuk menghitung total belanjaan customer setelah diskon jika mendapatkan diskon

![image](https://user-images.githubusercontent.com/130051156/232327197-63a7c22c-7dea-4c47-9459-b5170a9a9b96.png)


## Test Cases
1. Test Case 1
add_item untuk menambahkan item yang dipilih ke dalam bucket orders
![image](https://user-images.githubusercontent.com/130051156/232277976-b6c8766e-f512-4f6d-a4e9-6e55a76cefab.png)


2. Test Case 2
delete_item untuk menghapus item yang salah dipilih oleh user

![image](https://user-images.githubusercontent.com/130051156/232277987-e0aa2da1-6e38-405d-b365-91750ac17d92.png)


3. Test Case 3
reset_transaction untuk memulai pemilihan order dari awal dan menghapus seluruh order yang telah dipilih
![image](https://user-images.githubusercontent.com/130051156/232326897-8b99d641-2000-4be6-b846-0abaa3d8678c.png)



4. Test Case 4
total_price untuk menghitung total belanja customer
![image](https://user-images.githubusercontent.com/130051156/232278042-b6d0f36b-d821-4162-b3a1-7dcc7d5c37ac.png)


## Conclusion & Future Work
Sistem kasir sudah berhasil melewati test cases yang diberikan dan sudah bisa digunakan untuk melayani customer supermarket.

Kedepannya, ada beberapa hal yang bisa dilakukan untuk menarik ketertarikan customer untuk belanja di supermarket Andi:
1. Membuat loyalty program bagi customer yang memenuhi syarat tertentu seperti selama berapa bulan berturut - turut menjadi customer atau lainnya. Untuk customer yang dapat loyalty program, bisa mendapatkan diskon yang lebih besar dari normal.
2. Bundling program untuk item - item tertentu dimana jika item digabung pembelian dengan beberapa item lainnya, customer bisa mendapatkan harga yang lebih murah
