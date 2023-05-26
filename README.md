# Praktikum4
1. Membuat database
my sql: CREATE DATABASE Praktikum4;
2. Masuk ke database
my sql: Use Praktikum4;
3. Membuat table
my sql: CREATE TABLE data_pegawai (
 idpegawai VARCHAR(4) NOT NULL,
 nama_depan TEXT(10) NOT NULL,
 nama_belakang TEXT(10) NOT NULL,
 email TEXT(20) NOT NULL,
 telepon VARCHAR(12) NOT NULL,
 tgl_kontrak VARCHAR(10) NOT NULL,
 id_job VARCHAR(5) NOT NULL,
 gaji VARCHAR(7) NOT NULL,
 tunjangan VARCHAR(6) NOT NULL
);
4. Menjadikan nim sebagai primary key
my sql: ALTER TABLE data_pegawai ADD PRIMARY KEY(idpegawai);
5. Mengisi table data_pegawai
my sql: INSERT INTO data_pegawai
VALUES ('E001', 'Kelly', 'Fatmawati', 'Kelly@yahoo.com', '07117059004', '2005-09-01', 'L0001',
'2000000', '500000');
INSERT INTO data_pegawai
VALUES ('E002', 'Alok', 'Firmansyah', 'Alok@yahoo.com', '081312345678', '2006-09-01', 'L0002',
'2000000', '200000');
INSERT INTO data_pegawai
VALUES ('E003','Chrono', 'Odado', 'Coda@gmail.com', '081367384322', '2006-10-01', 'L0003', '1500000',
'NULL');
INSERT INTO data_pegawai
VALUES ('E004', 'Arvaro', 'cuki', 'Alvaro@gmail.com', '081363484342', '2006-10-01', 'L0004',
'1500000', '9');
INSERT INTO data_pegawai
VALUES ('E005', 'Primis', 'adam', 'primis@plasa.com', '08163454555', '2007-09-01', 'L0005', '1250000',
'9');
INSERT INTO data_pegawai
VALUES ('E006', 'Moco', 'Alima', 'moco@yahoo.com', '08527388432', '2008-09-01', 'L0006',
'1750000', 'NULL');
6. Menampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss1.png)
7. Menampilkan pegawai yang tunjangannya NULL
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss2.png)
8. Menampilkan pegawai yang tunjangannya tidak NULL
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss3.png)
9. Menampilkan/menghitung jumlah baris/record table pegawai
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss4.png)
10. Menampilkan/menghitung jumlah total gaji di tabel pegawai
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss5.png)
11. Menampilkan/menghitung rata-rata gaji pegawai
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss6.png)
12. Menampilkan gaji terkecil
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss7.png)
13. Menampilkan gaji terbesar
![gambar](https://github.com/IDOYGAMING/Praktikum4/blob/main/screnshotpraktikum4/ss8.png)