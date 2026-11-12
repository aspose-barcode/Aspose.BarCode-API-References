---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "मुख्य BarCode डिकोडिंग पैरामीटर।"
type: docs
weight: 150
url: /hi/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

मुख्य बारकोड डिकोडिंग पैरामीटर। उन पैरामीटरों को शामिल करता है जो पहचाने गए डेटा पर प्रभाव डालते हैं।

```js
new BarcodeSettings(settings)
```

BarcodeSettings कॉपी कंस्ट्रक्टर

| पैरामीटर | विवरण |
| --- | --- |
| सेटिंग्स | डेटा का स्रोत |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | AustraliaPost डिकोडिंग पैरामीटर प्राप्त करता है |
| [getChecksumValidation()](#getchecksumvalidation) | 1D और पोस्टल बारकोड्स के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें। डिफ़ॉल्ट रूप से symbologies whic के लिए हाँ माना जाता है। |
| [getDetectEncoding()](#getdetectencoding) | इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करने वाला फ़्लैग। डिफ़ॉल्ट मान true है। |
| [getStripFNC()](#getstripfnc) | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | पहचान के लिए स्पष्ट रूप से निर्दिष्ट केवल बारकोड प्रकार लौटाता है। जब सक्षम हो, अन्य संगत o के मान्यता प्राप्त बारकोड्स। |
| [setChecksumValidation(value)](#setchecksumvalidation) | 1D और पोस्टल बारकोड्स के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें। डिफ़ॉल्ट रूप से symbologies whic के लिए हाँ माना जाता है। |
| [setDetectEncoding()](#setdetectencoding) | इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करने वाला फ़्लैग। डिफ़ॉल्ट मान true है। |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | पहचान के लिए स्पष्ट रूप से निर्दिष्ट केवल बारकोड प्रकार लौटाता है। जब सक्षम हो, अन्य संगत o के मान्यता प्राप्त बारकोड्स। |
| [setStripFNC(value)](#setstripfnc) | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। |

### getAustraliaPost() {#getaustraliapost}

AustraliaPost डिकोडिंग पैरामीटर प्राप्त करता है

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

1D और पोस्टल बारकोड्स के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें। डिफ़ॉल्ट रूप से उन symbologies के लिए हाँ माना जाता है जिनमें चेकसम होना आवश्यक है, जबकि जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5। चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN। चेकसम हमेशा उपयोग किया जाता है: बाकी symbologies।

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करने वाला फ़्लैग। डिफ़ॉल्ट मान true है।

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है।

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

पहचान के लिए स्पष्ट रूप से निर्दिष्ट केवल बारकोड प्रकार लौटाता है। जब सक्षम हो, अन्य संगत या समकक्ष प्रकारों के मान्यता प्राप्त बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है। उदाहरण: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

1D और पोस्टल बारकोड्स के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें। डिफ़ॉल्ट रूप से उन symbologies के लिए हाँ माना जाता है जिनमें चेकसम होना आवश्यक है, जबकि जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम कभी उपयोग नहीं किया जाता: Codabar, PatchCode, Pharmacode, DataLogic2of5। चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN। चेकसम हमेशा उपयोग किया जाता है: बाकी symbologies।

| पैरामीटर | विवरण |
| --- | --- |
| मान | 1D और पोस्टल बारकोड्स के लिए पहचान के दौरान चेकसम सत्यापन सक्षम करें। |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

इंजन को यूनिकोड कोडसेट्स के लिए कोडटेक्स्ट एन्कोडिंग का पता लगाने के लिए मजबूर करने वाला फ़्लैग। डिफ़ॉल्ट मान true है।

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

पहचान के लिए स्पष्ट रूप से निर्दिष्ट केवल बारकोड प्रकार लौटाता है। जब सक्षम हो, अन्य संगत या समकक्ष प्रकारों के मान्यता प्राप्त बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है। उदाहरण: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | कोडटेक्स्ट से FNC1, FNC2, FNC3 अक्षरों को हटाएँ। डिफ़ॉल्ट मान false है। |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
