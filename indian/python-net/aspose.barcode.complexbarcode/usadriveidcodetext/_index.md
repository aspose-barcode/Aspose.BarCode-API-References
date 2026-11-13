---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode Python के लिए .NET API रेफ़रेंस"
description: 
type: docs
url: /hi/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

USADriveIdCodetext प्रकार निम्नलिखित सदस्यों को उजागर करता है:
## निर्माता
| नाम | विवरण |
| :- | :- |
| USADriveIdCodetext() | USADriveIdCodetext क्लास का नया उदाहरण प्रारंभ करता है |
## गुण
| नाम | विवरण |
| :- | :- |
| issuer_identification_number | यह संख्या जारी करने वाले अधिकार क्षेत्र को अद्वितीय रूप से पहचानती है <br/>            और ISO<br/>            जारी करने प्राधिकरण (AAMVA) से संपर्क करके प्राप्त की जा सकती है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए। |
| aamva_version_number | AAMVA संस्करण संख्या 00-99 |
| jurisdiction_version_number | अधिकार क्षेत्र संस्करण संख्या 00-99 |
| number_of_entries | उपफ़ाइलों की संख्या 00-99 |
| subfile_designator | निम्नलिखित उपफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। <br/>            महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी। |
| mandatory_elements | कार्ड के अनिवार्य तत्व (फ़ील्ड) |
| optional_elements | कार्ड के वैकल्पिक तत्व (फ़ील्ड) |
| jurisdiction_specific_subfile | अधिकार क्षेत्र विशिष्ट फ़ील्ड |
## विधियाँ
| नाम | विवरण |
| :- | :- |
| get_constructed_codetext() | USA DL डेटा से कोडटेक्स्ट बनाएं |
| init_from_string(constructed_codetext) | कोडटेक्स्ट से USA DL ऑब्जेक्ट प्रारंभ करें |
| get_barcode_type() | USA DL (Pdf417) का बारकोड प्रकार लौटाता है |
| save_to_xml(stream) | XML में सहेजता है |

### संबंधित देखें

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

