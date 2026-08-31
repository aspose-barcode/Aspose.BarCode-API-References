---
title:  method
linktitle: FormatQrReferenceNumber
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Formats a QR reference number by inserting spaces in C++.'
type: docs
weight: 700
url: /cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


Formats a QR reference number by inserting spaces.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parameter | Type | Description |
| --- | --- | --- |
| refNo | System::String | The reference number without white space. |

### ReturnValue

the formatted reference number.
## Remarks


Spaces are inserted to create groups of 5 digits. If a group of less than 5 digits is needed, it appears at the start of the formatted reference number. 

## See Also

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
