---
title: Pdf417Parameters
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: PDF417 पैरमटर PDF417 MacroPDF417 और MicroPDF417 पैरमटर शमल हैं MacroPDF417 क द फ़ल्ड क आवश्यकत है Pdf417MacroFileID और Pdf417MacroSegmentID अन्य सभ फ़ल्ड वैकल्पक हैं MicroPDF417 संरचत परशष्ट मड में MacroPDF417 मड के समन द फ़ल्ड क आवश्यकत हत है Pdf417MacroFileID और Pdf417MacroSegmentID अन्य सभ फ़ल्ड वैकल्पक हैं.
type: docs
weight: 1130
url: /hi/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 पैरामीटर। PDF417, MacroPDF417 और MicroPDF417 पैरामीटर शामिल हैं। MacroPDF417 को दो फ़ील्ड की आवश्यकता है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं। MicroPDF417 संरचित परिशिष्ट मोड में (MacroPDF417 मोड के समान) दो फ़ील्ड की आवश्यकता होती है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं.

```csharp
public class Pdf417Parameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2डी बारकोड मॉड्यूल की ऊंचाई/चौड़ाई का अनुपात. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation/) { get; set; } | कोड 128 अनुकरण के लिए फ़ंक्शन कोडवर्ड। केवल MicroPDF417 के लिए आवेदन किया गया। PDF417 और MacroPDF417 बारकोड के लिए उपेक्षित. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding/) { get; set; } | कोडेटेक्स्ट का एन्कोडिंग प्राप्त या सेट करता है। डिफ़ॉल्ट मान: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | कॉलम गिनती. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | पाठक को प्रतीक में निहित डेटा को पाठक आरंभीकरण के लिए प्रोग्रामिंग के रूप में व्याख्या करने के लिए निर्देश देने के लिए उपयोग किया जाता है। |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode/) { get; set; } | Pdf417 सहजीवन प्रकार बारकोड का संघनन मोड। डिफ़ॉल्ट मान: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding/) { get; set; } | विस्तारित चैनल व्याख्या पहचानकर्ता। इसका उपयोग बारकोड रीडर विवरण को प्रतीक में डेटा को एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में बताने के लिए किया जाता है। मैक्रो PDF417 टेक्स्ट फ़ील्ड के लिए लागू नहीं किया गया। वर्तमान कार्यान्वयन में सभी प्रसिद्ध वर्णसेट एन्कोडिंग शामिल हैं। |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel/) { get; set; } | बारकोड के त्रुटि सुधार स्तर के Pdf417 सिम्बोलॉजी प्रकार को प्राप्त या सेट करता है, स्तर 0 से लेकर स्तर 8 तक, स्तर 0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं, स्तर 8 का अर्थ है सर्वश्रेष्ठ त्रुटि सुधार जिसका अर्थ है एक बड़ी तस्वीर। |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee/) { get; set; } | मैक्रोपीडीएफ417 बारकोड पता पाने वाले का नाम (वैकल्पिक क्षेत्र) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum/) { get; set; } | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (संरचित परिशिष्ट मोड के लिए वैकल्पिक फ़ील्ड) चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट्स) CRC चेकसम का मान होता है। x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding/) { get; set; } | विस्तारित चैनल व्याख्या पहचानकर्ता। मैक्रो PDF417 टेक्स्ट फ़ील्ड के लिए लागू होता है. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid/) { get; set; } | MacroPdf417 बारकोड की फ़ाइल आईडी (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड की फ़ाइल आईडी (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename/) { get; set; } | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड). MicroPDF417 बारकोड फ़ाइल नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize/) { get; set; } | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (संरचित परिशिष्ट मोड के लिए वैकल्पिक फ़ील्ड) फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल के बाइट्स में आकार होता है। |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid/) { get; set; } | MacroPdf417 बारकोड का सेगमेंट आईडी (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount तक - 1. MicroPDF417 बारकोड का सेगमेंट आईडी (संरचित एपेंड मोड के लिए आवश्यक फ़ील्ड) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount/) { get; set; } | मैक्रोपीडीएफ417 बारकोड सेगमेंट काउंट (वैकल्पिक फील्ड) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender/) { get; set; } | MacroPdf417 बारकोड भेजने वाले का नाम (वैकल्पिक फ़ील्ड). MicroPDF417 बारकोड भेजने वाले का नाम (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड) |
| [Pdf417MacroTerminator](../../aspose.barcode.generation/pdf417parameters/pdf417macroterminator/) { get; set; } | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल मैक्रो PDF417. के लिए लागू |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp/) { get; set; } | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (संरचित एपेंड मोड के लिए वैकल्पिक फ़ील्ड) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate/) { get; set; } | क्या Pdf417 सहजीवन प्रकार का बारकोड छोटा है (स्थान कम करने के लिए)। को कॉम्पैक्टपीडीएफ417 के नाम से भी जाना जाता है। इस मोड में रिगथ रो इंडिकेटर और राइट स्टॉप पैटर्न हटा दिए जाते हैं। |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | पंक्तियों की संख्या. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | इसका एक मानव-पठनीय स्ट्रिंग प्रतिनिधित्व देता है`Pdf417Parameters` . |

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
