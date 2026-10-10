# Field Test Mode di iPhone — `*3001#12345#*` 📡

> Satu-satunya kode rahasia yang benar-benar powerful di iPhone. Wajib diketahui jika Anda sering mengalami kendala sinyal.

## Cara Membuka

```text
Phone → Keypad → ketik *3001#12345#* → tap Panggil (hijau)
```

Setelah itu akan muncul aplikasi **Field Test** (berjudul *FTM Dashboard*). Jika tidak muncul, coba perbarui iOS terlebih dahulu.

## Menu di Dalamnya

| Menu | Isi | Kegunaan |
|---|---|---|
| Dashboard / All Metrics | Ringkasan RAT (LTE/NR), RSRP, RSRQ, SINR, Band, Cell ID | Memeriksa penyebab sinyal lemah di ruangan tertentu |
| RAT → Serving Cell Info | Band aktif (B1/B3/B40/n78), bandwidth, TAC, PCI | Memastikan perangkat mendapat band 4G/5G yang optimal |
| RAT → CA Status | Carrier Aggregation | Memeriksa apakah operator menggabungkan beberapa band |
| RAT → Neighbor Cell | Sel tetangga dan kekuatannya | Membandingkan tower mana yang paling kuat |
| Stack → RRC / NAS | Status koneksi dan registrasi | Diagnostik VoLTE/IMS |
| IMS Status | VoLTE, VoWiFi, SMSoIMS | Memeriksa mengapa VoLTE tidak berfungsi |

## Contoh Praktis

**Memeriksa band aktif:** Dashboard → RAT → Serving Cell Info → lihat `Freq Band Indicator` = `3` berarti B3 (1800 MHz). `NR Band` = `n78` berarti 5G 3500 MHz.

**Memeriksa kualitas sinyal:**
- RSRP -80 dBm = bagus, -100 dBm = lemah, di bawah -110 dBm = sangat lemah.
- SINR di atas 10 dB = bersih, di bawah 0 dB = banyak interferensi.

**VoLTE tidak berfungsi:** Cari `IMS Status` → jika `Voice over LTE = Not Registered` berarti VoLTE belum aktif di SIM atau jaringan.

> Catatan: Field Test ini **hanya read-only** — tidak dapat digunakan untuk mengunci band seperti `*#*#4636#*#*` di Android.

[← Cara Penggunaan](01-cara-menggunakan-ios.md) | [Lanjut ke Kode Lainnya →](03-kode-iphone-lainnya.md)
