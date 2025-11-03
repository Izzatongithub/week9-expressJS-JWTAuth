# Express dengan JWT AUTH

### Penjelasan Hasil Program

Judul Program: API untuk program to do list, yang dapat melakukan CRUD

#### Struktur tabel
<img width="1188" height="458" alt="image" src="https://github.com/user-attachments/assets/ed0f3f31-fdfd-4a1a-87fd-2920be340955" />


1. GET, digunakan untuk menampilkan data.
   Dari gambar dibawah, hasil GET yang menampilkan semua data
   <img width="1920" height="1080" alt="GET, menampilkan seluruh data " src="https://github.com/user-attachments/assets/1193c50c-f1ec-416c-aa03-d8edcda9bdc7" />

3. GET, digunakan untuk menampilkan data.
   Dari gambar dibawah, hasil GET yang menampilkan data berdasarkan id_tugas
   <img width="1920" height="1080" alt="GET, menampilkan data sesuai id_tugas" src="https://github.com/user-attachments/assets/8f2e8fcf-ae1d-4a04-b347-f61e5590741c" />

5. POST, menambahkan data ke dalam tabel.
   Dari gambar dibawah, hasil POST yang menampilkan hasil tambah data
   <img width="1920" height="1080" alt="POST, menambahkan data baru" src="https://github.com/user-attachments/assets/2c811099-4c62-4571-9b4d-01429226a16d" />

7. PUT, digunakan untuk mengedit data.
   Dari gambar dibawah, hasil PUT yang menampilkan data yang telah di edit dan inputannya
   <img width="1920" height="1080" alt="PUT, edit data sesuai id_tugas" src="https://github.com/user-attachments/assets/675eff16-9432-473b-9075-85f8a972e371" />

9. DELETE, digunakan untuk menghapus data.
    Dari gambar dibawah, hasil DELETE yang menampilkan data yang telah di hapus
   <img width="1920" height="1080" alt="DELETE, hapus data sesuai id_tugas" src="https://github.com/user-attachments/assets/a0255d8b-dc1c-4304-b054-b7ab2a4e62f4" />

10. POST untuk mendapatkan token melalui routes `Registrasi`
    Dari gambar di bawah, gunakan method post untuk menambah data ke dalam tabel `users`, apabila berhasil akan menampilkan pesan sukses dan token     untuk autentikasi
    <img width="1541" height="808" alt="image" src="https://github.com/user-attachments/assets/b64c61d0-23db-4838-8dc6-08d73b97e283" />

11. POST untuk cek data `users`
    Dari gambar di bawahh, digunakan method post untuk mengirim data dan melakukan validasi data `users` yaitu `username` dan `password`. dan          apabila validasi berhasil makan akan menampilkan kondisi `success`
    <img width="1533" height="804" alt="image" src="https://github.com/user-attachments/assets/7bb69433-3306-46d8-a360-12e662eab2f9" />

12. Memasukkan `Key` dan `value` pada headers untuk validasi token yang suddah didapat dari `registrasi`, `Key` di atur menjadi `Authorization`
    <img width="1553" height="799" alt="image" src="https://github.com/user-attachments/assets/9f94b1d2-def3-4fae-949e-48bf682d5c3d" />
