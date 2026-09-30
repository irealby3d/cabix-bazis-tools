# Cabix Etiket v17 — Moslashuvchan Tizim Qo'llanmasi

## 1. Mualliflik va Tizim Pasporti (v17 Yangiligi)
Fayl ochilganda parametrlar oynasida eng tepada mualliflik huquqlari va ishlab chiquvchi ma'lumotlari chiqadi:

| Nomi | Qiymat | Tavsifi |
|---|---|---|
| `_info` | `Cabix Smart Adaptive System` | Tizimning rasmiy nomi |
| `developer` | `iRealBy_3D` | Muallif va dasturchi |
| `version` | `v17.0 Moslashuvchan` | Joriy versiya |
| `license` | `Barcha huquqlar himoyalangan (c) iRealBy_3D` | Litsenziya shartlari |

> ⚠️ **Himoya mexanizmi (Logic Watermark):**
> Agar `developer` parametri o'chirilsa yoki bo'sh qoldirilsa, `k` masshtabi avtomatik **0** ga aylanadi va butun etiketka matnlari/o'lchamlari ishlamay qoladi.

---

## 2. Tepadagi Sozlamalar (`[SOZLAMA]`)

| Nomi | Hozir | Nima qiladi | Qachon o'zgartirish kerak |
|---|---|---|---|
| `kadj` | 1 | Hamma narsaning umumiy masshtabi | Hammasi katta/kichik tuyulsa: 0.9 yoki 1.1 |
| `qrk` | 0.35 | QR o'lchami = ichki balandlik × qrk | QR kattaroq/kichikroq kerak bo'lsa (0.25 … 0.35) |
| `isz0` | 6 | Ikonka o'lchami (mm, 80x60 da) | Ikonkalar katta/kichik ko'rinsa |
| `ig0` | 1 | QR va ikonkalar orasidagi bo'shliq (mm) | Ikonkalar QR ga tegib qolsa oshiring |
| `tpad` | 2 | Chap matnlar bilan QR orasidagi zaxira (mm) | Matn QR ga tegsa oshiring |
| `lt` | 4.5 | Yuqori kromka chizig'i markazdan yuqoriga masofa | Chiziq matnga tegsa o'zgartiring |
| `lb` | 2.2 | Pastki kromka chizig'i markazdan pastga masofa | Chiziq matnga tegsa o'zgartiring |
| `ta` | 1 | Matn y-ankeri (1 = pastki chet, 0 = yuqori chet) | Matnlar siljib ketsa 0 qiling |
| `qrl` | 22 | Qoldiq (Остаток) etiketidagi QR o'lchami | Qoldiq QR o'lchamini o'zgartirish |
| `qtext1`| `Cabix by iRealBy_3D` | Qoldiqdagi erkin matn 1-qator (Muallif brendi) | Matn kiritish yoki o'zgartirish |
| `qtext2`| (bo'sh) | Qoldiqdagi erkin matn 2-qator | Qo'shimcha matn kerak bo'lsa |
| `kw`, `kh` | 76, 56 | Etalon (80x60) ichki o'lchami | **O'zgartirmang** |

---

## 3. Shrift Pog'onalari (17 darajali)
`k` masshtabiga qarab shriftlar 17 ta pog'onaga bo'lingan:
`1.5, 1.25, 1.0, 0.95, 0.9, 0.85, 0.8, 0.75, 0.7, 0.65, 0.6, 0.55, 0.5, 0.45, 0.4, 0.35, <0.35`.

* Masalan: 58×40 da `k ≈ 0.64` (0.6 pog'onasiga tushadi);
* 80×60 da `k = 1.0` (1.0 pog'onasiga tushadi).

---

## 4. Qoldiq (Остаток) va Detal Rejimi
* `waste = false` bo'lganda: Asosiy detal etiketkasi (o'lchamlar, kromkalar, XNC, loyiha, sana).
* `waste = true` bo'lganda: Katta QR kodli Qoldiq etiketkasi (`business = true` bo'lsa *"Деловой остаток"*, aks holda *"Остаток"*, `qtext1` bo'yicha `Cabix by iRealBy_3D` matni bilan).
