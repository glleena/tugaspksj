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

#### Langkah Instalasi Ubuntu 16.04
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


#### Langkah Instalasi Ubuntu Server

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/1.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/2.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/3.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/4.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/5.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/6.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/7.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/8.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/9.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/10.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/11.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/12.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/13.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/14.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/15.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/16.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/17.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/18.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/19.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/20.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/21.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/22.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/23.PNG)

pada tahap dibawah ini bisa saja memilih untuk langsung install SSH Server atau memilih install melalu apt-get install openssh-server
![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/24.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/25.PNG)

![Hasil install 1](https://github.com/glleena/tugaspksj/blob/master/ubuntu_server/26.PNG)


## Uji Penetrasi 1

#### Uji Penetrasi dengan Hydra

kami melakukan uji penetrasi dengan menginput password yang kita input sendiri, kami menginput dengan jumlah 19 password dengan menyisipkan 1 password yang benar untuk ubuntu server
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/3-hydra.JPG)

1. Pada aplikasi hydra yang sudah berhasil di install isi pada tab target di single target menuju ip server, disini IP Server yaitu 10.151.37.57 dan ubah protocol "ssh"
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/1-hydra.JPG)

2. Pada tab Passwords isi username dengan username pada ubuntu server disini kami menamai pksj. Lalu untuk password list arahkan ke file yang berisi list-list password yang ingin dicoba untuk brute force
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/2-hydra.JPG)

3. Pada tab Tuning kita bisa set Number of Tasks sesuai keinginan kita, kami disini set 4
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/4-hydra.JPG)

4. Pada tab Start lalu klik start lalu akan muncul hasilnya
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/5-hydra.JPG)
![hydra](https://github.com/glleena/tugaspksj/blob/master/hydra/hasil%20xhydra.JPG)

#### Uji Penetrasi dengan Ncrack
sama seperti hydra tetapi ncrack menggunakan terminal tidak dari aplikasi desktop
![hydra](https://github.com/glleena/tugaspksj/blob/master/ncrack/1-ncrack.JPG)

hasilnya akan seperti ini
![hydra](https://github.com/glleena/tugaspksj/blob/master/ncrack/2-ncrack.JPG)

## Uji Penetrasi 2
Dalam Uji Penetrasi 2, Ubuntu Server akan terinstalasi tools Fail2ban.
dan Konfigurasi pada ubuntu server akan diubah dari default konfigurasinya.

#### Uji Penetrasi dengan mengubah default konfigurasi
Pada Ubuntu Server konfigurasi ssh-server dengan mengubah file sshd_config lalu menambahkan seperti gambar dibawah
![sshd](https://github.com/glleena/tugaspksj/blob/master/sshd_config/1-sshd_config.JPG)

lalu restart service ssh dengan command : sudo service ssh restart

Pada ubuntu desktop lakukan langkah-langkah seperti pada uji penetrasi 1 lalu akan menghasilkan seperti dibawah
![sshd](https://github.com/glleena/tugaspksj/blob/master/sshd_config/hasil%20hydra%202-sshd_config.JPG)

#### Uji Penetrasi dengan menggunakan fail2ban
Pada ubuntu server install terlebih dahulu fail2ban dengan mengetik command: sudo apt-get install fail2ban
lalu lakukan configurasi pada fail2ban (/etc/fail2ban/jail.conf) seperti berikut
![fail2ban](https://github.com/glleena/tugaspksj/blob/master/fail2ban/1%20setting%20fail2ban.JPG)

Pada ubuntu desktop lakukan langkah-langkah seperti pada uji penetrasi 1 lalu akan menghasilkan seperti dibawah
![fail2ban](https://github.com/glleena/tugaspksj/blob/master/fail2ban/2%20fail2ban%20-%20hydra%20gagal.JPG)

## Kesimpulan dan Saran
- untuk mencegah ssh brute force dapat dilakukan beberapa hal, beberapa diantaranya adalah dengan melakukan konfigurasi pada ssh-server atau menggunakan tools untuk mencegah ssh brute-force attack seperti fail2ban.

- dari kedua cara yang telah di lakukan, pencegahan ssh brute force attack lebih baik menggunakan tools, dikarenakan lebih bervariasinya fitur pencegahan serangan yang dapat digunakan.
