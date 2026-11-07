---
title: "विधि"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड. C++ में पता लाइन 2 सेट करता है।"
type: docs
weight: 700
url: /hi/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


पता पंक्ति 2 सेट करता है।

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## टिप्पणियाँ


[Address](../) line 2 contains postal code and town. 

इस फ़ील्ड को सेट करने से पता प्रकार [AddressType::CombinedElements](../../addresstype/) हो जाता है, जब तक कि यह पहले से ही [AddressType::Structured](../../addresstype/) न हो, ऐसे में यह [AddressType::Conflicting](../../addresstype/) बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है। इस प्रकार के लिए यह अनिवार्य है।

पता लाइन 2।
## और देखें

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
