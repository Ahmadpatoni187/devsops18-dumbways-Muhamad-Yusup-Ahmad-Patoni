# Langkah Install Ubuntu di Windows dengan VMWare
Software:
VMware version 17
Ubuntu Server version 20.0.4 LTS

1. Buka VMWare lalu buat konfigurasi untuk instalasi ubuntu
2. Klik **Create new virtual** kemudian pada pilihan **installer disc_image file(ISO)** pilih **Browse** dan pilih file ISO ubuntu server yang sudah di download lalu klik *Next*. lihat Gambar 1
![Gambar 1](<Screenshot (27).png>)
3. Isi kolom *full name*, *username* dan *password* lalu klik *Next*. Lihat gambar 2
![Gambar 2](<Screenshot (28).png>)
4. Tentukan lokasi instalasi ubuntu server. Lihat gambar 3
![Gambar 3](<Screenshot (29).png>)
5. pada pilihan *harddisk* akan terdapat 2 pilihan yaitu *store virutal disk as a singke file* dan *split virtual disk into multiple disk*, jika memiliki ukuran harrdisk yang cukup banyak anda dapat memilih pilihan pertama, namun jika jumlah harddisk tidak cukup dapat memilih pilihan kedua. klilk *Next*. LIhat gambar 4
![Gambar 4](<Screenshot (30).png>)
6. pilih *Customize hardware* kemudian ubah Netword Adapter dari *NAT* menjadi *Bridge*, lihat gambar 5. Jika sudah centang pilihan *Power on this virtual machine after creation* agar proses instalasi dapat langsung dilakukan. Lihat gabmar 6
![Gambar 5](<Screenshot (31).png>)
![Gambar 6](<Screenshot (32).png>)
7. Setelah itu akan tampil layar hitam dimana instalasi sedang berlangsung. Lihat gamar 7
![Gambar 7](<Screenshot (21).png>)
8. Untuk configurasi instalasi dapat dilihat sebagai berikut:
    - Pilihan bahasa: English
    - Installer update: skip
    - Keyboard configuration: skip
    - Netword connection: DHCP (IP laptop yang sedang digunakan) Gambar 8
          * Subnet: 192.168.192.0/24
          * Address: 192.168.192.10
          * Gateway: 192.168.192.1
          * Name Server: 8.8.8.8,8.8.4.4
          * Search Domain: -
            ![Gambar 8](<Screenshot (24).png>)
    - Configure proxy: skip
    - Configure ubuntu archive mirror: skip
    - Custom stogare layout: 
          * root: 15G
          * swap: 4.99G
    - Profile Setup:
          * Your name: Ahmad Patoni
          * Servername: ahmadpatoni
          * username: ahmadpatoni
          * Password: 1234
          * Password: 1234
     - Ceklis Instal OpenSSH Server
     - Features Server Setup: skip
9. Tunggu sampai instalasi ubuntu server selesai.
10. Instalasi selesai. Gambar 9
![Gambat 9](<Screenshot (33).png>)
