# Diagnostik Sistem Android 🔍

Untuk melihat apa yang berjalan di latar belakang — mulai dari notifikasi push, statistik pemakaian, hingga pemeriksaan pembaruan sistem.

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#*#4636#*#*` | Menu testing utama | Informasi telepon, baterai, usage stats, informasi Wi-Fi |
| `*#*#426#*#*` | FCM event log | Log connect/disconnect notifikasi |
| `*#*#225#*#*` | Kalender | Sinkronisasi event kalender |
| `*#*#8255#*#*` | GTalk monitor | Legacy — hanya tersedia di Android versi lama |
| `*#*#2432546#*#*` | Check-in OTA | Memaksa pemeriksaan pembaruan OS ke server Google |

**Yang paling sering digunakan:** `*#*#4636#*#*` — di dalamnya terdapat Phone Info 1/2 (untuk mengatur network type, radio on/off, melihat dBm), Usage Statistics, dan Wi-Fi Information. Sangat berguna ketika sinyal tidak stabil.

[← Informasi Perangkat](02-informasi-perangkat.md) | [Lanjut ke Tes Hardware →](04-tes-hardware.md)
