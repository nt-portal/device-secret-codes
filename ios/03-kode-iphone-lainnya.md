# iOS — Kode iPhone Lainnya (MMI / USSD)

> Semua kode di bawah butuh **tap Panggil** setelah diketik.

## Identitas Perangkat

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#06#` | IMEI | Tap Panggil → pop-up IMEI / EID. Alternatif: **Settings → General → About** |
| `*#07#` | Legal & Regulatory | SAR & regulasi (iOS tampilkan panel legal) |

## Panggilan & Privasi (CLIR — Calling Line Identification)

| Kode | Fungsi | Contoh |
|---|---|---|
| `*#31#` | Cek status sembunyikan nomor (CLIR) | `Enabled` = nomor kamu tersembunyi saat telpon |
| `*31#<nomor>` → Panggil | Telpon sekali dengan nomor tersembunyi | `*31#08123456789` |
| `#31#<nomor>` → Panggil | Telpon sekali dengan nomor terlihat (override) | `#31#08123456789` |
| `*31#` → Panggil | Aktifkan sembunyikan nomor permanen | |
| `#31#` → Panggil | Matikan sembunyikan nomor | |

## Pengalihan & Panggilan Tunggu (sama lintas platform — detail di umum/)

| Kode | Fungsi |
|---|---|
| `*#21#` | Cek semua alihan |
| `*#61#` / `*#62#` / `*#67#` | Cek alihan tidak dijawab / tidak terjangkau / sibuk |
| `##002#` | Hapus semua alihan |
| `*#43#` / `*43#` / `#43#` | Cek / aktifkan / matikan call waiting |

→ Detail & contoh lengkap: [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md)

## SMS & Lainnya

| Kode | Fungsi | Catatan |
|---|---|---|
| `*#5005*7672#` | Cek nomor SMSC (SMS Center) | Alamat server SMS operator |
| `*5005*7672*<SMSC>#` | Set nomor SMSC | Jarang dipakai — biasanya auto dari SIM |
| `*3001#12345#*` | Field Test Mode | → [02-field-test-mode.md](02-field-test-mode.md) |
| `*#5005*...#` (lainnya) | Kode carrier custom | Tergantung operator (cek di situs operator) |

[← 02 Field Test](02-field-test-mode.md) | [→ 04 Tips iOS](04-tips-ios.md)
