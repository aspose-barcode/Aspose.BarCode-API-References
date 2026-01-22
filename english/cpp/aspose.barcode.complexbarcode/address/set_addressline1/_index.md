---
title:  method
linktitle: set_AddressLine1
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the address line 1 in C++.'
type: docs
weight: 500
url: /cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


Sets the address line 1.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## Remarks


[Address](../) line 1 contains street name, house number or P.O. box. 

Setting this field sets the address type to [AddressType::CombinedElements](../../addresstype/) unless it's already [AddressType::Structured](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for combined elements addresses and is optional. 

The address line 1.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
