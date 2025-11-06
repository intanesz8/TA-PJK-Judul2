# 🧩 10.4.4 Lab - Build a Switch and Router Network

## Deskripsi Singkat
Lab ini bertujuan untuk membangun dan mengonfigurasi jaringan sederhana menggunakan **router**, **switch**, dan **dua PC** (PC-A dan PC-B).  
Tujuan dari lab ini adalah untuk menguji pemahaman mengenai konfigurasi dasar perangkat jaringan menggunakan **Cisco IOS Command-Line Interface (CLI)**.

## Tujuan Pembelajaran
- Menyusun topologi jaringan sesuai diagram yang diberikan.  
- Mengonfigurasi alamat **IPv4** dan **IPv6** pada setiap perangkat.  
- Menetapkan **hostname**, **password**, dan **banner** pada router dan switch.  
- Memverifikasi konektivitas antar perangkat menggunakan perintah `ping`.  
- Menampilkan informasi jaringan dengan perintah `show` (seperti `show ip route`, `show ip interface brief`, dll).  

## Ringkasan Aktivitas
1. **Setup Topologi dan Inisialisasi Perangkat**
   - Menyambungkan router, switch, dan dua PC sesuai topologi.

2. **Konfigurasi Router (R1)**
   - Mengatur alamat IP pada interface `G0/0/0` dan `G0/0/1`.
   - Mengaktifkan IPv6 routing (`ipv6 unicast-routing`).
   - Mengatur password (console, VTY, enable secret) dan banner MOTD.

3. **Konfigurasi Switch (S1)**
   - Menetapkan hostname dan IP untuk `VLAN 1`.
   - Menentukan default gateway 
   - Menyimpan konfigurasi dengan `copy running-config startup-config`.

4. **Verifikasi**
   - Melakukan `ping` antar PC untuk memastikan konektivitas berjalan.
   - Menampilkan tabel routing (`show ip route`, `show ipv6 route`).
   - Mengecek status interface (`show ip interface brief`).

## Perangkat yang Digunakan
- 1 Router (Cisco 4221 / setara)
- 1 Switch (Cisco Catalyst 2960 / setara)
- 2 PC (Windows OS)
- Kabel Ethernet & kabel konsol

## Video Penjelasan
Link Youtube:https://www.youtube.com/watch?v=nKqSUS086vs

---
