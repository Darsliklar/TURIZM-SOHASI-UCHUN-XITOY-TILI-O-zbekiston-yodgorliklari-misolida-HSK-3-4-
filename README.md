# Turizm sohasi uchun xitoy tili — audio va darslik sayti

GitHub Pages uchun tayyor sayt.

## Fayllar

| Fayl | Vazifasi |
|---|---|
| `index.html` | Audio sahifa. `index.html?=1` — 1-darsning audiolari, `index.html?=40` — 40-dars. Raqamsiz ochilsa, 40 darsning ro‘yxati chiqadi. |
| `darslik.html` | Darslikning to‘liq veb-nusxasi. Har bir darsning “Yangi so‘zlar”, “Dialog” va “Gid matni” bo‘limi yonida pleyer bor. `darslik.html#dars-5` — 5-dars. |
| `audio/` | MP3 fayllar. Nomlari `audio/FAYLLAR.txt` da. |
| `qr/` | Darslikka bosilgan QR-kodlar (`D01.png` … `D40.png`, `index.png` — bosh sahifa). |
| `HAVOLALAR.txt` | 40 darsning to‘liq havolalari. |

Havola quyidagi shakllarda ham ishlaydi: `index.html?=1`, `index.html?1`, `index.html?d=1`, `index.html#1`.

## Audio fayllarni nomlash

```
audio/D01_1_sozlar.mp3   1-dars, yangi so‘zlar
audio/D01_2_dialog.mp3   1-dars, dialog
audio/D01_3_matn.mp3     1-dars, gid matni (yoki nazariy matn / namunaviy nutq)
...
audio/D40_3_matn.mp3
```

Dars raqami doim ikki xonali (`D01`…`D40`). Fayl hali joylanmagan bo‘lsa, sahifada “Bu yozuv hali joylanmagan” yozuvi chiqadi, sayt buzilmaydi. Tavsiya etiladigan format: MP3, mono, 64–96 kbit/s.

## Manzillar

- Bosh sahifa: https://darsliklar.github.io/TURIZM-SOHASI-UCHUN-XITOY-TILI-O-zbekiston-yodgorliklari-misolida-HSK-3-4-/index.html
- 1-dars audiosi: https://darsliklar.github.io/TURIZM-SOHASI-UCHUN-XITOY-TILI-O-zbekiston-yodgorliklari-misolida-HSK-3-4-/index.html?=1 (… ?=40)
- Darslik matni: https://darsliklar.github.io/TURIZM-SOHASI-UCHUN-XITOY-TILI-O-zbekiston-yodgorliklari-misolida-HSK-3-4-/darslik.html

Darslikdagi QR-kodlar aynan shu manzillarga olib boradi. **Ombor nomini va `Darsliklar` username’ini o‘zgartirmang** — aks holda bosilgan QR-kodlar ishlamay qoladi.

## GitHub’ga joylash

1. Ombor: https://github.com/Darsliklar/TURIZM-SOHASI-UCHUN-XITOY-TILI-O-zbekiston-yodgorliklari-misolida-HSK-3-4-
2. Shu papkadagi hamma narsani omborga yuklang (Add file → Upload files). Fayllar 100 MB dan kichik bo‘lishi kerak, Git LFS ishlatmang.
3. Settings → Pages → Source: “Deploy from a branch”, Branch: `main`, papka: `/ (root)` → Save.
4. Bir-ikki daqiqadan keyin sayt yuqoridagi manzilda ochiladi.

## Darslik matni yangilansa

`darslik.html` Word faylidan avtomatik yasalgan. Darslik o‘zgarsa, uni qayta yasash kerak.
