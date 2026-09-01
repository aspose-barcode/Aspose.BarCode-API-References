---
title:  method
linktitle: set_AddressLine2
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the address line 2 in C++.'
type: docs
weight: 700
url: /cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Sets the address line 2.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Remarks


[Address](../) line 2 contains postal code and town. 

Setting this field sets the address type to [AddressType::CombinedElements](../../addresstype/) unless it's already [AddressType::Structured](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for combined elements addresses. For this type, it's mandatory. 

The address line 2.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
