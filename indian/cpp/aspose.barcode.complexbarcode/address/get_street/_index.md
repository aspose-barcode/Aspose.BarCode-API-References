---
title: "विधि"
linktitle: "get_Street"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में सड़क प्राप्त करता है।"
type: docs
weight: 800
url: /hi/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


सड़क प्राप्त करता है।

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
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
