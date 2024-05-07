# PRAKTIKUM-DATA-BASE-2
# 1. Tampilkan semua isi tabel record!
![327658381-e4179815-32d9-437f-a0d4-74a94124941c](https://github.com/firman00009999/heri-firman/assets/148558300/3df55edf-541e-4001-91a9-42076fe9abf2)
# 2. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 31-08-1979!
![2](https://github.com/firman00009999/heri-firman/assets/148558300/45c9d21c-37c1-47d9-ba4a-d6190ac22256)
# 3. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja!
![3](https://github.com/firman00009999/heri-firman/assets/148558300/50c63ee4-9c31-4a77-ac76-d95d3f833c46)
# 4. Hapus Mahasiswa yang bernama Dina!
![4](https://github.com/firman00009999/heri-firman/assets/148558300/746373e3-49eb-4a64-bcaf-aaa387856048)
# 5. Tampilkan catatan atau data yang tanggal kelahirannya lebih dari atau sama dengan 2-1-1996!
![5](https://github.com/firman00009999/heri-firman/assets/148558300/6a387b3c-8c6f-4f3c-8a05-8d3c920b0300)
# 6. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan!
![6](https://github.com/firman00009999/heri-firman/assets/148558300/f108dd83-e2c3-4737-9ba5-8577bec70da1)
# 7.Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
![7](https://github.com/firman00009999/heri-firman/assets/148558300/c589a6ee-8689-445c-a8c2-cb7928d6f074)
# 8. Tampilkan data nama dan alamat siswa saja dari tabel tersebut
![8](https://github.com/firman00009999/heri-firman/assets/148558300/c64ed929-41e1-4a29-a8ce-42eb3b58382a)
# 9. Tampilkan data siswa terurut berdasarkan nama
![9](https://github.com/firman00009999/heri-firman/assets/148558300/eeba0d1b-f0bd-452f-bd04-543aa40ea40c)

# EVALUASI-DAN-PERTANYAAN
# 1. Tulis semua perintah-perintah SQL percobaan di atas beserta outputnya!
Jawaban :
1. Memasukkan data => INSERT
  • MASUKKAN KE <nama_tabel> (bidang1, ..., bidangn) NILAI (val1, ..., valn)
2. Mengubah data => UPDATE
  • UPDTAE <nama_tabel> SET [field1=val1, ,...fieldn=valn] WHERE <kondisi>
3. Menghapus data => HAPUS
  • HAPUS DARI <nama_tabel> DIMANA <kondisi>
4. Menampilkan data => PILIH
  • PILIH * DARI <nama_tabel>
# 2. Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ?
# • (misal: tgl_lahir ANTARA '10-10-1990' DAN '11-10-1992')
# • (misal: tgl_lahir >= '10-10-1990' DAN tgl_lahir <= '11-10-1992')
Jawaban :
Perbedaan antara penggunaan BETWEEN dan penggunaan operator >= dan <= dalam konteks yang Anda berikan adalah:
1. **BETWEEN**: Dalam kasus ini, penggunaan BETWEEN akan memeriksa apakah nilai tgl_lahir berada di antara '1990-10-10' dan '1992-10-11', termasuk kedua tanggal tersebut. Jadi, jika tgl_lahir sama dengan '1990-10-10' atau '1992-10-11', data tersebut akan disertakan dalam hasil kueri.
   tgl_lahir ANTARA '10-10-1990' DAN '11-10-1992'
   
2. **Operator >= dan <=**: Dalam kasus ini, operator >= dan <= akan memeriksa apakah nilai tgl_lahir lebih besar dari atau sama dengan '1990-10-10' dan kurang dari atau sama dengan '1992- 10-11'. Ini berarti data yang memiliki tgl_lahir sama dengan '1990-10-10' atau '1992-10-11' akan disertakan dalam hasil kueri hanya jika operator adalah <= atau >=. Hal ini menyebabkan perilaku sedikit berbeda dari penggunaan BETWEEN karena BETWEEN akan mencakup kedua nilai batas, sedangkan operator >= dan <= akan memperlakukan kedua batas secara terpisah.
   tgl_lahir >= '10-10-1990' DAN tgl_lahir <= '11-10-1992'
# Kesimpulan
Jadi kesimpulannya tentang praktikum Entity-Relationship Diagrams (ERD) dan Data Model Mapping, ERD adalah representasi visual dari struktur data yang menggambarkan entitas, atribut, dan hubungan antara entitas dalam suatu sistem atau domain. Entitas yang mewakili objek dunia nyata seperti orang, tempat, atau konsep, sedangkan atribut adalah properti yang mendefinisikan entitas. Hubungan menggambarkan cara entitas terkait satu sama lain dalam basis data, seperti hubungan satu-ke-satu, satu-ke-banyak, atau banyak-ke-banyak. ERD membantu dalam merancang, memahami, dan memelihara struktur data dengan menyediakan tampilan grafis yang jelas tentang elemen-elemen penting dalam basis data.
Sedangkan Data model maping adalah proses mengubah desain konsep dari ERD menjadi representasi logistik dalam suatu sistem basis data, seperti tabel dalam model relasional. Ini melibatkan identifikasi entitas, atribut, dan hubungan dalam ERD, dan kemudian memetakkannya ke dalam tabel, kolom, dan kunci tunggal dalam model basis data yang dipilih. Pemetaan model data memungkinkan desainer basis data untuk mentransformasikan konsep desain menjadi struktur yang dapat diimplementasikan dalam sistem basis data tertentu. Selain itu, proses ini juga mempertimbangkan batasan dan aturan dari model basis data yang dipilih, seperti normalisasi dan konsistensi data.
Penjelasan diatas bisa disimpulkan, bahwasanya ERD membantu dalam pemodelan struktur data secara konseptual, sementara pemetaan model data adalah langkah berikutnya yang mengubah desain konsep tersebut menjadi representasi logistik yang dapat diimplementasikan dalam sistem basis data. Keduanya merupakan bagian penting dari proses perancangan dan implementasi sistem basis data yang efektif.
