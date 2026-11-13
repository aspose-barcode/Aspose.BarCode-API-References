---
title: "BarCodeReader"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।

BarCodeReader प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| BarCodeReader() | डिफ़ॉल्ट मानों के साथ [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) क्लास का नया उदाहरण प्रारंभ करता है।<br/>            ReadBarCodes() मेथड को कॉल करने से पहले छवि (SetBitmapImage()) सेट करना आवश्यक है। |
| BarCodeReader(image) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, area, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, area, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, areas, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(image, areas, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(filename) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(filename, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(filename, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(stream) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(stream, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(stream, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, areas, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, areas, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, area, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, area, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, type) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame, decode_types) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
| BarCodeReader(frame) | BarCodeReader क्लास का नया उदाहरण प्रारंभ करता है |
## गुण
| नाम | विवरण |
| :- | :- |
| processor_settings | प्रोसेसर कोर के उपयोग की सेटिंग्स प्राप्त करता है। |
| timeout | पहचान प्रक्रिया के टाइमआउट को मिलीसेकंड में प्राप्त या सेट करता है। |
| found_bar_codes | पहचाने गए [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s एरे प्राप्त करता है |
| found_count | पहचाने गए बारकोड की संख्या प्राप्त करता है |
| quality_settings | QualitySettings आपको पहचान की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है।<br/>            आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं।<br/>            QualitySettings का डिफ़ॉल्ट मान NormalQuality है। |
| barcode_settings | मुख्य BarCode डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं। |
| bar_code_read_type | पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है या सेट करता है।<br/>            इसे कॉल करने से पहले सेट किया जाना चाहिए [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| set_bar_code_image(value) | पहचान के लिए बिटमैप इमेज सेट करता है। <br/>            इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(value, areas) | पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। <br/>            इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(value, area) | पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। <br/>            इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(filename) | पहचान के लिए इमेज फ़ाइल सेट करता है। <br/>            इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(stream) | पहचान के लिए इमेज स्ट्रीम सेट करता है। <br/>            इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(frame, area) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्र सेट करता है। इसे [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(frame, areas) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्रों को सेट करता है। इसे [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) मेथड से पहले कॉल किया जाना चाहिए। |
| set_bar_code_image(frame) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्र सेट करता है। इसे [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) मेथड से पहले कॉल किया जाना चाहिए। |
| export_to_xml(xml_file) | BarCode प्रॉपर्टीज़ को निर्दिष्ट xml-फ़ाइल में निर्यात करता है |
| export_to_xml(xml_stream) | BarCode प्रॉपर्टीज़ को निर्दिष्ट xml-स्ट्रीम में निर्यात करता है |
| import_from_xml(xml_file) | BarCode प्रॉपर्टीज़ को निर्दिष्ट xml-फ़ाइल से आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| import_from_xml(xml_stream) | BarCode प्रॉपर्टीज़ को निर्दिष्ट xml-स्ट्रीम से आयात करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| abort() | फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड है और कॉल करने के तुरंत बाद नियंत्रण लौटाता है। <br/>            यह मेथड तब उपयोग किया जाना चाहिए जब पहचान प्रक्रिया बहुत लंबी हो। |
| read_bar_codes() | छवि से [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) पढ़ता है। |
| set_bar_code_read_type(barcode_types) | [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) प्रकार की सरणी को पहचान के लिए सेट करता है। <br/>            ReadBarCodes() मेथड से पहले इसे कॉल किया जाना चाहिए। |

### संबंधित देखें

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

