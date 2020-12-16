# Peran Bagian MVC
## 1.Penjelasan Program
Aplikasi Sederahana untuk menambahkan item seperti keranjang belanja

## 2.Penjelasan Model
Pada class `Item.cs` digunakan untuk membuat getter dan setter untuk item dan price, kemudian pada class `Payment.cs` digunakan untuk mengatur logic pembayaran saldo diskon ongkir dan total, selanjutnya class `KeranjangBelanja.cs` digunakan untk menampung item,menghapus item kita menggunakan list

## 3.Penjelasan View
`MainWindow.xaml.cs` digunakan untk menampilkan item yang sudah terpilih dari penawaran, saldo, ongkir dan total harga, Kemudian `Penawaran.xaml.cs` digunakan untk menampilkan barang yang ditawarkan yang kemudian jika barang tersebut diklik maka akan ditambahkan ke list dan ditampilkan di `MainWindow.xaml.cs`

## 4. Class Diagram
![Class Diagram](https://github.com/MTYU-Luki/Peran-Bagian-MVC/blob/master/ClassDiagram1.png)
