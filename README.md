# Market-Basket-Analysis


Market Basket Analysis | The Bread Basket

dataset ini diambil dari sumber terbuka kaggle.com dengan url https://www.kaggle.com/mittalvasu95/the-bread-basket

**Introduce**

Dataset The Bread Basket merupakan laporan hasil penjualan dari toko roti yang berlokasi di Edinburgh. Dataset ini terdari dari 20507 data dengan 9000 transaksi.
Dataset ini terdari dari 5 variabel yaitu :
1. Transaction : id transaksi
2. Item : Nama item yang terjual
3. date_time : Waktu item terjual dalam tanggal dan jam
4. period_day : waktu item terjual dalam periode hari (pagi, siang, sore, malam)
5. weekday_weekend : waktu item terjual dalam minggu

![image](https://user-images.githubusercontent.com/70499692/125605377-53e6c466-d136-4287-88b0-166e41f886d4.png)

**Data Cleaning**

kemudian mengkonversi Transaction menjadi Numeric dan menggabungkan transaksi yang dilakukan oleh pembeli yang sama berdasarkan waktu pembelian dan menyimpannya ke dalam variabel itemList

![image](https://user-images.githubusercontent.com/70499692/125605715-61b7d5f5-ec2f-43d8-bfe2-efef806e24b6.png)

**Algoritma Apriori**

Mendapatkan rules dengan support 0=0.1, minlen=3, dan conf=0.01

![image](https://user-images.githubusercontent.com/70499692/125605876-fff5f075-1066-4fda-b1d2-b7d9b17af12d.png)

![image](https://user-images.githubusercontent.com/70499692/125606166-989a1a2e-39c3-4d40-8f54-359624c06ee0.png)

**
Kesimpulan :**
1. Jika ada yang membeli Coffee, maka penjual dapat menggabungkannya dengan Bread sebagai menu promo
2. Jika ada yang membeli Coffee, maka penjual dapat menggabungkannya dengan Tea sebagai menu promo
