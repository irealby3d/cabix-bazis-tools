# GibLab Export Skripti (v1.861 Cabix Edition)

Bazis-Mebelshchik loyihalaridagi detallar, frezerovka, priadka (sverlenie) va chizmalarni **GibLab** tizimiga to'g'ridan-to'g'ri eksport qilish uchun ixtisoslashgan avtomatlashtirish skripti.

> **Asl dvijok:** [giblab.com](https://giblab.com)  
> **Modifikatsiya va optimallashtirish muallifi:** `iRealBy_3D`  
> **Litsenziya:** Bepul foydalanish (Tijoriy qayta sotish qat'iyan taqiqlanadi!)

---

## 🚀 Asosiy afzalliklari va "L / R" tizimi

Asl skript giblab.com tomonidan taqdim etilgan, biroq standart eksportda detal kodlari va yuzalari chalkashlik tug'dirishi mumkin edi. `iRealBy_3D` tomonidan quyidagi muhim yaxshilanishlar kiritildi:

1. **Avtomatik `_L` va `_R` identifikatsiyasi:**
   - Detalning oldi (litsa / face) yuzasi uchun operatsiyalar avtomatik ravishda `_L` suffiksi bilan eksport qilinadi (`code="...xCount_L"`).
   - Detalning orqa (oborot / back) yuzasi uchun operatsiyalar avtomatik ravishda `_R` suffiksi bilan belgilanadi (`code="...xCount_R"`).
   - Bu stanok operatori va GibLab dasturida qaysi tarafga ishlov berilayotganini darhol aniqlash imkonini beradi.

2. **Toza detal nomlari (`Clean Part Names`):**
   - Detal nomlariga majburiy `№pozitsiya` tiqilishi olib tashlanib, Bazis modelidagi toza va aniq nomlar GibLab'ga uzatiladi.

3. **To'liq parametrli sozlamalar (`GibLabExport.prop`):**
   - Freza diametri, o'tish chuqurligi, kontur frezerovkasi, teshish (sverlenie) va paz parametrlari alohida XML konfiguratsiyasida saqlanadi.

---

## 📁 Fayllar tarkibi

| Fayl | Tavsif |
| :--- | :--- |
| **`GibLabExport_V1.861name_code.js`** | Asosiy Bazis JavaScript eksport skripti (L / R qo'llab-quvvatlaydi) |
| **`GibLabExport.prop`** | Skript sozlamalari fayli (asboblar, diametrlar, chegaralar) |

---

## 🛠 O'rnatish va ishlatish

1. `GibLabExport_V1.861name_code.js` va `GibLabExport.prop` fayllarini bitta papkaga (masalan, Bazis skriptlar papkasiga) yuklab oling.
2. **Bazis-Mebelshchik** dasturida modelni oching.
3. Menyu: **Скрипты -> Выполнить** orqali `GibLabExport_V1.861name_code.js` ni tanlang.
4. Chiqqan oynada parametrlarni tekshiring va **«Экспортировать»** tugmasini bosing.
5. Hosil bo'lgan faylni **GibLab** (giblab.com yoki Giblab Local) dasturiga yuklang.
