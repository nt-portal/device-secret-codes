# Android — Kode Khusus Vendor

## Samsung
| Kode | Fungsi |
|---|---|
| `*#0*#` | Test hardware lengkap (RGB, touch, speaker, sensor, kamera) |
| `*#0011#` | ServiceMode |
| `*#0228#` | Battery (voltase, ADC) |
| `*#1234#` | AP/CP/CSC firmware |
| `*#12580*369#` | SW/HW info |
| `*#9900#` | SysDump (hapus log) |
| `*#0808#` | USB settings (MTP/ADB/RNDIS) |
| `*#9090#` | Diagnostic config |
| `*#2263#` | Band selection |
| `*#2663#` | TSP FW |
| `*#7353#` | Quick test (seri lama) |

## Xiaomi / Redmi / POCO
| Kode | Fungsi |
|---|---|
| `*#*#6484#*#*` / `*#*#64663#*#*` | CIT / hardware test |
| `*#*#6485#*#*` | Battery health (`MF_02` cycle) |
| `*#*#284#*#*` | Bug report `.zip` |
| `*#*#86583#*#*` / `*#*#869434#*#*` | VoLTE / VoWiFi toggle |

## OPPO / Realme
` *#899#` / `*#808#` — EngineerMode; `*#800#` — Log Kit; `*#3644633#` — MTK Engineer.

## Vivo
`*#558#` — Factory test; `*#800#` — Log.

## Huawei
`*#*#2846579#*#*` — ProjectMenu; `*#*#1357946#*#*` — SN/Product ID.

## OnePlus
`*#888#` — PCB info; `*#808#` / `*#*#36446337#*#*` — hardware test.

## Sony Xperia
`*#*#7378423#*#*` (`SERVICE`) — Service menu + pressure/waterproof test.

## Pixel / Stock Android
`*#*#7287#*#*` — Pixel diagnostics; `*#*#4636#*#*` — Phone info.

[← 06 Pengalihan](06-pengalihan-panggilan.md) | [→ 08 Berisiko Tinggi](08-kode-berisiko-tinggi.md)
