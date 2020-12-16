# Peran Bagian MVC
## 1.Penjelasan Program
Aplikasi Sederahana untuk menambahkan item keranjang belanja

## 2.Penjelasan Model
Class yang terdapat dalam model yaitu `Item.cs` `KeranjangBelanja.cs` dan `Payment.cs`.
Pada class `Item.cs` digunakan untuk membuat getter dan setter untuk item dan price, kemudian pada class `Payment.cs` digunakan untuk mengatur logic pembayaran saldo diskon ongkir dan total, selanjutnya class `KeranjangBelanja.cs` digunakan untk menampung item,menghapus item kita menggunakan list

## 3.Penjelasan View
Class yang terdapat dalam view yaitu `MainWindow.xaml.cs` dan `Penawaran.xaml.cs` yang dipergunakan untuk menampilkan atau view kepada user terhadap logic kita tadi.
`MainWindow.xaml.cs` digunakan untk menampilkan item yang sudah terpilih dari penawaran, saldo, ongkir dan total harga, Kemudian `Penawaran.xaml.cs` digunakan untk menampilkan barang yang ditawarkan yang kemudian jika barang tersebut diklik maka akan ditambahkan ke list dan ditampilkan di `MainWindow.xaml.cs`

## 4. Class Diagram
![Class Diagram](https://github.com/MTYU-Luki/Peran-Bagian-MVC/blob/master/ClassDiagram1.png)