---
title:  method
linktitle: get_AddressLine1
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Gets the address line 1 in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


Gets the address line 1.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1()
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
