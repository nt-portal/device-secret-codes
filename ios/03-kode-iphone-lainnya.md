# Kode Lainnya di iPhone 📋

> Semua kode di bawah ini butuh **tap Panggil** setelah diketik ya.

## Info Perangkat

| Kode | Fungsinya | Keterangan |
|---|---|---|
| `*#06#` | IMEI | Tap Panggil → nongol pop-up IMEI/EID. Alternatif: Settings → General → About |
| `*#07#` | Legal & Regulatory | Panel SAR & regulasi |

## Panggilan & Privasi (CLIR)

| Kode | Fungsinya | Contoh |
|---|---|---|
| `*#31#` | Cek status sembunyikan nomor | `Enabled` = nomor kamu kesembunyi pas nelpon |
| `*31#<nomor>` → Panggil | Nelpon sekali dengan nomor kesembunyi | `*31#08123456789` |
| `#31#<nomor>` → Panggil | Nelpon sekali dengan nomor kelihatan | `#31#08123456789` |
| `*31#` → Panggil | Aktifin sembunyikan nomor permanen | |
| `#31#` → Panggil | Matiin sembunyikan nomor | |

## Pengalihan & Call Waiting

| Kode | Fungsinya |
|---|---|
| `*#21#` | Cek semua pengalihan |
| `*#61#` / `*#62#` / `*#67#` | Cek pengalihan nggak dijawab / nggak terjangkau / sibuk |
| `##002#` | Hapus semua pengalihan |
| `*#43#` / `*43#` / `#43#` | Cek / aktifin / matiin call waiting |

Detail lengkapnya ada di [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md).

## SMS & Lainnya

| Kode | Fungsinya | Catatan |
|---|---|---|
| `*#5005*7672#` | Cek nomor SMSC | Alamat server SMS operator |
| `*5005*7672*<SMSC>#` | Set nomor SMSC | Jarang dipake — biasanya otomatis dari SIM |
| `*3001#12345#*` | Field Test Mode | → [02-field-test-mode.md](02-field-test-mode.md) |

[← Field Test](02-field-test-mode.md) | [Lanjut ke Tips iOS →](04-tips-ios.md)
