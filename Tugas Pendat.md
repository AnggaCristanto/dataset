#### Tugas Pendat

##### Disini kita memakai beberapa database, seperti postgresql, database mysql, dan elephantsql yang didimpan pada postgresql di local dan exsel. untuk langkah pertama kita mengambil dataset dari  dataset iris yang berisi tentang data bunga. 

kita masukkan data iris tersebut kedalam 3 database + exsel yang kita punya cara untuk memasukkan kedalam mysql yaitu jalankan apache nya lalu masuk ke phpmyadmin buat database baru lalu import kan data iris( data bunga ).

​	1.postgresql

​	Database postgresql kita jalankan postgre nya lalu masuk ke server lalu database yang kita gunakan, lalu ke schemas, publik, lalu klik table, nah disini kita masukkan query tols untuk membuat table yang nantinya akan diisi oleh data bunga yang ada, setelah table tersebut dibuat kita tinggal import data yang ada. sebelum itu kita harus set dulu binarypath nya sesuai dengan file postgre nya. setelah selesai maka data akan dapat diimportkan. untuk memasukkan data ke power bi caranya, di power bi klik get data lalu pilih database postgre lalu akan muncul tampilan yang di jawibkan anda untuk mengisi server nya dan nama database yang terdapat iris.csv. setelah memasukkan itu klik "ok" maka akan muncul pilihan file ynag ada di database kita, lalu pilih file iris.csv lalu klik load data, tunggu sampai loading selesai maka data sudah ada di power bi.

​	2.Elephant

​	Data yang disimpan di server elephant yang ada di postgresql. saya disini lebih jelasnya hanya menumpangkan data diserver nya elephant yang free tersebut. karena gratis maka file nya juga ada batas mb nya. didalam elephant kita bisa mengirimkan data kita ke server sana. yang nantinya akan bisa dibuka di postgre sesuai dengan username yang diberikan dari elephant setelah kita berhasil membuat database pendat B tersebut.dari elephant akan memberikan username dan pasword yang bertujuan untuk mongkoneksikan antara data elephant yang ada di postgre dengan power bi. setelah terbuat database nya kita buka postgre untuk melihat database yang kita buat. setelah tampil kita harus mengimportkan data iris.csv kita ke dalam database itu. dengan cara klik kanan pada database pilih query tols untuk membuat tabel, setelah tabel terbuat kita tinggal pilih import lalu pilih iris.csv, jika berhasil maka akan muncul datanya di dalam database tersebut.

​	Postgre ke power bi kita pilih get data, lalu pilih database postgre lalu kita masukkan server dan usename kita sesuaikan dengan yang ada di elephant. Setelah itu klik "ok" maka akan muncul untuk kita memasukkan password dari databse kita, dengan cara, pergi ke elepant lalu salin password nya lalu masukkan ke dalam power bi tadi lalu klik connect, setelah itu maka data akan muncul kita tinggal memilih data iris.csv, lalu klik load tunggu sebentar maka data akan tampil didalam power bi.

​	3. File CSV atau dari exsel 

​	kita bisa buka file iris.csv ke exsel terlebih dalu, lalu kita pindah ke power bi pilih get data lalu pilih csv/exsel lalu klik "ok", setelah data muncul klik load untuk memasukan file iris kedalam power bi.

 4.  Database mysql.

     Jalankan dulu apache nya di xxamp, lalu buka php myadmin, stelah itu kita buat database baru dengan cara klik icon tambah di barisan database lalu masukkan nama database yaitu databaseiris. lalu pada database kita import kan file iris.csv setelah berhasil tinggal kita pergi ke power bi pilih get data lalu pilih database mysql lalu masukkan server dan username database terus klik "ok" masukkan root dan password bila ada, setelah itu klik connect lalu pilih file iris.csv lalu kilik load, tunggu sebentar maka data akan muncul.

Selesai, maka pengambilan data dari berbagai database dan exsel sudah siap selesai. 