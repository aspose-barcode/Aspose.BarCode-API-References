---
title:  method
linktitle: get_Street
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Gets the street in C++.'
type: docs
weight: 800
url: /cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Gets the street.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street()
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
