# Praktikum 12
<table bprder="1" cellpadding="5" cellspacing="0">
  <tbody>
  <tr>
  <td> Nama </td>
  <td> Ade maulani bilgis</td>
  </tr>
  <tr>
  <td>Prodi</td>
  <td>Teknik Informatika</td>
  </tr>
</table>

- Buka aplikasi postman dan pilih create new → HTTP Request

## Menampilkan Semua Data
Pilih method GET dan masukkan URL berikut: http://localhost:8080/post Lalu, klik Send. Jika hasil test menampilkan semua data artikel dari database, maka pengujian berhasil.
- Pilih method GET dan masukkan URL berikut: http://localhost:8080/post
- Lalu, klik Send. Jika hasil test menampilkan semua data artikel dari database, maka pengujian berhasil.

## Menampilkan Data Spesifik
Masih menggunakan method GET, hanya perlu menambahkan ID artikel di belakang URL seperti ini: http://localhost:8080/post/2 Selanjutnya, klik Send. Request tersebut akan menampilkan data artikel yang memiliki ID nomor 2 di database.
- Masih menggunakan method GET, hanya perlu menambahkan ID artikel di belakang URL seperti ini: 
http://localhost:8080/post/2 
- Selanjutnya, klik Send. Request tersebut akan menampilkan data artikel yang memiliki ID nomor 2 di database.



## Mengubah Data
Untuk mengubah data, silakan ganti method menjadi PUT. Kemudian, masukkan URL artikel yang ingin diubah. Misalnya, ingin mengubah data artikel dengan ID nomor 2, maka masukkan URL berikut: http://localhost:8080/post/2 Selanjutnya, pilih tab Body. Kemudian, pilih x-www-form-uriencoded. Masukkan nama atribut tabel pada kolom KEY dan nilai data yang baru pada kolom VALUE. Kalau sudah, klik Send.
- Untuk mengubah data, silakan ganti method menjadi PUT. Kemudian, masukkan URL artikel yang ingin diubah. Misalnya, ingin mengubah data artikel dengan ID nomor 2, maka masukkan URL berikut: 
http://localhost:8080/post/2 
- Selanjutnya, pilih tab Body. Kemudian, pilih x-www-form-uriencoded. Masukkan nama atribut tabel pada kolom KEY dan nilai data yang baru pada kolom VALUE. Kalau sudah, klik Send.

## Menambahkan Data
Anda perlu menggunakan method POST untuk menambahkan data baru ke database. Kemudian, masukkan URL berikut: http://localhost:8080/post Pilih tab Body, lalu pilih x-www-form-uriencoded. Masukkan atribut tabel pada kolom KEY dan nilai data baru di kolom VALUE. Jangan lupa, klik Send.
- Anda perlu menggunakan method POST untuk menambahkan data baru ke database. Kemudian, masukkan URL berikut: 
http://localhost:8080/post 
- Pilih tab Body, lalu pilih x-www-form-uriencoded. Masukkan atribut tabel pada kolom KEY dan nilai data baru di kolom VALUE. Jangan lupa, klik Send.

![Menambah Data](https://github.com/forusig/Lab12web/blob/63fa1d6d8f1061edc0e4088d801e0aac03f3846a/ss/ss1.png)

jika sudah berhasil akan seperti ini
![image](https://github.com/forusig/Lab12web/blob/63fa1d6d8f1061edc0e4088d801e0aac03f3846a/ss/ss2.png)

## Menghapus Data
Pilih method DELETE untuk menghapus data. Lalu, masukkan URL spesifik data mana yang ingin di hapus. Misalnya, ingin menghapus data nomor 4, maka URL-nya seperti ini: http://localhost:8080/post/7 Langsung saja klik Send, maka akan mendapatkan pesan bahwa data telah berhasil dihapus dari database.
- Pilih method DELETE untuk menghapus data. Lalu, masukkan URL spesifik data mana yang ingin di hapus. Misalnya, ingin menghapus data nomor 4, maka URL-nya seperti ini: 
http://localhost:8080/post/7 
- Langsung saja klik Send, maka akan mendapatkan pesan bahwa data telah berhasil dihapus dari database.

![Menghapus Data](https://github.com/forusig/Lab12web/blob/63fa1d6d8f1061edc0e4088d801e0aac03f3846a/ss/ss4.png)

## TERIMAKASIH !