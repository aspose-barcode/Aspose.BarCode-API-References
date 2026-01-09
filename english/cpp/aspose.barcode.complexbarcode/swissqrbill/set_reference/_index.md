---
title:  method
linktitle: set_Reference
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets the creditor payment reference in C++.'
type: docs
weight: 1200
url: /cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Sets the creditor payment reference.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Remarks


The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. 

If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting. 

The creditor payment reference.
## See Also

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
