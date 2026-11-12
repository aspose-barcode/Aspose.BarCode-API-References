---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة للون CMYK."
type: docs
weight: 180
url: /ar/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

فئة للون CMYK. يعني وجود نسخة فارغة أن CMYK غير مستخدم، ويتم استخدام لون RGB الافتراضي.

```js
new CMYKColor(c, m, y, k)
```

ينشئ مثيلاً جديداً من فئة CMYKColor باستخدام قيم CMYK. من المتوقع أن تكون قيم CMYK في النطاق 0–100.

| معامل | نوع | الوصف |
| --- | --- | --- |
| c | عدد | – قيمة السيان [0, 100] |
| m | عدد | – قيمة الماجنتا [0, 100] |
| y | عدد | – قيمة الأصفر [0, 100] |
| k | عدد | – قيمة الأسود [0, 100] |

## طرق

| اسم | الوصف |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | تحليل سلسلة CMYK بالشكل "C_M_Y_K" إلى مثيل CMYKColor. |
| [formatCMYK()](#formatcmyk) | تنسيق هذا CMYKColor إلى سلسلة "C_M_Y_K"، بضرب كل مكوّن داخلي (0–1) في 100 وتدوير النتيجة. |
| [toString()](#tostring) | اختياري: تمثيل قابل للقراءة من قبل الإنسان. |

### parseCMYK(str) (static) {#parsecmyk}

تحليل سلسلة CMYK بالشكل "C_M_Y_K" إلى مثيل CMYKColor.

| معامل | نوع | الوصف |
| --- | --- | --- |
| str | سلسلة | – سلسلة مثل "30_100_0_30" |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

تنسيق هذا CMYKColor إلى سلسلة "C_M_Y_K"، بضرب كل مكوّن داخلي (0–1) في 100 وتدوير النتيجة.

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

اختياري: تمثيل قابل للقراءة من قبل الإنسان.
