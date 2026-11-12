---
title: "BaseGenerationParameters"
linktitle: "BaseGenerationParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات إنشاء صورة الباركود."
type: docs
weight: 160
url: /ar/nodejs/aspose.barcode/basegenerationparameters/
---

## BaseGenerationParameters class

معلمات إنشاء صورة الباركود.

```js
new BaseGenerationParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAutoSizeMode()](#getautosizemode) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE. |
| [getBackColor()](#getbackcolor) | لون الخلفية لصورة الباركود. القيمة الافتراضية: #FFFFFF |
| [getBarcode()](#getbarcode) | يحصل على BarcodeParameters التي تحتوي على جميع خصائص الباركود. |
| [getBorder()](#getborder) | يحصل على BorderParameters التي تحتوي على جميع خصائص التكوين لإطار الباركود. |
| [getCaptionAbove()](#getcaptionabove) | التسمية التوضيحية فوق صورة BarCode. راجع CaptionParameters. |
| [getCaptionBelow()](#getcaptionbelow) | التسمية التوضيحية أسفل صورة BarCode. راجع CaptionParameters. |
| [getImage()](#getimage) | معلمات الصورة. راجع ImageParameters. |
| [getImageHeight()](#getimageheight) | ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getImageWidth()](#getimagewidth) | عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [getResolution()](#getresolution) | يحصل على دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi. معلمة Resolution |
| [getRotationAngle()](#getrotationangle) | زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا Ro |
| [getUseAntiAlias()](#getuseantialias) | يحصل على قيمة تشير إلى ما إذا كان يتم استخدام وضع anti-aliasing لتصيير الصورة |
| [setAutoSizeMode()](#setautosizemode) | يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE. |
| [setBackColor()](#setbackcolor) | لون الخلفية لصورة الباركود. القيمة الافتراضية: #FFFFFF |
| [setImageHeight()](#setimageheight) | ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setImageWidth()](#setimagewidth) | عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. |
| [setResolution()](#setresolution) | يضبط دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi. معلمة Resolution |
| [setRotationAngle()](#setrotationangle) | زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا Ro |
| [setUseAntiAlias()](#setuseantialias) | يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع anti-aliasing لتصيير الصورة |

### getAutoSizeMode() {#getautosizemode}

يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE.

### getBackColor() {#getbackcolor}

لون الخلفية لصورة الباركود. القيمة الافتراضية: #FFFFFF

### getBarcode() {#getbarcode}

يحصل على BarcodeParameters التي تحتوي على جميع خصائص الباركود.

### getBorder() {#getborder}

يحصل على BorderParameters التي تحتوي على جميع خصائص التكوين لإطار الباركود.

### getCaptionAbove() {#getcaptionabove}

التسمية التوضيحية فوق صورة BarCode. راجع CaptionParameters.

### getCaptionBelow() {#getcaptionbelow}

التسمية التوضيحية أسفل صورة BarCode. راجع CaptionParameters.

### getImage() {#getimage}

معلمات الصورة. راجع ImageParameters.

**Returns:** ImageParameters

### getImageHeight() {#getimageheight}

ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

### getImageWidth() {#getimagewidth}

عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

### getResolution() {#getresolution}

يحصل على دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi. قيمة معلمة Resolution أقل من أو تساوي 0.

### getRotationAngle() {#getrotationangle}

زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا كان RotationAngle لا يساوي 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الصورة بواسطة الماسح. القيمة الافتراضية: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### getUseAntiAlias() {#getuseantialias}

يحصل على قيمة تشير إلى ما إذا كان يتم استخدام وضع anti-aliasing لتصيير الصورة

### setAutoSizeMode() {#setautosizemode}

يحدد الأنواع المختلفة لأوضاع التحجيم التلقائي. القيمة الافتراضية: AutoSizeMode.NONE.

### setBackColor() {#setbackcolor}

لون الخلفية لصورة الباركود. القيمة الافتراضية: #FFFFFF

### setImageHeight() {#setimageheight}

ارتفاع صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

### setImageWidth() {#setimagewidth}

عرض صورة BarCode عندما تكون خاصية AutoSizeMode مضبوطة على AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

### setResolution() {#setresolution}

يضبط دقة صورة BarCode. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 dpi. قيمة معلمة Resolution أقل من أو تساوي 0.

### setRotationAngle() {#setrotationangle}

زاوية دوران صورة BarCode، مقاسة بالدرجة، على سبيل المثال RotationAngle = 0 أو RotationAngle = 360 يعني عدم وجود دوران. إذا كان RotationAngle لا يساوي 90 أو 180 أو 270 أو 0، قد يزيد ذلك من صعوبة قراءة الصورة بواسطة الماسح. القيمة الافتراضية: 0.

**Example:**

```js
//This sample shows how to create and save a BarCode image.
    let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
    generator.getParameters().setRotationAngle(7);
    generator.save("test.png", BarcodeImageFormat.PNG);
```

### setUseAntiAlias() {#setuseantialias}

يضبط قيمة تشير إلى ما إذا كان يتم استخدام وضع anti-aliasing لتصيير الصورة
