---
title:  method
linktitle: set_HouseNo
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the house number in C++.'
type: docs
weight: 1100
url: /cpp/aspose.barcode.complexbarcode/address/set_houseno/
---
## Address::set_HouseNo method


Sets the house number.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_HouseNo(System::String value)
```

## Remarks


Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses and is optional. 

The house number.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
