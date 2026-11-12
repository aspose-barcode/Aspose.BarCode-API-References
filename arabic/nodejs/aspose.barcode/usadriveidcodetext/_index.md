---
title: "USADriveIdCodetext"
linktitle: "USADriveIdCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز PDF417 لرخصة القيادة الأمريكية."
type: docs
weight: 940
url: /ar/nodejs/aspose.barcode/usadriveidcodetext/
---

## USADriveIdCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز PDF417 لرخصة القيادة الأمريكية.

```js
new USADriveIdCodetext()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addSubfileDesignator()](#addsubfiledesignator) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة والطول w |
| [getAAMVAVersionNumber()](#getaamvaversionnumber) | رقم إصدار AAMVA 00-99 |
| [getBarcodeType()](#getbarcodetype) | يرجع نوع الباركود لـ USA DL (Pdf417) |
| [getConstructedCodetext()](#getconstructedcodetext) | إنشاء codetext من بيانات USA DL |
| [getIssuerIdentificationNumber()](#getissueridentificationnumber) | هذا الرقم يحدد بشكل فريد الولاية الصادرة ويمكن الحصول عليه عن طريق التواصل مع هيئة الإصدار ISO (AAM |
| [getJurisdictionSpecificSubfile()](#getjurisdictionspecificsubfile) | الحقول الخاصة بالولاية |
| [getJurisdictionVersionNumber()](#getjurisdictionversionnumber) | رقم إصدار الولاية 00-99 |
| [getMandatoryElements()](#getmandatoryelements) | العناصر الإلزامية (الحقول) للبطاقة |
| [getNumberOfEntries()](#getnumberofentries) | عدد الملفات الفرعية 00-99 |
| [getOptionalElements()](#getoptionalelements) | العناصر (الحقول) الاختيارية للبطاقة. |
| [getSubfileDesignator()](#getsubfiledesignator) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة والطول w |
| [initFromString(constructedCodetext)](#initfromstring) | تهيئة كائن USA DL من codetext |
| [setAAMVAVersionNumber()](#setaamvaversionnumber) | رقم إصدار AAMVA 00-99 |
| [setIssuerIdentificationNumber()](#setissueridentificationnumber) | هذا الرقم يحدد بشكل فريد الولاية الصادرة ويمكن الحصول عليه عن طريق التواصل مع هيئة الإصدار ISO (AAM |
| [setJurisdictionSpecificSubfile()](#setjurisdictionspecificsubfile) | الحقول الخاصة بالولاية |
| [setJurisdictionVersionNumber()](#setjurisdictionversionnumber) | رقم إصدار الولاية 00-99 |
| [setMandatoryElements()](#setmandatoryelements) | العناصر الإلزامية (الحقول) للبطاقة |
| [setNumberOfEntries()](#setnumberofentries) | عدد الملفات الفرعية 00-99 |
| [setOptionalElements()](#setoptionalelements) | العناصر (الحقول) الاختيارية للبطاقة. |
| [setSubfileDesignator()](#setsubfiledesignator) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة والطول w |

### addSubfileDesignator() {#addsubfiledesignator}

يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة وسيتم ضبط الطول تلقائيًا.

### getAAMVAVersionNumber() {#getaamvaversionnumber}

رقم إصدار AAMVA 00-99

### getBarcodeType() {#getbarcodetype}

يرجع نوع الباركود لـ USA DL (Pdf417)

**Returns:** Barcode type (Pdf417)

### getConstructedCodetext() {#getconstructedcodetext}

إنشاء codetext من بيانات USA DL

**Returns:** Constructed codetext

### getIssuerIdentificationNumber() {#getissueridentificationnumber}

هذا الرقم يحدد بشكل فريد الولاية الصادرة ويمكن الحصول عليه عن طريق التواصل مع هيئة الإصدار ISO (AAMVA). يجب ترميز الرقم التعريفي الدولي IIN المكوّن من 6 أرقام بالكامل.

### getJurisdictionSpecificSubfile() {#getjurisdictionspecificsubfile}

الحقول الخاصة بالولاية

### getJurisdictionVersionNumber() {#getjurisdictionversionnumber}

رقم إصدار الولاية 00-99

### getMandatoryElements() {#getmandatoryelements}

العناصر الإلزامية (الحقول) للبطاقة

### getNumberOfEntries() {#getnumberofentries}

عدد الملفات الفرعية 00-99

### getOptionalElements() {#getoptionalelements}

العناصر (الحقول) الاختيارية للبطاقة.

### getSubfileDesignator() {#getsubfiledesignator}

يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة وسيتم ضبط الطول تلقائيًا.

### initFromString(constructedCodetext) {#initfromstring}

تهيئة كائن USA DL من codetext

| معامل | الوصف |
| --- | --- |
| constructedCodetext | codetext المُنشأ |

### setAAMVAVersionNumber() {#setaamvaversionnumber}

رقم إصدار AAMVA 00-99

### setIssuerIdentificationNumber() {#setissueridentificationnumber}

هذا الرقم يحدد بشكل فريد الولاية الصادرة ويمكن الحصول عليه عن طريق التواصل مع هيئة الإصدار ISO (AAMVA). يجب ترميز الرقم التعريفي الدولي IIN المكوّن من 6 أرقام بالكامل.

### setJurisdictionSpecificSubfile() {#setjurisdictionspecificsubfile}

الحقول الخاصة بالولاية

### setJurisdictionVersionNumber() {#setjurisdictionversionnumber}

رقم إصدار الولاية 00-99

### setMandatoryElements() {#setmandatoryelements}

العناصر الإلزامية (الحقول) للبطاقة

### setNumberOfEntries() {#setnumberofentries}

عدد الملفات الفرعية 00-99

### setOptionalElements() {#setoptionalelements}

العناصر (الحقول) الاختيارية للبطاقة.

### setSubfileDesignator() {#setsubfiledesignator}

يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والأطوال. مهم: اضبط فقط النوع، الإزاحة وسيتم ضبط الطول تلقائيًا.
