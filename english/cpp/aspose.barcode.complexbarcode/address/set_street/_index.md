---
title:  method
linktitle: set_Street
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the street in C++.'
type: docs
weight: 900
url: /cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Sets the street.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## Remarks


The street must be speicfied without house number. 

Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses and is optional. 

The street.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
