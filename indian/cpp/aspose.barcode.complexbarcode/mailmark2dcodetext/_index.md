---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext क्लास"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext क्लास। Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास C++ में।"
type: docs
weight: 1400
url: /hi/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Royal Mail 2D Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Class](./get_class/)() const | आइटम की क्लास की पहचान करता है। |
| [get_CustomerContent](./get_customercontent/)() const | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.C40। |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark प्रकार डेटा मैट्रिक्स बारकोड का आकार निर्धारित करता है। |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | डिलीवरी [Address](../address/) का पोस्टकोड DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। एरिया (1 या 2 अक्षर) डिस्ट्रिक्ट (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को एक वैध PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [get_InformationTypeID](./get_informationtypeid/)() const | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| [get_ItemID](./get_itemid/)() const | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों तक अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999। |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को एक PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [get_RTSFlag](./get_rtsflag/)() const | फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| [get_SupplyChainID](./get_supplychainid/)() const | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999। |
| [get_UPUCountryID](./get_upucountryid/)() const | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [get_VersionID](./get_versionid/)() const | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। |
| [GetBarcodeType](./getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [InitFromString](./initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से Mailmark डेटा को प्रारंभ करता है। |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | कंस्ट्रक्टर। डिफ़ॉल्ट [Mailmark2DCodetext](./) क्लास का उदाहरण बनाएं। |
| [set_Class](./set_class/)(System::String) | आइटम की क्लास की पहचान करता है। |
| [set_CustomerContent](./set_customercontent/)(System::String) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Datamatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: EncodeMode.C40। |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark प्रकार डेटा मैट्रिक्स बारकोड का आकार निर्धारित करता है। |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | डिलीवरी [Address](../address/) का पोस्टकोड DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। एरिया (1 या 2 अक्षर) डिस्ट्रिक्ट (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को एक वैध PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| [set_ItemID](./set_itemid/)(int32_t) | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को एक ID ले जाना आवश्यक है ताकि इसे कम से कम 90 दिनों तक अद्वितीय रूप से पहचाना जा सके। अधिकतम मान: 99999999। |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Return to Sender पोस्ट कोड शामिल करता है लेकिन DPS नहीं। PC (बिना DPS) को एक PAF® फ़ॉर्मेट का पालन करना चाहिए। |
| [set_RTSFlag](./set_rtsflag/)(System::String) | फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999। |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [set_VersionID](./set_versionid/)(System::String) | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। |
## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
