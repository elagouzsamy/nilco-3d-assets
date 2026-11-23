# nilco-3d-assets

مجسمات 3D (صور PNG بحجم 256×256 وخلفية شفافة) لاستخدامها في سيستمات NilCo والمحلات والتخليص.

## الأقسام
| الفولدر | المحتوى |
|---|---|
| `icons/money` | فلوس، خزنة، فواتير، رسوم بيانية |
| `icons/logistics` | شحن، مراكب، شاحنات، مخازن، محلات |
| `icons/general` | أيقونات عامة للأزرار (حفظ، تنبيه، إعدادات، عملاء…) |
| `icons/food` | خضار وفاكهة ومنتجات غذائية (مانجو، توابل، ألبان…) |
| `icons/oil-cars` | زيوت، عربيات، أدوات صيانة |
| `icons/clothes-sports` | ملابس وأحذية رياضية |
| `icons/electronics` | لابتوب، كمبيوتر، إكسسوارات |
| `icons/ai-marketing` | وكلاء الذكاء الاصطناعي، الحملات، الأهداف |

افتح `index.html` علشان تشوف كل المجسمات، وقايمة الأسماء كلها في `icons.json`.

## طريقة الاستخدام في السيستم
```html
<img src="icons/food/mango.png" width="48" alt="Mango">
```

## الرخصة
المجسمات من Microsoft Fluent UI Emoji، برخصة MIT (ملف `LICENSE-fluentui-emoji`). الاستخدام التجاري مسموح، بشرط إن ملف الرخصة يفضل موجود مع الملفات.

## مجسمات GLB (3D حقيقي يتلف)
فولدر `models/` فيه 12 مجسم GLB (أكل، تلاجة عرض، منتجات)، متصغّرين علشان يفتحوا بسرعة على الموبايل. افتح `models.html` علشان تشوفهم وتلفّهم، والقايمة كلها في `models.json`.

```html
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/4.0.0/model-viewer.min.js"></script>
<model-viewer src="models/food/avocado.glb" camera-controls auto-rotate></model-viewer>
```

الرخص في `models/LICENSES.md`: بعضها CC0 (من غير شروط)، وبعضها CC-BY-4.0 (لازم يتذكر اسم صاحبه).
