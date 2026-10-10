# Cara Menggunakan Kode Dial di iPhone 📱

Jika di Android tersedia banyak kode, di iPhone justru sebaliknya — Apple sengaja membatasi akses tersebut. Kode yang benar-benar powerful hanyalah **Field Test Mode**, selebihnya adalah kode MMI standar GSM.

## Perbedaan Android vs iPhone

|  | Android | iPhone |
|---|---|---|
| Kode internal | Banyak (`*#*#...#*#*`) | Hampir tidak ada — hanya Field Test |
| Perlu menekan Panggil? | Sebagian otomatis, sebagian perlu | **Semua wajib menekan Panggil (hijau)** |
| Penguncian band / EngineerMode | Bisa | **Tidak bisa** — iOS hanya read-only |
| Tes hardware | Tersedia via dial | Tidak tersedia — gunakan Settings / Apple Diagnostics |

## Langkah Penggunaan

```text
Buka Phone → Keypad → Ketik kode → Tap Panggil (hijau)
```

1. Buka aplikasi **Phone** bawaan (ikon hijau).
2. Pindah ke tab **Keypad**.
3. Ketik kode dengan tepat (contoh: `*3001#12345#*`).
4. Ketuk tombol **Panggil** berwarna hijau.
5. Jika kode valid, menu atau pop-up akan muncul. Jika tidak, biasanya akan kembali ke keypad atau menampilkan *Invalid MMI*.

> Untuk iPad yang hanya mendukung Wi-Fi (tanpa modem seluler), kode MMI tidak akan berfungsi.

[← ios/README](README.md) | [Lanjut ke Field Test →](02-field-test-mode.md)
