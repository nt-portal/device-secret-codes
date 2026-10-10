# Kode USSD / MMI Universal — Berlaku di Semua HP 🌍

> Diproses oleh jaringan operator GSM/4G/5G — sehingga dapat digunakan di Android, iPhone, HarmonyOS, maupun Nokia feature phone. Jangan lupa **ketuk Panggil** setelah mengetik kode.

## Pengalihan Panggilan (Call Forwarding)

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#21#` | Memeriksa pengalihan semua panggilan | Unconditional — panggilan langsung diteruskan tanpa berdering |
| `*#61#` | Memeriksa “tidak dijawab” | Diteruskan jika tidak diangkat sekitar 20–30 detik |
| `*#62#` | Memeriksa “tidak terjangkau / HP mati” | Diteruskan saat HP mati atau tidak ada sinyal |
| `*#67#` | Memeriksa “sibuk” | Diteruskan saat Anda menolak atau sedang sibuk |
| `*#004#` | Memeriksa semua pengalihan bersyarat | Sekaligus `*#61#` + `*#62#` + `*#67#` |
| `*#002#` | Memeriksa semua pengalihan |  |
| `##002#` | **Menghapus semua pengalihan** | Reset langsung di server operator |
| `##61#` / `##62#` / `##67#` | Menghapus per kondisi |  |

## Call Waiting & Sembunyikan Nomor (CLIR)

| Kode | Fungsi |
|---|---|
| `*#43#` | Memeriksa call waiting |
| `*43#` / `#43#` | Mengaktifkan / menonaktifkan call waiting |
| `*#31#` | Memeriksa status sembunyikan nomor |
| `*31#` / `#31#` | Mengaktifkan / menonaktifkan sembunyikan nomor permanen |
| `*31#<nomor>` | Menelpon sekali dengan nomor tersembunyi |
| `#31#<nomor>` | Menelpon sekali dengan nomor terlihat |

## Identitas & Jaringan

| Kode | Fungsi | Catatan |
|---|---|---|
| `*#06#` | IMEI | Berfungsi di semua HP, bahkan tanpa kartu SIM |
| `*#07#` | SAR / regulasi |  |
| `*3001#12345#*` | Field Test (iOS) | → [ios/02-field-test-mode.md](../ios/02-field-test-mode.md) |
| `*#*#4636#*#*` | Phone Info (Android) | → [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |

[← umum/README](README.md) | [Lanjut ke Contoh Kasus →](02-contoh-kasus-praktis.md)
