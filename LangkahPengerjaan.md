**Soal :**

<img src="Screenshots/soaluap.jpg">

Soal 1
------------------------------------------------

1) Membuat direktori baru dengan nama UAP-Adsis dengan menggunakan perintah
“mkdir”
<img src="Screenshots/Soal 1/createFolder.png">

2) Setelah itu, masuk ke dalam folder tersebut, dan buat file dengan nama catatanya-
ahmad.txt menggunakan perintah “touch”
<img src="Screenshots/Soal 1/createText.png">

3) Mengisikan file yang telah dibuat dengan nama dan nim
<img src="Screenshots/Soal 1/isiFile.png">

4) Lalu, memberikan permission view-only pada file yang telah dibuat menggunakan
perintah “chmod” menggunakan kode 644. Kode tersebut memiliki arti bahwa pemilik
akan memiliki akses untuk baca dan tulis, namun untuk user biasa hanya dapat
membacanya saja.
<img src="Screenshots/Soal 1/permission.png">

5) Menggunakan perintah “ls -l” untuk menampilkan hasil file yang telah diberikan
permission only.
<img src="Screenshots/Soal 1/viewlist.png">
Dapat dilihat bahwa file tersebut memiliki kode rw-r—r dimana kode tersebut
memiliki arti file hanya dapat baca dan diubah oleh pemiliki, dan user biasa hanya
dapat membaca saja

Soal 2
------------------------------------------------

1) Melakukan konfigurasi IP address menggunakan perintah “ifconfig" dengan IP
192.168.56.20.
<img src="Screenshots/Soal 2/config.png">

2) Melakukan pengecekan apakah IP sudah berubah atau belum menggunakan perintah
“ifconfig”
<img src="Screenshots/Soal 2/check.png">

3) Mengatur default gateway menggunakan perintah “route add”
<img src="Screenshots/Soal 2/routeAdd.png">

4) Setelah itu, melakukan pengecekan menggunakan perintah “route -n” untuk mengetahui
apakah sudah berhasil untuk mengkonfigurasi gateway atau belum.
<img src="Screenshots/Soal 2/routeN.png">
Dapat dilihat bahwa konfigurasi gateway sudah berhasil dilakukan pada interface
wlp3s0. Disini saya menggunakan IP yang sama, yaitu 192.168.56.20

Soal 3
------------------------------------------------

1) Masuk ke dalam direktori /etc/apt/sources.list. Kemudian, masukkan perintah
deb http://download.webmin.com/download/repository sarge contrib
<img src="Screenshots/Soal 3/sourcelist.png">

2) Selanjutnya, menambahkan key PGP Webmin agar sistem mempercayai repository baru
menggunakan 2 perintah, yaitu wget http://www.webmin.com/jcameron-key.asc dan
sudo apt-key add jcameron-key.asc
<img src="Screenshots/Soal 3/pgp.png">
<img src="Screenshots/Soal 3/aptkey.png">

3) Membuka webmin pada browser dan melakukan login
<img src="Screenshots/Soal 3/login_page.png">
<img src="Screenshots/Soal 3/dashboard.png">

4) Membuat user baru
<img src="Screenshots/Soal 3/making_user.png">
<img src="Screenshots/Soal 3/making_user_done.png">

5) Membuat grup baru
<img src="Screenshots/Soal 3/making_group.png">
<img src="Screenshots/Soal 3/making_group_done.png">

6) Memasukkan user ke dalam grup
<img src="Screenshots/Soal 3/change_primary_group.png">
<img src="Screenshots/Soal 3/primary_group_changed.png">

Soal 4
------------------------------------------------

1) Melakukan ping ke alamat IP

2) Membuat rule baru untuk melakukan reject kepada request paket bertipe ICMP
<img src="Screenshots/Soal 4/adding_new_rule.png">

3) Setelah rule baru ditambahkan, ping akan mengalami packet loss karena telah di-reject
<img src="Screenshots/Soal 4/ping.png">

Soal 5
------------------------------------------------

1) Menjalankan perintah sudo crontab -e dan menuliskan perintah berikut untuk melakukan otomatisasi ping ke filkom.ub.ac.id
<img src="Screenshots/Soal 5/crontab.png">

2) Setelah itu, dapat dilihat bahwa perintah ping telah terotomatisasi
<img src="Screenshots/Soal 5/result.png">