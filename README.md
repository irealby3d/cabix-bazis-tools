# Cabix Bazis Tools 🛠️

**Bazis-Mebelshchik va Bazis-Raskroy uchun professional avtomatlashtirish vositalari, skriptlar va universal moslashuvchan etiketka.**

✍️ **Muallif / Developer:** `iRealBy_3D`  
🏛️ **Asl baza / Original Base:** Giblab  
🌐 **GitHub Pages:** [https://irealby3d.github.io/cabix-bazis-tools/](https://irealby3d.github.io/cabix-bazis-tools/)  
📜 **Litsenziya / License:** `License: Free (Resale strictly prohibited!)` — CC BY-NC-SA 4.0

---

## 📁 Repositoriy Tuzilishi (Structure)

```text
cabix-bazis-tools/
│
├── labels/                                          <-- Moslashuvchan etiketka shabloni (.lbl)
│   ├── Cabix_Etiket_58x40_80x60_v1.0.1.lbl          (Asosiy Universal Moslashuvchan shablon)
│   └── Readme.md                                    (Etiketka bo'yicha to'liq qo'llanma)
│
├── scripts/                                         <-- Kelajakdagi JS skriptlar
│   ├── raskroy/                                     (2D Raskroy va nesting skriptlari)
│   ├── panels/                                      (Panellar bilan ishlash, elastik o'lchamlar)
│   └── export/                                      (Eksport va hisobot generatorlari)
│
├── LICENSE                                          <-- CC BY-NC-SA 4.0 (Free - Resale strictly prohibited)
├── README.md                                        <-- Asosiy bosh sahifa
└── index.html                                       <-- GitHub Pages rasmiy veb-sayti
```

---

## 🏷️ Cabix Smart Adaptive Label v1.0.1 (`Cabix_Etiket_58x40_80x60_v1.0.1.lbl`)

Bazis-Raskroy uchun yagona, to'liq universal va dinamik moslashuvchan etiketka shabloni.

### ✨ Asosiy Imkoniyatlar:
1. **17 Pog'onali Proporsional Masshtab (`k`):**
   Printer o'lchami 58×40 dan 100×60 mm gacha bo'lgan har qanday lentaga avtomatik moslashadi. Shriftlar, QR-kodlar va texnologik ikonkalar lentaga qarab proporsional kattalashadi va kichrayadi.
2. **Nol To'qnashuv (Zero Collision):**
   Kromka chiziqlari detal o'lcham raqamlari yoki yozuvlar ustiga chiqib ketmaydi.
3. **Avtomatik Qoldiq (Остаток / Деловой остаток) Moduli:**
   `waste = true` bo'lganda omborni hisobga olish uchun maxsus yirik QR-kodli qoldiq etiketkasi shakllanadi.
4. **XNC va Ishlov Berish Belgilari:**
   Freza (Радиусы), paz (Паз), teshik (Сверление), chorak (Четверть) va 2 detal (Сшивка) belgilari to'liq aks etadi.

---

## 🚀 Qanday O'rnatiladi?

1. `labels/` papkasidagi **`Cabix_Etiket_58x40_80x60_v1.0.1.lbl`** faylini yuklab oling.
2. **Bazis-Raskroy** dasturini oching:
   - `Настройки` -> `Параметры бирки (этикетки)` bo'limiga kiring.
   - Shablonni ochish tugmasini bosib, `Cabix_Etiket_58x40_80x60_v1.0.1.lbl` faylini tanlang.
3. Printeringiz o'lchami bo'yicha (masalan `58x40` yoki `80x60`) chop etishni boshlang!

---

## 📜 Mualliflik Huquqi va Foydalanish Shartlari

- **Asl Shablon Asosi:** Giblab namunaviy ochiq shabloni
- **Arxitektura va Modifikatsiya Muallifi:** **`iRealBy_3D`**
- **Litsenziya:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- ⛔ **Qat'iy Talab (License: Free - Resale strictly prohibited!):**
  Ushbu shablon barcha mebel ustalari va korxonalar uchun **butunlay bepul**. Shablonni yoki uning kodini sotish, pullik kurslarga qo'shish, pullik paketlar tarkibida tarqatish yoki **qayta sotish QAT'IYAN TAQIQLANADI!**
