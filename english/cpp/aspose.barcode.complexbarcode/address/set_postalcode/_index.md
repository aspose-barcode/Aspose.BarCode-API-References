---
title:  method
linktitle: set_PostalCode
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the postal code in C++.'
type: docs
weight: 1300
url: /cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


Sets the postal code.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## Remarks


Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses. For this type, it's mandatory. 

The postal code.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
