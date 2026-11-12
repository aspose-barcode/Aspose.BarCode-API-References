---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات."
type: docs
weight: 90
url: /ar/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader يضم صورة قد تحتوي على باركود واحد أو عدة باركودات، ثم يمكنه تنفيذ عملية ReadBarCodes لاكتشاف الباركودات.

```js
new BarCodeReader(image, areas, decodeTypes)
```

يُهيئ مثيلاً جديدًا من BarCodeReader

| معامل | الوصف |
| --- | --- |
| صورة | مُشفَّر كسلسلة base64 أو مسار إلى الصورة |
| المناطق | مصفوفة من الكائنات من النوع Rectangle |
| decodeTypes | مصفوفة الكائنات حسب DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | يصدّر خصائص الباركود إلى ملف XML المحدد |
| [containsAny()](#containsany) | يحدد ما إذا كان أي من أنواع الفك المشفرة المعطاة مدرجًا في |
| [exportToXml(xmlFile)](#exporttoxml) | يصدّر خصائص الباركود إلى ملف XML المحدد |
| [getBarCodeReadType()](#getbarcodereadtype) | يحصل على نوع فك الترميز لعملية فك شفرة الباركود المدخل |
| [getBarcodeSettings()](#getbarcodesettings) | معلمات فك ترميز الباركود الرئيسية. تحتوي على معلمات تؤثر على البيانات المعترف بها. |
| [getFoundBarCodes()](#getfoundbarcodes) | يحصل على مصفوفة BarCodeResult المعترف بها |
| [getFoundCount()](#getfoundcount) | يحصل على عدد الباركودات المعترف بها |
| [getQualitySettings()](#getqualitysettings) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة عن طريق em |
| [getTimeout()](#gettimeout) | يحصل على مهلة عملية التعرف بالمللي ثانية. |
| [readBarCodes()](#readbarcodes) | يقرأ BarCodeResult من الصورة. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | يضبط صورة البت ماب والمناطق للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | يضبط مصفوفة النوع SingleDecodeType للتعرف. يجب استدعاؤه قبل طريقة readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | تسمح QualitySettings بتكوين جودة وسرعة التعرف يدويًا. يمكنك إعداد QualitySettings بسرعة عن طريق em |
| [setTimeout(value)](#settimeout) | يضبط مهلة عملية التعرف بالمللي ثانية. |

### importFromXml(xmlFile) (static) {#importfromxml}

يصدّر خصائص الباركود إلى ملف XML المحدد

| معامل | الوصف |
| --- | --- |
| xmlFile | اسم الملف |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

يحدد ما إذا كان أي من أنواع الفك المشفرة المعطاة مدرجًا في

| معامل | الوصف |
| --- | --- |
| ...decodeTypes | أنواع للتحقق. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

يصدّر خصائص الباركود إلى ملف XML المحدد

| معامل | الوصف |
| --- | --- |
| xmlFile | اسم الملف |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

يحصل على نوع فك الترميز لعملية فك شفرة الباركود المدخل

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

معلمات فك ترميز الباركود الرئيسية. تحتوي على معلمات تؤثر على البيانات المعترف بها.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

يحصل على مصفوفة BarCodeResult المعترف بها

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

يحصل على عدد الباركودات المعترف بها

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

تسمح إعدادات الجودة بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد إعدادات الجودة بسرعة باستخدام القوالب المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لإعدادات الجودة هي NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

يحصل على مهلة عملية التعرف بالمللي ثانية.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

يقرأ BarCodeResult من الصورة.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

يضبط صورة البت ماب والمناطق للتعرف. يجب استدعاؤه قبل طريقة ReadBarCodes().

| معامل | الوصف |
| --- | --- |
| imageResource | الصورة للتعرف. |
| المناطق | قائمة المناطق للتعرف |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

يضبط مصفوفة النوع SingleDecodeType للتعرف. يجب استدعاؤه قبل طريقة readBarCodes().

| معامل | الوصف |
| --- | --- |
| الأنواع | مصفوفة النوع SingleDecodeType للقراءة. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

تسمح إعدادات الجودة بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد إعدادات الجودة بسرعة باستخدام القوالب المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لإعدادات الجودة هي NormalQuality.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

يضبط مهلة عملية التعرف بالمللي ثانية.

| معامل | الوصف |
| --- | --- |
| القيمة | المهلة. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
