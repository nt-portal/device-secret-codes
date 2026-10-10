# Android — Cara Menggunakan Kode Dial

## 2 Jenis Kode

**A. Kode Internal Android (`*#*#XXXX#*#*` / `*#XXXX#`)**
- Diolah OS Android / dialer bawaan.
- Auto-terbuka saat karakter terakhir diketik — *tanpa* tekan Panggil.
- Tidak butuh SIM / sinyal. Cth: `*#06#` → IMEI langsung muncul.

**B. Kode MMI / USSD Operator (`*...#` / `*#...#`)**
- Dikirim ke jaringan operator.
- Wajib tekan **Panggil** setelah ketik kode. Cth: `*#21#` → Panggil.

## Langkah

```
Buka Telepon bawaan → Keypad → Ketik kode → Auto / tekan Panggil
```

1. Pakai **Telepon bawaan** (Google Phone / Samsung Phone / MIUI Dialer) — bukan Truecaller/WhatsApp.
2. Ketik persis `*` dan `#`-nya.
3. Jika tidak muncul → kode diblokir vendor / tidak didukung ROM Android-mu.

> Jangan tekan Panggil untuk kode internal yang belum kamu pahami.

[← android/README](README.md) | [→ 02 Informasi Perangkat](02-informasi-perangkat.md)
