# IOT_Ethercard_13

Pada praktikum iot modul 13 ini kita belajar cara mengkoneksikan arduino ke web server.
Langkah pertama, kita download dan add library ethercard terlebih dahulu.
lalu ubah STATIC 0 menjadi STATIC 1 ubntuk menonaktifkan DHCP dan menggunakan ip yangakan kita buat
pada script static byte gwip[] adalah ip gateway yg digunakan untuk mengatur alamat ip pada komputer/device.
sedangkan static byte myip[] untuk membuka server diweb.

setelah di script di compile, lalu kita ke proteus dan masukkan directory file.hex nya.
Lalu setting ip gateway di modul ENC2860 agar arduino bisa terhubung ke web server
Lalu saat di web kita mengetikkan alamat ip server yang telah dibuat akan muncul Nama,nim,tanggal lahir dan email saya yg merupakan scipt php 
yg telah dibuat di arduino.
