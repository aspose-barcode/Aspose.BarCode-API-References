---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة المساعدة لتوليد النص الرمزي تلقائيًا لوضع Extended Codetext Mode"
type: docs
weight: 400
url: /ar/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

فئة المساعدة لتوليد النص الرمزي تلقائيًا لوضع Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | يضيف نص الشيفرة مع معرف القناة الموسعة |
| [addPlainCodetext(codetext)](#addplaincodetext) | يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة |
| [clear()](#clear) | يمسح عناصر النص الشيفري الموسعة |
| [getExtendedCodetext()](#getextendedcodetext) | إنشاء نص شيفري موسع من قائمة عناصر الإنشاء |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

يضيف نص الشيفرة مع معرف القناة الموسعة

| معامل | الوصف |
| --- | --- |
| ECIEncoding | معرف القناة الموسعة |
| codetext | نص شيفرة بترميز يونيكود لإضافته كعنصر نص شيفري موسع مع معرف القناة الموسعة |

### addPlainCodetext(codetext) {#addplaincodetext}

يضيف نص شيفرة عادي إلى عناصر النص الشيفري الموسعة

| معامل | الوصف |
| --- | --- |
| codetext | codetext بترميز Unicode لإضافته كعنصر codetext موسع |

### clear() {#clear}

يمسح عناصر النص الشيفري الموسعة

### getExtendedCodetext() {#getextendedcodetext}

إنشاء نص شيفري موسع من قائمة عناصر الإنشاء

**Returns:** Return string of extended codetext
