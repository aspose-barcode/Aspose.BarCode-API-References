---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417 पैरामीटर। इसमें PDF417, MacroPDF417, MicroPDF417 और GS1MicroPdf417 पैरामीटर शामिल हैं।<br/>            MacroPDF417 के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं।<br/>            Structured Append मोड में MicroPDF417 (MacroPDF417 मोड के समान) के लिए दो फ़ील्ड आवश्यक हैं: Pdf417MacroFileID और Pdf417MacroSegmentID। अन्य सभी फ़ील्ड वैकल्पिक हैं।

Pdf417Parameters प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## गुण
| नाम | विवरण |
| :- | :- |
| encode_mode | Pdf417 एन्कोड मोड की पहचान करता है। <br/>            डिफ़ॉल्ट मान: Auto. |
| error_level | BarCode के त्रुटि सुधार स्तर के Pdf417 सिम्बोलॉजी प्रकार को प्राप्त करता है या सेट करता है<br/>            जो level0 से level8 तक होते हैं, level0 का अर्थ है कोई त्रुटि सुधार जानकारी नहीं,<br/>            level8 का अर्थ है सर्वोत्तम त्रुटि सुधार जो बड़ी छवि बनाता है। |
| truncate | क्या BarCode का Pdf417 सिम्बोलॉजी प्रकार संक्षिप्त है (स्थान घटाने के लिए)। <br/>            इसे CompactPDF417 भी कहा जाता है। इस मोड में दाएँ पंक्ति संकेतक और दाएँ स्टॉप पैटर्न हटा दिए जाते हैं। |
| स्तम्भ | स्तम्भों की गिनती। |
| पंक्तियाँ | पंक्तियों की गिनती। |
| aspect_ratio | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| macro_pdf_417_file_id | MacroPdf417 बारकोड का फ़ाइल ID (आवश्यक फ़ील्ड)।<br/>            MicroPDF417 बारकोड का फ़ाइल ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| macro_pdf_417_segment_id | MacroPdf417 बारकोड का सेगमेंट ID (आवश्यक फ़ील्ड), जो 0 से शुरू होता है, MacroSegmentsCount - 1 तक।<br/>            MicroPDF417 बारकोड का सेगमेंट ID (Structured Append मोड के लिए आवश्यक फ़ील्ड)। |
| macro_pdf_417_segments_count | MacroPdf417 बारकोड सेगमेंट्स की संख्या (वैकल्पिक फ़ील्ड)।<br/>            MicroPDF417 बारकोड सेगमेंट्स की संख्या (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| macro_pdf_417_file_name | MacroPdf417 बारकोड फ़ाइल नाम (वैकल्पिक फ़ील्ड)।<br/>            MicroPDF417 बारकोड फ़ाइल नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| macro_pdf_417_time_stamp | MacroPdf417 बारकोड टाइम स्टैम्प (वैकल्पिक फ़ील्ड)।<br/>            MicroPDF417 बारकोड टाइम स्टैम्प (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| macro_pdf_417_sender | MacroPdf417 बारकोड प्रेषक नाम (वैकल्पिक फ़ील्ड)।<br/>            MicroPDF417 बारकोड प्रेषक नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| macro_pdf_417_addressee | MacroPdf417 बारकोड प्राप्तकर्ता नाम (वैकल्पिक फ़ील्ड)।<br/>            MicroPDF417 बारकोड प्राप्तकर्ता नाम (Structured Append मोड के लिए वैकल्पिक फ़ील्ड)। |
| macro_pdf_417_file_size | MacroPdf417 फ़ाइल आकार (वैकल्पिक फ़ील्ड).<br/>            MicroPDF417 फ़ाइल आकार (संरचित जोड़ मोड के लिए वैकल्पिक फ़ील्ड)<br/>            फ़ाइल आकार फ़ील्ड में संपूर्ण स्रोत फ़ाइल के बाइट्स में आकार शामिल है। |
| macro_pdf_417_checksum | MacroPdf417 बारकोड चेकसम (वैकल्पिक फ़ील्ड).<br/>            MicroPDF417 बारकोड चेकसम (संरचित जोड़ मोड के लिए वैकल्पिक फ़ील्ड)<br/>            चेकसम फ़ील्ड में CCITT-16 बहुपद का उपयोग करके 16-बिट (2 बाइट) CRC चेकसम का मान शामिल है। x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifiers. यह बारकोड रीडर को विवरण बताने के लिए उपयोग किया जाता है<br/>            प्रतीक में डेटा को एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में। Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू नहीं है।<br/>            वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifiers. Macro PDF417 टेक्स्ट फ़ील्ड के लिए लागू होता है। |
| macro_pdf_417_terminator | एन्कोडर को यह बताने के लिए उपयोग किया जाता है कि सेगमेंट में मैक्रो PDF417 टर्मिनेटर (कोडवर्ड 922) जोड़ना है या नहीं। <br/>            केवल मैक्रो PDF417 के लिए लागू। |
| is_reader_initialization | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह सिम्बल में निहित डेटा को रीडर प्रारंभिककरण के लिए प्रोग्रामिंग के रूप में व्याख्या करे।<br/>             |
| macro_characters | Macro Characters 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं।<br/>            केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड एन्कोड करता है<br/>            डिफ़ॉल्ट मान: MacroCharacters.None. |
| is_linked | GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है<br/>            GS1MicroPdf417 प्रतीक के साथ 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड करता है<br/>            MicroPdf417 और Pdf417 प्रतीकों के साथ 918 लिंकज फ़्लैग को संबंधित रैखिक घटक को एन्कोड करता है जो EAN.UCC नहीं है |
| is_code_128_emulation | केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है<br/>            दूसरे स्थान के मोड 908 और 909 में FNC1 एन्कोड कर सकता है, साथ ही 910 और 911 भी एन्कोड कर सकता है जो दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है |

### संबंधित देखें

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

