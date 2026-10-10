# Android — Kode Jaringan Seluler

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#*#4636#*#*` | Preferred network type | `LTE Only` / `NR Only` — kunci 4G/5G |
| `*#0011#` | ServiceMode (Samsung) | Band aktif, RSRP/SINR, CA |
| `*#2263#` | Band selection (Samsung) | Kunci B1/B3/B8/B40 |
| `*#*#86583#*#*` | VoLTE toggle (Xiaomi) | Bypass carrier check |
| `*#*#869434#*#*` | VoWiFi toggle (Xiaomi) | Bypass carrier check |
| `*#*#3646633#*#*` | EngineerMode (MediaTek) | MTK Helio/Dimensity |

> ⚠️ Kunci band sembarangan → sinyal hilang total.

**Cara kunci LTE Only:**
`*#*#4636#*#*` → Phone Info 1/2 → Set Preferred Network Type → `LTE Only`.

> Jika kartu belum VoLTE, `LTE Only` bikin tidak bisa telpon biasa.

[← 04 Tes Hardware](04-tes-hardware.md) | [→ 06 Pengalihan Panggilan](06-pengalihan-panggilan.md)
