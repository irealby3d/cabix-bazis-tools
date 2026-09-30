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
├── labels/                                          <-- Moslashuvchan etiketka shablonlari (.lbl)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1.lbl          (Asosiy Moslashuvchan shablon)
│   ├── Readme.md                                    (Barcha tillardagi Release Notes)
│   │
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1_UZ.lbl       (🇺🇿 O'zbekcha - 100% o'zbekcha matnlar)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1_RU.lbl       (🇷🇺 Русский - 100% русские тексты)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1_KZ.lbl       (🇰🇿 Қазақша - 100% қазақша мәтіндер)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1_KG.lbl       (🇰🇬 Кыргызча - 100% кыргызча тексттер)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1_TJ.lbl       (🇹🇯 Тоҷикӣ - 100% матнҳо бо забони тоҷикӣ)
│   └── Cabix_Etiket_58x40_80x60_v1.0.1_EN.lbl       (🇬🇧 English - 100% English texts)
│
├── scripts/                                         <-- Kelajakdagi JS skriptlar
│   ├── raskroy/                                     (2D Raskroy va nesting skriptlari)
│   ├── panels/                                      (Panellar bilan ishlash, elastik o'lchamlar)
│   └── export/                                      (Eksport va hisobot generatorlari)
│
├── LICENSE                                          <-- MIT Mualliflik litsenziyasi (iRealBy_3D)
├── README.md                                        <-- Asosiy bosh sahifa
└── index.html                                       <-- GitHub Pages interaktiv veb-sayti
```

---

## 🏷️ labels/ — Cabix Smart Adaptive Labels

Bazis-Raskroy uchun 100% universal va dinamik moslashuvchan etiketkalar shabloni.

### Asosiy Imkoniyatlar:
1. **Dinamik Til Sozlamasi (v1.01):**
   `Cabix_Etiket_v1.01_Moslashuvchan_MultiLang.lbl` faylida etiketka tilini parametrlardan bir zumda tanlash mumkin (`lang`: `1=UZ`, `2=RU`, `3=KZ`, `4=KG`, `5=TJ`, `6=EN`).
2. **100% Mahalliy Tilga Moslashgan Shablonlar (v1.0):**
   Har bir MDH davlati va xalqaro foydalanuvchilar uchun alohida to'liq o'z tilidagi izohlar va matnlarga ega shablonlar mavjud.
3. **17 Pog'onali Proporsional Masshtab (`k`):**
   Printer o'lchami 58×40 dan 100×60 mm gacha o'zgarganda shriftlar, QR-kod va ikonkalar avtomatik ravishda mutanosib kattalashadi va kichrayadi.
4. **Nol To'qnashuv (Zero Collision):**
   Kromka chiziqlari raqamlar yoki yozuvlar ustiga chiqib ketmaydi.
5. **Qoldiq (Остаток / Деловой остаток) Rejimi:**
   `waste = true` bo'lganda omborni hisobga olish uchun maxsus yirik QR-kodli qoldiq etiketkasi chiqadi.

---

## 🚀 Qanday Foydalaniladi?

1. Ushbu omborni yuklab oling (`Code` -> `Download ZIP`) yoki klonlang:
   ```bash
   git clone https://github.com/irealby3d/cabix-bazis-tools.git
   ```
2. `labels/` papkasidan o'zingizga ma'qul `.lbl` faylni tanlang:
   - Agar tilni Bazis ichidan tanlamoqchi bo'lsangiz: `Cabix_Etiket_v1.01_Moslashuvchan_MultiLang.lbl`
   - Agar to'liq o'z tilingizdagi shablonni istasangiz: `Cabix_Etiket_58x40_80x60_v1_UZ.lbl` (yoki RU, KZ, KG, TJ, EN).
3. **Bazis-Raskroy** dasturida:
   `Настройки` -> `Параметры бирки (этикетки)` bo'limiga kirib, tanlangan `.lbl` faylni oching.

---

## 📜 Mualliflik Huquqi

Ushbu loyiha muallifi: **`iRealBy_3D`**.  
Loyiha ochiq kodli va erkin foydalanish uchun taqdim etiladi (MIT License).
