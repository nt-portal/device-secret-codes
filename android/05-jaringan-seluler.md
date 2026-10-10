# Jaringan Seluler Android 📶

Untuk Anda yang sering mengalami sinyal hilang atau ingin mengunci jaringan ke 4G/5G only — bagian ini akan sangat membantu.

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#*#4636#*#*` | Preferred network type | Dapat diubah ke `LTE Only` / `NR Only` |
| `*#0011#` | ServiceMode (Samsung) | Melihat band aktif, RSRP/SINR, CA |
| `*#2263#` | Band selection (Samsung) | Mengunci B1/B3/B8/B40 |
| `*#*#86583#*#*` | VoLTE toggle (Xiaomi) | Bypass pemeriksaan operator |
| `*#*#869434#*#*` | VoWiFi toggle (Xiaomi) | Bypass pemeriksaan operator |
| `*#*#3646633#*#*` | EngineerMode (MediaTek) | Khusus chipset Helio/Dimensity |

> Perlu diperhatikan: kesalahan dalam mengunci band dapat menyebabkan sinyal hilang total.

**Cara mengunci LTE Only:**
Ketik `*#*#4636#*#*` → Phone Info 1/2 → Set Preferred Network Type → pilih `LTE Only`.

> Catatan: Jika kartu Anda belum mendukung VoLTE, pengaturan LTE Only akan membuat Anda tidak dapat menerima panggilan biasa.

[← Tes Hardware](04-tes-hardware.md) | [Lanjut ke Pengalihan →](06-pengalihan-panggilan.md)
