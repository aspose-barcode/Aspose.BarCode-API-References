---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "PDF417 पैरामीटर।"
type: docs
weight: 770
url: /hi/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 को दो फ़ील्ड की आवश्यकता होती है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं। Structured Append मोड में MicroPDF417 (MacroPDF417 मोड के समान) को भी दो फ़ील्ड की आवश्यकता होती है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं। ये उदाहरण दिखाते हैं कि GS1MicroPdf417 में UCC/EAN-128 गैर-लिंक्ड मोड कैसे एन्कोड करें।

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [getColumns()](#getcolumns) | स्तंभों की गिनती। |
| [getECIEncoding()](#geteciencoding) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [getEncodeMode()](#getencodemode) | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [getErrorLevel()](#geterrorlevel) | BarCode के त्रुटि सुधार स्तर के लिए Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है, जो level0 से level8 तक है, level0 का अर्थ कोई त्रुटि सुधार नहीं। |
| [getMacroCharacters()](#getmacrocharacters) | Macro Characters 05 और 06 मानों का उपयोग विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल Micro के साथ ही उपयोग किया जा सकता है। |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (संरचित A के लिए वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू। |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड का फ़ाइल ID (संरचित Append मोड के लिए आवश्यक फ़ील्ड)। |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड) फ़ाइल आकार। |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की संख्या (संरचित A के लिए वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (संरचित Append के लिए वैकल्पिक फ़ील्ड)। |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 Terminator (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PD के लिए लागू। |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417 सिम्बोलॉजी प्रकार BarCode के संपीड़न मोड का। डिफ़ॉल्ट मान: Pdf417CompactionMode.AUTO। |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | BarCode के त्रुटि सुधार स्तर के लिए Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है, जो level0 से level8 तक है, level0 का अर्थ कोई त्रुटि सुधार नहीं। |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | macro Pdf417 बारकोड प्राप्तकर्ता नाम प्राप्त करता है। |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | macro Pdf417 बारकोड चेकसम प्राप्त करता है। |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू। |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Getsmacro Pdf417 बारकोड का फ़ाइल ID। MacroPdf417 के लिए उपयोग किया जाता है। |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | macro Pdf417 बारकोड फ़ाइल नाम प्राप्त करता है। |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | macro Pdf417 फ़ाइल आकार प्राप्त करता है। |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | macro Pdf417 बारकोड का सेगमेंट ID प्राप्त करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | macro Pdf417 बारकोड सेगमेंट्स की संख्या प्राप्त करता है। |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | macro Pdf417 बारकोड प्रेषक नाम प्राप्त करता है। |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 Terminator (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PD के लिए लागू। |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | macro Pdf417 बारकोड टाइम स्टैम्प प्राप्त करता है। |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)। |
| [getRows()](#getrows) | पंक्तियों की गिनती। |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode संरचित Append मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। |
| [getTruncate()](#gettruncate) | क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)। इसे CompactPDF417 भी कहा जाता है। सही पंक्ति संकेतक |
| [isCode128Emulation()](#iscode128emulation) | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है। द्वितीय स्थिति मोड 908 में FNC1 एन्कोड कर सकता है। |
| [isLinked()](#islinked) | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 प्रतीक 906, 907 को एन्कोड करता है। |
| [isReaderInitialization()](#isreaderinitialization) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setAspectRatio()](#setaspectratio) | 2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात। |
| [setCode128Emulation()](#setcode128emulation) | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है। द्वितीय स्थिति मोड 908 में FNC1 एन्कोड कर सकता है। |
| [setColumns()](#setcolumns) | स्तंभों की गिनती। |
| [setECIEncoding()](#seteciencoding) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [setEncodeMode()](#setencodemode) | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [setErrorLevel(value)](#seterrorlevel) | बारकोड के त्रुटि सुधार स्तर को सेट करता है, जो level0 से level8 तक होता है; level0 का अर्थ है कोई त्रुटि सुधार नहीं। |
| [setLinked()](#setlinked) | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 प्रतीक 906, 907 को एन्कोड करता है। |
| [setMacroCharacters()](#setmacrocharacters) | Macro Characters 05 और 06 मानों का उपयोग विशेष मोड में अधिक संकुचित एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल Micro के साथ ही उपयोग किया जा सकता है। |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (संरचित A के लिए वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू। |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड का फ़ाइल ID (संरचित Append मोड के लिए आवश्यक फ़ील्ड)। |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड) फ़ाइल आकार। |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की संख्या (संरचित A के लिए वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (संरचित Append के लिए वैकल्पिक फ़ील्ड)। |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 Terminator (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PD के लिए लागू। |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (संरचित Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417 सिम्बोलॉजी प्रकार BarCode के संपीड़न मोड का। डिफ़ॉल्ट मान: Pdf417CompactionMode.AUTO। |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। इसका उपयोग बारकोड रीडर को उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए किया जाता है। |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | बारकोड के त्रुटि सुधार स्तर को सेट करता है, जो level0 से level8 तक होता है; level0 का अर्थ है कोई त्रुटि सुधार नहीं। |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड प्राप्तकर्ता का नाम सेट करता है। |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड चेकसम सेट करता है। |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू। |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड की फ़ाइल ID सेट करता है। MacroPdf417 के लिए उपयोग किया जाता है। |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड फ़ाइल नाम सेट करता है। |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | मैक्रो Pdf417 फ़ाइल आकार सेट करता है। |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड का सेगमेंट ID सेट करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड सेगमेंट्स की गिनती सेट करता है। |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड प्रेषक का नाम सेट करता है। |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 Terminator (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PD के लिए लागू। |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | मैक्रो Pdf417 बारकोड टाइम स्टैम्प सेट करता है। |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)। |
| [setReaderInitialization(value)](#setreaderinitialization) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setRows()](#setrows) | पंक्तियों की गिनती। |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | DotCode संरचित Append मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। |
| [setTruncate()](#settruncate) | क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)। इसे CompactPDF417 भी कहा जाता है। सही पंक्ति संकेतक |
| [toString()](#tostring) | इस Pdf417Parameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### getAspectRatio() {#getaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### getColumns() {#getcolumns}

स्तंभों की गिनती।

### getECIEncoding() {#geteciencoding}

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टर सेट एन्कोडिंग्स को शामिल करता है।

### getEncodeMode() {#getencodemode}

Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto।

### getErrorLevel() {#geterrorlevel}

बारकोड के त्रुटि सुधार स्तर को प्राप्त करता है, जो level0 से level8 तक होता है; level0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ है सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है।

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

मैक्रो कैरेक्टर्स 05 और 06 मान विशेष मोड्स में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। इन्हें केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 को एन्कोड करते हैं। डिफ़ॉल्ट मान: MacroCharacters.None। ये उदाहरण दिखाते हैं कि MicroPdf417 में मैक्रो कैरेक्टर्स को कैसे एन्कोड किया जाता है।

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान होता है। x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू।

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 बारकोड की फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड की फ़ाइल ID (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड)।

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल का बाइट में आकार होता है।

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का सेगमेंट ID (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड)।

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 बारकोड सेगमेंट्स की गिनती (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की गिनती (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### getMacroPdf417Terminator() {#getmacropdf417terminator}

एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू।

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (संरचित अपेंड मोड के लिए वैकल्पिक फ़ील्ड)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417 सिम्बोलॉजी प्रकार BarCode के संपीड़न मोड का। डिफ़ॉल्ट मान: Pdf417CompactionMode.AUTO।

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग से बना है।

### getPdf417EncodeMode() {#getpdf417encodemode}

Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto।

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

बारकोड के त्रुटि सुधार स्तर को प्राप्त करता है, जो level0 से level8 तक होता है; level0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ है सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है।

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड प्राप्तकर्ता नाम प्राप्त करता है।

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड चेकसम प्राप्त करता है।

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू।

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Getsmacro Pdf417 बारकोड का फ़ाइल ID। MacroPdf417 के लिए उपयोग किया जाता है।

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड फ़ाइल नाम प्राप्त करता है।

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

macro Pdf417 फ़ाइल आकार प्राप्त करता है।

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड का सेगमेंट ID प्राप्त करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है।

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड सेगमेंट्स की संख्या प्राप्त करता है।

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड प्रेषक नाम प्राप्त करता है।

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू।

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

macro Pdf417 बारकोड टाइम स्टैम्प प्राप्त करता है।

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)।

### getRows() {#getrows}

पंक्तियों की गिनती।

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode संरचित अपेंड मोड बारकोड की ID की पहचान करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

### getTruncate() {#gettruncate}

क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार छोटा किया गया है (स्थान कम करने के लिए)। इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं।

### isCode128Emulation() {#iscode128emulation}

केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड को एन्कोड करता है। द्वितीय स्थिति में FNC1 को मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है। ये उदाहरण दिखाते हैं कि कैसे Code 128 अनुकरण मोड को द्वितीय स्थिति में FNC1 के साथ और बिना एन्कोड किया जाए। इस प्रकार MicroPdf417 को Code 128 बारकोड के रूप में डिकोड किया जा सकता है।

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी के साथ 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड होते हैं। MicroPdf417 और Pdf417 सिम्बोलॉजी के साथ 918 लिंकज फ़्लैग एन्कोड होता है जो EAN.UCC के अलावा संबंधित रैखिक घटक को दर्शाता है। ये उदाहरण दिखाते हैं कि कैसे "Linked" UCC/EAN-128 मोड को GS1MicroPdf417 में और लिंकज फ़्लैग (918) को MicroPdf417 और Pdf417 बारकोड में एन्कोड किया जाए।

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

2D बारकोड मॉड्यूल की ऊँचाई/चौड़ाई अनुपात।

### setCode128Emulation() {#setcode128emulation}

केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड को एन्कोड करता है। द्वितीय स्थिति में FNC1 को मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है। ये उदाहरण दिखाते हैं कि कैसे Code 128 अनुकरण मोड को द्वितीय स्थिति में FNC1 के साथ और बिना एन्कोड किया जाए। इस प्रकार MicroPdf417 को Code 128 बारकोड के रूप में डिकोड किया जा सकता है।

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

स्तंभों की गिनती।

### setECIEncoding() {#seteciencoding}

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। मैक्रो PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टर सेट एन्कोडिंग्स को शामिल करता है।

### setEncodeMode() {#setencodemode}

Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto।

### setErrorLevel(value) {#seterrorlevel}

BarCode के Pdf417 सिम्बोलॉजी प्रकार के त्रुटि सुधार स्तर को सेट करता है जो level0 से level8 तक होते हैं, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार है जो बड़ी छवि का संकेत देता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | BarCode के Pdf417 सिम्बोलॉजी प्रकार का त्रुटि सुधार स्तर level0 से level8 तक होता है, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार है जो बड़ी छवि का संकेत देता है। |

### setLinked() {#setlinked}

GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी के साथ 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड होते हैं। MicroPdf417 और Pdf417 सिम्बोलॉजी के साथ 918 लिंकज फ़्लैग एन्कोड होता है जो EAN.UCC के अलावा संबंधित रैखिक घटक को दर्शाता है। ये उदाहरण दिखाते हैं कि कैसे "Linked" UCC/EAN-128 मोड को GS1MicroPdf417 में और लिंकज फ़्लैग (918) को MicroPdf417 और Pdf417 बारकोड में एन्कोड किया जाए।

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

मैक्रो कैरेक्टर्स 05 और 06 मान विशेष मोड्स में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। इन्हें केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 को एन्कोड करते हैं। डिफ़ॉल्ट मान: MacroCharacters.None। ये उदाहरण दिखाते हैं कि MicroPdf417 में मैक्रो कैरेक्टर्स को कैसे एन्कोड किया जाता है।

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान होता है। x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू।

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 बारकोड की फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड की फ़ाइल ID (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड)।

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल का बाइट में आकार होता है।

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का सेगमेंट ID (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड)।

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 बारकोड सेगमेंट्स की गिनती (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की गिनती (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड)।

### setMacroPdf417Terminator() {#setmacropdf417terminator}

एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू।

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (संरचित अपेंड मोड के लिए वैकल्पिक फ़ील्ड)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417 सिम्बोलॉजी प्रकार BarCode के संपीड़न मोड का। डिफ़ॉल्ट मान: Pdf417CompactionMode.AUTO।

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग से बना है।

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto।

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

BarCode के Pdf417 सिम्बोलॉजी प्रकार के त्रुटि सुधार स्तर को सेट करता है जो level0 से level8 तक होते हैं, level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार है जो बड़ी छवि का संकेत देता है।

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड प्राप्तकर्ता का नाम सेट करता है।

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड चेकसम सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान होता है। |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू।

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड की फ़ाइल ID सेट करता है। MacroPdf417 के लिए उपयोग किया जाता है।

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड फ़ाइल नाम सेट करता है।

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 फ़ाइल आकार सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल का आकार बाइट्स में होता है। |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड का सेगमेंट ID सेट करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है।

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड सेगमेंट्स की गिनती सेट करता है।

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड प्रेषक का नाम सेट करता है।

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू।

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

मैक्रो Pdf417 बारकोड टाइम स्टैम्प सेट करता है।

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

क्या Pdf417 सिम्बोलॉजी प्रकार BarCode संक्षिप्त है (स्थान बचाने के लिए)।

### setReaderInitialization(value) {#setreaderinitialization}

रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

| पैरामीटर | विवरण |
| --- | --- |
| मान |  |

### setRows() {#setrows}

पंक्तियों की गिनती।

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

DotCode संरचित अपेंड मोड बारकोड की ID की पहचान करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

### setTruncate() {#settruncate}

क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार छोटा किया गया है (स्थान कम करने के लिए)। इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं।

### toString() {#tostring}

इस Pdf417Parameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this Pdf417Parameters.
