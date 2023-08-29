# Perbedaan Ip Private & IP Public
## Pengertian
IP Public adalah IP Address yang digunakan untuk komunikasi antar host di Internet global

Sedangkan IP Private hanya ada di jaringan lokal saja
## Range IP
Range pada IP Public memiliki 5 kelas lebih banyak dari Range IP Private
- Class A  : 1.0.0.0 sampai 126.0.0.0
- Class B : 128.0.0.0 sampai 191.0.0.0
- Class C : 192.0.0.0 sampai 223.0.0.0
- Class D (Multicast)  : 224.0.0.0 sampai 239.0.0.0
- Class E (For Research)  : 240.0.0.0 sampai 255.0.0.0

Range IP Private
- Kelas A: 10.0.0.0 hingga 10.255.255.255
- Kelas B: 172.16.0.0 hingga 172.31.255.255
- Kelas C: 192.168.0.0 hingga 192.168.255.255
## Contoh IP 
Contoh IP PUblic adalah sebagai berikut:
1.1.1.1 (ip dns cloudflare), 8.8.8.8 (ip dns google)

Sedangkan contoh IP Private adalah sebagai berikut:
192.186.xxx.xxx atau 127.xxx.xxx.xxx atau 10.xxx.xxx.xxx dan seterusnya

## Perbedaan
### IP Public
- Lingkup area bersifat global, seluruh dunia.
- IP Publik bersifat unik, tidak ada yang sama di dunia.
- IP Publik didapat dari ISP tempat berlangganan Internet.
- IP Publik bisa diakses langsung dari Internet
- IP Publik digunakan untuk komunikasi antar jaringan di Internet
- IP Public yang menjadi gateway ke Internet bisa diketahui ketika mengunjungi situs
- IP Public tidak gratis alias berbayar.
- IP Publik ada yang bersifat static dan dinamis (berubah-ubah), dimana IP Satic harganya lebih tinggi daripada IP Dinamis

### IP Private
- Lingkup area bersifat lokal
- IP Private tidak bersifat unik, setiap orang bebas menggunakannya.
- IP Private ditentukan oleh kita sendiri
- Tidak bisa langsung terhubung ke internet (harus melalui router / gateway)
- IP Private digunakan untuk komunikasi antar device dalam jaringan lokal
- IP Private komputer atau laptop bisa diketahui dengan perintah “ipconfig” pada command prompt
- IP Private bisa diset manual ataupun otomatis didapat dari DHCP Server
- IP Private tentu saja gratis.


# Perbedaan IP Dinamic dan IP Static
### IP Static
- IP tidak berubah-ubah
- Stabil untuk digunakan
- digunakan pada jaringan lokal

### IP Dinamic
- IP dapat berubah-ubah
- digunakan pada jaringan public
- fleksible
- Keamanan yang baik
- tidak memerlukan biaya banyak