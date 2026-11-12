---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات DotCode."
type: docs
weight: 390
url: /ar/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

معلمات DotCode.

```js
new DotCodeParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [getColumns()](#getcolumns) | يحدد عدد الأعمدة. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون عددًا فرديًا. Number o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. |
| [getECIEncoding()](#geteciencoding) | يحدد ترميز ECI. يُستخدم عندما تكون DotCodeEncodeMode هي AUTO. القيمة الافتراضية: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [getRows()](#getrows) | يحدد عدد الصفوف. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. عدد r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. |
| [isReaderInitialization()](#isreaderinitialization) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [setAspectRatio()](#setaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [setColumns()](#setcolumns) | يحدد عدد الأعمدة. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون عددًا فرديًا. Number o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. |
| [setECIEncoding()](#seteciencoding) | يحدد ترميز ECI. يُستخدم عندما تكون DotCodeEncodeMode هي AUTO. القيمة الافتراضية: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [setReaderInitialization()](#setreaderinitialization) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [setRows()](#setrows) | يحدد عدد الصفوف. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. عدد r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا قابلًا للقراءة من قبل الإنسان لهذا DotCodeParameters. |

### getAspectRatio() {#getaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### getColumns() {#getcolumns}

يحدد عدد الأعمدة. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

### getECIEncoding() {#geteciencoding}

يحدد ترميز ECI. يُستخدم عندما تكون DotCodeEncodeMode هي AUTO. القيمة الافتراضية: ISO-8859-1

### getEncodeMode() {#getencodemode}

يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

### getRows() {#getrows}

يحدد عدد الصفوف. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

### isReaderInitialization() {#isreaderinitialization}

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### setAspectRatio() {#setaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### setColumns() {#setcolumns}

يحدد عدد الأعمدة. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

### setECIEncoding() {#seteciencoding}

يحدد ترميز ECI. يُستخدم عندما تكون DotCodeEncodeMode هي AUTO. القيمة الافتراضية: ISO-8859-1

### setEncodeMode() {#setencodemode}

يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

### setReaderInitialization() {#setreaderinitialization}

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### setRows() {#setrows}

يحدد عدد الصفوف. مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode يجب أن يكون فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

يحدد عدد الباركودات في وضع الإلحاق المهيكل لرمز DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

### toString() {#tostring}

يعيد تمثيلًا نصيًا قابلًا للقراءة من قبل الإنسان لهذا DotCodeParameters.

**Returns:** A string that represents this DotCodeParameters.
