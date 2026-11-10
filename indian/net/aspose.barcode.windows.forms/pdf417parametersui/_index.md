---
title: "क्लास Pdf417ParametersUI"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI क्लास। Pdf417Parameters क्लास के लिए UI रैपर"
type: docs
weight: 1860
url: /hi/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI रैपर for [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) क्लास।

```csharp
public class Pdf417ParametersUI
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | स्तंभों की संख्या। |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए रेफ़रेंसेज़ के बारे में विवरण बताने के लिए उपयोग किया जाता है। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | BarCode के एन्कोड मोड का Pdf417 सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: Pdf417EncodeMode.Auto। |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है या सेट करता है, जो level0 से level8 तक है; level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है। |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 एमुलेशन मोड को एन्कोड करता है। यह मोड 908 और 909 में दूसरे स्थान पर FNC1 को एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है, जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है। |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड को एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग को संबंधित रैखिक घटक (EAN.UCC के अलावा) को एन्कोड करती हैं। |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro Characters 05 और 06 मानों का उपयोग विशेष मोड्स में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड्स को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड चेकसम (वैकल्पिक फ़ील्ड) चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान होता है। x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड पर लागू होते हैं। |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Macro Pdf417 बारकोड का फ़ाइल ID प्राप्त करता है या सेट करता है। MacroPdf417 के लिए उपयोग किया जाता है। |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (Structured Append मोड के लिए वैकल्पिक फ़ील्ड) फ़ाइल आकार फ़ील्ड पूरे स्रोत फ़ाइल के बाइट्स में आकार दर्शाता है। |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Macro Pdf417 बारकोड के सेगमेंट ID को प्राप्त करता है या सेट करता है, जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Macro Pdf417 बारकोड सेगमेंट्स की गिनती को प्राप्त करता है या सेट करता है। |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू। |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैंप (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | पंक्तियों की संख्या। |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | क्या बारकोड का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त किया गया है (स्थान बचाने के लिए)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | इस [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### और देखें

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


