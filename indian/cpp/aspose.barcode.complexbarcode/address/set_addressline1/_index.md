---
title: "विधि"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड. C++ में पता लाइन 1 सेट करता है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


पता पंक्ति 1 सेट करता है।

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## टिप्पणियाँ


[Address](../) line 1 contains street name, house number or P.O. box. 

इस फ़ील्ड को सेट करने से पता प्रकार [AddressType::CombinedElements](../../addresstype/) हो जाता है, जब तक कि यह पहले से ही [AddressType::Structured](../../addresstype/) न हो, ऐसे में यह [AddressType::Conflicting](../../addresstype/) बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है और वैकल्पिक है।

पता लाइन 1।
## और देखें

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
