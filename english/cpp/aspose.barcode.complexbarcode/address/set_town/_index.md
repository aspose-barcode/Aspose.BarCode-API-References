---
title:  method
linktitle: set_Town
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the town or city in C++.'
type: docs
weight: 1500
url: /cpp/aspose.barcode.complexbarcode/address/set_town/
---
## Address::set_Town method


Sets the town or city.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Town(System::String value)
```

## Remarks


Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses. For this type, it's mandatory. 

The town or city.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
