---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "BarcodeGenerator لتوليد صور الباركود في الخلفية."
type: docs
weight: 130
url: /ar/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator لتوليد صور الباركود في الخلفية. الرموز المدعومة: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended, Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet, EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

منشئ BarcodeGenerator.

| معامل | الوصف |
| --- | --- |
| encodeType | نوع ترميز الباركود. استخدم الفئة EncodeTypes لإعداد الترميز. |
| codeText | النص المراد ترميزه. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## طرق

| اسم | الوصف |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | يستورد خصائص BarCode من ملف XML المحدد وينشئ مثيلة BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | يصدّر خصائص BarCode إلى ملف XML المحدد. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | أنشئ صورة الباركود وفق الإعدادات الحالية. يوضح هذا المثال كيفية إنشاء وحفظ صورة الباركود. |
| [getBarcodeType()](#getbarcodetype) | نوع ترميز الباركود. |
| [getCodeText()](#getcodetext) | النص المراد ترميزه. |
| [getParameters()](#getparameters) | معلمات الإنشاء. |
| [save(filePath, format)](#save) | احفظ صورة الباركود إلى ملف محدد بصيغة محددة. |
| [setBarcodeType()](#setbarcodetype) | نوع ترميز الباركود. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | يقوم بترميز Unicode `codeText ` إلى تسلسل بايت باستخدام `encoding ` المحدد. UTF-8 هو الترميز الأكثر شيوعًا. |

### importFromXml(filePath) (static) {#importfromxml}

يستورد خصائص BarCode من ملف XML المحدد وينشئ مثيلة BarcodeGenerator.

| معامل | الوصف |
| --- | --- |
| filePath | اسم الملف |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

يصدّر خصائص BarCode إلى ملف XML المحدد.

| معامل | الوصف |
| --- | --- |
| filePath | ملف xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

أنشئ صورة الباركود وفق الإعدادات الحالية. يوضح هذا المثال كيفية إنشاء وحفظ صورة الباركود.

| معامل | نوع | الوصف |
| --- | --- | --- |
| التنسيق | BarCodeImageFormat | قيمة BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

نوع ترميز الباركود.

### getCodeText() {#getcodetext}

النص المراد ترميزه.

### getParameters() {#getparameters}

معلمات الإنشاء.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

احفظ صورة الباركود إلى ملف محدد بصيغة محددة.

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار للحفظ إليه. |
| التنسيق | BarCodeImageFormat | قيمة BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

نوع ترميز الباركود.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

يقوم بترميز Unicode `codeText ` إلى تسلسل بايت باستخدام `encoding ` المحدد. UTF-8 هو الترميز الأكثر شيوعًا. إذا كان الترميز يدعم ذلك وتم تعيين `insertBOM ` إلى `true`، فإن الدالة تتضمن علامة ترتيب البايت (BOM). هذه الدالة مخصصة للاستخدام مع الباركود ثنائي الأبعاد فقط (مثل Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR، إلخ). تتيح الترميز اليدوي لنص Unicode باستخدام الترميزات الوطنية أو الخاصة؛ ومع ذلك، يعتبر هذا الأسلوب قديمًا في التطبيقات الحديثة. للحالات الحديثة، يُنصح باستخدام ترميز `ECI ` لبيانات Unicode. استخدام هذه الدالة مع باركود أحادي الأبعاد، أو باركود متوافق مع GS1 (بما في ذلك ثنائي الأبعاد)، أو باركود HIBC (بما في ذلك ثنائي الأبعاد) غير مدعوم من قبل معايير الباركود المقابلة وقد يؤدي إلى نتائج غير متوقعة. يوضح هذا المثال كيفية استخدام `SetCodeText` مع أو بدون BOM للباركود ثنائي الأبعاد.
//Encode codetext using UTF-8 with BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText(\"車種名\", \"UTF-8\", true);
gen.save(\"barcode.png\", BarCodeImageFormat.PNG);
let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log(\"BarCode CodeText: \" + result.getCodeText());
}
//Encode codetext using UTF-8 without BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText(\"車種名\", \"UTF-8\", false);
gen.save(\"barcode.png\", BarCodeImageFormat.PNG);
let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log(\"BarCode CodeText: \" + result.getCodeText());
}

| معامل | الوصف |
| --- | --- |
| codeText | سلسلة CodeText |
| الترميز | الترميز المطبق |
| insertBOM | يحدد ما إذا كان يجب إدراج علامة ترتيب البايت (BOM) عندما يدعم الترميز المحدد ذلك (مثل UTF-8, UTF-16, UTF-32). إذا تم تعيينه إلى `true`، يتم إضافة الـ BOM؛ إذا كان `false`، يتم حذف الـ BOM حتى لو كان الترميز يستخدمه عادةً. |
