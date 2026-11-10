# 🌊 تعريب لعبة BioShock Remastered الكامل (الإصدار المدقق 2.1.0)
### BioShock Remastered — Complete Arabic Localization Patch

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.1.0--Audited-gold?style=for-the-badge" alt="Version 2.1.0">
  <img src="https://img.shields.io/badge/Platform-PC%20(Steam%20%2F%20GOG)-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Language-العربية%20(Arabic)-green?style=for-the-badge" alt="Language">
  <img src="https://img.shields.io/badge/Font-Cairo%20(SIL%20OFL%201.1)-orange?style=for-the-badge" alt="Font">
  <img src="https://img.shields.io/badge/Status-100%25%20Tested-brightgreen?style=for-the-badge" alt="Tested">
</p>

---

## 📖 نبذة عن المشروع (About the Project)

مشروع تعريب كامل واحترافي للتحفة الكلاسيكية **BioShock Remastered** على الكمبيوتر (PC). يغطي التعريب جميع جوانب اللعبة من البداية للنهاية بدقة لغوية وهندسية عالية، مع مراعاة الطابع القصصي والسوداوي لمدينة **رابتشر (Rapture)** تحت الماء.

تم تدقيق هذا الإصدار هندسياً وفحص جميع ملفات المحرك وتوافق خط **Cairo** المدمج مع محرك **Scaleform GFx**، مع دعم اتجاه الكتابة الصحيح من اليمين إلى اليسار (RTL) والحفاظ على بنية ملفات الحفظ وسلامتها.

---

## ✨ المميزات الرئيسية (Features)

* **تعريب شامل 100% لجميع النصوص:**
  * جميع القوائم الرئيسية، الإعدادات، وأزرار التحكم.
  * واجهة المستخدم داخل اللعبة (HUD) والخرائط وشاشات الأهداف.
  * رسائل التدريب، شاشات التطوير في محطات الاختراع ومحطات المقويات الجينية.
* **ترجمة درامية كاملة لحوارات الشخصيات:**
  * مكالمات الراديو مع أطلس (Atlas) وخطابات أندرو رايان (Andrew Ryan).
  * جميع التسجيلات الصوتية (Audio Diaries) الموزعة في أرجاء رابتشر.
  * تعليقات وهمسات الأخوات الصغيرات (Little Sisters) والسبلايسرز (Splicers).
* **ترجمة وثائقي تعليق المخرج (Director's Commentary):**
  * ترجمة كاملة لجميع الأفلام الوثائقية الـ 11 الحصرية المدمجة داخل اللعبة (1,710 كتلة حوارية).
* **خط عربي أنيق ومتصل:**
  * حقن خط **Cairo** (برخصة SIL OFL 1.1) داخل كافة ملفات Flash الداخلية لمنع ظهور أي مربعات مفقودة (Tofu).
* **حزمة خفيفة وسهلة التثبيت:**
  * تثبيت بنقرة زر واحدة عبر برنامج مستقل أو نسخ يدوي بسيط.
  * لا يتم المساس بملفات اللعبة الأصلية إلا عبر استبدال ملفات اللغات، مع إمكانية الإزالة النظيفة في أي وقت.

---

## 📥 التحميل (Download)

يمكنك تحميل حزمة التعريب من قسم **[Releases](../../releases)**:

| الملف | الوصف | الحجم | الرابط |
| :--- | :--- | :---: | :---: |
| **ملف تعريب.zip** | حزمة التعريب الكاملة (تتضمن برنامج التثبيت التلقائي والمجلد اليدوي) | ~85 MB | [تحميل الإصدار الأحدث](../../releases/latest) |

---

## 🛠️ طرق التثبيت (Installation Guide)

### 🔹 الطريقة الأولى: التثبيت التلقائي (موصى بها)
1. حمّل ملف `ملف تعريب.zip` وفك الضغط عنه.
2. شغّل البرنامج المرفق: `BioShock_Remastered_Arabic_Setup.exe`.
3. سيتعرف البرنامج تلقائياً على مسار اللعبة (أو يمكنك اختياره يدوياً).
4. اضغط على **[تثبيت التعريب]**.
5. سيتم أخذ نسخة احتياطية لملفاتك وتثبيت التعريب في ثوانٍ.

### 🔹 الطريقة الثانية: التثبيت اليدوي (عبر النسخ واللصق)
1. افتح مجلد اللعبة الرئيسي:
   * **Steam:** كليك يمين على اللعبة في المكتبة ⬅️ `Manage` ⬅️ `Browse local files`.
   * المسار الافتراضي عادة:  
     `C:\Program Files (x86)\Steam\steamapps\common\BioShock Remastered`
2. انسخ مجلد `ContentBaked` من داخل حزمة التعريب.
3. الصقه داخل مجلد اللعبة الرئيسي `BioShock Remastered`.
4. وافق على استبدال الملفات عند ظهور المطالبة: **[Replace the files in the destination]**.
5. شغّل اللعبة واستمتع!

---

## 📁 هيكلية ملفات التعريب (File Structure)

```text
BioShock Remastered/
└── ContentBaked/
    └── pc/
        ├── Localizedint.lbf                     # الأرشيف الثنائي المجمّع لنصوص اللعبة (34 ملف .int)
        ├── FlashMovies/                         # ملفات الواجهة والخط العربي المدمج
        │   ├── fonts.swf
        │   ├── HUDPC.swf
        │   ├── maps.swf
        │   ├── mapsPC.swf
        │   ├── pause.swf
        │   ├── pausePC.swf
        │   └── sharedlibrary.swf
        └── BinkMovies/                          # ترجمات أفلام تعليق المخرج
            ├── DC_1-Medical_INT.srt
            ├── DC_1-Welcome_INT.srt
            ├── DC_2-Fisheries_INT.srt
            └── ... (11 files)
```

---

## ⚖️ الحقوق والرخصة (License & Credits)

* **حقوق اللعبة الأصلية:** جميع الحقوق محفوظة لشركة **2K Games** و **Blind Squirrel Games**. هذا التعديل غير رسمي ومجاني بالكامل لعشاق السلسلة في الوطن العربي.
* **الخط العربي:** خط **Cairo** مرخص تحت رخصة الخطوط المفتوحة **SIL Open Font License 1.1**.
* **كود التثبيت والأدوات:** مرخصة تحت رخصة **MIT**.

---

<p align="center">
  صُنع بكل حب لعشاق الألعاب باللغة العربية 🤍
</p>
