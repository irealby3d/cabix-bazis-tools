# Cabix Bazis Tools 🛠️

**Bazis-Mebelshchik va Bazis-Raskroy uchun professional avtomatlashtirish vositalari, skriptlar va adaptiv etiketkalar to'plami.**

✍️ **Muallif:** `iRealBy_3D`  
🌐 **GitHub Pages:** [https://irealby3d.github.io/cabix-bazis-tools/](https://irealby3d.github.io/cabix-bazis-tools/)  
📜 **Litsenziya:** MIT License

---

## 📁 Repositoriy Tuzilishi (Structure)

```text
cabix-bazis-tools/
│
├── labels/                      <-- Moslashuvchan etiketka shablonlari (.lbl)
│   ├── Cabix_Etiket_v17_Moslashuvchan.lbl
│   ├── Qollanma_v17.md
│   │
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_UZ.lbl  (O'zbekcha)
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_RU.lbl  (Русский)
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_KZ.lbl  (Қазақша)
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_KG.lbl  (Кыргызча)
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_TJ.lbl  (Тоҷикӣ)
│   ├── Cabix_Etiket_58x40_80x60_v1_Moslashuvchan_EN.lbl  (English)
│   └── Qollanma_v1_Multilingual.md
│
├── scripts/                     <-- Kelajakdagi JS skriptlar
│   ├── raskroy/                 (2D Raskroy va nesting skriptlari)
│   ├── panels/                  (Panellar bilan ishlash, elastik o'lchamlar)
│   └── export/                  (Eksport va hisobot generatorlari)
│
├── LICENSE                      <-- Mualliflik litsenziyasi (MIT)
├── README.md                    <-- Asosiy bosh sahifa
└── index.html                   <-- GitHub Pages interaktiv veb-sayti
```

---

## 🏷️ labels/ — Cabix Smart Adaptive Labels

Bazis-Raskroy uchun 100% universal va dinamik moslashuvchan etiketkalar shabloni.

### Asosiy Imkoniyatlar:
1. **17 Pog'onali Proporsional Masshtab (`k`):**
   Printer o'lchami 58×40 dan 100×60 mm gacha o'zgarganda shriftlar, QR-kod va ikonkalar avtomatik ravishda mutanosib kattalashadi va kichrayadi.
2. **Nol To'qnashuv (Zero Collision):**
   Kromka chiziqlari raqamlar yoki yozuvlar ustiga chiqib ketmaydi.
3. **Qoldiq (Остаток / Деловой остаток) Rejimi:**
   `waste = true` bo'lganda omborni hisobga olish uchun maxsus yirik QR-kodli qoldiq etiketkasi chiqadi.
4. **Ko'p Tilli Qo'llab-quvvatlash:**
   O'zbek, Rus, Qazoq, Qirg'iz, Tojik va Ingliz tillaridagi tayyor shablonlar.

---

## 🚀 Qanday Foydalaniladi?

1. Ushbu omborni yuklab oling (`Code` -> `Download ZIP`) yoki klonlang:
   ```bash
   git clone https://github.com/irealby3d/cabix-bazis-tools.git
   ```
2. `labels/` papkasidagi o'zingizga kerakli `.lbl` faylni tanlang (masalan, `Cabix_Etiket_v17_Moslashuvchan.lbl` yoki tilga mos `..._UZ.lbl`).
3. **Bazis-Raskroy** dasturida:
   `Настройки` -> `Параметры бирки (этикетки)` bo'limiga kirib, yuklab olingan `.lbl` faylni tanlang.
4. Qog'oz o'lchami o'zgarganda shablon avtomatik ravishda moslashadi!

---

## 📜 Mualliflik Huquqi

Ushbu loyiha muallifi: **`iRealBy_3D`**.  
Loyiha ochiq kodli va erkin foydalanish uchun taqdim etiladi.
