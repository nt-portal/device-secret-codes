# Info Perangkat Android ℹ️

Mau tau IMEI, alamat MAC, versi build, sampai tipe RAM yang kepasang? Semua bisa dicek lewat kode-kode ini.

| Kode | Buat cek apa | Contoh & gunanya |
|---|---|---|
| `*#06#` | IMEI & serial number | Nongol `IMEI 1: 86452...` — cocok buat samain sama dusbook atau cek Bea Cukai |
| `*#07#` | Regulasi & SAR | Liat batas radiasi HP |
| `*#*#4636#*#*` | Info telepon & usage | Baterai, statistik aplikasi, info Wi-Fi |
| `*#*#225#*#*` | Sinkronisasi kalender | Jumlah event & akun yang nyambung |
| `*#*#426#*#*` | Diagnostik FCM | Status push notification Google |
| `*#*#44336#*#*` | Build version | Tanggal build & changelist firmware |
| `*#*#1111#*#*` | FTA Software | Versi software field test |
| `*#*#2222#*#*` | FTA Hardware | Revisi motherboard |
| `*#*#3264#*#*` | Versi RAM | Tipe & versi RAM |
| `*#*#232338#*#*` | MAC Wi-Fi | Kayak `00:0a:95:...` — kepake buat MAC filtering di router |
| `*#*#232337#*#*` | Alamat Bluetooth | Alamat unik Bluetooth HP |

[← Cara Menggunakan](01-cara-menggunakan.md) | [Lanjut ke Diagnostik →](03-diagnostik-system.md)
