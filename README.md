# Tugas 1 PKSJ



| NRP         | Nama                     |
|-------------|--------------------------|
| 5114100001  | M. Nezar Mahardika       |
| 5114100040  | Rizky Fenaldo M          |
| 5114100171  | Glleen Allan M           |

#### Penjelasan Tugas
**Uji penetrasi 1 :**
* Instal sebuah virtual OS dengan Ubuntu server
* Instal SSH server dengan konfigurasi default
* Instal satu lagi virtual OS dengan OS bebas, misalnya Kali Linux atau Ubuntu Desktop
* Pastikan tools untuk SSH brute force attack sudah terinstal
* Lakukan uji penetrasi 1: dengan THC-Hydra atau Ncrack dan catat hasil uji penetrasi 

**Uji penetrasi 2:**
* Instal fail2ban pada Ubuntu server yang telah diinstal SSH servernya lalu konfigurasi fail2ban.
* Konfigurasilah SSH server agar tidak default lagi
* Lakukan uji penetrasi 2 dengan tools yang sama dan catat hasilnya

SSH(Secure Shell) adalah  sebuah protokol jaringan kriptografi untuk komunikasi data yang aman, login antarmuka baris perintah, perintah eksekusi jarak jauh, dan layanan jaringan lainnya antara dua jaringan komputer. Ini terkoneksi, melalui saluran aman atau melalui jaringan tidak aman, server dan klien menjalankan server SSH dan SSH program klien secara masing-masing.
Terdapat 2 versi SSH yaitu SSH 1 dan SSH 2. bedanya terletak pada mencakup kedua fitur keamanan dan peningkatan perbaikan tingkat keamanan yang disediakan.
Sebagai contoh, applikasi menggunakan ssh adalah openssh.(https://id.wikipedia.org/wiki/SSH)

Akan tetapi karena masih menggunakan password dan username yang digunakan sebagai otentikasi pada SSH sehingga menimbulkan serangan yang disebut dengan SSH brute force attack. Yang dimaksud dengan SSH brute force attack adalah kita menggirimkan password / passphrases dan username yang kita ketahui dengan harapan membuka komunikasi SSH yang ada (https://en.wikipedia.org/wiki/Brute-force_attack)

## Dasar Teori


**1. OS yang digunakan**
* **Ubuntu** adalah 
Ubuntu merupakan salah satu distribusi Linux yang berbasiskan Debian dan didistribusikan sebagai perangkat lunak bebas. Nama Ubuntu berasal dari filosofi dari Afrika Selatan yang berarti "kemanusiaan kepada sesama". Ubuntu dirancang untuk kepentingan penggunaan pribadi, namun versi server Ubuntu juga tersedia, dan telah dipakai secara luas. (https://id.wikipedia.org/wiki/Ubuntu)

* **Ubuntu Server** adalah 
Ubuntu server adalah suatu desain ubuntu yang digunakan untuk diinstall di lingkungan enterprise atau perusahaan untuk keperluan seperti web server ataupun router, secara default versi server ini tidak menyertakan antarmuka GUI, yang ada hanya shell alias Command line,aplikasi bawaan dari ubuntu server sekedar info buat anda berupa aplikasi serveri webserver, DNS server, DHCP server, firewall, openSSH, dan applikasi yang berhubungan dengan server, teknologi yang dibenamkan diserver juga umumnya hanya dipakai oleh orang yang benar benar advanced di Linux. (https://etix.wordpress.com/2010/01/28/perbedaan-ubuntu-server-dan-desktop/)

**2. Tools yang digunakan**

*Cracking Tool*

* **Hydra**, adalah paralelisasi cracker login yang mendukung banyak protokol untuk menyerang sasaran yang diinginkan. software ini sangat cepat dan fleksibel dan modulenya diinginkan dapat ditambah dengan mudah. Tools ini sangat memungkinkan untuk peneliti dan konsultan keamanan untuk mendapatkan unauthorized access kepada suatu remote sistem. (http://tools.kali.org/password-attacks/hydra)

* **Ncrack** adalah alat cracking autentikasi yang sangat cepat. Dibuat untuk membantu perusahaan mengamankan jaringan mereka dengan testing secara brute force pada host dan jaringan dengan password yang berkekuatan lemah. (https://tools.kali.org/password-attacks/ncrack)

*Defending Tool*

* **Fail2Ban** adalah package keamanan yang digunakan untuk mencegah serangan brute-force dan DDoS pada linux. cara kerjanya sebagai berikut memonitor jumlah kegagalan login untuk selanjutnya memblok ip address dari login yang gagal tersebut.(https://kpunikomlipi.wordpress.com/2012/07/30/konfigurasi-fail2ban-untuk-mengamankan-server/)
 
 
 ## Persiapan

#### 1. Langkah Instalasi Ubuntu 16.04
1. Pilih bahasa yang digunakan
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/1.png)
2.
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/2.png)
3.
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/4.png)
4.
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/5.png)
5.
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/6.png)
6. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/7.png)
7. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/8.png)
8. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/9.png)
9. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/10.png)
10. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/11.png)
11. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/12.png)
12. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/13.png)
13. 
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_16/14.png)


