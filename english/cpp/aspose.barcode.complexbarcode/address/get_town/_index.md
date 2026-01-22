---
title:  method
linktitle: get_Town
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Gets the town or city in C++.'
type: docs
weight: 1400
url: /cpp/aspose.barcode.complexbarcode/address/get_town/
---
## Address::get_Town method


Gets the town or city.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Town()
```

## Remarks


Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses. For this type, it's mandatory. 

The town or city.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
