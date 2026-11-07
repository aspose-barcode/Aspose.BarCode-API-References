---
title: "Aspose::BarCode::ComplexBarcode::Address क्लास"
linktitle: "पता"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::Address क्लास। C++ में लेनदार या ऋणकर्ता का पता।"
type: docs
weight: 100
url: /hi/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Address](./address/)() | [Address](./) का उदाहरण बनाता है |
| [Clear](./clear/)() | सभी फ़ील्ड साफ़ करता है और प्रकार को [AddressType::Undetermined](../addresstype/) पर सेट करता है। |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | निर्धारित करता है कि निर्दिष्ट पता वर्तमान पते के बराबर है या नहीं। |
| [get_AddressLine1](./get_addressline1/)() const | पता पंक्ति 1 प्राप्त करता है। |
| [get_AddressLine2](./get_addressline2/)() const | पता पंक्ति 2 प्राप्त करता है। |
| [get_CountryCode](./get_countrycode/)() const | दो-अक्षरीय ISO देश कोड प्राप्त करता है। |
| [get_HouseNo](./get_houseno/)() const | घर संख्या प्राप्त करता है। |
| [get_Name](./get_name/)() const | नाम प्राप्त करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम। |
| [get_PostalCode](./get_postalcode/)() const | डाक कोड प्राप्त करता है। |
| [get_Street](./get_street/)() const | सड़क प्राप्त करता है। |
| [get_Town](./get_town/)() const | शहर या कस्बा प्राप्त करता है। |
| [get_Type](./get_type/)() const | पता प्रकार प्राप्त करता है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड प्राप्त करता है। |
| [set_AddressLine1](./set_addressline1/)(System::String) | पता पंक्ति 1 सेट करता है। |
| [set_AddressLine2](./set_addressline2/)(System::String) | पता पंक्ति 2 सेट करता है। |
| [set_CountryCode](./set_countrycode/)(System::String) | दो-अक्षरीय ISO देश कोड सेट करता है। |
| [set_HouseNo](./set_houseno/)(System::String) | घर संख्या सेट करता है। |
| [set_Name](./set_name/)(System::String) | नाम सेट करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम। |
| [set_PostalCode](./set_postalcode/)(System::String) | डाक कोड सेट करता है। |
| [set_Street](./set_street/)(System::String) | सड़क सेट करता है। |
| [set_Town](./set_town/)(System::String) | शहर या कस्बा सेट करता है। |
## टिप्पणियाँ


आप या तो सड़क, घर नंबर, पोस्टल कोड और शहर सेट कर सकते हैं (प्रकार *structured address*) या पता पंक्ति 1 और 2 (प्रकार *combined address elements*). प्रकार स्वचालित रूप से सेट हो जाता है जब इन फ़ील्ड्स में से कोई भी सेट किया जाता है। फ़ील्ड्स सेट करने से पहले, पता प्रकार *undetermined* होता है। यदि दोनों प्रकार की फ़ील्ड्स सेट की जाती हैं, तो पता प्रकार *conflicting* हो जाता है। नाम और देश कोड हमेशा सेट होना चाहिए जब तक सभी फ़ील्ड्स खाली न हों।
## और देखें

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
