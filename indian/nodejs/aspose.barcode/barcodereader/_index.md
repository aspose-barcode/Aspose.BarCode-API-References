---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।"
type: docs
weight: 90
url: /hi/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।

```js
new BarCodeReader(image, areas, decodeTypes)
```

BarCodeReader का नया उदाहरण प्रारंभ करता है

| पैरामीटर | विवरण |
| --- | --- |
| छवि | base64 स्ट्रिंग या छवि के पथ के रूप में एन्कोड किया गया |
| क्षेत्र | Rectangle प्रकार के ऑब्जेक्ट की एरे |
| डिकोडटाइप्स | DecodeType द्वारा ऑब्जेक्ट की एरे |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है |
| [containsAny()](#containsany) | निर्धारित करता है कि दिए गए decode types में से कोई भी शामिल है या नहीं |
| [exportToXml(xmlFile)](#exporttoxml) | निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है |
| [getBarCodeReadType()](#getbarcodereadtype) | इनपुट barcode डिकोडिंग का decode type प्राप्त करता है |
| [getBarcodeSettings()](#getbarcodesettings) | मुख्य बारकोड डिकोडिंग पैरामीटर। उन पैरामीटरों को शामिल करता है जो पहचाने गए डेटा पर प्रभाव डालते हैं। |
| [getFoundBarCodes()](#getfoundbarcodes) | पहचाने गए BarCodeResult एरे प्राप्त करता है |
| [getFoundCount()](#getfoundcount) | पहचाने गए barcodes की गिनती प्राप्त करता है |
| [getQualitySettings()](#getqualitysettings) | QualitySettings मैन्युअली पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप जल्दी से QualitySettings सेट अप कर सकते हैं। |
| [getTimeout()](#gettimeout) | पहचान प्रक्रिया का timeout मिलीसेकंड में प्राप्त करता है। |
| [readBarCodes()](#readbarcodes) | छवि से BarCodeResult पढ़ता है। |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | पहचान के लिए bitmap image और क्षेत्रों को सेट करता है। ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है। |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | पहचान के लिए SingleDecodeType प्रकार एरे सेट करता है। readBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है। |
| [setQualitySettings()](#setqualitysettings) | QualitySettings मैन्युअली पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप जल्दी से QualitySettings सेट अप कर सकते हैं। |
| [setTimeout(value)](#settimeout) | पहचान प्रक्रिया का timeout मिलीसेकंड में सेट करता है। |

### importFromXml(xmlFile) (static) {#importfromxml}

निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है

| पैरामीटर | विवरण |
| --- | --- |
| xmlFile | फ़ाइल का नाम |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

निर्धारित करता है कि दिए गए decode types में से कोई भी शामिल है या नहीं

| पैरामीटर | विवरण |
| --- | --- |
| ...decodeTypes | सत्यापित करने के प्रकार। |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

निर्दिष्ट xml-फ़ाइल में BarCode गुण निर्यात करता है

| पैरामीटर | विवरण |
| --- | --- |
| xmlFile | फ़ाइल का नाम |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

इनपुट barcode डिकोडिंग का decode type प्राप्त करता है

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

मुख्य बारकोड डिकोडिंग पैरामीटर। उन पैरामीटरों को शामिल करता है जो पहचाने गए डेटा पर प्रभाव डालते हैं।

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

पहचाने गए BarCodeResult एरे प्राप्त करता है

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

पहचाने गए barcodes की गिनती प्राप्त करता है

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

पहचान प्रक्रिया का timeout मिलीसेकंड में प्राप्त करता है।

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

छवि से BarCodeResult पढ़ता है।

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

पहचान के लिए bitmap image और क्षेत्रों को सेट करता है। ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है।

| पैरामीटर | विवरण |
| --- | --- |
| imageResource | पहचान के लिए छवि। |
| क्षेत्र | पहचान के लिए क्षेत्रों की सूची |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

पहचान के लिए SingleDecodeType प्रकार एरे सेट करता है। readBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है।

| पैरामीटर | विवरण |
| --- | --- |
| types | पढ़ने के लिए SingleDecodeType प्रकार एरे। |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

पहचान प्रक्रिया का timeout मिलीसेकंड में सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | timeout। |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
