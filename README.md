# Jarkom-Modul-1-F08-2022

1. Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!

Cara pengerjaan, yaitu kita harus mendownload file soal 1 dan 2 terlebih dahulu, kemudian mencari menggunakan filter tcp contains monta.if.its.ac.id.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/1.Filter%20tcp.png'>
Follow file TCP untuk mendapatkan server dari monta.if.its.ac.id sebagai berikut.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/1.Follow%20TCP.png'>
Sehingga didapatkan bahwa server dari monta.if.its.ac.id adalah nginx/1.10.3.

2. Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?

Menggunakan filter http.host contains monta.if.its.ac.id.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/2.Filter%20http.png'>
Pilih lah file yang terdapat tulisan detail topik. Kemudian Export Objek

<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/2.Hasil%20Export.png'>
Save as file 40 dan 194 dengan format html. Bukalah file 40 dan 194 satu per satu untuk menemukan detail topik TA. Sebagai hasil akhir akan didapat topik TA pada file 194.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/2.%20Topik%20TA.png'>

3.Filter sehingga wireshark hanya menampilkan paket yang menuju port 80! 

Cara pengerjaan, yaitu mendownload file soal no 3-7 terlebih dahulu, kemudian menggunakan tcp.dstport == 80 untuk menampilkan file yang dicari.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/3..png'>

4. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!

Menggunakan tcp.srcport == 21 untuk menampilkan file yang dicari.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/4.png'>

5. Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!

Menggunakan tcp.srcport == 443 untuk menampilkan file yang dicari.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/5.png'>

6. Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id !

Menggunakan tcp contains lipi.go.id untuk menapilkan file yang dicari.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/6.png'>

7. Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

Menggunakan ip.src == 192.168.1.5 untuk mencari file yang dicari.
<img src='https://github.com/D-060103/Jarkom-Modul-1-F08-2022/blob/main/7.png'>

8.
