# Data Model Mapping

- mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, ho_hp, kd_ds)
- dosen (kd_ds, nama)
- matakuliah (kd_mk, nama, sks)
- jadwalmengajar (kd_ds, kd_mk, hari, jam, ruang)
- KRSmahasiswa (nim, kd_mk, kd_ds, semester, nilai)

![Screenshot_25](https://user-images.githubusercontent.com/115523263/232718918-70a4bb74-57c5-4c4d-9103-c838f228f742.png)

## - script DDL mahasiswa

![Screenshot_7](https://user-images.githubusercontent.com/115523263/232721184-3a79fe9f-2942-461d-8644-e78e9e74681e.png)

output

![Screenshot_9](https://user-images.githubusercontent.com/115523263/232721637-58f79a19-f60c-4791-baf6-4fd324999303.png)

## - script DDL dosen

![Screenshot_1](https://user-images.githubusercontent.com/115523263/232725312-c6a5be64-0de2-47a3-9d31-6445716de03f.png)

output

![Screenshot_4](https://user-images.githubusercontent.com/115523263/232725393-b168bbbb-83ff-407e-9fae-4934946b4fcd.png)

## - script DDL matakuliah

![Screenshot_3](https://user-images.githubusercontent.com/115523263/232722251-5a680c72-48e2-4ea9-b75c-3e6e242eb993.png)

output

![Screenshot_10](https://user-images.githubusercontent.com/115523263/232722428-a0b1b411-305c-4608-b0ba-03e90af8f094.png)

## - script DDL jadwalmengajar

![Screenshot_5](https://user-images.githubusercontent.com/115523263/232722600-cc7d74cd-a1a4-4b27-a70e-2a7db39d48c0.png)

output 

![image](https://user-images.githubusercontent.com/115523263/232726442-aec36134-e953-49b8-89b0-be1cc47036ab.png)

## - script DDL KRSmahasiswa

![Screenshot_6](https://user-images.githubusercontent.com/115523263/232722997-de19e2e7-ee2a-4255-ba2a-b555ae425c7e.png)

output

![Screenshot_8](https://user-images.githubusercontent.com/115523263/232723139-4ea48516-efcc-4371-a67a-7c5c2c9e707d.png)
# INDEX TABLE

## - index untuk table dosen
- menambahkan primary key pada (kd_ds)

![Screenshot_11](https://user-images.githubusercontent.com/115523263/232727608-aa87661d-d1ce-4df5-a6e7-f150d5a519d8.png)

output 

![Screenshot_12](https://user-images.githubusercontent.com/115523263/232727756-bb20b070-0d99-4743-ab7e-612b21f2eb5d.png)

## - index untuk table jadwalmengajar
- menambahkan primary key pada (kd_ds) dan key pada (kd_mk)

![Screenshot_13](https://user-images.githubusercontent.com/115523263/232728552-62a62f8b-70d9-45a8-b51b-b600175d620c.png)

output

![Screenshot_14](https://user-images.githubusercontent.com/115523263/232728344-604060c1-8fbc-44a5-afde-b5894abe1918.png)

## - index untuk table KRSmahasiswa
- menambahkan primary key pada (nim) dan key pada (kd_ds,kd_mk)

![Screenshot_15](https://user-images.githubusercontent.com/115523263/232728828-5ad53785-ec45-4d02-8366-814925bb8ffd.png)

output

![Screenshot_16](https://user-images.githubusercontent.com/115523263/232728918-fc6b9d90-8809-476f-8de4-0e6fd62e1e21.png)

## - index untuk table mahasiswa
- menambahkan primary key pada (nim)

![Screenshot_17](https://user-images.githubusercontent.com/115523263/232729250-78c35fdd-1641-40e7-908d-ffc82a589cf4.png)

output

![Screenshot_18](https://user-images.githubusercontent.com/115523263/232729308-ccdefb0e-0a0b-48e4-bb33-f878f380dd28.png)

# Tugas praktikum

## 1. isi data pada table mahasiswa sebanyak 5 record data

![image](https://user-images.githubusercontent.com/115523263/232890233-adb83190-2281-4db3-aed3-b043365463de.png)

## 2. tampilkan semua record table

![image](https://user-images.githubusercontent.com/115523263/232891216-597b3b99-f279-4e0e-8adb-92131ba88866.png)

## 3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31!

![image](https://user-images.githubusercontent.com/115523263/232892551-df6b33f0-f114-4cde-be71-7eaccc82d606.png)

## 4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan
nama Ari saja!

![image](https://user-images.githubusercontent.com/115523263/232892871-1179f654-f2e5-444a-b538-4799095d6244.png)

## 5. Hapus Mahasiswa yang bernama Dina!

![image](https://user-images.githubusercontent.com/115523263/232893159-0068f4b8-8bf9-4bdb-a3e9-0862c51176a2.png)

## 6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama
dengan 1996-1-2!

![image](https://user-images.githubusercontent.com/115523263/232893506-447d106a-478d-4b13-8f83-bed9cf8f5ad7.png)

## 7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin
perempuan!

![image](https://user-images.githubusercontent.com/115523263/232893797-1728acfb-a4df-41d9-9f7f-36e49d597297.png)

## 8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki
atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!

![image](https://user-images.githubusercontent.com/115523263/232894476-b22a4ede-fce9-42a5-865f-a1d207a01740.png)

## 9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut

![image](https://user-images.githubusercontent.com/115523263/232894706-d98b687f-8722-4cf8-ae73-26075760372d.png)

## 10. Tampilkan data mahasiswa terurut berdasarkan nama

![image](https://user-images.githubusercontent.com/115523263/232895015-f2db0b98-c800-40d2-9972-c2a47e04be8b.png)

# evaluasi dan pertanyaan
## Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ?
- (misal: tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11')

BETWEEN: Kata kunci "BETWEEN" digunakan untuk memilih nilai yang berada di antara dua nilai yang diberikan, termasuk kedua nilai tersebut.

- (misal: tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11')

Operator ">=" dan "<=": Operator ">=" digunakan untuk memilih nilai yang lebih besar atau sama dengan nilai yang diberikan, sedangkan operator "<=" digunakan untuk memilih nilai yang lebih kecil atau sama dengan nilai yang diberikan

## kesimpulan
DML (Data Manipulation Language) adalah sebuah bahasa pemrograman yang berfungsi untuk mengakses, memanipulasi, dan mengelola data yang tersimpan dalam sebuah database. Fungsi dari DML adalah memungkinkan pengguna untuk melakukan berbagai operasi pada data, seperti menambahkan data baru, memperbarui data yang sudah ada, menghapus data, dan mengambil data yang dibutuhkan. Untuk mengakses data dalam DML, pengguna dapat menggunakan perintah SQL (Structured Query Language) yang merupakan bahasa standar untuk mengelola dan mengakses data dalam basis data relasional. Perintah SQL yang tersedia dalam DML antara lain menyisipkan data baru, memodifikasi data, menghapus data, dan menampilkan data seperti yang telah dijelaskan sebelumnya.
