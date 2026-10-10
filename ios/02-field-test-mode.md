# Field Test Mode di iPhone — `*3001#12345#*` 📡

> Ini satu-satunya kode rahasia yang bener-bener powerful di iPhone. Wajib tau kalau kamu sering ngeluh sinyal lemot.

## Cara Buka

```text
Phone → Keypad → ketik *3001#12345#* → tap Panggil (hijau)
```

Nanti bakal muncul aplikasi **Field Test** (judulnya *FTM Dashboard*). Kalau nggak muncul, coba update iOS dulu.

## Di Dalamnya Ada Apa?

| Menu | Isinya | Gunanya |
|---|---|---|
| Dashboard / All Metrics | Ringkasan RAT (LTE/NR), RSRP, RSRQ, SINR, Band, Cell ID | Cek kenapa sinyal lemah di ruangan tertentu |
| RAT → Serving Cell Info | Band aktif (B1/B3/B40/n78), bandwidth, TAC, PCI | Mastiin dapet band 4G/5G yang kenceng |
| RAT → CA Status | Carrier Aggregation | Cek operator nge-aggregate berapa band |
| RAT → Neighbor Cell | Sel tetangga & kekuatannya | Bandingin tower mana paling kuat |
| Stack → RRC / NAS | State koneksi & registrasi | Diagnostik VoLTE/IMS |
| IMS Status | VoLTE, VoWiFi, SMSoIMS | Cek kenapa VoLTE nggak jalan |

## Contoh Gampangnya

**Cek band aktif:** Dashboard → RAT → Serving Cell Info → liat `Freq Band Indicator` = `3` berarti B3 (1800 MHz). `NR Band` = `n78` berarti 5G 3500 MHz.

**Cek kualitas sinyal:**
- RSRP -80 dBm = bagus, -100 dBm = lemah, di bawah -110 dBm = parah.
- SINR di atas 10 dB = bersih, di bawah 0 dB = banyak interferensi.

**VoLTE nggak jalan:** Cari `IMS Status` → kalau `Voice over LTE = Not Registered` berarti VoLTE belum aktif di SIM/jaringan.

> Catatan: Field Test ini **read-only** ya — nggak bisa buat ngunci band kayak `*#*#4636#*#*` di Android.

[← Cara Pakai](01-cara-menggunakan-ios.md) | [Lanjut ke Kode Lainnya →](03-kode-iphone-lainnya.md)
