# iOS — Cara Menggunakan Kode Dial

Apple jauh lebih tertutup dari Android. Tidak ada `*#*#4636#*#*` atau CIT. Hanya **Field Test Mode** + kode **MMI/USSD standar GSM**.

## Beda Android vs iPhone

|  | Android | iPhone (iOS) |
|---|---|---|
| Kode internal | Banyak (`*#*#...#*#*`) | Hampir tidak ada — hanya Field Test |
| Butuh tekan Panggil? | Sebagian auto, sebagian butuh | **Semua butuh tekan Panggil (hijau)** |
| EngineerMode / band lock | Bisa | **Tidak bisa** — iOS read-only |
| Tes hardware | Ada via dial | Tidak ada — pakai **Settings / Apple Diagnostics** |

## Langkah di iPhone

```
Buka Phone → Keypad → Ketik kode → Tap Panggil (hijau)
```

1. Buka app **Phone** bawaan (ikon hijau).
2. Tab **Keypad**.
3. Ketik kode persis (cth: `*3001#12345#*`).
4. Tap tombol **Panggil** hijau.
5. Jika kode valid → menu / pop-up muncul. Jika tidak → `Invalid MMI` atau kembali ke keypad.

> iPad Wi-Fi only tanpa modem seluler → kode MMI tidak jalan.

[← ios/README](README.md) | [→ 02 Field Test Mode](02-field-test-mode.md)
