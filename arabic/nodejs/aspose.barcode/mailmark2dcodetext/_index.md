---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /ar/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

إنشاء نسخة افتراضية من فئة Mailmark2DCodetext.

## طرق

| اسم | الوصف |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | يحصل على نوع الباركود. |
| [getClass_()](#getclass-) | يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - Economy (تجزئة) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | إنشاء نص الترميز من بيانات Mailmark. |
| [getCustomerContent()](#getcustomercontent) | مساحة اختيارية لاستخدام العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي |
| [getInformationTypeID()](#getinformationtypeid) | يحدد حمولة باركود Royal Mail Mailmark لكل نوع منتج. القيم الصالحة: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. كل باركود Mailmark مطلوب أن يحمل معرفًا حتى يمكن أن يكون غير |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق رمز البريد (بدون DPS) مع تنسيق PAF®. |
| [getRTSFlag()](#getrtsflag) | علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوب. |
| [getSupplyChainID()](#getsupplychainid) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999. |
| [getUPUCountryID()](#getupucountryid) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [getVersionID()](#getversionid) | يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و '2' إلى '9' و |
| [initFromString(constructedCodetext)](#initfromstring) | يقوم بتهيئة بيانات Mailmark من نص الترميز المُنشأ. |
| [setClass_(value)](#setclass-) | يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - Economy (تجزئة) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | مساحة اختيارية لاستخدام العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي |
| [setInformationTypeID(value)](#setinformationtypeid) | يحدد حمولة باركود Royal Mail Mailmark لكل نوع منتج. القيم الصالحة: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. كل باركود Mailmark مطلوب أن يحمل معرفًا حتى يمكن أن يكون غير |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق رمز البريد (بدون DPS) مع تنسيق PAF®. |
| [setRTSFlag()](#setrtsflag) | علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوب. |
| [setSupplyChainID(value)](#setsupplychainid) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [setVersionID(value)](#setversionid) | يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و '2' إلى '9' و |

### getBarcodeType() {#getbarcodetype}

يحصل على نوع الباركود.

**Returns:** Barcode type.

### getClass_() {#getclass-}

يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - اقتصاد (تجزئة) '5' - مؤجل (تجزئة) '8' - مميز (وصول الشبكة) '9' - قياسي (وصول الشبكة)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

إنشاء نص الترميز من بيانات Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

مساحة اختيارية للاستخدام من قبل العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

نوع 2D Mailmark يحدد حجم باركود Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. المنطقة (حرف أو حرفان) الحي (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي وDPS مع تنسيق PAF® صالح.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

يحدد حمولة باركود Mailmark الخاص بـ Royal Mail لكل نوع منتج. القيم الصالحة: '0' - محلي مُصنف وغير مُصنف 'A' - بريد إلكتروني 'B' - فرنكينغ 'C' - تجميع

**Returns:** Information type ID

### getItemID() {#getitemid}

يحدد العنصر الفريد داخل معرف سلسلة التوريد. كل باركود Mailmark مطلوب أن يحمل معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق رمز البريد (بدون DPS) مع تنسيق PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوب.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف.

**Returns:** Country ID

### getVersionID() {#getversionid}

يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و '2' إلى '9' و 'A' إلى 'Z' محجوزة للاستخدام المستقبلي المحتمل.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

يقوم بتهيئة بيانات Mailmark من نص الترميز المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setClass_(value) {#setclass-}

يحدد فئة العنصر. القيم الصالحة: '1' - 1C (تجزئة) '2' - 2C (تجزئة) '3' - اقتصاد (تجزئة) '5' - مؤجل (تجزئة) '8' - مميز (وصول الشبكة) '9' - قياسي (وصول الشبكة)

| معامل | الوصف |
| --- | --- |
| القيمة | فئة العنصر |

### setCustomerContent(value) {#setcustomercontent}

مساحة اختيارية للاستخدام من قبل العميل. الحد الأقصى للطول حسب النوع: النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

| معامل | الوصف |
| --- | --- |
| القيمة | محتوى العميل |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

وضع الترميز لباركود Datamatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40.

| معامل | الوصف |
| --- | --- |
| القيمة | وضع الترميز لباركود Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

نوع 2D Mailmark يحدد حجم باركود Data Matrix.

| معامل | الوصف |
| --- | --- |
| القيمة | حجم باركود Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. المنطقة (حرف أو حرفان) الحي (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي وDPS مع تنسيق PAF® صالح.

| معامل | الوصف |
| --- | --- |
| القيمة | الرمز البريدي لعنوان التسليم مع DPS |

### setInformationTypeID(value) {#setinformationtypeid}

يحدد حمولة باركود Mailmark الخاص بـ Royal Mail لكل نوع منتج. القيم الصالحة: '0' - محلي مُصنف وغير مُصنف 'A' - بريد إلكتروني 'B' - فرنكينغ 'C' - تجميع

| معامل | الوصف |
| --- | --- |
| القيمة | معرف نوع المعلومات |

### setItemID(value) {#setitemid}

يحدد العنصر الفريد داخل معرف سلسلة التوريد. كل باركود Mailmark مطلوب أن يحمل معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

| معامل | الوصف |
| --- | --- |
| القيمة | عنصر داخل معرف سلسلة التوريد |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق رمز البريد (بدون DPS) مع تنسيق PAF®.

| معامل | الوصف |
| --- | --- |
| القيمة | رمز البريد للعودة إلى المرسل ولكن بدون DPS |

### setRTSFlag() {#setrtsflag}

علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوب.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999.

| معامل | الوصف |
| --- | --- |
| القيمة | معرف سلسلة التوريد |

### setUPUCountryID(value) {#setupucountryid}

يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف.

| معامل | الوصف |
| --- | --- |
| القيمة | معرف الدولة |

### setVersionID(value) {#setversionid}

يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. القيم الصالحة: حاليًا '1'. '0' و '2' إلى '9' و 'A' إلى 'Z' محجوزة للاستخدام المستقبلي المحتمل.

| معامل | الوصف |
| --- | --- |
| القيمة | معرف الإصدار |
