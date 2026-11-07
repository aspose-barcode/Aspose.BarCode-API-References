---
title: "विधि"
linktitle: "set_Street"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में स्ट्रीट सेट करता है।"
type: docs
weight: 900
url: /hi/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


सड़क सेट करता है।

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## टिप्पणियाँ


स्ट्रीट को हाउस नंबर के बिना निर्दिष्ट किया जाना चाहिए।

इस फ़ील्ड को सेट करने से पता प्रकार [AddressType::Structured](../../addresstype/) हो जाता है, जब तक कि यह पहले से ही [AddressType::CombinedElements](../../addresstype/) न हो, ऐसे में यह [AddressType::Conflicting](../../addresstype/) बन जाता है।

यह फ़ील्ड केवल संरचित पते के लिए उपयोग किया जाता है और वैकल्पिक है।

स्ट्रीट।
## और देखें

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
