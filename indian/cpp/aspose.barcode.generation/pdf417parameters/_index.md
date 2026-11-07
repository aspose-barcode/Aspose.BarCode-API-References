---
title: "Aspose::BarCode::Generation::Pdf417Parameters क्लास।"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Generation::Pdf417Parameters क्लास। PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं। Structured Append मोड में MicroPDF417 (MacroPDF417 मोड के समान) के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। C++ में अन्य सभी फ़ील्ड वैकल्पिक हैं।"
type: docs
weight: 4000
url: /hi/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं। MacroPDF417 के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। सभी अन्य फ़ील्ड वैकल्पिक हैं। Structured Append मोड में MicroPDF417 (MacroPDF417 मोड के समान) के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। सभी अन्य फ़ील्ड वैकल्पिक हैं।

```cpp
class Pdf417Parameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [get_Columns](./get_columns/)() const | कॉलम की संख्या। |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers। इसका उपयोग बारकोड रीडर को संकेत देने के लिए किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं। Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू नहीं है। वर्तमान कार्यान्वयन में सभी ज्ञात कैरेक्टरसेट एन्कोडिंग शामिल हैं। |
| [get_EncodeMode](./get_encodemode/)() const | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [get_ErrorLevel](./get_errorlevel/)() const | यह प्राप्त करता है [BarCode](../../aspose.barcode/) के त्रुटि सुधार स्तर का Pdf417 सिम्बोलॉजी प्रकार, जो level0 से level8 तक होता है; level0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ है सर्वोत्तम त्रुटि सुधार, जिससे चित्र बड़ा होता है। |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है। यह दूसरे स्थान पर FNC1 को मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड करता है, जो दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है। |
| [get_IsLinked](./get_islinked/)() const | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी में 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड होते हैं। MicroPdf417 और Pdf417 सिम्बोलॉजी में 918 लिंकेज फ़्लैग एन्कोड होता है, जो EAN.UCC के अलावा जुड़े रैखिक घटक को दर्शाता है। |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड एन्कोड करता है। डिफ़ॉल्ट मान: [MacroCharacters.None](../barcodeclassifications/)। |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड में CCITT-16 बहुपद (x^16 + x^12 + x^5 + 1) का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम मान होता है। |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation Identifiers। Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू होता है। |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड का फ़ाइल ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल का आकार बाइट्स में होता है। |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का सेगमेंट ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की संख्या (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल मैक्रो PDF417 के लिए लागू होता है। |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [get_Rows](./get_rows/)() const | पंक्तियों की संख्या। |
| [get_Truncate](./get_truncate/)() const | क्या [BarCode](../../aspose.barcode/) का Pdf417 सिम्बोलॉजी प्रकार ट्रंकेटेड है (स्थान घटाने के लिए)। इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं। |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [set_Columns](./set_columns/)(int32_t) | कॉलम की संख्या। |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers। इसका उपयोग बारकोड रीडर को संकेत देने के लिए किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं। Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू नहीं है। वर्तमान कार्यान्वयन में सभी ज्ञात कैरेक्टरसेट एन्कोडिंग शामिल हैं। |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Pdf417 एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto। |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | सेट करता है Pdf417 सिम्बोलॉजी प्रकार को [BarCode](../../aspose.barcode/)'s त्रुटि सुधार स्तर को level0 से level8 तक निर्धारित करता है, level0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं, level8 का अर्थ है सर्वोत्तम त्रुटि सुधार जो बड़े चित्र का कारण बनता है। |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है। यह दूसरे स्थान पर FNC1 को मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड करता है, जो दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है। |
| [set_IsLinked](./set_islinked/)(bool) | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी में 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड होते हैं। MicroPdf417 और Pdf417 सिम्बोलॉजी में 918 लिंकेज फ़्लैग एन्कोड होता है, जो EAN.UCC के अलावा जुड़े रैखिक घटक को दर्शाता है। |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 और 06 मान विशेष मोड में अधिक कॉम्पैक्ट एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड एन्कोड करता है। डिफ़ॉल्ट मान: [MacroCharacters.None](../barcodeclassifications/)। |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्राप्तकर्ता नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड चेकसम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। चेकसम फ़ील्ड में CCITT-16 बहुपद (x^16 + x^12 + x^5 + 1) का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम मान होता है। |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers। Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू होता है। |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)। MicroPDF417 बारकोड का फ़ाइल ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड फ़ाइल नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड)। MicroPDF417 फ़ाइल आकार (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल का आकार बाइट्स में होता है। |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होकर MacroSegmentsCount - 1 तक जाता है। MicroPDF417 बारकोड का सेगमेंट ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड सेगमेंट्स की संख्या (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड प्रेषक नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। केवल मैक्रो PDF417 के लिए लागू होता है। |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)। MicroPDF417 बारकोड टाइम स्टैम्प (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| [set_Rows](./set_rows/)(int32_t) | पंक्तियों की संख्या। |
| [set_Truncate](./set_truncate/)(bool) | क्या [BarCode](../../aspose.barcode/) का Pdf417 सिम्बोलॉजी प्रकार ट्रंकेटेड है (स्थान घटाने के लिए)। इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं। |
| [ToString](./tostring/)() const override | इस [Pdf417Parameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


ये नमूने दिखाते हैं कि GS1MicroPdf417 में UCC/EAN-128 गैर-लिंक्ड मोड्स को कैसे एन्कोड करें।
```cpp
[C#]
//AI 01 (GTIN) के साथ GS1 UCC/EAN-128 गैर-लिंक्ड मोड 905 को एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//किसी भी AI के साथ GS1 UCC/EAN-128 गैर-लिंक्ड मोड्स 903, 904 को एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
