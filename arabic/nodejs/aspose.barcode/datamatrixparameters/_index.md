---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات DataMatrix."
type: docs
weight: 360
url: /ar/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

معلمات DataMatrix.

```js
new DataMatrixParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [getColumns()](#getcolumns) | عدد الأعمدة. |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | يحصل على نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | يحصل على حجم رمز Datamatrix. القيمة الافتراضية: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | يحصل على نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | يحصل على ترميز ECI. يُستخدم عندما يكون DataMatrixEncodeMode على Auto. القيمة الافتراضية: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 أحرف الماكرو 11.3 بروتوكول لأحرف الماكرو في الموضع الأول (ECC 200 فقط) Macro Cha |
| [getRows()](#getrows) | عدد الصفوف. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | معرف الباركود لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | عدد الباركودات لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | معرف الملف لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [getVersion()](#getversion) | يحصل على حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setAspectRatio()](#setaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [setColumns()](#setcolumns) | عدد الأعمدة. |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | يضبط نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | يضبط حجم رمز Datamatrix. القيمة الافتراضية: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | يضبط نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | يضبط ترميز ECI. يُستخدم عندما يكون DataMatrixEncodeMode على Auto. القيمة الافتراضية: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 أحرف الماكرو 11.3 بروتوكول لأحرف الماكرو في الموضع الأول (ECC 200 فقط) Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setRows()](#setrows) | عدد الصفوف. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | معرف الباركود لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | عدد الباركودات لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | معرف الملف لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0 |
| [setVersion(value)](#setversion) | يضبط حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto. |
| [toString()](#tostring) | يعيد تمثيل سلسلة قابلة للقراءة للبشر لهذا DataMatrixParameters. |

### getAspectRatio() {#getaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### getColumns() {#getcolumns}

عدد الأعمدة.

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

يحصل على نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

يحصل على حجم رمز Datamatrix. القيمة الافتراضية: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

يحصل على نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

يحصل على ترميز ECI. يُستخدم عندما يكون DataMatrixEncodeMode على Auto. القيمة الافتراضية: ISO-8859-1

### getEncodeMode() {#getencodemode}

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 أحرف الماكرو 11.3 بروتوكول لأحرف الماكرو في الموضع الأول (ECC 200 فقط) تُستخدم قيم أحرف الماكرو 05 و 06 للحصول على ترميز أكثر كثافة في أوضاع خاصة. يمكن استخدامها فقط مع DataMatrixEccType.ECC_200 أو DataMatrixEccType.ECC_AUTO. لا يمكن استخدامها مع EncodeTypes.GS_1_DATA_MATRIX القيمة الافتراضية: MacroCharacter.NONE.

### getRows() {#getrows}

عدد الصفوف.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

معرف الباركود لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

عدد الباركودات لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

معرف الملف لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### getVersion() {#getversion}

يحصل على حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false

### setAspectRatio() {#setaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### setColumns() {#setcolumns}

عدد الأعمدة.

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

يضبط نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

يضبط حجم رمز Datamatrix. القيمة الافتراضية: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

يضبط نوع ECC لـ Datamatrix. القيمة الافتراضية: DataMatrixEccType.Ecc200.

| معامل | الوصف |
| --- | --- |
| القيمة | نوع ECC لرمز Datamatrix. |

### setECIEncoding() {#seteciencoding}

يضبط ترميز ECI. يُستخدم عندما يكون DataMatrixEncodeMode على Auto. القيمة الافتراضية: ISO-8859-1

### setEncodeMode() {#setencodemode}

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 أحرف الماكرو 11.3 بروتوكول لأحرف الماكرو في الموضع الأول (ECC 200 فقط) تُستخدم قيم أحرف الماكرو 05 و 06 للحصول على ترميز أكثر كثافة في أوضاع خاصة. يمكن استخدامها فقط مع DataMatrixEccType.ECC_200 أو DataMatrixEccType.ECC_AUTO. لا يمكن استخدامها مع EncodeTypes.GS_1_DATA_MATRIX القيمة الافتراضية: MacroCharacter.NONE.

### setReaderProgramming() {#setreaderprogramming}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false

### setRows() {#setrows}

عدد الصفوف.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

معرف الباركود لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

عدد الباركودات لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

معرف الملف لوضع Structured Append لباركود Datamatrix. القيمة الافتراضية: 0

### setVersion(value) {#setversion}

يضبط حجم رمز Datamatrix. القيمة الافتراضية: Version.Auto.

| معامل | الوصف |
| --- | --- |
| القيمة | حجم رمز Datamatrix. |

### toString() {#tostring}

يعيد تمثيل سلسلة قابلة للقراءة للبشر لهذا DataMatrixParameters.

**Returns:** presentation of this DataMatrixParameters.
