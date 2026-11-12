---
title: "إعدادات الجودة"
linktitle: "إعدادات الجودة"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "تسمح إعدادات الجودة بتكوين جودة التعرف والسرعة يدويًا."
type: docs
weight: 860
url: /ar/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

تسمح إعدادات الجودة بتكوين جودة التعرف والسرعة يدويًا. يمكنك إعداد إعدادات الجودة بسرعة باستخدام القوالب المدمجة: HighPerformance، NormalQuality، HighQuality، MaxBarCodes أو يمكنك تكوين الخيارات المنفصلة يدويًا. القيمة الافتراضية لإعدادات الجودة هي NormalQuality.

```js
new QualitySettings()
```

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

## طرق

| اسم | الوصف |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | قالب جودة التعرف HighPerformance. يتم التعرف على الباركود عالي الجودة بشكل جيد في هذا الوضع. |
| [getHighQuality()](#gethighquality) *(static)* | قالب جودة التعرف HighQuality. تم تطوير هذا القالب للباركود منخفض الجودة. |
| [getMaxQuality()](#getmaxquality) *(static)* | قالب جودة التعرف MaxQuality. تم تطوير هذا القالب للتعرف على جميع الباركود الممكنة، حتى الباركود غير الصحيح. |
| [getNormalQuality()](#getnormalquality) *(static)* | قالب جودة التعرف NormalQuality. مناسب لمعظم الباركود. |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | يسمح للمحرك بالتعرف على الباركود الذي يحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركود التالف. |
| [getBarcodeQuality()](#getbarcodequality) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل r |
| [getComplexBackground()](#getcomplexbackground) | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركود الملون في الصور الملونة. |
| [getDeconvolution()](#getdeconvolution) | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة |
| [getInverseImage()](#getinverseimage) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة). |
| [getMinimalXDimension()](#getminimalxdimension) | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية مصفوفة أو شريط. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | يسمح للمحرك بالتعرف على الباركود الذي يحتوي على مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركود التالف. |
| [setBarcodeQuality(value)](#setbarcodequality) | الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل r |
| [setComplexBackground(value)](#setcomplexbackground) | الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركود الملون في الصور الملونة. |
| [setDeconvolution(value)](#setdeconvolution) | وضع فك الالتفاف (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة |
| [setInverseImage(value)](#setinverseimage) | الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة). |
| [setMinimalXDimension(value)](#setminimalxdimension) | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية مصفوفة أو شريط. |

### getHighPerformance() (static) {#gethighperformance}

قالب جودة التعرف HighPerformance. يتم التعرف على الباركود عالي الجودة بشكل جيد في هذا الوضع.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

قالب جودة التعرف HighQuality. تم تطوير هذا القالب للباركود منخفض الجودة.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

إعداد مسبق لجودة التعرف MaxQuality. تم تطوير هذا الإعداد المسبق للتعرف على جميع الباركودات الممكنة، حتى الباركودات غير الصحيحة. يوضح هذا المثال كيفية استخدام وضع MaxQuality reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } القيمة: إعداد مسبق لجودة التعرف MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

قالب جودة التعرف NormalQuality. مناسب لمعظم الباركود.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

يسمح للمحرك بالتعرف على الباركودات التي لديها مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

الوضع الذي يتيح الطرق للتعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركود الملون في الصور الملونة.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

وضع فك الالتفاف (استعادة الصورة) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. بما أننا لا نستطيع اكتشاف دالة الصورة التي تفسد الصورة، علينا فحص أكثر الدالات المعروفة مثل الحدة أو التشكل الرياضي.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية مصفوفة أو شريط.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

يسمح للمحرك بالتعرف على الباركودات التي لديها مجموع تحقق غير صحيح أو قيم غير صحيحة. يمكن استخدام الوضع للتعرف على الباركودات التالفة ذات النص غير الصحيح.

| معامل | الوصف |
| --- | --- |
| القيمة | يسمح للمحرك بالتعرف على الباركودات غير الصحيحة. |

### setBarcodeQuality(value) {#setbarcodequality}

الوضع الذي يتيح الطرق للتعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

| معامل | الوصف |
| --- | --- |
| القيمة | الوضع الذي يتيح الطرق للتعرف على عناصر الباركود بالجودة المحددة. |

### setComplexBackground(value) {#setcomplexbackground}

الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركود الملون في الصور الملونة.

| معامل | الوصف |
| --- | --- |
| القيمة | التعرف الإضافي على الباركودات الملونة في الصور الملونة. |

### setDeconvolution(value) {#setdeconvolution}

وضع فك الالتفاف (استعادة الصورة) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. بما أننا لا نستطيع اكتشاف دالة الصورة التي تفسد الصورة، علينا فحص أكثر الدالات المعروفة مثل الحدة أو التشكل الرياضي.

| معامل | الوصف |
| --- | --- |
| القيمة | وضع فك الالتفاف الذي يحدد مستوى تدهور الصورة. |

### setInverseImage(value) {#setinverseimage}

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (الإضاءة).

| معامل | الوصف |
| --- | --- |
| القيمة | التعرف الإضافي على الباركودات في الصور ذات الألوان العكسية |

### setMinimalXDimension(value) {#setminimalxdimension}

الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension.

| معامل | الوصف |
| --- | --- |
| القيمة | الحد الأدنى لحجم XDimension بالبكسل والذي يُستخدم مع UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية مصفوفة أو شريط.

| معامل | الوصف |
| --- | --- |
| القيمة | (من 1 إلى ما لا نهاية) للعنصر الأدنى للباركود: خلية مصفوفة أو شريط. |
