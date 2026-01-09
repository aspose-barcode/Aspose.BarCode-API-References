---
title:  method
linktitle: get_PostalCode
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Gets the postal code in C++.'
type: docs
weight: 1200
url: /cpp/aspose.barcode.complexbarcode/address/get_postalcode/
---
## Address::get_PostalCode method


Gets the postal code.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_PostalCode()
```

## Remarks


Setting this field sets the address type to [AddressType::Structured](../../addresstype/) unless it's already [AddressType::CombinedElements](../../addresstype/), in which case it becomes [AddressType::Conflicting](../../addresstype/). 

This field is only used for structured addresses. For this type, it's mandatory. 

The postal code.
## See Also

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
