# Jarkom-Modul-5-E13-2023

| No | Nama | NRP |
|----------|----------|----------|
| 1 | Nadya Permata Sari | 5025201015 |
| 2 | Najma Ulya Agustina | 5025211239 |

<h2>Daftar Isi</h2>

| Soal | Solusi | Testing |
|----------|----------|----------|
| [Soal 1](#soal-1) | [Solusi](#solusi1) | [Testing](#testing1) |
| [Soal 2](#soal-2&3) | [Solusi](#solusi2&3) | [Testing](#testing2&3) |
| [Soal 3](#soal-2&3) | [Solusi](#solusi2&3) | [Testing](#testing2&3) |
| [Soal 4](#soal-4) | [Solusi](#solusi4) | [Testing](#testing4) |
| [Soal 5](#soal-5) | [Solusi](#solusi5) | [Testing](#testing5) |
| [Soal 6](#soal-6) | [Solusi](#solusi6) | [Testing](#testing6) |
| [Soal 7](#soal-7) | [Solusi](#solusi7) | [Testing](#testing7) |
| [Soal 8](#soal-8) | [Solusi](#solusi8) | [Testing](#testing8) |
| [Soal 9](#soal-9) | [Solusi](#solusi9) | [Testing](#testing9) |
| [Soal 10](#soal-10) | [Solusi](#solusi10) | [Testing](#testing10) |


(A) Tugas pertama, buatlah peta wilayah sesuai berikut ini:

<img width="470" alt="soal 1" src="images/01.png">

Keterangan:	Richter adalah DNS Server
		Revolte adalah DHCP Server
		Sein dan Stark adalah Web Server
		Jumlah Host pada SchwerMountain adalah 64
		Jumlah Host pada LaubHills adalah 255
		Jumlah Host pada TurkRegion adalah 1022
		Jumlah Host pada GrobeForest adalah 512


(B) Untuk menghitung rute-rute yang diperlukan, gunakan perhitungan dengan metode VLSM. Buat juga pohonnya, dan lingkari subnet yang dilewati.

(C) Kemudian buatlah rute sesuai dengan pembagian IP yang kalian lakukan. 

(D) Tugas berikutnya adalah memberikan ip pada subnet SchwerMountain, LaubHills, TurkRegion, dan GrobeForest menggunakan bantuan DHCP.

Soal:
<h3>Soal 1</h3>

Agar topologi yang kalian buat dapat mengakses keluar, kalian diminta untuk mengkonfigurasi Aura menggunakan iptables, tetapi tidak ingin menggunakan MASQUERADE.

<h4>Solusi</h4> <a name="solusi1"></a>
<h4>Testing</h4> <a name="testing1"></a>

<h3>Soal 2</h3>

Kalian diminta untuk melakukan drop semua TCP dan UDP kecuali port 8080 pada TCP.

<h4>Solusi</h4> <a name="solusi2"></a>
<h4>Testing</h4> <a name="testing2"></a>

<h3>Soal 3</h3>

Kepala Suku North Area meminta kalian untuk membatasi DHCP dan DNS Server hanya dapat dilakukan ping oleh maksimal 3 device secara bersamaan, selebihnya akan di drop.

<h4>Solusi</h4> <a name="solusi3"></a>
<h4>Testing</h4> <a name="testing3"></a>

<h3>Soal 4</h3>

Lakukan pembatasan sehingga koneksi SSH pada Web Server hanya dapat dilakukan oleh masyarakat yang berada pada GrobeForest.

<h4>Solusi</h4> <a name="solusi4"></a>
<h4>Testing</h4> <a name="testing4"></a>

<h3>Soal 5</h3>

Selain itu, akses menuju WebServer hanya diperbolehkan saat jam kerja yaitu Senin-Jumat pada pukul 08.00-16.00.

<h4>Solusi</h4> <a name="solusi5"></a>
<h4>Testing</h4> <a name="testing5"></a>

<h3>Soal 6</h3>

Lalu, karena ternyata terdapat beberapa waktu di mana network administrator dari WebServer tidak bisa stand by, sehingga perlu ditambahkan rule bahwa akses pada hari Senin - Kamis pada jam 12.00 - 13.00 dilarang (istirahat maksi cuy) dan akses di hari Jumat pada jam 11.00 - 13.00 juga dilarang (maklum, Jumatan rek).

<h4>Solusi</h4> <a name="solusi6"></a>
<h4>Testing</h4> <a name="testing6"></a>

<h3>Soal 7</h3>

Karena terdapat 2 WebServer, kalian diminta agar setiap client yang mengakses Sein dengan Port 80 akan didistribusikan secara bergantian pada Sein dan Stark secara berurutan dan request dari client yang mengakses Stark dengan port 443 akan didistribusikan secara bergantian pada Sein dan Stark secara berurutan.

<h4>Solusi</h4> <a name="solusi7"></a>
<h4>Testing</h4> <a name="testing7"></a>

<h3>Soal 8</h3>

Karena berbeda koalisi politik, maka subnet dengan masyarakat yang berada pada Revolte dilarang keras mengakses WebServer hingga masa pencoblosan pemilu kepala suku 2024 berakhir. Masa pemilu (hingga pemungutan dan penghitungan suara selesai) kepala suku bersamaan dengan masa pemilu Presiden dan Wakil Presiden Indonesia 2024.

<h4>Solusi</h4> <a name="solusi8"></a>
<h4>Testing</h4> <a name="testing8"></a>

<h3>Soal 9</h3>

Sadar akan adanya potensial saling serang antar kubu politik, maka WebServer harus dapat secara otomatis memblokir  alamat IP yang melakukan scanning port dalam jumlah banyak (maksimal 20 scan port) di dalam selang waktu 10 menit. 

<h4>Solusi</h4> <a name="solusi9"></a>
<h4>Testing</h4> <a name="testing9"></a>

<h3>Soal 10</h3>

Karena kepala suku ingin tau paket apa saja yang di-drop, maka di setiap node server dan router ditambahkan logging paket yang di-drop dengan standard syslog level. 

<h4>Solusi</h4> <a name="solusi10"></a>
<h4>Testing</h4> <a name="testing10"></a>

(clue: test dengan nmap)


