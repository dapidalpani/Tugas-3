Nama: Dapid alpani
Nim:09030582226016

ALAT DAN BAHAN
Alat dan Bahan yang diperlukan dalam praktikum Jaringan Komputer ini adalah :
1. Sebuah PC atau Laptop
2. Software Jaringan ‘Cisco Packet Tracer’
SWITCH
Switch merupakan perangkat jaringan yang bekerja pada OSI Layer 2, Data Link Layer. 
dia bekerja sebagai penyambung / concentrator dalam Jaringan. Switch mengenal MAC 
Adressing shingga bisa memilah paket data mana yang akan di teruskan ke mana. Dan 
switch ini digunakan sebagai repeater/penguat. Berfungsi untuk menghubungkan kabelkabel UTP ( Kategori 5/5e ) komputer yang satu dengan komputer yang lain. Dalam switch 
biasanya terdapat routing, routing sendiri berfungsi untuk batu loncat untuk melakukan 
koneksi dengan komputer lain dalam LAN.
Switch dapat diartikan sebagai sebuah alat jaringan yang melakukan bridging transparan 
(penghubung segementasi banyak jaringan dengan forwarding berdasarkan alamat MAC).
Switch jaringan dapat digunakan sebagai penghubung komputer atau router pada satu area 
yang terbatas, switch juga bekerja pada lapisan data link, cara kerja switch hampir sama 
seperti bridge, tetapi switch memiliki sejumlah port sehingga sering dinamakan multi-port 
bridge.
Switch dapat dikatakan sebagai multi-port bridge karena mempunyai collision domain dan 
broadcast domain tersendiri, dapat mengatur lalu lintas paket yang melalui switch jaringan.
Cara menghubungkan komputer ke switch sangat mirip dengan cara menghubungkan 
komputer atau router ke hub. Switch dapat digunakan langsung untuk menggantikan hub 
yang sudah terpasang pada jaringan.
Fungsi Switch adalah untuk melakukan bridging transparan sebagai penghubung 
segmentasi dari banyak jaringan dengan mem-forward berdasarkan alamat MAC. Switch
juga sebagai penghubung beberapa alat untuk membentuk suatu Local Area Network 
(LAN).
CARA KERJA SWITCH
Cara Kerja Switch yaitu menerima dan menganalisa seluruh isi paket sebelum 
meneruskannya ke tujuan. Switch memeriksa satu persatu paket untuk mengetahui adanya 
kerusakan pada paket tersebut dan mencegahnya agar tidak mengganggu jaringan. Switch 
mengalokasikan bandwidth secara penuh untuk setiap portnya. Komputer pengguna akan 
selalu memiliki bandwidth secara penuh seberapapun komputer yang ada. Switch bekerja 
di lapisan Data Link dan Setiap port didalam swith memiliki domain collision sendirisendiri. Switch melakukan transmisi secara 2 arah (Full duplex).
LANGKAH KERJA
- Persiapkan 2 buah PC dan 1 buah Switch.
- Pasang kabel penghubung antara PC 0 ke Switch dan PC 1 ke Switch.
- Double click pada PC 0 sehingga muncul jendela baru, seperti berikut
- Click pada tab Desktop sehingga muncul tampilan sebagai berikut.
- Click pada tab IP Configuration, untuk mengatur alamat IP pada PC 0.
- Isikan Alamat IP dan Subnet Mask pada PC 0 dengan alamat seperti dibawah ini 
dan kosongkan kolom Default Gateaway dan DNS server.
- Lakukan hal serupa pada PC 1 tetapi dengan konfigurasi alamat IP yang berbeda 
dengan PC 0, tetapi Subnet Mask nya biarkan sama. Selain itu tetap kosongkan 
kolom Default Gateaway dan DNS server.
- Setelah mengkonfigurasi IP maka 3 buah device tersebut akan saling terhubung 
ditandai dengan dot / node yang berwarna hijau.
- Untuk melakukan testing pada jaringan tersebut, kita dapat melakukan “ping”
- Caranya dengan double clik salah satu dari dua PC (antara PC 0 atau PC 1) dan 
clik pada tab Desktop.
- Kemudian pilih tab Command Prompt dan akan muncul jendela seperti di bawah 
ini.
- Kemudian ketik “PING (alamat IP tujuan) “ ; Contoh nya adalah ‘PING 
192.168.123.2’ maka jaringan kita telah terhubung, akan jadi seperti di bawah 
