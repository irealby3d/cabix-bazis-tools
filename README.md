# Cabix Bazis Tools 🛠️

**Giblab Local dasturi va giblab.com saytida to'liq test qilingan, Bazis-Mebelshchik va Bazis-Raskroy uchun professional universal moslashuvchan etiketka.**

✍️ **Muallif / Developer:** `iRealBy_3D`  
🏛️ **Asl baza / Original Base:** Giblab  
🧪 **Sinov / Tested:** **Giblab Local** dasturi va **[giblab.com](https://giblab.com)** platformasida 100% test qilingan va sinovdan o'tgan  
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
├── scripts/                                         <-- Avtomatlashtirish JS skriptlari
│   ├── raskroy/                                     (2D Raskroy va nesting skriptlari)
│   ├── panels/                                      (Panellar bilan ishlash, elastik o'lchamlar)
│   └── export/                                      (GibLab eksport skripti: L / R tizimi)
│       ├── GibLabExport_V1.861name_code.js          (Asosiy eksport skripti)
│       ├── GibLabExport.prop                        (Konfiguratsiya sozlamalari)
│       └── README.md                                (Skript qo'llanmasi)
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


---

## 📹 Video Qo'llanma (Video Guide)

Etiketkani Bazis-Raskroy dasturiga o'rnatish, printer o'lchamlarini tanlash va chop etish jarayoni bo'yicha to'liq amaliy video darslik:
- ⚙️ **Parametrlar va sozlamalar qo'llanmasi:** [sozlamalar.html](https://irealby3d.github.io/cabix-bazis-tools/sozlamalar.html)
- 🎬 **Onlayn tomosha qilish (GitHub Pages):** [https://irealby3d.github.io/cabix-bazis-tools/#video-guide](https://irealby3d.github.io/cabix-bazis-tools/#video-guide)
- ⚡ **Tezkor yuklab olish (x265, 22.8 MB):** [Cabix_Etiket_58x40_80x60_v1.0.1_guide_x265.mp4](https://github.com/irealby3d/cabix-bazis-tools/releases/download/v1.0.1/Cabix_Etiket_58x40_80x60_v1.0.1_guide_x265.mp4)
- 📥 **Asl variantni yuklab olish (H.264, 271 MB):** [Cabix_Etiket_58x40_80x60_v1.0.1_guide.mp4](https://github.com/irealby3d/cabix-bazis-tools/releases/download/v1.0.1/Cabix_Etiket_58x40_80x60_v1.0.1_guide.mp4)
- 📦 **Rasmiy GitHub Reliz:** [Releases v1.0.1](https://github.com/irealby3d/cabix-bazis-tools/releases/tag/v1.0.1)

## 🚀 Qanday O'rnatiladi?

1. `labels/` papkasidagi **`Cabix_Etiket_58x40_80x60_v1.0.1.lbl`** faylini yuklab oling.
2. **Bazis-Raskroy** dasturini oching:
   - `Настройки` -> `Параметры бирки (этикетки)` bo'limiga kiring.
   - Shablonni ochish tugmasini bosib, `Cabix_Etiket_58x40_80x60_v1.0.1.lbl` faylini tanlang.
3. Printeringiz o'lchami bo'yicha (masalan `58x40` yoki `80x60`) chop etishni boshlang!

---

## ⚙️ GibLab Export Skripti (v1.861 Cabix Edition)

GibLab tizimi va [giblab.com](https://giblab.com) uchun Bazis-Mebelshchik modelidan detallar, frezerovka, priadka (sverlenie) va chizmalarni kesishga to'liq tayyorlab beradigan professional eksport skripti.

- **Asl baza:** [giblab.com](https://giblab.com) rasmiy eksport skripti
- **Modifikatsiya va yangilanishlar muallifi:** `iRealBy_3D`

### 🌟 Asosiy Imkoniyatlar va "L / R" Tizimi:
1. **Oldi va Orqa Yuzalarni Avtomatik Farqlash ("L" va "R"):**
   - Detalning old (litsa / face) yuzasidagi operatsiyalar avtomatik ravishda `_L` (Left / Face) bilan belgilanadi (`side="true"`, `code="...xCount_L"`).
   - Detalning orqa (oborot / back) yuzasidagi operatsiyalar avtomatik ravishda `_R` (Right / Back) bilan belgilanadi (`side="false"`, `code="...xCount_R"`).
   - Bu stanok operatoriga qaysi tarafga ishlov berilayotganini aniq ko'rsatib, xatoliklarni oldini oladi.
2. **Toza Detal Nomlari (Clean Part Names):**
   - Detal nomlariga majburiy `№pozitsiya` tiqilishi olib tashlangan, modeldagi toza nom to'g'ridan-to'g'ri GibLab'ga uzatiladi.
3. **Moslashuvchan Sozlamalar (`GibLabExport.prop`):**
   - Freza diametri, o'tish chuqurligi, priadka va paz parametrlari alohida XML konfiguratsiyasida qulay boshqariladi.

### 📥 Fayllar:
- 📜 **Skript:** [`scripts/export/GibLabExport_V1.861name_code.js`](https://github.com/irealby3d/cabix-bazis-tools/raw/main/scripts/export/GibLabExport_V1.861name_code.js)
- ⚙️ **Sozlamalar:** [`scripts/export/GibLabExport.prop`](https://github.com/irealby3d/cabix-bazis-tools/raw/main/scripts/export/GibLabExport.prop)
- 📖 **Batafsil qo'llanma:** [`scripts/export/README.md`](https://github.com/irealby3d/cabix-bazis-tools/blob/main/scripts/export/README.md)

---

## 📜 Mualliflik Huquqi va Foydalanish Shartlari

- **Asl Shablon Asosi:** Giblab namunaviy ochiq shabloni
- **Arxitektura va Modifikatsiya Muallifi:** **`iRealBy_3D`**
- **Litsenziya:** [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- ⛔ **Qat'iy Talab (License: Free - Resale strictly prohibited!):**
  Ushbu shablon barcha mebel ustalari va korxonalar uchun **butunlay bepul**. Shablonni yoki uning kodini sotish, pullik kurslarga qo'shish, pullik paketlar tarkibida tarqatish yoki **qayta sotish QAT'IYAN TAQIQLANADI!**
