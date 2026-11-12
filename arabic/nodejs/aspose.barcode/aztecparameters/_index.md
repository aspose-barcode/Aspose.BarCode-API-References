---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات Aztec."
type: docs
weight: 70
url: /ar/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

معلمات Aztec.

```js
new AztecParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | يحصل على ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [getErrorLevel()](#geterrorlevel) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95. |
| [getLayersCount()](#getlayerscount) | يحصل على عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع Compact وفي النطاق من 1 إلى 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | معرف الباركود لوضع Structured Append لباركود Aztec. يجب أن يكون معرف الباركود في النطاق من 1 إلى عدد الباركودات. الافتراضي |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | عدد الباركود في وضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركود في النطاق من 1 إلى 26. القيمة الافتراضية |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: |
| [getSymbolMode()](#getsymbolmode) | يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setAspectRatio()](#setaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [setErrorLevel()](#seterrorlevel) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95. |
| [setLayersCount()](#setlayerscount) | يضبط عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 لوضع Compact وفي النطاق من 1 إلى 3 |
| [setReaderInitialization()](#setreaderinitialization) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | معرف الباركود لوضع Structured Append لباركود Aztec. يجب أن يكون معرف الباركود في النطاق من 1 إلى عدد الباركودات. الافتراضي |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | عدد الباركود في وضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركود في النطاق من 1 إلى 26. القيمة الافتراضية |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: |
| [setSymbolMode(value)](#setsymbolmode) | يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto. |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

يحصل على ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

### getEncodeMode() {#getencodemode}

يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

### getLayersCount() {#getlayerscount}

يحصل على عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 لوضع Compact وفي النطاق من 1 إلى 32 لوضع Full Range. القيمة الافتراضية: 0 (تلقائي).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركود. القيمة الافتراضية: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

عدد الباركود في وضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركود في النطاق من 1 إلى 26. القيمة الافتراضية: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

### getSymbolMode() {#getsymbolmode}

يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

### setAspectRatio() {#setaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto.

| معامل | الوصف |
| --- | --- |
| القيمة | وضع ترميز Aztec. |

### setErrorLevel() {#seterrorlevel}

مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

### setLayersCount() {#setlayerscount}

يضبط عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 لوضع Compact وفي النطاق من 1 إلى 32 لوضع Full Range. القيمة الافتراضية: 0 (تلقائي).

### setReaderInitialization() {#setreaderinitialization}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركود. القيمة الافتراضية: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

عدد الباركود في وضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركود في النطاق من 1 إلى 26. القيمة الافتراضية: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

### setSymbolMode(value) {#setsymbolmode}

يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

| معامل | الوصف |
| --- | --- |
| القيمة | وضع رمز Aztec. |

### toString() {#tostring}

يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
