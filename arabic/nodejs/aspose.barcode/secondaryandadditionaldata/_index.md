---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC."
type: docs
weight: 880
url: /ar/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC.

```js
new SecondaryAndAdditionalData()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `SecondaryAndAdditionalData` محددة. |
| [getDateOfManufacture()](#getdateofmanufacture) | يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. Defa |
| [getExpiryDate()](#getexpirydate) | يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat على None. |
| [getExpiryDateFormat()](#getexpirydateformat) | يحدد تنسيق تاريخ الانتهاء. |
| [getLotNumber()](#getlotnumber) | يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. . |
| [getQuantity()](#getquantity) | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. Defa |
| [getSerialNumber()](#getserialnumber) | يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | ينشئ البيانات الثانوية والإضافية التكميلية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |
| [setDateOfManufacture()](#setdateofmanufacture) | يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. Defa |
| [setExpiryDate()](#setexpirydate) | يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat على None. |
| [setExpiryDateFormat()](#setexpirydateformat) | يحدد تنسيق تاريخ الانتهاء. |
| [setLotNumber()](#setlotnumber) | يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. . |
| [setQuantity()](#setquantity) | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. Defa |
| [setSerialNumber()](#setserialnumber) | يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [toString()](#tostring) | يحوّل البيانات إلى تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |

### equals(obj) {#equals}

يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `SecondaryAndAdditionalData` محددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة `SecondaryAndAdditionalData` للمقارنة مع هذه الحالة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat على None.

### getExpiryDateFormat() {#getexpirydateformat}

يحدد تنسيق تاريخ الانتهاء.

### getLotNumber() {#getlotnumber}

يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. .

### getQuantity() {#getquantity}

يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1

### getSerialNumber() {#getserialnumber}

يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

ينشئ البيانات الثانوية والإضافية التكميلية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC.

| معامل | الوصف |
| --- | --- |
| secondaryDataCodetext | سلسلة منسقة. |

### setDateOfManufacture() {#setdateofmanufacture}

يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat على None.

### setExpiryDateFormat() {#setexpirydateformat}

يحدد تنسيق تاريخ الانتهاء.

### setLotNumber() {#setlotnumber}

يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. .

### setQuantity() {#setquantity}

يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1

### setSerialNumber() {#setserialnumber}

يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

### toString() {#tostring}

يحوّل البيانات إلى تنسيق السلسلة وفقًا لمواصفات HIBC LIC.

**Returns:** Formatted string.
