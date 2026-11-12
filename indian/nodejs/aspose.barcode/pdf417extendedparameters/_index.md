---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी संग्रहीत करता है"
type: docs
weight: 760
url: /hi/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी संग्रहीत करता है

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [equals(obj)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट Pdf417ExtendedParameters मान के बराबर है या नहीं। |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | मैक्रो PDF417 प्राप्तकर्ता नाम (वैकल्पिक)। |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | मैक्रो PDF417 चेकसम (वैकल्पिक)। |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | बारकोड का फ़ाइल आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। मान: MacroPdf417 का फ़ाइल आईडी। |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 फ़ाइल नाम (वैकल्पिक)। |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 फ़ाइल आकार (वैकल्पिक)। |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | बारकोड का सेगमेंट ID प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। मान: बारकोड का सेगमेंट ID। |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | macro pdf417 बारकोड सेगमेंट की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: सेगमेंट गिनती। |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 प्रेषक नाम (वैकल्पिक)। |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 टाइम स्टैम्प (वैकल्पिक)। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isCode128Emulation()](#iscode128emulation) | फ़्लैग जो दर्शाता है कि MicroPdf417 बारकोड 908, 909, 910 या 911 Code 128 इम्यूलेशन कोडवर्ड्स के साथ एन्कोड किया गया है। |
| [isLinked()](#islinked) | फ़्लैग जो दर्शाता है कि बारकोड को 1D बारकोड से लिंक किया जाना चाहिए। मान: लिंकज फ़्लैग |
| [isReaderInitialization()](#isreaderinitialization) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [toString()](#tostring) | इस Pdf417ExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### equals(obj) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट Pdf417ExtendedParameters मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

मैक्रो PDF417 प्राप्तकर्ता नाम (वैकल्पिक)।

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

मैक्रो PDF417 चेकसम (वैकल्पिक)।

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

बारकोड का फ़ाइल आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। मान: MacroPdf417 का फ़ाइल आईडी।

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 फ़ाइल नाम (वैकल्पिक)।

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 फ़ाइल आकार (वैकल्पिक)।

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

बारकोड का सेगमेंट ID प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। मान: बारकोड का सेगमेंट ID।

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

macro pdf417 बारकोड सेगमेंट की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। मान: सेगमेंट गिनती।

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 प्रेषक नाम (वैकल्पिक)।

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 टाइम स्टैम्प (वैकल्पिक)।

**Returns:** Time stamp.

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

फ़्लैग जो दर्शाता है कि MicroPdf417 बारकोड 908, 909, 910 या 911 Code 128 इम्यूलेशन कोडवर्ड्स के साथ एन्कोड किया गया है।

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

फ़्लैग जो दर्शाता है कि बारकोड को 1D बारकोड से लिंक किया जाना चाहिए। मान: लिंकज फ़्लैग

### isReaderInitialization() {#isreaderinitialization}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Returns:** Reader initialization flag

### toString() {#tostring}

इस Pdf417ExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this Pdf417ExtendedParameters.
