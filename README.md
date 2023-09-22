# Jarkom-Modul-1-E02-2023
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

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/05e9902e-9069-4181-a2d6-43d003fc4c8d)

Step by step mengerjakan:
1. Display filter telnet
2. Lalu buka paket satu persatu hingga menemukan Data: Login: , dan Data: Password:, akan banyak paket pengecoh yang berisi admin:admin atau admin:1234567
3. Lalu buka paket setelah paket yang berisi Data: Login: untuk username , dan Data: Password: untuk password
4. Lalu akan terlihat username:password adalah dhafin:kesayangank0k0

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/1dfe273f-0b61-497a-9bfd-f3a50f43b975)

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/9f80168d-e11d-4afc-98ce-286a4fa8b1b5)

![image](https://github.com/sultanmp/Jarkom-Modul-1-E02-2023/assets/81198376/129e4cdc-a2b5-41bb-9d38-146b7fd5e5e3)


