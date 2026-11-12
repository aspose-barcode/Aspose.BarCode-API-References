---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات فك ترميز AustraliaPost."
type: docs
weight: 30
url: /ar/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

معلمات فك ترميز AustraliaPost. تحتوي على معلمات تؤثر على البيانات المعترف بها لرموز AustraliaPost.

```js
new AustraliaPostSettings()
```

منشئ AustraliaPostSettings

## طرق

| اسم | الوصف |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | يحصل على نوع التفسير لمعلومات العميل لباركود AustralianPost. الافتراضي هو CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | العلم الذي يجبر محلل AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء فك الترميز |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | يضبط نوع التفسير لمعلومات العميل لباركود AustralianPost. الافتراضي هو CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | العلم الذي يجبر محلل AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء فك الترميز |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

يحصل على نوع التفسير لمعلومات العميل لباركود AustralianPost. الافتراضي هو CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

العلم الذي يجبر محلل AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء فك الترميز كطريقة CTable. طريقة ترميز CTable لا تحتوي على أي فراغات في جدول الترميز وتسلسل \"333\" من أنماط التعبئة يتم فك ترميزه كالحرف \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

يضبط نوع التفسير لمعلومات العميل لباركود AustralianPost. الافتراضي هو CustomerInformationInterpretingType.OTHER.

| معامل | الوصف |
| --- | --- |
| القيمة | نوع التفسير (CTable، NTable أو Other) لمعلومات العميل لباركود AustralianPost |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

العلم الذي يجبر محلل AustraliaPost على تجاهل أنماط التعبئة الأخيرة في حقل معلومات العميل أثناء فك الترميز كطريقة CTable. طريقة ترميز CTable لا تحتوي على أي فراغات في جدول الترميز وتسلسل \"333\" من أنماط التعبئة يتم فك ترميزه كالحرف \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
