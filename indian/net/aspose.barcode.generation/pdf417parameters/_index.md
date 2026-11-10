---
title: "क्लास Pdf417Parameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.Pdf417Parameters क्लास। PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 को दो फ़ील्ड्स Pdf417MacroFileID और Pdf417MacroSegmentID की आवश्यकता होती है। अन्य सभी फ़ील्ड वैकल्पिक हैं। Structured Append मोड में MicroPDF417, MacroPDF417 मोड के समान, दो फ़ील्ड्स Pdf417MacroFileID और Pdf417MacroSegmentID की आवश्यकता रखता है। अन्य सभी फ़ील्ड वैकल्पिक हैं।"
type: docs
weight: 1570
url: /hi/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 को दो फ़ील्ड की आवश्यकता होती है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं। Structured Append मोड में MicroPDF417 (MacroPDF417 मोड के समान) को भी दो फ़ील्ड की आवश्यकता होती है: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं।

```csharp
public class Pdf417Parameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | स्तंभों की संख्या। |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए रेफ़रेंसेज़ के बारे में विवरण बताने के लिए उपयोग किया जाता है। Macro PDF417 टेक्स्ट फ़ील्ड्स के लिए लागू नहीं है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | BarCode के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार प्राप्त करता है या सेट करता है, जो level0 से level8 तक है; level0 का अर्थ कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ सर्वोत्तम त्रुटि सुधार जो बड़ी छवि देता है। |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 एमुलेशन मोड को एन्कोड करता है। यह मोड 908 और 909 में दूसरे स्थान पर FNC1 को एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है, जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है। |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड को एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग को संबंधित रैखिक घटक (EAN.UCC के अलावा) को एन्कोड करती हैं। |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Macro Characters 05 और 06 मानों का उपयोग विशेष मोड्स में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड्स को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड चेकसम (वैकल्पिक फ़ील्ड) चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान होता है। x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। Macro PDF417 टेक्स्ट फ़ील्ड पर लागू होते हैं। |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड का फ़ाइल ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। Structured Append मोड के लिए MicroPDF417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (Structured Append मोड के लिए वैकल्पिक फ़ील्ड) फ़ाइल आकार फ़ील्ड पूरे स्रोत फ़ाइल के बाइट्स में आकार दर्शाता है। |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का सेगमेंट ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की संख्या (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में Macro PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल Macro PDF417 के लिए लागू। |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 बारकोड टाइम स्टैंप (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैंप (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | पंक्तियों की संख्या। |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त (स्पेस कम करने के लिए) है। इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | इस `Pdf417Parameters` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

## उदाहरण

ये उदाहरण दिखाते हैं कि GS1MicroPdf417 में UCC/EAN-128 गैर-लिंक्ड मोड कैसे एन्कोड करें।

```csharp
[C#]
//AI 01 (GTIN) के साथ 905 गैर-लिंक्ड मोड को GS1 UCC/EAN-128 में एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//किसी भी AI के साथ 903, 904 गैर-लिंक्ड मोड को GS1 UCC/EAN-128 में एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


