# Kode Vendor Android 🏷️

Setiap merek memiliki kode andalannya masing-masing — berikut rangkumannya.

## Samsung

| Kode | Fungsi |
|---|---|
| `*#0*#` | Tes hardware lengkap (RGB, touch, speaker, sensor, kamera) |
| `*#0011#` | ServiceMode |
| `*#0228#` | Informasi baterai (voltase, ADC) |
| `*#1234#` | Versi AP/CP/CSC firmware |
| `*#12580*369#` | Informasi SW/HW |
| `*#9900#` | SysDump (menghapus log untuk melegakan penyimpanan) |
| `*#0808#` | Pengaturan USB (MTP/ADB/RNDIS) |
| `*#9090#` | Diagnostic config |
| `*#2263#` | Band selection |
| `*#2663#` | TSP firmware |
| `*#7353#` | Quick test (seri lama) |

## Xiaomi / Redmi / POCO

| Kode | Fungsi |
|---|---|
| `*#*#6484#*#*` / `*#*#64663#*#*` | CIT — pengujian hardware |
| `*#*#6485#*#*` | Informasi baterai (`MF_02` cycle) |
| `*#*#284#*#*` | Bug report `.zip` |
| `*#*#86583#*#*` / `*#*#869434#*#*` | Toggle VoLTE / VoWiFi |

## OPPO / Realme
`*#899#` / `*#808#` — EngineerMode; `*#800#` — Log Kit; `*#3644633#` — Engineer MTK.

## Vivo
`*#558#` — Factory test; `*#800#` — Log.

## Huawei
`*#*#2846579#*#*` — ProjectMenu; `*#*#1357946#*#*` — SN/Product ID.

## OnePlus
`*#888#` — Informasi PCB; `*#808#` / `*#*#36446337#*#*` — pengujian hardware.

## Sony Xperia
`*#*#7378423#*#*` (`SERVICE`) — Service menu dan tes pressure/waterproof.

## Pixel / Stock Android
`*#*#7287#*#*` — Pixel diagnostics; `*#*#4636#*#*` — Phone info.

[← Pengalihan](06-pengalihan-panggilan.md) | [Lanjut ke Kode Berisiko Tinggi →](08-kode-berisiko-tinggi.md)
