---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext क्लास"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext क्लास। USA ड्राइविंग लाइसेंस PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास C++ में।"
type: docs
weight: 2900
url: /hi/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


USA ड्राइविंग [License](../../aspose.barcode/license/) PDF417 कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA संस्करण संख्या 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | यह संख्या जारी करने वाले अधिकार क्षेत्र की विशिष्ट पहचान करती है और इसे ISO जारी करने वाले प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए। |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | क्षेत्राधिकार विशिष्ट फ़ील्ड्स |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | क्षेत्राधिकार संस्करण संख्या 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | कार्ड के अनिवार्य तत्व (फ़ील्ड्स) |
| [get_NumberOfEntries](./get_numberofentries/)() const | सबफ़ाइलों की संख्या 00-99 |
| [get_OptionalElements](./get_optionalelements/)() const | कार्ड के वैकल्पिक तत्व (फ़ील्ड्स) |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी। |
| [GetBarcodeType](./getbarcodetype/)() override | USA DL (Pdf417) का बारकोड प्रकार लौटाता है |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | USA DL डेटा से कोडटेक्स्ट बनाएं |
| [InitFromString](./initfromstring/)(System::String) override | कोडटेक्स्ट से USA DL ऑब्जेक्ट को प्रारंभ करें |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | XML में सहेजता है |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA संस्करण संख्या 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | यह संख्या जारी करने वाले अधिकार क्षेत्र की विशिष्ट पहचान करती है और इसे ISO जारी करने वाले प्राधिकरण (AAMVA) से संपर्क करके प्राप्त किया जा सकता है। पूर्ण 6-अंकीय IIN को एन्कोड किया जाना चाहिए। |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | क्षेत्राधिकार विशिष्ट फ़ील्ड्स |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | क्षेत्राधिकार संस्करण संख्या 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | कार्ड के अनिवार्य तत्व (फ़ील्ड्स) |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | सबफ़ाइलों की संख्या 00-99 |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | कार्ड के वैकल्पिक तत्व (फ़ील्ड्स) |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | निम्नलिखित सबफ़ाइलों, प्रकारों, ऑफ़सेट और लंबाइयों के बारे में जानकारी शामिल है। महत्वपूर्ण: केवल प्रकार सेट करें, ऑफ़सेट और लंबाई स्वचालित रूप से सेट हो जाएगी। |
| [USADriveIdCodetext](./usadriveidcodetext/)() | डिफ़ॉल्ट कंस्ट्रक्टर |
## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
