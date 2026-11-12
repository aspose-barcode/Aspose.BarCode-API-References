---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए बारकोड डेटा को संग्रहीत करता है जैसे SingleDecodeType प्रकार, `string` कोडटेक्स्ट, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर।"
type: docs
weight: 110
url: /hi/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

पहचाने गए बारकोड डेटा को संग्रहीत करता है जैसे SingleDecodeType प्रकार, `string` कोडटेक्स्ट, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर।

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [deepClone()](#deepclone) | BarCodeResult क्लास की एक कॉपी बनाता है। |
| [equals(other)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BarCodeResult मान के बराबर है या नहीं। |
| [getCodeBytes()](#getcodebytes) | एन्कोडेड कोड बाइट्स प्राप्त करता है मान: बारकोड के कोड बाइट्स। |
| [getCodeText(encoding)](#getcodetext) | कोड टेक्स्ट को एन्कोडिंग के साथ प्राप्त करता है। यह उदाहरण दिखाता है कि `getCodeText` का उपयोग कैसे करें: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | बारकोड प्रकार प्राप्त करता है मान: पहचाने गए बारकोड की प्रकार जानकारी। |
| [getCodeTypeName()](#getcodetypename) | बारकोड प्रकार का नाम प्राप्त करता है मान: पहचाने गए बारकोड का प्रकार नाम। |
| [getConfidence()](#getconfidence) | पहचाने गए बारकोड का पहचान विश्वास स्तर प्राप्त करता है मान: BarCodeConfidence.Strong में नकली या गलत नहीं होते। |
| [getExtended()](#getextended) | पहचाने गए बारकोड के विस्तारित पैरामीटर प्राप्त करता है मान: पहचाने गए बारकोड के विस्तारित पैरामीटर। |
| [getReadingQuality()](#getreadingquality) | पढ़ने की गुणवत्ता प्राप्त करता है। 1D और पोस्टल बारकोड के लिए काम करता है। मान: पढ़ने की गुणवत्ता प्रतिशत। |
| [getRegion()](#getregion) | बारकोड क्षेत्र प्राप्त करता है मान: पहचाने गए बारकोड का क्षेत्र। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [toString()](#tostring) | इस BarCodeResult की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### deepClone() {#deepclone}

BarCodeResult क्लास की एक कॉपी बनाता है।

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BarCodeResult मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| अन्य | इस इंस्टेंस से तुलना करने के लिए एक BarCodeResult मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

एन्कोडेड कोड बाइट्स प्राप्त करता है मान: बारकोड के कोड बाइट्स।

### getCodeText(encoding) {#getcodetext}

कोड टेक्स्ट को एन्कोडिंग के साथ प्राप्त करता है। यह उदाहरण दिखाता है कि `getCodeText` का उपयोग कैसे करें: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| पैरामीटर | विवरण |
| --- | --- |
| एन्कोडिंग | कोडटेक्स्ट के लिए एन्कोडिंग। |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

बारकोड प्रकार प्राप्त करता है मान: पहचाने गए बारकोड की प्रकार जानकारी।

### getCodeTypeName() {#getcodetypename}

बारकोड प्रकार का नाम प्राप्त करता है मान: पहचाने गए बारकोड का प्रकार नाम।

### getConfidence() {#getconfidence}

पहचाने गए बारकोड का पहचान विश्वास स्तर प्राप्त करता है मान: BarCodeConfidence.Strong में नकली या गलत पहचान नहीं होती, BarCodeConfidence.Moderate कभी-कभी नकली या गलत कोडटेक्स्ट रख सकता है क्योंकि यह विश्वास स्तर कमजोर चेकसम वाले या बिना चेकसम वाले बारकोड के लिए है, BarCodeConfidence.NONE हमेशा गलत कोडटेक्स्ट रखता है और नकली पहचान हो सकती है।

### getExtended() {#getextended}

पहचाने गए बारकोड के विस्तारित पैरामीटर प्राप्त करता है मान: पहचाने गए बारकोड के विस्तारित पैरामीटर।

### getReadingQuality() {#getreadingquality}

पढ़ने की गुणवत्ता प्राप्त करता है। 1D और पोस्टल बारकोड के लिए काम करता है। मान: पढ़ने की गुणवत्ता प्रतिशत।

### getRegion() {#getregion}

बारकोड क्षेत्र प्राप्त करता है मान: पहचाने गए बारकोड का क्षेत्र।

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

इस BarCodeResult की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this BarCodeResult.
