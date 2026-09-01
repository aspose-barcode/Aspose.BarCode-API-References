---
title:  method
linktitle: FormatIban
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Formats an IBAN or creditor reference by inserting spaces in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


Formats an IBAN or creditor reference by inserting spaces

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parameter | Type | Description |
| --- | --- | --- |
| iban | System::String | The IBAN or creditor reference without spaces. |

### ReturnValue

The formatted IBAN or creditor reference.
## Remarks


Spaces are inserted to form groups of 4 letters/digits. If a group of less than 4 letters/digits is needed, it appears at the end. 

## See Also

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
