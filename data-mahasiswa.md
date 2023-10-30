### Cara Membuat Database dengan PostgreSQL
Langkah-langkah membuat Database dengan PostgreSQL :
1. Membuka SQL Shell (psql)

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/b1b23441-5fea-4084-bed8-499e3090bf62)

2. Setelah masuk ke SQL Shell (psql), enter hingga memasukan password for user postgres :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/dde9ec38-11b9-4df1-8dde-87fcf771aea7)

3. Membuat Database terlebih dahulu dengan perintah `CREATE DATABASE nama_database;` , seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/5a1ded4c-339b-4f80-b945-158ff9e6a0ca)

4. Masuk ke Database untuk mengedit isi Database  dengan perintah `\c nama_database;`, seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/3dd96f66-2f02-4778-ad4c-35da57fbc4a2)

5. Setelah masuk, Membuat tabel terlebih dahulu dalam Database dengan perintah `CREATE TABLE nama_tabel (kolom1 tipedata,kolom2 tipedata,...);`, seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/daa7e1c4-1444-4d40-99ae-be9d89e6edc7)

6. Pastikan jika tabel tersebut sudah benar-benar dibuat dengan perintah `\dt`, seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/f36d0183-7189-4ab2-aa7f-f41b7afd9466)

7. Pastikan isi kolom pada tabel tersebut dengan perintah `SELECT * FROM nama_tabel`, seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/8afffbce-f2b0-4d56-ad8a-d0c92b45c159)

8. Masukan input data, dengan berdasarkan kolom yang diinginkan Jika ingin menginputkan sebuah data kepada semua kolom dapat dengan perintah `INSERT INTO nama_tabel (kolom1,kolom2,...) VALUES (values1,values2,...);`, seperti berikut :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/5e5191ed-4b8e-4565-a684-ae078fe8f735)

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/334f03d7-4208-4c99-aadf-e9c618137ec9)

9. Menampilan data pada database dengan perintah `SELECT * FROM nama_tabel;`, seperti berikut :
    
![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/f3a9e260-25d1-4142-aea3-25be8b7777b5)

10. Cek Tabel Database Pada Dbeaver :

![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/d01bb53a-d03b-4e2f-ad3d-867b94aa01e4)
![image](https://github.com/azzamkhalif10/pertemuan2-basis-data/assets/148309117/b106ff50-ade2-4d24-a18d-6a8fcd00ce9c)

