# ProvisionX — Distribusi APK Android

Binari rilis publik aplikasi ProvisionX (kode sumber ada di repo privat).

## Unduh (selalu versi terbaru)

- **Pelanggan:** https://github.com/yandinovriandi/provisionx-apk/releases/latest/download/provisionx-pelanggan.apk
- **Reseller:** https://github.com/yandinovriandi/provisionx-apk/releases/latest/download/provisionx-reseller.apk
- **Operator:** https://github.com/yandinovriandi/provisionx-apk/releases/latest/download/provisionx-operator.apk

Tautan `releases/latest/download/...` selalu menunjuk ke rilis terbaru.

## Cara update versi baru

```
gh release create vX.Y.Z provisionx-*.apk -R yandinovriandi/provisionx-apk -t "vX.Y.Z" -n "catatan rilis"
# atau tambahkan aset ke rilis yang ada:
gh release upload vX.Y.Z provisionx-*.apk -R yandinovriandi/provisionx-apk --clobber
```
Nama berkas HARUS tetap sama agar tautan `latest/download` web tetap valid.
