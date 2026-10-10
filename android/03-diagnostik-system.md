# Diagnostik System Android 🔍

Buat ngintip apa yang lagi jalan di belakang layar — notifikasi push, statistik pemakaian, sampai cek update.

| Kode | Fungsinya | Keterangan |
|---|---|---|
| `*#*#4636#*#*` | Menu testing utama | Info telepon, baterai, usage stats, info Wi-Fi |
| `*#*#426#*#*` | FCM event log | Log connect/disconnect notifikasi |
| `*#*#225#*#*` | Kalender | Sinkronisasi event kalender |
| `*#*#8255#*#*` | GTalk monitor | Legacy — cuma ada di Android lama |
| `*#*#2432546#*#*` | Check-in OTA | Maksa cek update OS ke server Google |

**Yang paling sering kepake:** `*#*#4636#*#*` — di dalamnya ada Phone Info 1/2 (buat atur network type, radio on/off, liat dBm), Usage Statistics, sama Wi-Fi Information. Cocok buat yang sinyalnya naik-turun.

[← Info Perangkat](02-informasi-perangkat.md) | [Lanjut ke Tes Hardware →](04-tes-hardware.md)
