# Cara Pakai Kode Dial di iPhone 📱

Kalau di Android kodenya banyak banget, di iPhone kebalikannya — Apple sengaja bikin tertutup. Yang bener-bener powerful cuma **Field Test Mode**, sisanya kode MMI standar GSM.

## Bedanya Android vs iPhone

|  | Android | iPhone |
|---|---|---|
| Kode internal | Banyak (`*#*#...#*#*`) | Hampir nggak ada — cuma Field Test |
| Perlu tekan Panggil? | Sebagian auto, sebagian perlu | **Semua wajib tekan Panggil (hijau)** |
| Kunci band / EngineerMode | Bisa | **Nggak bisa** — iOS cuma read-only |
| Tes hardware | Ada via dial | Nggak ada — pakai Settings / Apple Diagnostics |

## Caranya

```text
Buka Phone → Keypad → Ketik kode → Tap Panggil (hijau)
```

1. Buka aplikasi **Phone** bawaan (ikon hijau).
2. Pindah ke tab **Keypad**.
3. Ketik kodenya persis (contoh: `*3001#12345#*`).
4. Tap tombol **Panggil** hijau.
5. Kalau kodenya valid, menu atau pop-up bakal muncul. Kalau nggak, biasanya balik lagi ke keypad atau muncul *Invalid MMI*.

> Buat iPad yang cuma Wi-Fi (tanpa modem seluler), kode MMI nggak bakal jalan.

[← ios/README](README.md) | [Lanjut ke Field Test →](02-field-test-mode.md)
