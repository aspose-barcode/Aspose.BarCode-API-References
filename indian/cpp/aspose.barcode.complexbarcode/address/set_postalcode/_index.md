---
title: "विधि"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में पोस्टल कोड सेट करता है।"
type: docs
weight: 1300
url: /hi/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


डाक कोड सेट करता है।

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## टिप्पणियाँ


इस फ़ील्ड को सेट करने से पता प्रकार [AddressType::Structured](../../addresstype/) हो जाता है, जब तक कि यह पहले से ही [AddressType::CombinedElements](../../addresstype/) न हो, ऐसे में यह [AddressType::Conflicting](../../addresstype/) बन जाता है।

यह फ़ील्ड केवल संरचित पते के लिए उपयोग किया जाता है। इस प्रकार के लिए यह अनिवार्य है।

पोस्टल कोड।
## और देखें

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
