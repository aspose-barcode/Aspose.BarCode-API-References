---
title:  method
linktitle: CreateIso11649Reference
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Creates a ISO11649 creditor reference from a raw string by prefixing the string with "RF" and the modulo 97 checksum in C++.'
type: docs
weight: 500
url: /cpp/aspose.barcode.complexbarcode/payments/createiso11649reference/
---
## Payments::CreateIso11649Reference method


Creates a ISO11649 creditor reference from a raw string by prefixing the string with "RF" and the modulo 97 checksum

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::CreateIso11649Reference(System::String rawReference)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rawReference | System::String | The raw reference. |

### ReturnValue

The created creditor reference.
## Remarks


Whitespace is removed from the reference. 

## See Also

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
