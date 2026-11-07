---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. C++ में 4-स्थिति Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 1500
url: /hi/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (RetailPublishing Mail) (संभावित भविष्य उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (संभावित भविष्य उपयोग के लिए) "7" - सतह (रिटेल) (संभावित भविष्य उपयोग के लिए) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - मानक (नेटवर्क एक्सेस) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतरराष्ट्रीय "XY11     " को दर्शाती है (ध्यान दें 5 trailing spaces) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं। |
| [get_Format](./get_format/)() const | "0" – शून्य या परीक्षण "1" – पत्र "2" – बड़ा पत्र |
| [get_ItemID](./get_itemid/)() const | अधिकतम मान 99999999 है। |
| [get_SupplychainID](./get_supplychainid/)() const | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [get_VersionID](./get_versionid/)() const | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित) |
| [GetBarcodeType](./getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [InitFromString](./initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |
| [MailmarkCodetext](./mailmarkcodetext/)() | नए [MailmarkCodetext](./) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [set_Class](./set_class/)(System::String) | "0" - शून्य या परीक्षण "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रीमियम (RetailPublishing Mail) (संभावित भविष्य उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (संभावित भविष्य उपयोग के लिए) "7" - सतह (रिटेल) (संभावित भविष्य उपयोग के लिए) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - मानक (नेटवर्क एक्सेस) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतरराष्ट्रीय "XY11     " को दर्शाती है (ध्यान दें 5 trailing spaces) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं। |
| [set_Format](./set_format/)(int32_t) | "0" – शून्य या परीक्षण "1" – पत्र "2" – बड़ा पत्र |
| [set_ItemID](./set_itemid/)(int32_t) | अधिकतम मान 99999999 है। |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [set_VersionID](./set_versionid/)(int32_t) | वर्तमान में "1" – Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित) |
## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
