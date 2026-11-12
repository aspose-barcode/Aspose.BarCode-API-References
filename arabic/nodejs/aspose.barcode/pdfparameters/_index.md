---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "غلاف معلمات PDF."
type: docs
weight: 780
url: /ar/nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

غلاف معلمات PDF. يتوقع كائن `mwObject` أساسي يوفر طرق getter/setter المقابلة التي تُعيد/تقبل سلاسل CMYK مثل "30_100_0_30" أو `null`.

```js
new PdfParameters(mwObject)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mwObject | كائن | – كائن من فئة Java PdfParameters |

## طرق

| اسم | الوصف |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | مُهيئ لا-عملية |
| [getCMYKBackColor()](#getcmykbackcolor) | قيمة لون الخلفية CMYK. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [getCMYKBarColor()](#getcmykbarcolor) | قيمة لون CMYK للباركود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | قيمة لون CMYK للتعليق أعلاه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | قيمة لون CMYK للتعليق أدناه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | قيمة لون CMYK لنص الكود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [isTextAsPath()](#istextaspath) | هل تُستخدم المسارات بدلاً من النص (استخدم إذا لم تُعرض أحرف Unicode) القيمة الافتراضية: false. |
| [setCMYKBackColor(value)](#setcmykbackcolor) | قيمة لون الخلفية CMYK. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [setCMYKBarColor(value)](#setcmykbarcolor) | قيمة لون CMYK للباركود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | قيمة لون CMYK للتعليق أعلاه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | قيمة لون CMYK للتعليق أدناه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | قيمة لون CMYK لنص الكود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي. |
| [setTextAsPath()](#settextaspath) | هل تُستخدم المسارات بدلاً من النص (استخدم إذا لم تُعرض أحرف Unicode) القيمة الافتراضية: false. |

### _initializeWrapperMembers() {#-initializewrappermembers}

مُهيئ لا-عملية

### getCMYKBackColor() {#getcmykbackcolor}

قيمة لون الخلفية CMYK. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

قيمة لون CMYK للباركود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

قيمة لون CMYK للتعليق أعلاه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

قيمة لون CMYK للتعليق أدناه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

قيمة لون CMYK لنص الكود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

هل تُستخدم المسارات بدلاً من النص (استخدم إذا لم تُعرض أحرف Unicode) القيمة الافتراضية: false.

### setCMYKBackColor(value) {#setcmykbackcolor}

قيمة لون الخلفية CMYK. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | CMYKColor\ | null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

قيمة لون CMYK للباركود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | CMYKColor\ | null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

قيمة لون CMYK للتعليق أعلاه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | CMYKColor\ | null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

قيمة لون CMYK للتعليق أدناه. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | CMYKColor\ | null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

قيمة لون CMYK لنص الكود. يعني Null أن لون CMYK غير مستخدم، وبدلاً من ذلك يُستخدم لون RGB العادي.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | CMYKColor\ | null |  |

### setTextAsPath() {#settextaspath}

هل تُستخدم المسارات بدلاً من النص (استخدم إذا لم تُعرض أحرف Unicode) القيمة الافتراضية: false.
