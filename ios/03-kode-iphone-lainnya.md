# Kode Lainnya di iPhone 📋

> Semua kode di bawah ini memerlukan **tap Panggil** setelah diketik.

## Informasi Perangkat

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#06#` | IMEI | Ketuk Panggil → pop-up IMEI/EID akan muncul. Alternatif: Settings → General → About |
| `*#07#` | Legal & Regulatory | Panel SAR dan regulasi |

## Panggilan & Privasi (CLIR)

| Kode | Fungsi | Contoh |
|---|---|---|
| `*#31#` | Memeriksa status sembunyikan nomor | `Enabled` = nomor Anda tersembunyi saat menelepon |
| `*31#<nomor>` → Panggil | Menelpon sekali dengan nomor tersembunyi | `*31#08123456789` |
| `#31#<nomor>` → Panggil | Menelpon sekali dengan nomor terlihat | `#31#08123456789` |
| `*31#` → Panggil | Mengaktifkan sembunyikan nomor permanen | |
| `#31#` → Panggil | Menonaktifkan sembunyikan nomor | |

## Pengalihan & Call Waiting

| Kode | Fungsi |
|---|---|
| `*#21#` | Memeriksa semua pengalihan |
| `*#61#` / `*#62#` / `*#67#` | Memeriksa pengalihan tidak dijawab / tidak terjangkau / sibuk |
| `##002#` | Menghapus semua pengalihan |
| `*#43#` / `*43#` / `#43#` | Memeriksa / mengaktifkan / menonaktifkan call waiting |

Penjelasan lengkap tersedia di [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md).

## SMS & Lainnya

| Kode | Fungsi | Catatan |
|---|---|---|
| `*#5005*7672#` | Memeriksa nomor SMSC | Alamat server SMS operator |
| `*5005*7672*<SMSC>#` | Mengatur nomor SMSC | Jarang digunakan — biasanya otomatis dari SIM |
| `*3001#12345#*` | Field Test Mode | → [02-field-test-mode.md](02-field-test-mode.md) |

[← Field Test](02-field-test-mode.md) | [Lanjut ke Tips iOS →](04-tips-ios.md)
