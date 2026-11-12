---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "AustraliaPost डिकोडिंग पैरामीटर।"
type: docs
weight: 30
url: /hi/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो AustraliaPost सिम्बोलॉजी के मान्यता प्राप्त डेटा को प्रभावित करते हैं।

```js
new AustraliaPostSettings()
```

AustraliaPostSettings कन्स्ट्रक्टर

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | AustralianPost BarCode के ग्राहक जानकारी के लिए इंटरप्रेटिंग टाइप प्राप्त करता है। DEFAULT है CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भराव पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को मजबूर करने वाला फ़्लैग |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | AustralianPost BarCode के ग्राहक जानकारी के लिए इंटरप्रेटिंग टाइप सेट करता है। DEFAULT है CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भराव पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को मजबूर करने वाला फ़्लैग |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

AustralianPost BarCode के ग्राहक जानकारी के लिए इंटरप्रेटिंग टाइप प्राप्त करता है। DEFAULT है CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भराव पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को मजबूर करने वाला फ़्लैग, CTable विधि के रूप में। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई गैप नहीं होते और भराव पैटर्न की श्रृंखला "333" को अक्षर "z" के रूप में डिकोड किया जाता है।

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

AustralianPost BarCode के ग्राहक जानकारी के लिए इंटरप्रेटिंग टाइप सेट करता है। DEFAULT है CustomerInformationInterpretingType.OTHER.

| पैरामीटर | विवरण |
| --- | --- |
| मान | AustralianPost BarCode के ग्राहक जानकारी का इंटरप्रेटिंग टाइप (CTable, NTable या Other) |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

डिकोडिंग के दौरान ग्राहक जानकारी फ़ील्ड में अंतिम भराव पैटर्न को अनदेखा करने के लिए AustraliaPost डिकोडर को मजबूर करने वाला फ़्लैग, CTable विधि के रूप में। CTable एन्कोडिंग विधि में एन्कोडिंग टेबल में कोई गैप नहीं होते और भराव पैटर्न की श्रृंखला "333" को अक्षर "z" के रूप में डिकोड किया जाता है।

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
