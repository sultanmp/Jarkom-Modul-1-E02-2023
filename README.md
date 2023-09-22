# Jarkom-Modul-1-E02-2023

## Soal 2
**Pertanyaan** : Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!
![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/blob/main/Images/Screenshot%202023-09-22%20202618.png)
**Jawaban** :   
1. Buka file soal2.pcapng
2. Ketik "http" di display filter dan tekan enter
3. Cari info yang bertuliskan "200 OK" dan klik line tersebut
4. Klik "Hypertext Transfer Protocol"
5. Server tertulis di bagian tersebut (gunicorn)



## Soal 3
**Pertanyaan** :
![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/blob/main/Images/Screenshot%202023-09-22%20202725.png)
A. Mencari banyak paket yang tercapture dengan dengan IP source maupun destination address 239.255.255.250 dengan port 3702

B. Protokol layer transport apa yang digunakan
                 
**Jawaban** : 

A. 
1. Buka file soal3.pcapng
2. Ketik "ip.addr == 239.255.255.250 and udp.port == 3702"
3. Hitung (21)

B.
1. Protokol yang digunakan dapat dilihat di bagian "Protocol" (UDP)



## Soal 4
**Pertanyaan** : Berapa nilai checksum yang didapat dari header pada paket nomor 130?

**Jawaban** : Sort sesuai nomor urutan paket lalu scroll menuju paket 130 lalu buka paket dan disana akan tertera nilai checksum dari paket nomor 130 yaitu 0x18e5

## Soal Nomor 7
Berapa nilai checksum yang didapat dari header pada paket nomor 130?

Step by step mengerjakan:
1. Sort sesuai nomor urutan paket
2. Scroll menuju nomor urutan paket yang ingin dicari yaitu 130
3. Lalu buka paket dan buka bagian user datagram protocol
4. Lalu akan terlihat checksum bernilai 0x18e5

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/f6523299-c5ee-434c-a778-5a40c5730de2)

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/3a294daf-5236-4138-9922-c4c284a31882)
## Soal Nomor 10
Sebutkan kredensial yang benar ketika user mencoba login menggunakan Telnet!

Step by step mengerjakan namun fail:
1. Display filter telnet
2. Lalu buka window analyze dan follow tcp stream
3. Lalu seharusnya akan keluar kredensial dari telnet namun pada case kali ini tidak muncul kredensial

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/3f408578-d1e8-4ede-97da-80f617851bbf)


Step by step mengerjakan:
1. Display filter telnet
2. Lalu buka paket satu persatu hingga menemukan Data: Login: , dan Data: Password:, akan banyak paket pengecoh yang berisi admin:admin atau admin:1234567
3. Lalu buka paket setelah paket yang berisi Data: Login: untuk username , dan Data: Password: untuk password
4. Lalu akan terlihat username:password adalah dhafin:kesayangank0k0

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/1dfe273f-0b61-497a-9bfd-f3a50f43b975)

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/9f80168d-e11d-4afc-98ce-286a4fa8b1b5)

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/129e4cdc-a2b5-41bb-9d38-146b7fd5e5e3)


