---
title:  method
linktitle: IsValidQrReference
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Validates if the string is a valid QR reference in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Validates if the string is a valid QR reference.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Type | Description |
| --- | --- | --- |
| reference | System::String | The QR reference number to validate. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Remarks


A valid QR reference is a valid ISR reference. 

The string is checked for valid characters, valid length and a valid check digit. White space is ignored. 

## See Also

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
