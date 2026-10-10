# Informasi Perangkat Android ℹ️

Ingin mengetahui IMEI, alamat MAC, versi build, hingga tipe RAM yang terpasang? Semua dapat diperiksa melalui kode-kode berikut.

| Kode | Untuk memeriksa | Contoh & kegunaan |
|---|---|---|
| `*#06#` | IMEI & serial number | Menampilkan `IMEI 1: 86452...` — cocok untuk dicocokkan dengan dusbook atau pengecekan Bea Cukai |
| `*#07#` | Regulasi & SAR | Melihat batas radiasi perangkat |
| `*#*#4636#*#*` | Informasi telepon & usage | Baterai, statistik aplikasi, informasi Wi-Fi |
| `*#*#225#*#*` | Sinkronisasi kalender | Jumlah event dan akun yang terhubung |
| `*#*#426#*#*` | Diagnostik FCM | Status push notification Google |
| `*#*#44336#*#*` | Build version | Tanggal build dan changelist firmware |
| `*#*#1111#*#*` | FTA Software | Versi software field test |
| `*#*#2222#*#*` | FTA Hardware | Revisi motherboard |
| `*#*#3264#*#*` | Versi RAM | Tipe dan versi RAM |
| `*#*#232338#*#*` | MAC Wi-Fi | Seperti `00:0a:95:...` — berguna untuk MAC filtering di router |
| `*#*#232337#*#*` | Alamat Bluetooth | Alamat unik Bluetooth perangkat |

[← Cara Menggunakan](01-cara-menggunakan.md) | [Lanjut ke Diagnostik →](03-diagnostik-system.md)
