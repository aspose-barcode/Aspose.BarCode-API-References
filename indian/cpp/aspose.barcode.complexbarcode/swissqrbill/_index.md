---
title: "Aspose::BarCode::ComplexBarcode::SwissQRBill class"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::SwissQRBill class. C++ में SwissQR बिल डेटा।"
type: docs
weight: 2700
url: /hi/cpp/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class


SwissQR बिल डेटा.

```cpp
class SwissQRBill : public System::IEquatable<System::SharedPtr<SwissQRBill>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [CreateAndSetCreditorReference](./createandsetcreditorreference/)(System::String) | कच्ची स्ट्रिंग से ISO11649 क्रेडिटर रेफ़रेंस बनाता और सेट करता है, स्ट्रिंग को "RF" से प्रीफ़िक्स करके और मोड्यूलो 97 चेकसम जोड़कर। |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| [Equals](./equals/)(System::SharedPtr\<SwissQRBill\>) override | निर्धारित करता है कि निर्दिष्ट बिल वर्तमान बिल के बराबर है या नहीं। |
| [get_Account](./get_account/)() const | क्रेडिटर का खाता नंबर प्राप्त करता है। |
| [get_AlternativeSchemes](./get_alternativeschemes/)() const | वैकल्पिक भुगतान योजनाओं को प्राप्त या सेट करता है। |
| [get_Amount](./get_amount/)() const | भुगतान राशि प्राप्त करता है। |
| [get_BillInformation](./get_billinformation/)() const | अतिरिक्त संरचित बिल जानकारी प्राप्त करता है। |
| [get_Creditor](./get_creditor/)() const | क्रेडिटर का पता प्राप्त करता है। |
| [get_Currency](./get_currency/)() const | भुगतान मुद्रा प्राप्त करता है। |
| [get_Debtor](./get_debtor/)() const | देयकर्ता का पता प्राप्त करता है। |
| [get_Reference](./get_reference/)() const | क्रेडिटर भुगतान रेफ़रेंस प्राप्त करता है। |
| [get_UnstructuredMessage](./get_unstructuredmessage/)() const | अतिरिक्त असंरचित संदेश प्राप्त करता है। |
| [get_Version](./get_version/)() const | SwissQR बिल मानक का संस्करण प्राप्त करता है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड प्राप्त करता है। |
| [set_Account](./set_account/)(System::String) | क्रेडिटर का खाता नंबर सेट करता है। |
| [set_AlternativeSchemes](./set_alternativeschemes/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<AlternativeScheme\>>>) | वैकल्पिक भुगतान योजनाओं को प्राप्त या सेट करता है। |
| [set_Amount](./set_amount/)(System::Decimal) | भुगतान राशि सेट करता है। |
| [set_BillInformation](./set_billinformation/)(System::String) | अतिरिक्त संरचित बिल जानकारी सेट करता है। |
| [set_Creditor](./set_creditor/)(System::SharedPtr\<Address\>) | क्रेडिटर का पता सेट करता है। |
| [set_Currency](./set_currency/)(System::String) | भुगतान मुद्रा सेट करता है। |
| [set_Debtor](./set_debtor/)(System::SharedPtr\<Address\>) | देयकर्ता का पता सेट करता है। |
| [set_Reference](./set_reference/)(System::String) | क्रेडिटर भुगतान रेफ़रेंस सेट करता है। |
| [set_UnstructuredMessage](./set_unstructuredmessage/)(System::String) | अतिरिक्त असंरचित संदेश सेट करता है। |
| [set_Version](./set_version/)(SwissQRBill::QrBillStandardVersion) | SwissQR बिल मानक का संस्करण सेट करता है। |
## Typedefs

| टाइपडिफ | विवरण |
| --- | --- |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR बिल मानक संस्करण |
## और देखें

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
