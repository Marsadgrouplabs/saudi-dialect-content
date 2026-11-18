<p align="center"><a href="README.md">English</a> · <b>العربية</b></p>

<p align="center"><img src=".github/assets/banner.ar.svg" width="100%" alt="Saudi Dialect Content: محتوى سعودي يفهمه أهل الديرة"></p>

> **محتوى سعودي يفهمه أهل الديرة.** تكتب وتعدّل وتراجع المحتوى العربي للجمهور السعودي، باللهجة البيضاء أو لهجات المناطق: نجدي وحجازي وشرقي وشمالي وجنوبي. تنفع للسوشيال والإعلانات والسكربتات وصفحات الهبوط.

## بتشتغل إزاي؟

<p align="center"><img src=".github/assets/flow.ar.svg" width="100%" alt="الخطوات: عطها النص، حدد المنطقة، الكتابة، المراجعة"></p>

## قولها كده وسيبها تشتغل

- «اكتب إعلان باللهجة السعودية البيضاء»
- «حوّل النص ده للهجة الحجازية»

## النتايج (بهزر، بس بجد مفيدة)

<p align="center"><img src=".github/assets/chart.ar.svg" width="100%" alt="رسم فكاهي غير علمي. نص مترجم وبارد: 90% من غيرها و8% معاها؛ كلمات مصرية متخفية: 75% من غيرها و5% معاها؛ تعليق «كفو عليك»: 15% من غيرها و88% معاها"></p>

## ركّبها في دقيقة

| بتستخدم إيه؟ | الطريقة |
|---|---|
| حساب Claude أو ChatGPT | نزّل [`saudi-dialect-content.zip`](https://github.com/Marsadgrouplabs/saudi-dialect-content/releases/latest/download/saudi-dialect-content.zip) وارفعه من قسم Skills |
| Claude Code | `claude plugin marketplace add Marsadgrouplabs/saudi-dialect-content` |
| Claude Code أو Codex بسكربت | حمّل الـ repo وشغّل `install.ps1` أو `install.sh` |

<details>
<summary><b>الخطوات بالتفصيل</b></summary>

### حساب Claude أو ChatGPT

1. نزّل [`saudi-dialect-content.zip`](https://github.com/Marsadgrouplabs/saudi-dialect-content/releases/latest/download/saudi-dialect-content.zip) وماتفكّهوش.
2. **Claude:** افتح قسم Skills في حسابك واختار رفع ملف.
3. **ChatGPT:** افتح Skills، ثم Create، ثم Upload from your computer. الميزة متاحة حسب خطة الحساب.

### Claude Code كـ Plugin

```bash
claude plugin marketplace add Marsadgrouplabs/saudi-dialect-content
claude plugin install saudi-dialect-content@marsad-saudi-dialect-content
```

### ويندوز

```powershell
git clone https://github.com/Marsadgrouplabs/saudi-dialect-content.git
cd saudi-dialect-content
powershell -ExecutionPolicy Bypass -File .\install.ps1
```

### ماك أو لينكس

```bash
git clone https://github.com/Marsadgrouplabs/saudi-dialect-content.git
cd saudi-dialect-content
bash install.sh
```

السكربت بيركّبها لـ Claude Code في `~/.claude/skills` ولـ Codex في `~/.agents/skills`، ولو فيه نسخة قديمة بيحتفظ بيها.

</details>

## مطمنك: مين الناشر وبياناتك فين؟

الناشر هو **[Marsad Labs](https://labs.marsadgroup.co)**. Marsad Labs هي ذراع المنتجات في Marsad Group، شركة تسويق مسجلة في بريطانيا، وبتبني أدوات عملية للمسوقين والمطورين. [اعرف أكتر عننا](https://labs.marsadgroup.co/about-us/) · [سياسة الخصوصية](https://labs.marsadgroup.co/privacy-policy/)

| السؤال | الإجابة |
|---|---|
| **بتقرا إيه؟** | النص أو الفكرة اللي بتديهالها. |
| **بتتصل بإيه؟** | كل الشغل بيتم جوه أداة الذكاء الاصطناعي اللي انت مستخدمها. |
| **محتاجة مفاتيح؟** | لأ. |
| **الكود** | تعليمات ومراجع نصية بس، ومفيهاش أي سكربتات بتشتغل على جهازك. |

النسخة دي اتفحصت بأداة SkillSpector، واتراجعت تنبيهاتها الحرجة والعالية يدوياً، واتشال منها أي بيانات عملاء أو مفاتيح. النتيجة الكاملة وطريقة التأكد من الملف والإبلاغ عن مشكلة في [`SECURITY.ar.md`](SECURITY.ar.md).

## محتاج إيه؟

- مفيش متطلبات خاصة.

## الحقوق

كل الحقوق محفوظة لـ Marsad Labs. ممنوع النسخ أو إعادة النشر بدون إذن.

---

<p align="center">معمولة بحب وشاي كتير في <a href="https://labs.marsadgroup.co"><b>Marsad Labs</b></a></p>
