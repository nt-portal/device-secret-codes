# Jaringan Seluler Android 📶

Buat yang sinyalnya sering hilang atau mau ngunci ke 4G/5G only — ini tempatnya.

| Kode | Fungsinya | Keterangan |
|---|---|---|
| `*#*#4636#*#*` | Preferred network type | Bisa ubah ke `LTE Only` / `NR Only` |
| `*#0011#` | ServiceMode (Samsung) | Liat band aktif, RSRP/SINR, CA |
| `*#2263#` | Band selection (Samsung) | Kunci B1/B3/B8/B40 |
| `*#*#86583#*#*` | VoLTE toggle (Xiaomi) | Bypass cek operator |
| `*#*#869434#*#*` | VoWiFi toggle (Xiaomi) | Bypass cek operator |
| `*#*#3646633#*#*` | EngineerMode (MediaTek) | Khusus chipset Helio/Dimensity |

> Hati-hati ya, kalau salah kunci band bisa-bisa sinyal malah hilang total.

**Cara kunci LTE Only:**
Ketik `*#*#4636#*#*` → Phone Info 1/2 → Set Preferred Network Type → pilih `LTE Only`.

> Catatan: kalau kartu kamu belum support VoLTE, pas LTE Only nanti nggak bisa nerima telpon biasa.

[← Tes Hardware](04-tes-hardware.md) | [Lanjut ke Pengalihan →](06-pengalihan-panggilan.md)
