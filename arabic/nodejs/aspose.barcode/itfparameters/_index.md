---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات ITF."
type: docs
weight: 540
url: /ar/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

معلمات ITF.

```js
new ITFParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | يحصل على سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt. |
| [getBorderType()](#getbordertype) | نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | يحصل على سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px. |
| [setBorderThickness(value)](#setborderthickness) | يضبط سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt. |
| [setBorderType()](#setbordertype) | نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | يضبط سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px. |
| [toString()](#tostring) | إرجاع تمثيل نصي قابل للقراءة البشرية لهذا الكائن ITFParameters. |

### getBorderThickness() {#getborderthickness}

يحصل على سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

يحصل على سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px.

**Throws:** IllegalArgumentException
قيمة معامل QuietZoneCoef أقل من 10.

### setBorderThickness(value) {#setborderthickness}

يضبط سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt.

| معامل | الوصف |
| --- | --- |
| القيمة | حد ITF (شريط الحامل) سمكه بوحدة Unit. |

### setBorderType() {#setbordertype}

نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

يضبط سمك حد ITF (شريط الحامل) بوحدة Unit. القيمة الافتراضية: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

نوع الحد لباركود ITF. القيمة الافتراضية: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

حجم المناطق الهادئة في xDimension. القيمة الافتراضية: 10، مما يعني إذا كان xDimension = 2px فإن المناطق الهادئة ستكون 20px.

**Throws:** IllegalArgumentException
قيمة معامل QuietZoneCoef أقل من 10.

### toString() {#tostring}

إرجاع تمثيل نصي قابل للقراءة البشرية لهذا الكائن ITFParameters.

**Returns:** A string that represents this ITFParameters.
