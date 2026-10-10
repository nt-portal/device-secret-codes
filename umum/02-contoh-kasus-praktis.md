# Contoh Kasus Praktis — Semua HP 📝

> Skenario nyata yang sering kejadian — dari beli HP bekas sampai curiga disadap.

---

## 1. Beli HP Bekas — Checklist 5 Menit

### Android
1. `*#06#` → samain IMEI layar sama dusbook & bodi.
2. Samsung `*#0*#` / Xiaomi `*#*#6484#*#*` → tes RGB, touch (usap semua kotak), speaker, proximity, getar. → [android/04-tes-hardware.md](../android/04-tes-hardware.md)
3. Xiaomi `*#*#6485#*#*` → `MF_02` (cycle), `MB_06` (health).
4. `*#*#4636#*#*` → cek dBm & tes data.

### iPhone
1. `*#06#` → IMEI vs Settings → General → About.
2. `*3001#12345#*` → cek RSRP/SINR & band.
3. Settings → Battery → Battery Health → liat Maximum Capacity & Cycle Count. → [ios/04-tips-ios.md](../ios/04-tips-ios.md)

### Huawei HarmonyOS
`*#*#2846579#*#*` → ProjectMenu → Battery / Network / Veneer Info. → [harmonyos/01-harmonyos-codes.md](../harmonyos/01-harmonyos-codes.md)

### Nokia / Feature Phone
` *#06#` → IMEI; `*#0000#` → firmware & model; `*#7370#` jangan dicoba (hard reset!). → [feature-phone/01-feature-phone-codes.md](../feature-phone/01-feature-phone-codes.md)

---

## 2. Sinyal Lemah / Mau Kunci 4G/5G

| HP | Caranya |
|---|---|
| Android | `*#*#4636#*#*` → Phone Info → Set Preferred Network Type → `LTE Only` / `NR Only`. → [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |
| iPhone | Nggak bisa lock band via kode — Field Test cuma read-only. Solusinya pindah lokasi / Reset Network Settings / hubungin operator. |
| HarmonyOS | `*#*#2846579#*#*` → Network Information Query (read-only). |
| Feature Phone | Settings → Network selection → manual/auto. |

> Kalau di Android kamu set `LTE Only` tapi kartu belum VoLTE, nanti nggak bisa nelpon biasa — aktifin VoLTE dulu (Xiaomi: `*#*#86583#*#*`).

---

## 3. Curiga Panggilan Dialihkan / Disadap (Semua HP — Jangan Lupa Panggil)

> Ini jalan di semua HP karena diproses operator.

1. Ketik `*#21#` → **tap Panggil**. Liat `Voice: Forwarded to +62...`?
2. Kalau nomor asing dan bukan voicemail operator → ketik `##002#` → **Panggil** → `Erasing successful`.
3. Verifikasi lagi `*#21#` → Panggil → harusnya udah `Not Forwarded`.

Detail lengkapnya di [01-kode-ussd-mmi-universal.md](01-kode-ussd-mmi-universal.md).

---

## 4. Cek IMEI Buat Bea Cukai / Kemenperin

` *#06#` di semua HP — catat IMEI 1/2, cek di situs Kemenperin / bea cukai. Jangan sebar IMEI di medsos ya. → [04-troubleshooting-keamanan.md](04-troubleshooting-keamanan.md)

[← Universal](01-kode-ussd-mmi-universal.md) | [Lanjut ke Tips Menghafal →](03-tips-mengingat-kode.md)
