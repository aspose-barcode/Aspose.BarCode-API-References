---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "बैकएंड बारकोड छवियों के निर्माण के लिए BarcodeGenerator।"
type: docs
weight: 130
url: /hi/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

बैकएंड बारकोड छवियों के निर्माण के लिए BarcodeGenerator। समर्थित सिम्बोलॉजीज़: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator कंस्ट्रक्टर।

| पैरामीटर | विवरण |
| --- | --- |
| encodeType | बारकोड सिम्बोलॉजी प्रकार। सिम्बोलॉजी सेट करने के लिए EncodeTypes क्लास का उपयोग करें। |
| codeText | एन्कोड करने के लिए पाठ। |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | निर्दिष्ट xml फ़ाइल से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है। |
| [exportToXml(filePath)](#exporttoxml) | BarCode गुणों को निर्दिष्ट xml फ़ाइल में निर्यात करता है। |
| [generateBarCodeImage(format)](#generatebarcodeimage) | वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। यह उदाहरण दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें। |
| [getBarcodeType()](#getbarcodetype) | बारकोड सिम्बोलॉजी प्रकार। |
| [getCodeText()](#getcodetext) | एन्कोड करने के लिए पाठ। |
| [getParameters()](#getparameters) | उत्पादन पैरामीटर। |
| [save(filePath, format)](#save) | बारकोड छवि को विशिष्ट फ़ॉर्मेट में विशिष्ट फ़ाइल में सहेजें। |
| [setBarcodeType()](#setbarcodetype) | बारकोड सिम्बोलॉजी प्रकार। |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | निर्दिष्ट `encoding` का उपयोग करके Unicode `codeText` को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला है en |

### importFromXml(filePath) (static) {#importfromxml}

निर्दिष्ट xml फ़ाइल से BarCode गुण आयात करता है और BarcodeGenerator इंस्टेंस बनाता है।

| पैरामीटर | विवरण |
| --- | --- |
| filePath | फ़ाइल का नाम |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

BarCode गुणों को निर्दिष्ट xml फ़ाइल में निर्यात करता है।

| पैरामीटर | विवरण |
| --- | --- |
| filePath | XML फ़ाइल |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें। यह उदाहरण दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | BarCodeImageFormat | BarCodeImageFormat मान (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

बारकोड सिम्बोलॉजी प्रकार।

### getCodeText() {#getcodetext}

एन्कोड करने के लिए पाठ।

### getParameters() {#getparameters}

उत्पादन पैरामीटर।

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

बारकोड छवि को विशिष्ट फ़ॉर्मेट में विशिष्ट फ़ाइल में सहेजें।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | सहेजने के लिए पथ। |
| फ़ॉर्मेट | BarCodeImageFormat | BarCodeImageFormat मान (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

बारकोड सिम्बोलॉजी प्रकार।

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

निर्दिष्ट `encoding` का उपयोग करके Unicode `codeText` को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसका समर्थन करती है और `insertBOM` को `true` पर सेट किया जाता है, तो फ़ंक्शन `byte order mark (BOM)` शामिल करता है। यह फ़ंक्शन केवल 2D बारकोड के साथ उपयोग के लिए है (जैसे, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि)। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके Unicode टेक्स्ट को मैन्युअल रूप से एन्कोड करने की अनुमति देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, Unicode डेटा के लिए `ECI` एन्कोडिंग की सिफारिश की जाती है। इस फ़ंक्शन को 1D बारकोड, GS1-अनुपालन बारकोड (2D सहित), या HIBC बारकोड (2D सहित) के साथ उपयोग करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और अप्रत्याशित परिणाम दे सकता है। यह उदाहरण दिखाता है कि 2D बारकोड के लिए `SetCodeText` को BOM के साथ या बिना कैसे उपयोग किया जाए। //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| पैरामीटर | विवरण |
| --- | --- |
| codeText | CodeText स्ट्रिंग |
| एन्कोडिंग | लागू किया गया एन्कोडिंग |
| insertBOM | निर्दिष्ट एन्कोडिंग के समर्थन होने पर बाइट ऑर्डर मार्क (BOM) डालना है या नहीं, यह दर्शाता है (जैसे, UTF-8, UTF-16, UTF-32)। यदि `true` पर सेट किया जाता है, तो BOM जोड़ा जाता है; यदि `false` पर सेट किया जाता है, तो BOM को छोड़ दिया जाता है भले ही एन्कोडिंग सामान्यतः इसका उपयोग करती हो। |
