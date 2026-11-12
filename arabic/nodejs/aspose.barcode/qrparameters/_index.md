---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات QR."
type: docs
weight: 830
url: /ar/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

معلمات QR.

```js
new QrParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [getECIEncoding()](#geteciencoding) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت لرموز QR وRectMicroQR |
| [getEncodeMode()](#getencodemode) | نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR وMicroQR وRectMicroQR. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [getQrEncodeMode()](#getqrencodemode) | نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR. من الأقل إلى الأعلى: LEVEL_L، LEVEL_M، LEVEL_Q، LEVEL_H. راجع QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | إصدار رمز QR. من Version1 إلى Version40 لرمز QR ومن M1 إلى M4 لـ MicroQr. القيمة الافتراضية هي QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | معلمات الإلحاق المهيكل QR. |
| [getVersion()](#getversion) | إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [setECIEncoding()](#seteciencoding) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت لرموز QR وRectMicroQR |
| [setEncodeMode()](#setencodemode) | نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR وMicroQR وRectMicroQR. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR. من الأقل إلى الأعلى: LEVEL_L، LEVEL_M، LEVEL_Q، LEVEL_H. راجع QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | إصدار رمز QR. من Version1 إلى Version40 لرمز QR ومن M1 إلى M4 لـ MicroQr. القيمة الافتراضية هي QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | معلمات الإلحاق المهيكل QR. |
| [setVersion()](#setversion) | إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي QRVersion.Auto. |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا QrParameters. |

### getAspectRatio() {#getaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### getECIEncoding() {#geteciencoding}

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت لباركودات QR وRectMicroQR. إذا كانت false، قد يتم ترميز فواصل GS1 كـ '%' في وضع أبجدي رقمي وفقًا لمواصفات QR. إذا كانت true، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، كما يتم ترميز أحرف '%' في وضع البايت للحفاظ عليها كبيانات. قد يحسن هذا الخيار التوافق مع المفككات التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR وMicroQR وRectMicroQR. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ، LevelH. راجع QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يتضمن التنفيذ الحالي جميع ترميزات مجموعات الأحرف المعروفة.

### getQrEncodeMode() {#getqrencodemode}

نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR. من الأقل إلى الأعلى: LEVEL_L، LEVEL_M، LEVEL_Q، LEVEL_H. راجع QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

إصدار رمز QR. من Version1 إلى Version40 لرمز QR ومن M1 إلى M4 لـ MicroQr. القيمة الافتراضية هي QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

معلمات الإلحاق المهيكل QR.

### getVersion() {#getversion}

إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### setECIEncoding() {#seteciencoding}

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت لباركودات QR وRectMicroQR. إذا كانت false، قد يتم ترميز فواصل GS1 كـ '%' في وضع أبجدي رقمي وفقًا لمواصفات QR. إذا كانت true، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، كما يتم ترميز أحرف '%' في وضع البايت للحفاظ عليها كبيانات. قد يحسن هذا الخيار التوافق مع المفككات التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

| معامل | الوصف |
| --- | --- |
| القيمة | قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت لباركودات QR وRectMicroQR. |

### setEncodeMode() {#setencodemode}

نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR وMicroQR وRectMicroQR. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ، LevelH. راجع QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يتضمن التنفيذ الحالي جميع ترميزات مجموعات الأحرف المعروفة.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

مستوى تصحيح الأخطاء Reed‑Solomon لباركود QR. من الأقل إلى الأعلى: LEVEL_L، LEVEL_M، LEVEL_Q، LEVEL_H. راجع QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

إصدار رمز QR. من Version1 إلى Version40 لرمز QR ومن M1 إلى M4 لـ MicroQr. القيمة الافتراضية هي QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

معلمات الإلحاق المهيكل QR.

### setVersion() {#setversion}

إصدار رمز QR. من Version1 إلى Version40. القيمة الافتراضية هي QRVersion.Auto.

### toString() {#tostring}

يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا QrParameters.

**Returns:** A string that represents this QrParameters.
