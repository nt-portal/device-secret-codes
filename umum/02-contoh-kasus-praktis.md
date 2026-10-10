# Contoh Kasus Praktis — Semua HP 📝

> Kumpulan skenario nyata yang sering dihadapi — mulai dari membeli HP bekas hingga mencurigai adanya penyadapan.

---

## 1. Membeli HP Bekas — Checklist 5 Menit

### Android
1. `*#06#` → cocokkan IMEI di layar dengan dusbook dan bodi perangkat.
2. Samsung `*#0*#` / Xiaomi `*#*#6484#*#*` → uji RGB, touch (usap semua kotak), speaker, proximity, dan getar. → [android/04-tes-hardware.md](../android/04-tes-hardware.md)
3. Xiaomi `*#*#6485#*#*` → periksa `MF_02` (cycle), `MB_06` (health).
4. `*#*#4636#*#*` → periksa dBm dan uji koneksi data.

### iPhone
1. `*#06#` → cocokkan IMEI dengan Settings → General → About.
2. `*3001#12345#*` → periksa RSRP/SINR dan band.
3. Settings → Battery → Battery Health → lihat Maximum Capacity dan Cycle Count. → [ios/04-tips-ios.md](../ios/04-tips-ios.md)

### Huawei HarmonyOS
`*#*#2846579#*#*` → ProjectMenu → Battery / Network / Veneer Info. → [harmonyos/01-harmonyos-codes.md](../harmonyos/01-harmonyos-codes.md)

### Nokia / Feature Phone
` *#06#` → IMEI; `*#0000#` → firmware dan model; `*#7370#` jangan dicoba (hard reset!). → [feature-phone/01-feature-phone-codes.md](../feature-phone/01-feature-phone-codes.md)

---

## 2. Sinyal Lemah / Ingin Mengunci ke 4G/5G

| Perangkat | Cara |
|---|---|
| Android | `*#*#4636#*#*` → Phone Info → Set Preferred Network Type → `LTE Only` / `NR Only`. → [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |
| iPhone | Tidak dapat mengunci band via kode — Field Test hanya read-only. Solusinya: pindah lokasi, Reset Network Settings, atau hubungi operator. |
| HarmonyOS | `*#*#2846579#*#*` → Network Information Query (hanya read-only). |
| Feature Phone | Settings → Network selection → manual/auto. |

> Jika di Android Anda mengatur `LTE Only` tetapi kartu belum mendukung VoLTE, maka Anda tidak akan dapat melakukan panggilan biasa — aktifkan VoLTE terlebih dahulu (Xiaomi: `*#*#86583#*#*`).

---

## 3. Curiga Panggilan Dialihkan / Disadap (Semua HP — Jangan Lupa Tekan Panggil)

> Berlaku di semua HP karena diproses oleh operator.

1. Ketik `*#21#` → **ketuk Panggil**. Perhatikan `Voice: Forwarded to +62...`?
2. Jika nomor tersebut asing dan bukan voicemail operator → ketik `##002#` → **Panggil** → `Erasing successful`.
3. Verifikasi kembali `*#21#` → Panggil → seharusnya sudah `Not Forwarded`.

Penjelasan lengkap tersedia di [01-kode-ussd-mmi-universal.md](01-kode-ussd-mmi-universal.md).

---

## 4. Pengecekan IMEI untuk Bea Cukai / Kemenperin

` *#06#` di semua HP — catat IMEI 1/2, lalu periksa di situs Kemenperin atau Bea Cukai. Jangan menyebarkan IMEI di media sosial. → [04-troubleshooting-keamanan.md](04-troubleshooting-keamanan.md)

[← Universal](01-kode-ussd-mmi-universal.md) | [Lanjut ke Tips Mengingat →](03-tips-mengingat-kode.md)
