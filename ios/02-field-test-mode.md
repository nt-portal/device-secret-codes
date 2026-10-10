# iOS — Field Test Mode (`*3001#12345#*`)

> Satu-satunya "secret code" yang benar-benar powerful di iPhone.

## Cara Buka

```
Phone → Keypad → ketik *3001#12345#* → tap Panggil (hijau)
```

Muncul app **Field Test** (judul `FTM Dashboard`). Jika tidak muncul → update iOS & coba lagi.

## Dashboard — Apa yang Ada di Dalam

| Menu | Isi | Contoh pakai |
|---|---|---|
| **Dashboard / All Metrics** | Ringkasan RAT (LTE/NR), RSRP, RSRQ, SINR, Band, EARFCN, Cell ID | Cek kenapa sinyal lemah di ruangan tertentu |
| **RAT → Serving Cell Info** | Band aktif (B1/B3/B40/n78), bandwidth, TAC, PCI | Pastikan dapat band 4G/5G yang kencang |
| **RAT → CA Status** | Carrier Aggregation — band yang di-aggregate | Cek apakah operator agregasi 2–3 band |
| **RAT → Meas / Neighbor Cell** | Sel tetangga & daya sinyalnya | Bandingkan tower mana paling kuat |
| **Stack → RRC / NAS** | State koneksi & registrasi jaringan | Diagnostik VoLTE/IMS |
| **IMS Status** | VoLTE, VoWiFi, SMSoIMS `Registered` / `Not Registered` | Kenapa telpon VoLTE tidak jalan |

## Contoh Praktis

**1. Cek band aktif:** Dashboard → RAT → Serving Cell Info → lihat `Freq Band Indicator` = `3` → B3 (1800 MHz). `NR Band` = `n78` → 5G 3500 MHz.

**2. Cek kualitas sinyal:**
- **RSRP** -80 dBm = bagus, -100 dBm = lemah, <-110 dBm = sangat lemah.
- **SINR** >10 dB = bersih, <0 dB = interferensi tinggi.

**3. VoLTE tidak jalan:** Cari `IMS Status` → `Voice over LTE = Not Registered` → VoLTE belum aktif di SIM/jaringan.

> Field Test **read-only** — tidak bisa kunci band / ubah mode seperti `*#*#4636#*#*` di Android.

[← 01 Cara Menggunakan](01-cara-menggunakan-ios.md) | [→ 03 Kode iPhone Lainnya](03-kode-iphone-lainnya.md)
